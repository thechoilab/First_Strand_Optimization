# Title: MPE-Seq Protocol (9/2019)

## Materials:

### **Equipment:**

| Equipment           | Description                                                  | Cat#  |
| ------------------- | ------------------------------------------------------------ | ----- |
| Thermo-cycler       |                                                              |       |
| Zymo-5 columns      | Fiberglass columns for nucleic acid purification from Zymogen | D4013 |
| Magnetic Stand      | Preferably 2 stands: 1 that can handle both 1.5mL and 1 that can handle 0.2mL PCR tubes. |       |
| Rotator             | For bead binding incubations                                 |       |
| RT-PCR Machine      | For determining library number of amplification cycles       |       |
| Q-bit               | For library quantification and pooling                       |       |
| Acrylamide gel gear | For library size selection                                   |       |

### **Reagents and Solutions:**

#### **mRNA Fragmentation:**

| Reagent         | Stock Concentration | Vendor | Cat # |
| --------------- | ------------------- | ------ | ----- |
| 10x Stop Buffer | 0.5M EDTA, pH 8.0   |        |       |

| Reagent                                    | Stock Concentration | Vendor | Cat #  |
| ------------------------------------------ | ------------------- | ------ | ------ |
| NEBNext Magnesium RNA Fragmentation Module |                     | NEB    | E6150S |

#### **Fragmentation Purification:**

| Reagent            | Stock Concentration | Vendor | Cat # |
| ------------------ | ------------------- | ------ | ----- |
| RNA Binding Buffer |                     | Zymo   |       |
| RNA Wash Buffer    |                     | Zymo   |       |
| RNA Prep Buffer    |                     | Zymo   |       |

#### **1st strand Strand Synthesis:**

| Reagent                | Stock Concentration                                          | Vendor                      | Cat #  |
| ---------------------- | ------------------------------------------------------------ | --------------------------- | ------ |
| 5X SSIV RT Buffer      |                                                              | ThermoFisher                |        |
| Super Script IV        |                                                              | ThermoFisher                |        |
| 1st strand primer pool | Each primer in pool is at ~80.0 nM (309 for _S. cerevisiae_) | IDT Synthesized             |        |
| DTT                    | 0.1M                                                         | Homemade                    |        |
| Individual dNTPs       | 100mM                                                        | Sigma-Aldrich (Roche)       |        |
| 5-(3-Aminoallyl)-dUTP  | 50mM                                                         | ThermoFisher (Ambion)       | AM8439 |
| Aminoallyl-dNTP mix    | 10mM dATP,dGTP, dCTP, 6mM dTTP, 4mM Aminoallyl dUTP          | Mixed from above components |        |
| DEPC Water             |                                                              | Homemade                    |        |

#### **RNA Hydrolysis:**

| Reagent                 | Stock Concentration   | Vendor   | Cat # |
| ----------------------- | --------------------- | -------- | ----- |
| RNA Hydrolysis Solution | 0.3M NaOH, 0.03M EDTA | Homemade |       |
| Neutralization Solution | 0.3M HCl              | Homemade |       |

#### **Column Purification:**

| Reagent        | Stock Concentration                 | Vendor   | Cat # |
| -------------- | ----------------------------------- | -------- | ----- |
| Binding Buffer | 2M Guanidinium-HCl, 75% Isopropanol | Homemade |       |
| Washing Buffer | 10mM TRIS pH 8.0, 80% Ethanol       | Homemade |       |

#### **Biotin Coupling:**

| Reagent            | Stock Concentration                                          | Vendor       | Cat # |
| ------------------ | ------------------------------------------------------------ | ------------ | ----- |
| Sodium Bicarbonate | 1.0M pH 9.0                                                  | Homemade     |       |
| EZ-link NHS-Biotin | Add 976 uL DMSO to 100 mg(Diluted to 300nmol/uL in DMSO , store 50 uL aliquots in 1.5 mL tubes) | ThermoFisher | 20217 |

#### **Bead Purification:**

