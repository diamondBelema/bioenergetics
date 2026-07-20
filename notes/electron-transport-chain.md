# Electron Transport Chain

## Overview

The electron transport chain (ETC) describes how electrons captured by NAD and other biological reductants are transferred through several electron carriers until eventually transferred to oxygen by cytochrome oxidase with concomitant efflux of protons into the intermembrane space.

## Mitochondrial Structure

### Outer Membrane
- Contains porin channel proteins
- Permeable to molecules up to 10 kDa

### Inner Mitochondrial Membrane
- Highly impermeable to most small ions and molecules including H⁺
- Has large infoldings called cristae
- Site of oxidative phosphorylation and electron transport
- Specialized transporter proteins for substrate entry (e.g., pyruvate)

### Intermembrane Space (IMS)
- Between outer and inner membranes
- Site of proton accumulation during ETC

### Central Matrix
- Site of numerous metabolic reactions
- Includes citric acid cycle and fatty acid breakdown

---

## The Four Complexes

### Complex I (NADH:Ubiquinone Oxidoreductase / NADH Dehydrogenase)

- Catalyzes transfer of hydride ion and 2e⁻ from NADH to FMN
- Electrons passed through series of Fe-S proteins
- Energy released drives translocation of 4 H⁺ from matrix to IMS
- Electrons passed to coenzyme Q (ubiquinone) which carries to Complex III

**Inhibitors:**
- Rotenone
- Metformin
- Amytal

### Complex II (Succinate–Ubiquinone Reductase / Succinate Dehydrogenase)

- Couples oxidation of succinate to fumarate with reduction of ubiquinone
- FADH₂ generated from succinate oxidation
- 2e⁻ transferred through Fe-S proteins to reduce ubiquinone to ubiquinol
- Does NOT pump protons
- Electrons entering via FADH₂/succinate bypass first proton pump

**Inhibitors:**
- Carboxin
- TTFA (thenoyltrifluoroacetone)

### Complex III (Ubiquinone:Cytochrome c Oxidoreductase / Cytochrome bc₁ Complex)

- Couples transfer of electrons from ubiquinol to cytochrome c
- Dimer with monomeric units containing cyt b, cyt c₁, and Rieske iron-sulfur protein
- Oxidation of 2 ubiquinone molecules coupled with transport of 4 protons to IMS
- 2 electrons transferred to cytochrome c

**Inhibitors:**
- Antimycin A
- Myxothiazol

### Complex IV (Cytochrome Oxidase)

- Carries electrons from cyt c to molecular oxygen
- Converts O₂ to H₂O
- Every 4 electrons passing through generate 2 H₂O molecules
- Transfer of 4 H⁺ from matrix to IMS

**Inhibitors:**
- Cyanide (CN⁻)
- Carbon monoxide (CO)
- Hydrogen sulfide (H₂S)
- Azide (N₃⁻)

---

## Electron Flow and Reduction Potentials

| Component | Approx. E°' (Volts) | Function |
|-----------|---------------------|----------|
| NAD⁺/NADH | -0.32 V | Entry point; electron donor |
| FMN/FMNH₂ | ~-0.30 V | Accepts from NADH (Complex I) |
| Fe-S clusters | ~-0.3 to +0.05 V | Multiple within Complex I and III |
| Coenzyme Q (Ubiquinone) | ~+0.045 V | Lipid-soluble mobile carrier |
| Cytochrome b | ~+0.07 V | Complex III |
| Cytochrome c₁ | ~+0.22 V | Transfers to cytochrome c |
| Cytochrome c | +0.25 V | Small soluble protein carrier |
| Complex IV (Cytochrome aa₃) | ~+0.29 to +0.40 V | Sequentially higher within complex |
| O₂/H₂O | +0.82 V | Final electron acceptor |

### Key Points

- Electrons flow from more negative to more positive E°'
- Flow releases energy used to pump protons at Complexes I, III, and IV
- Oxygen (O₂) is ultimate electron acceptor with highest reduction potential (+0.82 V)
- Makes aerobic respiration highly efficient

---

## Proton Pumping

For each pair of electrons transferred to oxygen:
- Complex I: 4 H⁺ pumped
- Complex III: 4 H⁺ pumped
- Complex IV: 2 H⁺ pumped

**Total: 10 H⁺ per NADH**

---

## ATP Synthesis Theories

### 1. Chemical Coupling Theory (Slater, 1953)

