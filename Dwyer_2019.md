# From Dwyer 2019 correspondence

 In the original method, replace **First Strand Synthesis** with the following:

**Primer Annealing:**

1. Make a primer/template mix for each sample as detailed below:

| Reagent                        | Volume (uL) |
| ------------------------------ | ----------- |
| 5x SSIV buffer                 | 4           |
| 1 ug primer (80 nM per primer) | 2           |
| 10 ug                          |             |
| ddH2O                          | to 20 uL    |
| **Total**                      | **20**      |

2. Place samples in thermo-cycler and run the following cycle: **70°C 1 min, 65°C 5 min, 55°C Hold**
3. Make the enzyme dNTP mix for each sample as detailed below (this is following the Invitrogen Superscript IV protocol):

| Reagent                                                      | Volume (uL) |
| ------------------------------------------------------------ | ----------- |
| 5X SSIV buffer                                               | 4 uL        |
| 0.1 M DTT                                                    | 2 uL        |
| low-dTTP mix [10 mM dATP, 10 mM dCTP, 10 mM dGTP, 6 mM dTTP] | 2 uL        |
| 1 mM biotin-11-dUTP                                          | 8 uL        |
| SSIV MMLV enzyme                                             | 2 uL        |
| ddH2O                                                        | 2 uL        |

Here the biotin-11-dUTP + TTP concentration is at 10 mM combined.

4. Heat dNTP Enzyme mix to **55°C** by placing it in the thermo-cycler containing the template/primer mix
5. Directly add 20uL dNTP mix to the template/primer mix, ensuring that both samples are kept at **55°C**
   - **Note:** Maintaining a temperature of **50-55°C** is crucial for minimizing non-specific primer annealing and thus off-target 1st stand products.
6. Allow the 1st strand synthesis reaction to proceed for 10 min at **55°C**

7. Incubate sample at **80°C** for 10 min to inactivate the enzyme
   - **Note:** Sample volume is now 40uL
   - This is a good stopping point for Day 1- put samples at -20°C (or you can go through the RNA hydrolysis step as well and then freeze at -20°C). 
   - **Everything else is the same, except the coupling step is unnecessary. Therefore, during the column clean-up after RNA hydrolysis we elute with 50 µL and go straight into the bead purification.**

# Things to consider optimizing