| Reagent                          | Stock Concentration                      | Vendor       | Cat #     |
| -------------------------------- | ---------------------------------------- | ------------ | --------- |
| Dyna Beads MyOne Streptavidin C1 | 10mg/mL                                  | ThermoFisher | 65001     |
| 2x Bind and Wash Buffer          | 10mM Tris-HCl pH 7.5, 1mM EDTA, 2M NaCl  | Homemade     |           |
| 1x Bind and Wash Buffer          | 5mM Tris-HCl pH 7.5, 0.5mM EDTA, 1M NaCl | Homemade     |           |
| 1x SSC                           | 150mM NaCl, 15mM Sodium Citrate          | Homemade     | 46-020-CM |
| Denaturing Solution              | 0.1M NaOH                                | Homemade     |           |
| TE Buffer                        | 10mM Tris pH 7.5, 1mM EDTA               | Homemade     |           |
| Bead Elution Buffer              | 95% Formamide, 10mM EDTA, pH 8.2         | Homemade     |           |

#### **1st Strand Strand Extension:**

| Reagent                     | Stock Concentration | Vendor               | Cat #  |
| --------------------------- | ------------------- | -------------------- | ------ |
| 10x NEB Buffer 2            |                     | NEB                  |        |
| Klenow exo-                 | 5000 units/mL       | NEB                  | MO212L |
| dNTPs                       | 10mM each           | Sigma-Aldrich(Roche) |        |
| 1st Strand Extension Primer | 100uM               | IDT?                 |        |

#### **Library qPCR and Amplification:**

| Reagent                     | Stock Concentration | Vendor               | Cat # |
| --------------------------- | ------------------- | -------------------- | ----- |
| 5x Phusion Buffer           |                     | NEB                  |       |
| Phusion Polymerase          |                     | Homemade             |       |
| dNTPs                       | 10mM each           | Sigma-Aldrich(Roche) |       |
| 1st Strand Extension Primer | 100uM               | IDT?                 |       |
| DMSO                        |                     |                      |       |
| Nextera 5XX primer          | 10uM                | IDT?                 |       |
| Nextera 7xx primer          | 10uM                | IDT?                 |       |
| EvaGreen 20X                |                     |                      |       |

**Gel Purification:**

| Reagent                 | Stock Concentration                    | Vendor   | Cat # |
| ----------------------- | -------------------------------------- | -------- | ----- |
| Acrylamide/Bis          | 29:1                                   | VWR      |       |
| 10X TBE                 | 1M Tris, 1M Boric acid, 0.02M EDTA     | Homemade |       |
| 1x TBE                  | 100mM Tris, 100mM Boric acid, 2mM EDTA | Homemade |       |
| 10% APS                 |                                        |          |       |
| TEMED                   |                                        |          |       |
| 1x SyBr Gold            |                                        |          |       |
| 100bp Ladder            |                                        | NEB      |       |
| Gel Extraction Solution | 0.3M Sodium Acetate                    | Homemade |       |
| Glycogen                | 20mg/mL                                |          |       |
| Isopropanol             | 100%                                   |          |       |

## **General Protocols:**

Below are 2 general protocols that are repeated several times throughout the library prep. They are listed here for reference.

### **Column Purification/Clean up:**

1. Add 7 volumes of binding buffer to each sample and mix well
2. Transfer each sample to a **zymo-5** column placed inside a collection tube
3. Spin samples at 14K RPM for **1 min**
4. Discard flow through and place zymo column back in collection tube
5. Wash columns by adding 700uL washing buffer to each column
6. Spin for **1 min** at 14k RPM
7. Discard flow through
8. Repeat washing for a total of 2 washes
9. Dry column by spinning for an additional **1 min** at 14k RPM
10. Add appropriate elution buffer volume to each column and incubate for ~_ **1-2 min** *at RT (see specific step)*
11. Place columns in labeled collection tubes and spin at 14K RPM for **1 min**
12. You now have purified nucleic acid

### **Bead Purification (do all three parts each time used during protocol):**

#### **Bead prep and wash:**