- Energy captured in high-energy covalent chemical intermediates
- Intermediates transfer phosphate to ADP to form ATP
- **Status**: Rejected - no phosphorylated intermediates ever identified

### 2. Chemiosmotic Coupling Theory (Mitchell, 1961) - ACCEPTED

- Electron transport and ATP synthesis coupled by proton gradient
- Proton-motive force (PMF) across inner mitochondrial membrane

**Key Postulates:**
1. Inner mitochondrial membrane impermeable to H⁺ under normal conditions
2. ETC through Complexes I, III, IV pumps protons from matrix to IMS
3. Protons can only re-enter matrix through ATP synthase (Complex V)
4. Proton flow down electrochemical gradient drives ATP synthesis

**Evidence:**
- Membrane disruption abolishes ATP synthesis
- Artificial proton gradients can drive ATP synthesis
- Uncoupling agents dissipate gradient, abolish ATP synthesis
- Oligomycin blocks F₀ channel, gradient still builds

### 3. Conformational Coupling Theory (Boyer, 1964)

- Free energy stored as conformational change in mitochondrial membrane protein
- Strained protein drives ATP synthesis when it relaxes
- **Status**: Partially correct - evolved into Binding Change Mechanism

### 4. Binding Change Mechanism (Boyer, 1979-1994) - MOLECULAR MODEL

- Explains molecular mechanism of ATP synthase function
- Extension and refinement of chemiosmotic theory

---

## ATP Synthase (F₀F₁-ATPase)

### Structure

**F₀ Domain (Membrane-Embedded):**
- Ring of 10-14 c subunits in inner mitochondrial membrane
- Contacts single a subunit
- Links to two b subunits and δ subunit
- Forms column connecting to F₁ head

**F₁ Domain (Peripheral Membrane Protein):**
- Five types of polypeptides: α₃β₃γδε
- Three β subunits alternate with α subunits in ring
- Central stalk formed by γ and ε subunits

### Mechanism

1. Protons flow through F₀ down electrochemical gradient
2. Drives rotation of c-ring (~100 revolutions/second)
3. Rotation transmitted to γ subunit (asymmetric camshaft)
4. γ subunit induces sequential conformational changes in three β subunits
5. Each complete 360° rotation generates 3 ATP molecules

### Three Catalytic States of β Subunits

| State | Conformation | Function |
|-------|--------------|----------|
| Open (βO) | Open/empty | Releases ATP; binds ADP + Pi loosely |
| Loose (βL) | Loose | Binds ADP + Pi with moderate affinity |
| Tight (βT) | Tight/closed | Synthesizes ATP (spontaneously formed) |

### Key Insight

- ATP formation from ADP + Pi on enzyme requires little free energy
- ATP spontaneously formed in tight conformation
- Proton-motive force used primarily to release tightly bound ATP
- Energy drives product release, not bond formation

---

## P/O Ratio and ATP Yield

| Electron Carrier | H⁺ Pumped | ATP Produced (P/O Ratio) |
|------------------|-----------|--------------------------|
| NADH | 10 H⁺ | ~2.5 ATP |
| FADH₂ | 6 H⁺ | ~1.5 ATP |

---

## Transport Across Inner Mitochondrial Membrane

### ATP-ADP Translocase

- Exports ATP from matrix
- Imports ADP into matrix
- 1 ATP exits for 1 ADP entering
- Moves out 4 negative charges against 3 moving in
- Favors electrochemical gradient

### Phosphate Translocase

- Imports Pi in exchange for OH⁻ exiting
- Favored by transmembrane proton gradient

### ATP Synthasome

- Association of ATP synthase with transport proteins
- Provides safe passage for protons into matrix
- Coupled to ADP phosphorylation

---

## Mitochondrial Uncouplers

### What Are Uncouplers?

- Provide alternative proton-conducting pathway bypassing ATP synthase
- Uncouple electron transport from ATP synthesis
- Electron flow and O₂ continue, but ATP production reduced/halted

### Consequences of Uncoupling

- Proton gradient dissipates rapidly → ATP synthesis stops
- Electron transport continues unimpeded (O₂ consumption increases)
- Energy released dissipated as heat
- Metabolic rate increases dramatically
- Results in hyperthermia, hyperventilation, diaphoresis, metabolic acidosis

### Chemical Uncouplers (Protonophores)

