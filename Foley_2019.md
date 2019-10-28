# From mcSCRB-Seq, Smart-3Seq

- mcSCRB-seq protocol (https://www.protocols.io/view/mcscrb-seq-protocol-p9kdr4w) -> note that in this protocol the first strand synthesis/template switch concentrations are double the final concentration
- http://core-genomics.blogspot.com/2012/04/how-do-spri-beads-work.html

## First Strand Synthesis and Template Switch

1. Add the following reagents:

   | Reagent                | Volume (uL) |
   | ---------------------- | ----------- |
   | 5x Maxima buffer       | 4           |
   | 1st strand primer pool | 2           |
   | total RNA              | 10 ug       |
   | **Total**              | **20**      |

2. Place samples in thermo-cycler and run the following cycle:  **70°C 1 min, 65°C 5 min, 60°C Hold**

3. Make the enzyme dNTP mix for each sample as detailed below:

| Reagent (final concentration per protocol in parentheses)    | Volume (uL) |
| ------------------------------------------------------------ | ----------- |
| 5X Maxima buffer                                             | 4           |
| 25 mM dNTP mix (25 mM of each dNTP; final conc = 1 mM mcSCRB-seq protocol, 0.5 mM Dwyer protocol, 1 mM Smart3Seq protocol, 0.5 mM Thermo protocol -> try 1 mM for now) | 1.6         |
| 50% PEG 8000 mix (7.5% mcSCRB-seq)                           | 6           |
| TSO 50 uM stock (2 uM mcSCRB-seq, 1 uM Smart3Seq protocol -> try 1 uM for now) | 0.8         |
| 200 U/uL Maxima H Minus RT (2 U/uL mcSCRB-Seq, 10 U/uL Thermo protocol -> try 10 U/uL for now) | 2           |
| ddH2O                                                        | 5.6         |
| **Total**                                                    | **20**      |

4. Heat dNTP mix to **60°C** by placing it in the thermo-cycler containing the template/primer mix
5. Directly add 20 uL dNTP mix to the template/primer mix, ensuring that both samples are kept at **60°C**
   - **Note:** Maintaining a temperature of **55-60°C** is crucial for minimizing non-specific primer annealing and thus off-target 1st stand products.
6. Allow the 1st strand synthesis reaction to proceed for **90 min** (vs 90 min in mcSCRB protocol)
7. Incubate sample at **85°C** for 5 minutes to inactivate the enzyme
   - Will likely eliminate RNA hydrolysis step in the future but do it for now for sake of equivalent comparison. Elute in 18 uL DEPC H2O on this step (save 1 uL for analysis).
   - Huang et al 2013 (NAR) and Okello et al 2010 (PLoS One) shows RT enzyme severely inhibits the PCR reaction which is reason to inactivate it

Purify the DNA at this step with the column purification method from the original MPE-Seq protocol

- Sasaki et al 2007 (NAR) shows that exonuclease I is significantly inhibited by PEG
- Okello et al 2010 (PLoS One) suggests that PCI Microcon results in higher yield PCR than the Zymo-like ethanol-based MinElute

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