1. Turn on a heat block to 95°C

      2. Vortex beads vigorously to resuspend
      3. Transfer 20uL of beads per sample to be purified into a 1.5mL Eppendorf tube
      4. Place tube on magnetic stand and incubate for **1 min**
      5. While leaving tube on magnetic stand, aspirate buffer
      6. Remove tube from magnetic stand
      7. Wash beads by adding 500uL of 1x bind and wash buffer to tube containing the beads and mix well with a pipette
         8. Place tube on magnetic stand and incubate for **1 min**
         9. Aspirate buffer
         10. Repeat wash for a total of 2 washes
         11. Resuspend beads in 50uL of 2x bind and wash buffer per sample to be purified
         12. Mix beads well with a pipette
         13. Aliquot 50uL of beads into a new tube.  1 for each sample to be purified

#### **Bead Purification:**

##### **Biotin Binding:**

  1. Add each 50uL sample to an aliquot of washed beads
  2. Place on rotator and incubate at RT for **30min**
  3. Place tubes on magnetic stand and incubate for **1 min**
  4. Aspirate buffer
  5. Remove samples from magnetic stand
  6. Add 500uL of 1x bind and wash buffer and mix well with pipette
  7. Place on magnetic stand and incubate for **1 min**
  8. aspirate buffer
  9. repeat washing for a total of **2 washes**
  10. Wash each sample with 100uL 1x SSC, mixing well by pipetting
  11. Place on magnetic stand for **1 min**
  12. Aspirate buffer
  13. Remove samples from magnetic stand

##### **Denaturation of unlabeled strand (Background):**

  1. Add 100uL of denaturing solution to each sample
  2. Incubate each sample for **10min** at **RT**
  3. Place samples on magnetic stand for **1 min** and aspirate buffer
  4. Wash by adding 50uL of denaturation solution to each sample. Mix well by pipetting
  5. Place samples on magnetic stand for **1 min** and aspirate buffer
  6. Add 100uL of TE buffer and mix well with pipette
  7. Place on magnetic stand and incubate for **1 min**
  8. aspirate buffer
  9. Repeat TE buffer wash 2 times for a total of **3** washes

##### **Elution:**

  1. Add 100uL of bead elution buffer (stored at 4C in 50 ml tube covered in foil) to each sample
  2. Incubate samples at **90°C** for **2 min**
  3. Immediately place samples on magnetic stand and incubate for **1 min**
  4. Aspirate each sample and transfer to a new tube

## **Library Prep Protocol:**

### **Poly-A Selection:**

Use NEBNext Poly(A) mRNA Magnetic Isolation Module (E7490S) to enrich for mRNA from 5 ug of RNA

  - **Do 4 tubes of polyA selection on 5 ug of total RNA each** (20 ug total RNA total) per sample to obtain enough mRNA for the first-strand synthesis
  - Expected yield is ~100ng mRNA in 20 uL per tube (400 ng in 80 uL total)

