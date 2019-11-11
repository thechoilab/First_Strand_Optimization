# TSO Revision 1

- mcSCRB-seq protocol (https://www.protocols.io/view/mcscrb-seq-protocol-p9kdr4w) -> note that in this protocol the first strand synthesis/template switch concentrations are double the final concentration
- http://core-genomics.blogspot.com/2012/04/how-do-spri-beads-work.html

## First Strand Synthesis and Template Switch

1. Add the following reagents:

   | Reagent                                              | Volume (uL)   |
   | ---------------------------------------------------- | ------------- |
   | 5x Maxima buffer                                     | 4             |
   | 1st strand primer pool (~1.5 uM final concentration) | 1             |
   | total RNA                                            | 10 ug (14 uL) |
   | **Total**                                            | **18**        |

2. Place samples in thermo-cycler and run the following cycle:  **70°C 1 min, 65°C 5 min, 4°C Hold**

3. Make the enzyme dNTP mix for each sample as detailed below:

| Reagent (final concentration per protocol in parentheses)    | Volume (uL) |
| ------------------------------------------------------------ | ----------- |
| 5X Maxima buffer                                             | 4           |
| 25 mM dNTP mix (25 mM of each dNTP; final conc = 1 mM mcSCRB-seq protocol, 0.5 mM Dwyer protocol, 1 mM Smart3Seq protocol, 0.5 mM Thermo protocol -> try 1 mM for now) | 1.6         |
| 50% PEG 8000 mix (7.5% mcSCRB-seq)                           | 0           |
| TSO 50 uM stock (2 uM mcSCRB-seq, 1 uM Smart3Seq protocol -> try 1 uM for now) | 1.6         |
| 200 U/uL Maxima H Minus RT (2 U/uL mcSCRB-Seq, 10 U/uL Thermo protocol -> try 10 U/uL for now) | 1.5         |
| ddH2O                                                        | 11.3        |
| **Total**                                                    | **20**      |

5. Directly add 20 uL dNTP mix to the template/primer mix on ice
   - **Note:** Maintaining a temperature of **55-60°C** is crucial for minimizing non-specific primer annealing and thus off-target 1st stand products. <- Not sure about this still actually, but test at a future date
6. Transfer the tubes to a preheated thermocycler at **50°C**. Allow the 1st strand synthesis reaction to proceed for **90 min**
7. Incubate sample at **85°C** for 5 minutes to inactivate the enzyme
   - Huang et al 2013 (NAR) and Okello et al 2010 (PLoS One) shows RT enzyme severely inhibits the PCR reaction which is reason to inactivate it
4. Purify the DNA at this step using **SPRI bead purification** at 1.6X.

## Exonuclease I Treatment

Since the unextended primer cannot be sequenced, we can have a less stringent purification than biotin-streptavidin now.

1. Prepare the following reaction mix:

| Reagent                  | Volume (uL) |
| ------------------------ | ----------- |
| cDNA                     | 17 uL       |
| 10X Exonuclease I buffer | 2 uL        |
| Exonuclease I            | 1 uL        |

2. Place samples in thermo-cycler and run the following cycle: **37°C 45 min (ExoI digest), 80°C 15 min (heat inactivate), 4°C Hold**
   - Timing based of off considerations of Enroth et al 2019, NEB protocol, mcSCRB protocol
3. Consider purifying before PCR at this step.

## Things to consider optimizing

- Temperature (55,60, 65)
- 1st strand synthesis time
- Purification after exonuclease I treatment before PCR
- +PEG (7.5%)
- +Trehalose (0.6M)
- +Betaine (1M)