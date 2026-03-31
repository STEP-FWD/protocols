# EBL - Raith Elphy Plus using single-layer PMMA

**Authors:** [Ediz Herkert](https://orcid.org/0000-0003-3040-8077)

---

# Description

This STEP protocol defines the process parameters for fabricating patterns up to 250 μm in size with a resolution of approximately 30 – 50 nm [A1]. It is based on a single-layer PMMA resist and carried out using a 30 kV Raith Elphy Plus electron-beam lithography system. Although primarily developed for lift-off applications, the process can also be applied to fabricate etching masks.

---

# Protocol

## 1. Substrate cleaning

#### Materials and equipment (ME)
* Beakers with spout for acetone 
* Crystalizing dishes with spout for isopropanol and distilled water

#### Parameters and ranges (PR)

#### Issues, warnings, troubleshooting and difficulties (IWTD)
* *WARNING*: Acetone is flammable and irritating. All following sub tasks *MUST* be carried out in a fume hood.

#### Validation and expected outcomes (VEO)

---

### 1.1 Acetone immersion

Immerse the substrate in an acetone beaker. Close the beaker with tin foild to avoid acetone evaporation.

#### Materials and equipment (ME)
* Acetone (Scharlab AC0311)
* Tin foil
* Beaker with spout
* Sonicator (optional)

#### Parameters and ranges (PR)
* **Temperature:** Room temperature (heating up acetone to 50ºC and longer sonication times have been tried without noticeable differences)
* **Time:** 15 min

#### Issues, warnings, troubleshooting and difficulties (IWTD)
* Gentle sonication improves the cleaning if your sample can withstand it
* The acetone beaker should be full enough to be stable in the sonication bath

#### Validation and expected outcomes (VEO)

---

### 1.2 Isopropanol rinsing

Rinse the front and back of your substrate for ~30 s with isopropanol while holding the substrate with a tweezer.

#### Materials and equipment (ME)
* Isopropanol (Scharlab AL0311)
* Crystalizing dish with spout 
* Tweezer

#### Parameters and ranges (PR)
* **Time**: 15 – 30 s is the typical time required for this step

#### Issues, warnings, troubleshooting and difficulties (IWTD)
* Rinse the substrate with isopropanol before the acetone has evaporated

#### Validation and expected outcomes (VEO)

---

### 1.3 Distilled water rinsing

Rinse the front and back of your substrate for ~30 s with distilled water while holding the substrate with a tweezer.

#### Materials and equipment (ME)
* Distilled water
* Crystalizing dish with spout 
* Tweezer

#### Parameters and ranges (PR)
* **Time**: 15 – 30 s is the typical time required for this step

#### Issues, warnings, troubleshooting and difficulties (IWTD)
* Rinse the substrate with water before the isopropanol has evaporated
* Typically, it is not recommend to rinse with water after isopropanol because it leaves water residues. However, we found that the isopropanol that we used has left some residues on the substrates.

#### Validation and expected outcomes (VEO)

---

### 1.4 Substrate dehydration

#### Materials and equipment (ME)
* Hot plate

#### Parameters and ranges (PR)
* **Time**: 3 - 5 min 
* **Temperature**: 150 - 180°C

#### Issues, warnings, troubleshooting and difficulties (IWTD)
* Ensure good thermal contact between substrate and (clean) hot plate.

#### Validation and expected outcomes (VEO)
It is good practice to inspect your substrate after cleaning with the microscope. Especially, darkfield images can show any residual debris. Normally, there  should be no visible debris. Be aware that you might see debris from the microscopy slide below your (transparent) substrate.

---

## 2. Spin-coat resists 

#### Materials and equipment (ME)
We use a spin coater and a micropipette (20 – 200 µl) with a fresh tip for each chemical

#### Parameters and ranges (PR)
A 3–5 min dehydration bake at 150–180 °C improves resist adhesion if the sample was not dehydrated the same day [[1]](https://www.epfl.ch/research/facilities/cmi/equipment/ebeam-lithography/raith-ebpg5000/ebeam-resists-available-in-cmi/mma-pmma-resists/
). 

#### Issues, warnings, troubleshooting and difficulties (IWTD)
* *WARNING*: The PMMA solvents are often corrosive, flammable, and irritating
* All following sub tasks MUST be carried out in a fume hood
* It is mandatory to use a fresh pipette tip for each coating step to prevent contamination

#### Validation and expected outcomes (VEO)

---

### 2.1 Spin-coat PMMA

Spin coat PMMA for 60 s at 4000 rpm.

#### Materials and equipment (ME)
* Spin coater
* 20 – 200 µl micropipette
* PMMA (Allresist AR-P 679.04)

Using a micropipette is not strictly necessary but reduces waste and improves process controllability.

#### Parameters and ranges (PR)
* **Spin time**: 60 s
* **Spin speed**: 2000 - 8000 rpm depending on the required thickness [[2]](./attachments/raith_exposure_parameters.pdf)
* **Volume**: 50 µl for a 10 x 10 mm^2 substrate

#### Issues, warnings, troubleshooting and difficulties (IWTD)
* Take care that there are no bubbles in the resist before spin coating
* Ensure that your substrate is hold in place by a good vacuum

#### Validation and expected outcomes (VEO)

---

# Attachments

## A1: Exemplary structure
20 nm gold dots with about 200 nm pitch achieved using a slightly modified version of the process described here (optimized dose and cold development).
![SEM: 20 nm gold dots, ~200 nm pitch](./attachments/attachment_1.jpg)

## A2: Underexposure
The second pattern was exposed at a 50% higher dose than the first pattern. The first pattern is clearly underexposed as can be seen by badly defined edges and resist residues trapped below the deposited metal film.
![Underexposed pattern](./attachments/attachment_2a.tif)
![Correctly exposed pattern](./attachments/attachment_2b.tif)