1. Start with 1-5 uL of DNA-free total RNA, dilute total RNA with nuclease free water to a final volume of 50 uL.
2. Aliquot 20 uL of well resuspended NEB Magnetic Oligo Beads in another 0.2 mL PCR tube.
3. Wash beads by adding 100 uL of 2X RNA binding buffer, pipette entire volume up and down 6 times to mix.
4. Place the tube on the magnetic rack at room temperature for 2 minutes or until solution is clear.
5. Remove and discard all supernatant.
6. Remove the tube from the magnetic rack.
7. Repeat steps 3-6 one more time, 2 washes total.
8. Resuspend beads in 50 uL of 2X RNA Binding Buffer and add 50 uL of total RNA sample from step 1.
9. Place tubes on thermal cycler, incubate at 65 **°** C for 5 min and hold at 4 **°** C to denature RNA and facilitate binding to beads. Can remove tubes once temperature reaches 4 **°**
10. Resuspend beads. Pipette up and down slowly 6 times to mix.
11. Place tubes on bench and incubate at room temperature for 5 minutes to allow RNA to bind beads.
12. Resuspend the beads. Pipette up and down slowly 6 times to mix thoroughly.
13. Incubate for 5 more minutes at room temperature to allow the RNA to bind to the beads.
14. Place the tubes on the magnetic rack at room temperature for 2 minutes or until the solution is clear to separate the poly-A RNA bound to the beads from the solution.
15. Remove and discard all of the supernatant. Take care not to disturb the beads.
16. Remove the tubes from the magnetic rack.
17. Wash the beads by adding 200 μl of Wash Buffer to remove unbound RNA. Pipette the entire volume up and down 6 times to mix thoroughly.
18. Place the tubes on the magnetic rack at room temperature for 2 minutes or until the solution is clear.
19. Remove and discard all the supernatant from each well of the plate. Take care not to disturb the beads.
20. Remove the tubes from the magnetic rack.
21. Repeat Steps 18-21.
22. Add 50 μl of Tris Buffer to each tube. Gently pipette the entire volume up and down 6 times to mix thoroughly.
23. Place the tubes on the thermal cycler. Close the lid and heat the sample at 80°C for 2 minutes, then hold at 25°C to elute the poly-A RNA from the beads.
24. Remove the tubes from the thermal cycler when the temperature reaches 25°C.
25. Add 50 μl of 2X RNA Binding Buffer to each sample to allow the RNA to bind to the same beads. Gently pipette the entire volume up and down 6 times to mix thoroughly.
26. Incubate the tubes on the bench at room temperature for 5 minutes.
27. Resuspend the beads. Pipette up and down slowly 6 times to mix thoroughly.
28. Incubate the tubes on the bench at room temperature for 5 more minutes to allow the RNA to bind to the beads.
29. Place the tubes on the magnetic stand at room temperature for 2 minutes or until the solution is clear.
30. Remove and discard all of the supernatant from each tube. Take care not to disturb the beads.
31. Remove the tubes from the magnetic rack.
32. Wash the beads once with 200 μl of Wash Buffer. Gently pipette the entire volume up and down 6 times to mix thoroughly.
33. Place the tubes on the magnetic rack at room temperature for 2 minutes or until the solution is clear.
34. Remove and discard all of the supernatant from each tube. Take care not to disturb the beads.

    - **Note: It is important to remove all of the supernatant to successfully use the RNA in downstream steps. Spin down the tube. Place the tube on the magnetic rack and with a 10 µl tip remove all of the wash buffer. (Caution: Do not disturb beads that contain the mRNA).**
35. Remove the tubes from the magnetic rack.
36. Elute the mRNA from the beads by adding 17 µl of the Tris Buffer, mix by pipetting 6 times and incubating the sample at 80°C for 2 minutes, then hold at 25°C to elute the polyA RNA from the beads. Immediately, place the tubes on the magnetic rack for 2 minutes or until the solution is clear.
37. Collect the purified mRNA by transferring the supernatant to a clean nuclease-free PCR Tube.
38. Place tube on ice.
39. Assess the Yield and the Size Distribution of the purified mRNA. Run 1 µl on the Bioanalyzer using a RNA Pico Chip. You may have to dilute your sample before loading.

### **Assess Yield and Size Distribution of Purified mRNA**

**Bioanalyzer on RNA Pico Chip**

**See Bioanalyzer protocol for reference**

It is recommended to heat denature all RNA samples and RNA ladder before use for 2 min and 70 **°** C (once) and keep them on ice.

- Do not touch the Agilent 2100 Bioanalyzer instrument during analysis and never place it on vibrating surface.
- Always vortex the dye concentrate for 10 s before preparing the gel-dye mix and spin down afterwards.

#### Preparing ladder:

1. Spin the ladder down
2. Heat denature the ladder for 2 min at 70°
3. Immediately cool the vial on ice.
4. Add 90 μL of RNase-free water and mix thoroughly.
5. Prepare aliquots in recommended 0.5 mL RNase-free vials with the required amount for typical daily use.
6. Store aliquots at -70°
7. Before use, thaw ladder aliquots and keep them on ice (avoid extensive warming upon thawing process).