**2,4-Dinitrophenol (DNP):**
- Lipid-soluble weak acid
- Protonated form diffuses from IMS to matrix, releases H⁺
- Returns as anion via non-specific transport
- Historically marketed as weight-loss drug (1930s)
- Banned by FDA after fatal toxicity reports
- Re-emerged as illicit "fat-burner"

**Other Chemical Uncouplers:**
- CCCP (carbonyl cyanide m-chlorophenyl hydrazone)
- FCCP (carbonyl cyanide p-trifluoromethoxyphenyl hydrazone)
- 2,4-Dinitrocresol
- Valinomycin (potassium ionophore)
- High-dose aspirin (salicylate)

### Physiological Uncoupler: Thermogenin (UCP1)

- Uncoupling Protein 1 (UCP1)
- 33 kDa protein in inner mitochondrial membrane of brown adipose tissue (BAT)

**Properties:**
- Location: Inner mitochondrial membrane of brown adipocytes only
- Function: Transports protons back into matrix → dissipates PMF as heat
- Activators: Free fatty acids, norepinephrine (via β-adrenoceptors and cAMP)
- Inhibitors: GDP, GTP (purine nucleotides lock UCP1 in closed state)
- Physiological role: Thermoregulation in newborns, cold adaptation

**Clinical High-Yield:**
- Newborns have abundant brown fat in interscapular region, mediastinum, perirenal areas
- UCP1-mediated thermogenesis critical for maintaining core body temperature
- Neonates cannot shiver effectively due to underdeveloped skeletal muscle

**Other UCPs:**
- UCP2: Widely expressed, reduces oxidative stress
- UCP3: Skeletal muscle and heart, reduces ROS under stress
- UCP4/UCP5: Neuronal, neuroprotection

---

## ATP Synthase Inhibitor: Oligomycin

- Antibiotic that blocks ATP synthesis
- Plugs F₀ proton channel of ATP synthase
- Not an uncoupler - blocks both electron transport AND phosphorylation
- Prevents proton re-entry, gradient builds up to maximum
- Back-inhibits electron transport
- Uncouplers increase O₂ consumption (gradient dissipated)

---

## Reactive Oxygen Species (ROS) and the ETC

- Electron "leakage" at several ETC complexes
- Partial reduction of O₂ to form superoxide (O₂⁻)
- Primary reactive oxygen species

### Effects of ROS

**Normal (Moderate):**
- Signaling molecule
- Autophagy, hypoxia adaptation, cell differentiation

**Excessive:**
- Irreversible damage to proteins, lipids, DNA
- Implicated in aging, neurodegeneration (Parkinson's, Alzheimer's)
- Ischemia-reperfusion injury
- Cancer

---

## Clinical Correlations

### Cyanide Poisoning

- From smoke inhalation, industrial exposure, or ingestion of amygdalin
- Binds irreversibly to Fe³⁺ in cytochrome a₃ of Complex IV
- Stops electron transport
- Cells cannot utilize O₂ (histotoxic hypoxia)
- Venous blood appears bright red

**Treatment:**
- Hydroxocobalamin (binds cyanide)
- Amyl nitrite/sodium nitrite (oxidize Hb to metHb, sequesters CN⁻)
- Sodium thiosulfate (converts CN⁻ to thiocyanate)

### Carbon Monoxide Poisoning

- CO has ~250× higher affinity for hemoglobin than O₂
- Also inhibits Complex IV
- Dual mechanism: impaired O₂ delivery AND impaired O₂ utilization

### DNP Toxicity

- Uncouples OXPHOS
- Dramatic metabolic rate elevation
- Hyperthermia, profuse sweating, tachycardia
- Fatal "runaway uncoupling" phenomenon described in 2025 study

### Mitochondrial Diseases

- Mutations in mtDNA or nuclear genes encoding ETC subunits
- Examples: MELAS, MERRF, Leigh syndrome, Leber hereditary optic neuropathy
- Tissues most dependent on OXPHOS (brain, skeletal muscle, heart) most severely affected

### Ischemia-Reperfusion Injury

- During ischemia (e.g., myocardial infarction), ETC stalls due to O₂ deprivation
- NADH accumulation and proton gradient collapse
- Upon reperfusion, sudden reactivation generates burst of ROS
- Damages cardiomyocytes - key mechanism of reperfusion injury

### Newborn Thermogenesis

- Neonates rely heavily on UCP1-mediated non-shivering thermogenesis
- Premature or growth-restricted neonates with reduced brown fat at risk for hypothermia
- Clinically managed with incubator warming