#### Clean the electrodes:

1. Slowly fill one of the wells of the electrode cleaner with 350 μl of fresh RNase-free water.
2. Open the lid and place the electrode cleaner in the Agilent 2100 Bioanalyzer instrument.
3. Close the lid and leave it closed for 5 minutes.
4. Open the lid and remove the electrode cleaner. Label the electrode cleaner and keep it for future use.
5. Wait another 30 seconds to allow the water on the electrodes to evaporate before closing the lid.

#### Preparing the Gel

1. Allow all reagents to equilibrate to room temperature for 30 minutes before use.
2. Place 550 μl of RNA 6000 Pico gel matrix (red ) into the top receptacle of a spin filter.
3. Place the spin filter in a microcentrifuge and spin for 10 minutes at 1500 g ± 20 % (for Eppendorf microcentrifuge, this corresponds to 4000 rpm)
4. Aliquot 65 μl filtered gel into 0.5 ml RNase-free microcentrifuge tubes that are included in the kit. Store the aliquots at 4°C and use them within one month of preparation.

#### Preparing the Gel-Dye Mix

1. Allow all reagents to equilibrate to room temperature for 30 minutes before use. Protect the dye concentrate from light while bringing it to room temperature.
2. Vortex RNA 6000 Pico dye concentrate (blue ) for 10 seconds and spin down.
3. Add 1 μl of RNA 6000 Pico dye concentrate (blue ) to a 65 μl aliquot of filtered gel (prepared as described in &quot;Preparing theGel&quot; n page 15).
4. Cap the tube, vortex thoroughly and visually inspect proper mixing of gel and dye. Store the dye concentrate at 4°C in the dark again.
5. Spin tube for 10 minutes at room temperature at 13000 g (for Eppendorf microcentrifuge, this corresponds to 14000 rpm). Use prepared gel-dye mix within one day.

#### Loading Gel-Dye Mix

1. 1 Allow the gel-dye mix to equilibrate to room temperature for 30 minutes before use. Protect the gel-dye mix from light during this time.
2. Take a new RNA chip out of its sealed bag.
3. Place the chip on the chip priming station.
4. Pipette 9.0 μl of the gel-dye mix at the bottom of the well marked and dispense the gel-dye mix.
5. Set the timer to 30 seconds, make sure that the plunger is positioned at 1 ml and then close the chip priming station. The lock of the latch will click when the chip priming station is closed correctly.
6. Press the plunger of the syringe down until it is held by the clip.
7. Wait for exactly 30 seconds and then release the plunger with the clip release mechanism.
8. Visually inspect that the plunger moves back at least to the 0.3 ml mark.
9. Wait for 5 seconds, then slowly pull back the plunger to the 1 ml position.
10. Before loading the gel-dye mix, make sure that the base plate of the chip priming station is in position (C) and the adjustable clip is set to the highest position. Refer to &quot;Setting up the Chip Priming Station&quot; n page 8 for details.
11. When pipetting the gel-dye mix, make sure not to draw up particles that may sit at the bottom of the gel-dye mix vial. Insert the tip of the pipette to the bottom of the chip well when dispensing. This prevents a large air bubble forming under the gel-dye mix. Placing the pipette at the edge of the well may lead to poor results.
12. Open the chip priming station.
13. Pipette 9.0 μl of the gel-dye mix in each of the wells marked.

#### Loading the RNA 6000 Pico Conditioning Solution and Marker

1. Pipette 9 μl of the RNA 6000 Pico conditioning solution (white ) into the well marked CS.
2. Pipette 5 μL of the RNA 6000 Pico marker (green) into the well marked with a ladder (symbol) and each of the 11 sample wells.
3. Vortex for 60 seconds at 2400 rpm
4. Refer to the next topic on how to insert the chip in the Agilent 2100 Bioanalyzer instrument. Make sure that the run is started within 5 minutes.

#### Cleaning Electrodes after a RNA 6000 Pico Chip Run

1. Slowly fill one of the wells of the electrode cleaner with 350 μl of fresh RNase-free water.
2. Open the lid and place the electrode cleaner in the Agilent 2100 bioanalyzer.
3. Close the lid and leave it closed for 30 s.
4. Open the lid and remove the electrode cleaner.
5. Wait another 30 seconds to allow the water on the electrodes to evaporate before closing the lid.

#### Loading the Diluted Ladder and Samples

1. To minimize secondary structure, you may heat denature (70 ÆC, 2 minutes) the samples before loading on the chip.
2. 2 Before use, thaw ladder aliquots and keep them on ice (avoid extensive warming upon thawing process).
3. Pipette 1 μl of the diluted RNA 6000 Pico ladder (prepared as described in &quot;Preparing the RNA Ladderafter Arrival&quot; n page 13) into the well marked with the ladder symbol
4. Pipette 1 μl of each sample into each of the 11 sample wells.
5. Place the chip horizontally in the adapter of the IKA vortex mixer and make sure not to damage the bulge that fixes the chip during vortexing. If there is liquid spill at the top of the chip, carefully remove it with a tissue.
6. Vortex for 60 seconds at 2400 rpm.
7. Refer to the next topic on how to insert the chip in the Agilent 2100 Bioanalyzer instrument. Make sure that the run is started within 5 minutes.

### **DNA fragmentation**

Starting Material: 4 tubes of purified mRNA (50–250 ng). Do separate preps of this for each of the 4 tubes.

1. Mix the following components in a sterile PCR tube:

| **Reagent**                    | **Volume (uL)** |
| ------------------------------ | --------------- |
| Purified Poly-A mRNA           | 17              |
| RNA Fragmentation Buffer (10X) | 2               |
| DEPC MiliQ water               | 1               |
| **Total**                      | **20**          |

1. Incubate in a preheated thermal cycler for **5 minutes** at 94 C
2. IMMEDIATELY transfer tube to ice and add 2 uL chilled 10X RNA Fragmentation Stop Solution

#### **Fragment Purification**

1. Mix the following components in a sterile 1.5 mL tube:

| **Reagent**        | **Volume (uL)** |
| ------------------ | --------------- |
| Fragmented RNA     | 22              |
| RNA Binding Buffer | 44              |
| 100% Ethanol       | 66              |
| **Total**          | **142**         |

1. Combine all 4 tubes: transfer all 4 tubes into a single Zymo-Spin IC Column in Collection Tube and centrifuge for 30 seconds at 14K RPM,. Discard flow-through.
2. Add 400 uL RNA Prep Buffer, centrifuge for 30 seconds at 14K RPM. Discard flow-through.
3. Add 700 uL RNA Wash Buffer, centrifuge for 30 seconds at 14K RPM. Discard flow-through.
4. Add 400 uL RNA Wash Buffer, centrifuge for 2 minutes at 14K RPM. Transfer column into a new tube.
5. Add 14 uL DEPC MiliQ Water and centrifuge for 30 seconds.

### **First Strand Synthesis:**

Library prep starts with 10 ug of total RNA input per sample (use 10ul from the DNase step above).

#### **Primer Annealing:**

1. Make a primer/template mix for each sample as detailed below:


| Reagent                | Volume (uL)           |
| ---------------------- | --------------------- |
| 5X RT buffer           | 4                     |
| 1st strand primer pool | 2                     |
| Total RNA              | whole 14ul from above |
| total                  | **20**                |

1. Place samples in thermo-cycler and run the following cycle: **70°C 1 min, 65°C 5 min, 55°C Hold**
2. Make the enzyme dNTP mix for each sample as detailed below (this is following the Invitrogen Superscript IV protocol):

| Reagent                    | Volume (uL) |
| -------------------------- | ----------- |
| 5X RT buffer               | 4           |
| DTT                        | 2           |
| Aminoallyl-dNTP mix        | 2           |
| Superscript IV MMLV enzyme | 2           |
| ddH20                      | 10          |
| Total                      | **20**      |

1. Heat dNTP Enzyme mix to **55°C** by placing it in the thermo-cycler containing the template/primer mix
2. Directly add 20uL dNTP mix to the template/primer mix, ensuring that both samples are kept at **55°C**

   - **Note:** Maintaining a temperature of 50-55°C is crucial for minimizing non-specific primer annealing and thus off-target 1st stand products.
3. Allow the 1st strand synthesis reaction to proceed for 10 min at 55°C
4. Incubate sample at **80°C** for 10 min to inactivate the enzyme
   - **Note:** Sample volume is now 40uL

**This is a good stopping point for Day 1- put samples at -20C (or you can go through the RNA hydrolysis step as well and then freeze at -20C).**

### **Day 2:**

### **RNA Hydrolysis:**

Perform RNA hydrolysis to digest template RNA, leaving only the 1st strand cDNA products

      1. Add 20 uL of RNA hydrolysis solution to each sample
      2. Incubate at **65°C** for **15 min**
         3. Add 20uL of neutralization solution to each sample
            - **Note:** Sample volume is now 80 uL

4. Perform **column clean up** as detailed in the protocol above
5. Elute each sample with 16uL DEPC H20 
   - Can save uL for analysis

### **Aminoallyl Biotin Coupling:**

In this step biotin will be coupled to the aminoallyl groups incorporated into the 1st strand synthesis products to enable purification away from un-extended 1st strand primers

1. To each sample add:

   1. Add 2uL of sodium bicarbonate to each sample
   2. Add 2uL of NHS-biotin to each sample
2. Incubate sample at **65°C** for **1 hour** in the dark
   - **Note:** Perform the next few steps quickly to prevent biotin precipitation
3. Briefly spin tubes in a table top centrifuge, then place them back at **65°C** for 30 sec
4. Add 40uL pre-warmed ddH20 (warm to **65°C** first)
   - **Note:** Sample volume is now 60uL
5. Perform column cleanup  (use 420ul column binding buffer)
6. Elute in 50uL DEPC H20
7. Perform **streptavidin bead purification** n each sample
8. Perform **column purification** and elute in 40uL DEPC H20
9. You now have purified 1st strand cDNA
10. The protocol can be paused here by storing the samples at -20°C

### 1st Strand Extension
1. Prepare the following reaction mix for each sample:

| Reagent                     | Volume (uL) |
| --------------------------- | ----------- |
| 10X NEB Buffer 2            | 5           |
| 10mM dNTP Mix               | 1           |
| cDNA from previous          | 40          |
| 1st Strand Extension Primer | 1           |
| Total                       | 47          |

2. Incubate each sample at **65°C** for **2 min**.
3. Cool samples to RT by placing on bench top for **~5min**.
4. Add 3 uL of Klenow exo- enzyme to each sample.
5. Incubate samples at **25°C** (room temperature) **for** 5 min
6. Heat samples to **37°C** and incubate for **30 min**  (can stop here and place samples at -20C)
7. Perform **streptavidin bead purification** n each sample
8. Perform **column purification** n each sample eluting with 33uL of DEPC H20
9. You now have a library ready for PCR amplification
10. This is also a safe stopping point. Samples can be stored at **-20° C**
11. Continue to library amplification

### **Library Amplification:**

#### **qPCR:**

This step is performed to determine the number of cycles to amplify each sample

1. Perform triplicate qPCR reactions on each sample by mixing the following qPCR reaction mix:

##### Using Phusion

| Reagent                      | Volume (uL) |
| ---------------------------- | ----------- |
| 5X Phusion Buffer            | 10          |
| dNTP Mix (10mM dNTPs)        | 1           |
| 1st Strand Extension Product | 2           |
| Nextera 5xx Primer           | 2.5         |
| Nextera 7xx Primer           | 2.5         |
| Phusion Polymerase           | 0.5         |
| DMSO                         | 0.5         |
| SyBr Green/EvaGreen          | 0.5         |
| H2O                          | 30.5        |
| Total                        | 50 uL       |

##### Using KAPA

| Reagent                      | Volume (uL) |
| ---------------------------- | ----------- |
| 2X KAPA Master Mix           | 25          |
| 1st Strand Extension Product | 2           |
| Nextera 5xx Primer           | 2.5         |
| Nextera 7xx Primer           | 2.5         |
| DMSO                         | 0.5         |
| SyBr Green/EvaGreen          | 0.5         |
| H2O                          | 17          |
| Total                        | 50 uL       |

2. Aliquot 15uL of each qPCR reaction mix into 3 separate wells of a qPCR plate
3. Perform the following qPCR cycling:

##### Using Phusion

| **Denaturation:**                                            |
| ------------------------------------------------------------ |
| 98°C        30 s                                             |
| **Amplification (40x):**                                     |
| 98 °C        10 sec<br />62 °C        20 sec<br />72 °C        30 sec |
| **Final elongation:**                                        |
| 72 °C        3 min<br />4 °C        Hold                     |

**Using KAPA**

| **Denaturation:**                                            |
| ------------------------------------------------------------ |
| 98°C        45 s                                             |
| **Amplification (40x):**                                     |
| 98 °C        15 sec<br />62 °C        30 sec<br />72 °C        30 sec |
| **Final elongation:**                                        |
| 72 °C        1 min<br />4 °C        Hold                     |



4. After the qPCR calculate the Ct value for each sample and average the 3 values for each library
5. Calculate the number of amplification cycles to perform by adding 3 to the average Ct value and rounding to the nearest whole number.

- **Note:** This cycle number will vary from sample to sample by a few cycles. A good _S. cerevisiae_ library should have a Ct of ~12-16 cycles (15-19 cycles after addition of 3).  Experiments in our lab have determined that if a library has a Ct of greater than 18, the libraries are likely low quality.  Generally, this means a high proportion of 1st strand and 1st strand extension primer dimer reads will be present in the sequencing data.

#### **PCR Amplification:**

1. For each sample, prepare the following PCR reaction mix:

##### Using Phusion

| Reagent                      | Volume (uL) |
| ---------------------------- | ----------- |
| 5x Phusion Buffer            | 10          |
| dNTP Mix                     | 1           |
| 1st Strand Extension Product | 10          |
| Nextera 5xx Primer           | 2.5         |
| Nextera 7xx Primer           | 2.5         |
| Phusion Polymerase           | 0.5         |
| DMSO                         | 0.5         |
| H2O                          | 23          |
| Total                        | 50          |

##### Using KAPA

| Reagent                      | Volume (uL) |
| ---------------------------- | ----------- |
| 2X KAPA Master Mix           | 25          |
| 1st Strand Extension Product | 10          |
| Nextera 5xx Primer           | 2.5         |
| Nextera 7xx Primer           | 2.5         |
| DMSO                         | 0.5         |
| H2O                          | 9.5         |
| Total                        | 50          |

1. Run the following cycling conditions on each PCR reaction mix:

##### Using Phusion

| **Denaturation:**                                            |
| ------------------------------------------------------------ |
| 98°C        30 s                                             |
| **Amplification (Cycle # determined in step 5 of qPCR):**    |
| 98 °C        10 sec<br />62 °C        20 sec<br />72 °C        30 sec |
| **Final elongation:**                                        |
| 72 °C        3 min<br />4 °C        Hold                     |

##### **Using KAPA **

| **Denaturation:**                                            |
| ------------------------------------------------------------ |
| 98°C        45 s                                             |
| **Amplification (Cycle # determined in step 5 of qPCR):**    |
| 98 °C        15 sec<br />62 °C        30 sec<br />72 °C        30 sec |
| **Final elongation:**                                        |
| 72 °C        1 min<br />4 °C        Hold                     |

### Ampure bead size selection

Purify with Ampure beads. Do with Ampure bead ratio of 0.8.

https://www.neb.com/protocols/2015/09/16/protocol-for-use-with-nebext-ultra-ii-dna-library-prep-kit-for-illumina-and-with-sample-purification-beads-e7645-e7103

https://www.neb.com/protocols/1/01/01/size-selection-using-ampure-xp-beads-e7330

