---
format_version: 1
type: concept_set
set: Bioenergetics Overview
concepts:
  - id: c-bioenergetics
    name: Bioenergetics
    parent_id: null
  - id: c-atp
    name: Adenosine Triphosphate (ATP)
    parent_id: c-bioenergetics
  - id: c-high-energy-compounds
    name: High-Energy Compounds
    parent_id: c-bioenergetics
  - id: c-redox-reactions
    name: Oxidation-Reduction Reactions
    parent_id: c-bioenergetics
  - id: c-electron-carriers
    name: Electron Carriers
    parent_id: c-redox-reactions
  - id: c-tca-cycle
    name: TCA Cycle
    parent_id: c-bioenergetics
  - id: c-metabolic-integration
    name: Metabolic Integration - Glucose to ATP
    parent_id: c-bioenergetics
  - id: c-fatty-acid-oxidation
    name: Fatty Acid Oxidation
    parent_id: c-bioenergetics
  - id: c-ketogenesis
    name: Ketogenesis
    parent_id: c-fatty-acid-oxidation
  - id: c-phosphagen-system
    name: Phosphagen System
    parent_id: c-bioenergetics
  - id: c-protein-catabolism
    name: Protein Catabolism
    parent_id: c-bioenergetics
  - id: c-bioenergetics-summary
    name: Bioenergetics Summary and Clinical Integration
    parent_id: c-bioenergetics
  - id: c-enzyme-introduction
    name: Enzyme Introduction
    parent_id: c-enzymes
  - id: c-enzyme-binding-models
    name: Enzyme-Substrate Binding Models
    parent_id: c-enzymes
  - id: c-catalytic-strategies
    name: Catalytic Strategies
    parent_id: c-enzymes
---
## c-bioenergetics
Bioenergetics is the study of energy flow through living systems. It encompasses how cells obtain, transform, and utilize energy to drive metabolic processes like muscular contraction, active transport, and macromolecule synthesis.

## c-bioenergetics:summary
Bioenergetics studies energy transformations in biological systems. Cells require free energy for essential activities, which is obtained from chemical compounds with high energy bonds. The principles of thermodynamics govern these energy transformations.

## c-atp
Adenosine triphosphate (ATP) is the universal energy currency of cells. It contains three phosphate groups linked by phosphoanhydride bonds. Hydrolysis of ATP to ADP + Pi releases ΔG° = -7.3 kcal/mol (-30.5 kJ/mol), which is coupled to endergonic reactions. ATP serves as the principal donor of free energy in most biochemical processes.

## c-atp:summary
ATP is the cell's energy currency with three phosphate groups. Its hydrolysis releases significant free energy (-7.3 kcal/mol) used to drive cellular work. Energy transfer occurs through phosphoryl, pyrophosphoryl, or adenyl group transfers to substrates or enzymes.

## c-high-energy-compounds
Five types of high energy bonds exist in cells: (1) Phosphoanhydride bonds (~30.5 kJ/mol) found in ATP, (2) Enolphosphate bonds (~61 kJ/mol) found in phosphoenolpyruvate, (3) Acyl phosphate bonds (~49 kJ/mol) found in 1,3-bisphosphoglycerate, (4) Guanidine phosphate bonds (~43 kJ/mol) found in phosphocreatine, and (5) Thioester bonds (~41 kJ/mol) found in acetyl-CoA.

## c-high-energy-compounds:summary
High-energy compounds contain chemical bonds capable of releasing large amounts of free energy when hydrolyzed. Cells store energy in these compounds to rapidly drive biological reactions.

Five major high-energy bonds: (1) Phosphoanhydride (~30.5 kJ/mol) - between two phosphates in ATP/GTP/UTP; ATP has two such bonds (α-β, β-γ). (2) Enol phosphate (~61 kJ/mol) - in PEP (highest phosphoryl transfer potential); PEP → pyruvate + ATP via pyruvate kinase. (3) Acyl phosphate (~49 kJ/mol) - in 1,3-BPG; 1,3-BPG + ADP → 3-PG + ATP via phosphoglycerate kinase. (4) Guanidine phosphate (~43 kJ/mol) - in phosphocreatine; provides rapid ATP in sprinting/weight lifting via creatine kinase. Phosphagens include phosphocreatine (humans) and arginine phosphate (some animals). (5) Thioester (~41 kJ/mol) - in acetyl-CoA; transfers acetyl groups into TCA cycle.

Biological redox reactions involve electron transfer. Oxidation = loss of electrons (OIL); Reduction = gain of electrons (RIG). Reducing agent donates electrons and becomes oxidized; oxidizing agent accepts electrons and becomes reduced. Standard reduction potential (E°') measured in volts - more positive E°' means greater tendency to accept electrons. Electrons flow from negative to positive E°'. ΔG°' = -nFΔE°' relates free energy to reduction potential difference.

Electron carriers: NAD⁺/NADH (catabolism, accepts 2e⁻ + H⁺), NADP⁺/NADPH (anabolism, has extra phosphate), FAD/FADH₂ (from vitamin B₂, accepts 2H), FMN (Complex I), CoQ (lipid-soluble with isoprenoid tail, mobile between Complex I/II → III), iron-sulfur proteins ([2Fe-2S], [3Fe-4S], [4Fe-4S] clusters).

## c-tca-cycle:summary
The TCA cycle (tricarboxylic acid/citric acid/Krebs cycle) is a series of enzymatic reactions in the mitochondrial matrix that oxidizes acetyl-CoA to carbon dioxide while producing NADH, FADH₂, and GTP for energy production. Discovered by Hans Krebs in 1937.

Location: Mitochondrial matrix (except succinate dehydrogenase which is Complex II in inner membrane). Links carbohydrate, fat, and protein metabolism via acetyl-CoA.

The TCA cycle does NOT directly produce much ATP. Its main purpose is to harvest high-energy electrons stored in NADH and FADH₂. Think: TCA Cycle = Electron collector, ETC = ATP generator.

Acetyl-CoA is the central metabolic junction - comes from carbohydrates (glucose → pyruvate → acetyl-CoA), fats (fatty acids → β-oxidation → acetyl-CoA), and proteins (amino acids → acetyl-CoA or TCA intermediates).

Pyruvate Dehydrogenase Complex (PDH) converts pyruvate to acetyl-CoA: Pyruvate + CoA + NAD⁺ → Acetyl-CoA + CO₂ + NADH. Three enzymes: E1 (pyruvate dehydrogenase), E2 (dihydrolipoyl transacetylase), E3 (dihydrolipoyl dehydrogenase). Requires five cofactors - mnemonic "Tender Loving Care For Nancy": TPP (B1), Lipoic acid, CoA (B5), FAD (B2), NAD⁺ (B3). Thiamine deficiency impairs PDH → pyruvate → lactate → lactic acidosis.

Eight TCA steps: (1) Citrate synthase: OAA + acetyl-CoA → citrate (irreversible, inhibited by ATP/NADH/succinyl-CoA/citrate). (2) Aconitase: citrate → isocitrate (contains Fe-S cluster). (3) Isocitrate dehydrogenase: isocitrate → α-ketoglutarate + CO₂ + NADH (rate-limiting enzyme, activated by ADP/Ca²⁺, inhibited by ATP/NADH). (4) α-Ketoglutarate dehydrogenase: α-KG → succinyl-CoA + CO₂ + NADH (similar to PDH, requires same cofactors, inhibited by NADH/succinyl-CoA). After first half: 2 NADH + 2 CO₂ produced, acetyl carbons completely oxidized.

(5) Succinyl-CoA synthetase: succinyl-CoA → succinate + GTP (substrate-level phosphorylation). (6) Succinate dehydrogenase: succinate → fumarate + FADH₂ (Complex II). (7) Fumarase: fumarate → malate (+H₂O). (8) Malate dehydrogenase: malate → OAA + NADH.

Per acetyl-CoA: 3 NADH + 1 FADH₂ + 1 GTP + 2 CO₂ ≈ 10 ATP. Per glucose (2 acetyl-CoA): ≈20 ATP from TCA products.

Amphibolic pathway: catabolic (breaks down acetyl-CoA) and anabolic (provides intermediates for fatty acid, amino acid synthesis). Regulated at citrate synthase, isocitrate dehydrogenase (most important), and α-ketoglutarate dehydrogenase.

Mental picture: TCA is a battery charging station - Acetyl-CoA enters, TCA Cycle machine charges NADH and FADH₂ batteries, ETC uses batteries to produce ATP.

Products per acetyl-CoA: 3 NADH + 1 FADH₂ + 1 GTP + 2 CO₂. Products per glucose (2 acetyl-CoA): 6 NADH + 2 FADH₂ + 2 GTP + 4 CO₂.

ATP calculation from TCA (per glucose): 6 NADH × 2.5 = 15 ATP + 2 FADH₂ × 1.5 = 3 ATP + 2 GTP = 2 ATP = 20 ATP total from TCA. Complete ATP yield from glucose: Glycolysis ≈7 ATP + PDH ≈5 ATP + TCA ≈20 ATP = 30-32 ATP total.

Regulation: (1) Citrate synthase - inhibited by ATP, NADH, succinyl-CoA, citrate (high energy slows entry). (2) Isocitrate dehydrogenase (most important) - activated by ADP (low energy increases TCA) and Ca²⁺ (muscle contraction needs more ATP), inhibited by ATP/NADH. (3) α-Ketoglutarate dehydrogenase - inhibited by NADH, succinyl-CoA.

Amphibolic pathway - intermediates used for biosynthesis: citrate → fatty acid synthesis, α-ketoglutarate → glutamate/amino acids, succinyl-CoA → heme synthesis, oxaloacetate → aspartate/gluconeogenesis. Anaplerotic reactions replenish intermediates: pyruvate carboxylase (pyruvate → OAA, requires biotin/B7).

Clinical: Thiamine deficiency (B1) impairs PDH and α-KG dehydrogenase → ↓TCA → ↓ATP → affects brain/heart (beriberi, Wernicke-Korsakoff). Fluoroacetate poisoning → fluorocitrate inhibits aconitase → citrate accumulates → TCA stops. Hypoxia → ETC slows → NADH accumulates → NAD⁺ decreases → TCA slows → ↓ATP.

## c-redox-reactions
Biological oxidation-reduction reactions involve electron transfer between molecules. Oxidation is loss of electrons; reduction is gain. The standard reduction potential (E°') measured at pH 7 and 25°C determines electron flow direction. ΔG°' = -nFΔE°' relates free energy change to reduction potential difference.

## c-redox-reactions:summary
Redox reactions involve electron transfer. The tendency to donate electrons is measured by standard reduction potential (E°'). Electrons flow from more negative to more positive E°'. This flow releases energy used for cellular work like proton pumping in the ETC.

## c-electron-carriers
Specialized electron carriers include: (1) Water-soluble coenzymes (NAD⁺, NADP⁺, FMN, FAD), (2) Lipid-soluble carriers (ubiquinone/CoQ), (3) Tightly bound prosthetic groups (iron-sulfur proteins, cytochromes, copper proteins). NAD⁺ functions in catabolism; NADPH in anabolism.

## c-electron-carriers:summary
Cells use specialized carriers to transfer electrons in redox reactions. NAD⁺/NADP⁺ accept hydride ions; FMN/FAD accept hydrogen atoms; CoQ is lipid-soluble and mobile; iron-sulfur proteins and cytochromes have tightly bound prosthetic groups. Each has characteristic reduction potentials.

## c-atp-structure
ATP consists of adenine, ribose sugar, and three phosphate groups (α, β, γ). The phosphoanhydride bonds between α-β and β-γ phosphates are high energy. The phosphodiester bond between α-phosphate and ribose is not energy-rich. ATP is the principal phosphoryl group donor in cells.

## c-atp-structure:summary
ATP structure includes adenine base, ribose sugar, and three phosphates. Two phosphoanhydride bonds store energy. ATP functions as energy currency by transferring phosphoryl groups to substrates or through adenylate kinase reactions.

## c-phosphoanhydride
Phosphoanhydride bonds form between two phosphoric acid molecules. Hydrolysis generates ~30.5 kJ/mol. Found in ATP (2 bonds), all tri- and diphosphates of purine and pyrimidine nucleosides. ATP is the principal donor of free energy in most biochemical processes.

## c-phosphoanhydride:summary
Phosphoanhydride bonds are the most common high energy bonds in cells. Their hydrolysis releases significant energy used to drive endergonic reactions. ATP contains two such bonds between its phosphate groups.

## c-enolphosphate
Enolphosphate bonds form when phosphate attaches to a hydroxyl group on a carbon with a double bond. Energetically the richest bond at ~61 kJ/mol. Found in phosphoenolpyruvate (PEP) from glycolysis. Energy used to phosphorylate ADP to ATP via pyruvate kinase.

## c-enolphosphate:summary
Enolphosphate bonds have the highest energy yield of all high energy bonds (~61 kJ/mol). PEP is the classic example, and its energy drives the final step of glycolysis producing ATP.

## c-acyl-phosphate
Acyl phosphate bonds form by reaction of carboxylic acid with phosphate. Hydrolysis generates ~49 kJ/mol. Found in 1,3-bisphosphoglycerate. Hydrolysis coupled to ADP phosphorylation in glycolysis via phosphoglycerate kinase.

## c-acyl-phosphate:summary
Acyl phosphate bonds are intermediate in energy between phosphoanhydride and enolphosphate bonds. 1,3-BPG uses this bond type to generate ATP in the payoff phase of glycolysis.

## c-guanidine-phosphate
Guanidine phosphate bonds form when phosphate attaches to a guanidine group. Releases ~43 kJ/mol. Found in phosphocreatine (instantaneous energy in skeletal muscle) and arginine phosphate. These compounds are called phosphagens.

## c-guanidine-phosphate:summary
Guanidine phosphate bonds serve as rapidly mobilizable energy reserves. Phosphocreatine is the main phosphagen in vertebrates, providing immediate ATP regeneration during intense muscle contraction.

## c-thioester
Thioester bonds form between sulfur and carbon atoms, where sulfur replaces oxygen in a regular ester bond. Found in acetyl-CoA. Hydrolysis liberates ~41 kJ/mol. Important in linking catabolic pathways to the TCA cycle.

## c-thioester:summary
Thioester bonds in acetyl-CoA and other acyl-CoA derivatives conserve energy from fuel oxidation. Their hydrolysis is highly exergonic, driving metabolic reactions forward.

## c-reduction-potential
Standard reduction potential (E°') is measured at pH 7, 25°C, 1M concentrations. By convention, ΔE°' = E°' acceptor - E°' donor. Electrons flow from more negative to more positive E°'. The hydrogen electrode (0.00 V at pH 0) is the reference.

## c-reduction-potential:summary
Reduction potential quantifies tendency to gain electrons. More positive E°' means stronger tendency to accept electrons. Electron flow direction follows the potential gradient from negative to positive, releasing free energy.

## c-nernst-equation
ΔG°' = -nFΔE°' relates free energy change to reduction potential difference. n = electrons transferred, F = Faraday constant (96.485 kV/mol). This equation explains why electron flow through the ETC releases energy sufficient for proton pumping and ATP synthesis.

## c-nernst-equation:summary
The Nernst equation connects electrochemistry to bioenergetics. The large potential difference between NADH (-0.32V) and O₂ (+0.82V) provides ~1.14V driving force, yielding substantial free energy for ATP production.

## c-nad-nadp
NAD⁺ and NADP⁺ are nicotinamide adenine dinucleotides that accept hydride ions (2e⁻ + H⁺). NAD⁺ functions in catabolic oxidation reactions; NADPH in anabolic reduction reactions. Over 200 enzymes utilize these carriers. NAD⁺ is reduced to NADH; NADP⁺ to NADPH.

## c-nad-nadp:summary
NAD⁺/NADP⁺ are versatile electron carriers accepting hydride ions. Their roles diverge: NAD⁺ in energy-yielding catabolism, NADPH in biosynthetic anabolism. Both are water-soluble and dissociable from enzymes.

## c-flavin-nucleotides
FMN and FAD are derived from riboflavin (vitamin B₂). Tightly bound to flavoproteins as prosthetic groups. Accept two hydrogen atoms (2e⁻ + 2H⁺) into isoalloxazine ring. Can accept one H to form stable semiquinone radical intermediate.

## c-flavin-nucleotides:summary
Flavin nucleotides are versatile carriers that can accept one or two electrons, forming semiquinone intermediates. FMN is in Complex I; FAD in Complex II and other dehydrogenases. Their tight binding allows direct electron transfer.

## c-ubiquinone
Coenzyme Q (CoQ/ubiquinone) is a benzoquinone with isoprenoid tail. Lipid-soluble, mobile in inner mitochondrial membrane. Transports electrons from Complex I/II to Complex III. Can exist as ubiquinone (oxidized), semiquinone (radical), or ubiquinol (reduced).

## c-ubiquinone:summary
CoQ is the mobile electron shuttle between ETC complexes. Its lipid solubility and long isoprenoid tail enable rapid diffusion. It accepts electrons from both Complex I (via NADH) and Complex II (via FADH₂).

## c-iron-sulfur
Iron-sulfur proteins contain nonheme iron bound to sulfur (elemental or cysteine thiol). Common clusters: [2Fe-2S], [3Fe-4S], [4Fe-4S]. Participate in one-electron transfers. Found in Complexes I, II, and III of the ETC.

## c-iron-sulfur:summary
Fe-S proteins are ancient electron carriers using iron's ability to cycle between Fe²⁺/Fe³⁺. They transfer single electrons through cluster redox changes. Essential components of ETC complexes and many metabolic enzymes.

## c-tca-cycle
The TCA cycle is a series of enzymatic reactions in the mitochondrial matrix that oxidizes acetyl-CoA to CO₂ while producing NADH, FADH₂, and GTP. Eight enzymatic steps regenerate oxaloacetate. The cycle is amphibolic - involved in both catabolism and anabolism.

## c-pdh-complex
The pyruvate dehydrogenase complex converts pyruvate to acetyl-CoA, linking glycolysis to the TCA cycle. Three enzymes (E1, E2, E3) require five cofactors: TPP (vitamin B₁), lipoic acid, CoA, FAD (vitamin B₂), and NAD⁺ (niacin).

## c-metabolic-integration
Complete glucose oxidation integrates glycolysis (cytoplasm), PDH link reaction, TCA cycle (matrix), and oxidative phosphorylation (inner membrane). Total yield: ~30-32 ATP per glucose. NADH shuttles (malate-aspartate for liver/heart, glycerol phosphate for muscle/brain) transfer cytoplasmic reducing equivalents into mitochondria.

## c-cori-cycle
The Cori cycle recycles lactate from muscle to liver, where it's converted back to glucose via gluconeogenesis and returned to muscle. Costs 6 ATP per glucose regenerated. Links anaerobic glycolysis in muscle with gluconeogenesis in liver.

## c-gluconeogenesis
Synthesis of glucose from non-carbohydrate precursors (lactate, alanine, glycerol). Occurs mainly in liver. Requires 6 ATP equivalents. Important during fasting, starvation, and prolonged exercise. Bypasses three irreversible glycolytic steps using different enzymes.

## c-fatty-acid-oxidation
Fat provides ~9 kcal/g compared to carbohydrate at ~4 kcal/g, making it the body's most efficient energy store. Triglycerides are broken down via lipolysis (stimulated by glucagon/epinephrine, inhibited by insulin) into glycerol and free fatty acids. Fatty acids travel in blood bound to albumin.

## c-fatty-acid-oxidation:summary
Glucose storage is limited to glycogen in liver and muscle. During fasting, starvation, prolonged exercise, or low carbohydrate intake, the body shifts to fatty acid oxidation as the major alternative fuel. Fat contains more than twice the energy density of carbohydrates (~9 vs ~4 kcal/g). Triglycerides (glycerol + 3 fatty acids) are broken down via lipolysis, stimulated by glucagon and epinephrine but inhibited by insulin. Released fatty acids travel in blood bound to albumin to tissues including muscle, heart, and liver for β-oxidation.

## c-beta-oxidation
β-oxidation is the mitochondrial process where fatty acids are broken down into two-carbon acetyl-CoA units. Each cycle has four steps: Oxidation (acyl-CoA dehydrogenase, FADH₂), Hydration (enoyl-CoA hydratase), Oxidation (β-hydroxyacyl-CoA dehydrogenase, NADH), Thiolysis (thiolase, acetyl-CoA). For palmitate (16C): 7 cycles produce 7 NADH + 7 FADH₂, yielding 8 acetyl-CoA → 80 ATP from TCA + 28 ATP from NADH/FADH₂ - 2 ATP activation = ~106 ATP total.

## c-carnitine-shuttle
Long-chain fatty acids cannot enter mitochondria directly. The carnitine shuttle moves them across: (1) Activation - fatty acid + CoA → fatty acyl-CoA (cytoplasm), (2) CPT-I transfers fatty acid to carnitine forming acyl-carnitine (outer membrane), (3) Acyl-carnitine enters matrix, (4) CPT-II transfers fatty acid back to CoA (inner membrane). Carnitine deficiency impairs this process, especially affecting heart and muscle.

## c-ketogenesis
Ketogenesis produces ketone bodies from acetyl-CoA in liver mitochondria during fasting, starvation, diabetes, or low carbohydrate states. When oxaloacetate is diverted for gluconeogenesis, excess acetyl-CoA cannot enter TCA and is converted to ketone bodies: acetoacetate, β-hydroxybutyrate (most abundant), and acetone (volatile, causes fruity breath). Ketones are used by brain, heart, and muscle but liver cannot use them (lacks thiophorase enzyme).

## c-dka
Diabetic ketoacidosis occurs mainly in Type 1 diabetes. Insulin deficiency prevents glucose entry into cells, triggering fat breakdown and ketone production. Ketones accumulate causing metabolic acidosis. Features include high blood glucose, ketones in blood/urine, fruity breath, and Kussmaul respiration (deep rapid breathing).

## c-phosphagen-system
The phosphagen system provides immediate ATP during short bursts of intense activity (0-10 seconds). Creatine phosphate + ADP → Creatine + ATP via creatine kinase. Used during sprinting and weight lifting. This is the first energy system activated during exercise, followed by anaerobic glycolysis (10s-2min) and then aerobic metabolism (>2min).

## c-protein-catabolism
Proteins can provide energy when broken down into amino acids. The amino group is removed (deamination) and converted to ammonia → urea cycle → excreted by kidney. The carbon skeleton can enter metabolism as pyruvate, TCA intermediates, or acetyl-CoA depending on the amino acid type.

## c-glucogenic-amino-acids
Glucogenic amino acids produce pyruvate or TCA intermediates during breakdown, which can be used to synthesize glucose via gluconeogenesis. Examples include alanine, aspartate, and glutamate. These are important during fasting and prolonged exercise.

## c-ketogenic-amino-acids
Ketogenic amino acids produce acetyl-CoA or ketone bodies during breakdown. Leucine and lysine are purely ketogenic and cannot contribute to glucose synthesis. They feed directly into ketogenesis or the TCA cycle via acetyl-CoA.

## c-bioenergetics-summary
Cells extract energy from nutrients (carbohydrates, fats, proteins) by converting electrons into a proton gradient through the ETC, then use ATP synthase to convert that stored energy into ATP for cellular work. Complete glucose oxidation: glucose → glycolysis → pyruvate → acetyl-CoA → TCA cycle → NADH/FADH₂ → ETC → proton gradient → ATP synthase → ATP.

## c-bioenergetics-summary:summary
The complete energy story: nutrients are converted to ATP, the universal energy currency. NADH and FADH₂ from the TCA cycle carry electrons to the ETC (inner mitochondrial membrane). The ETC consists of Complexes I-IV, CoQ, and cytochrome c. NADH enters at Complex I (pumps 4H⁺), FADH₂ at Complex II (no pumping). Electrons flow to oxygen, the final acceptor, forming water. Complexes I, III, and IV pump protons from matrix to intermembrane space, creating the proton motive force (chemical + electrical gradient). ATP synthase (Complex V) uses proton flow to synthesize ATP via the binding change mechanism (Paul Boyer). NADH yields ~2.5 ATP (10H⁺ pumped), FADH₂ yields ~1.5 ATP (6H⁺ pumped). Mitochondrial transport systems (ATP-ADP translocase, phosphate translocase) move ATP out. Uncouplers (DNP) or physiological uncoupling (thermogenin/UCP1 in brown fat) dissipate gradient as heat instead of ATP. Oligomycin blocks ATP synthase F₀ channel. ROS (superoxide, H₂O₂, hydroxyl radicals) form when electrons escape ETC; defended by SOD, catalase, glutathione peroxidase. Clinical correlations: cyanide (blocks Complex IV), CO (blocks hemoglobin + Complex IV), mitochondrial diseases (MELAS, MERRF, Leber), ischemia-reperfusion injury.

## c-reactive-oxygen-species
Reactive oxygen species (ROS) are oxygen-containing molecules capable of damaging cellular components. Types include superoxide (O₂⁻), hydrogen peroxide (H₂O₂), and hydroxyl radicals. They form when electrons escape the ETC and partially reduce oxygen. Defenses include superoxide dismutase (SOD), catalase, and glutathione peroxidase. Excess ROS causes protein damage, lipid peroxidation, and DNA mutations, associated with aging, cancer, and neurodegeneration.

## c-cyanide-poisoning
Cyanide binds cytochrome a₃ in Complex IV, stopping electron transport and preventing oxygen utilization (histotoxic hypoxia). Venous blood appears bright red because oxygen remains unused. Treatment: hydroxocobalamin (binds cyanide), nitrites (convert hemoglobin to methemoglobin which binds cyanide), sodium thiosulfate (converts cyanide to thiocyanate for excretion).

## c-mitochondrial-diseases
Mitochondria contain their own DNA (mtDNA) encoding ETC proteins. Mutations affect high-energy tissues (brain, heart, skeletal muscle). Examples: MELAS (mitochondrial encephalomyopathy, lactic acidosis, stroke-like episodes), MERRF (myoclonic epilepsy with ragged red fibers), Leber hereditary optic neuropathy (vision loss).

## c-enzyme-introduction
Enzymes are biological catalysts that increase reaction rates without being consumed. Most are proteins, but some RNA molecules (ribozymes) also act as enzymes. They enable essential processes: energy production (glycolysis, TCA), digestion (amylase, lipase, proteases), DNA/RNA synthesis, and protection (catalase, SOD).

## c-activation-energy
Activation energy (Ea) is the minimum energy required for reactants to reach the transition state. Enzymes lower Ea, speeding up reactions. Like pushing a ball over a hill - the enzyme lowers the hill. Important: enzymes do NOT change ΔG of the reaction.

## c-transition-state
The transition state is the unstable, high-energy intermediate between reactants and products. Enzymes work primarily by stabilizing the transition state, making the reaction easier to proceed.

## c-enzyme-introduction:summary
Every chemical reaction requires energy to begin. Without enzymes, reactions would be too slow to sustain life. Enzymes are biological catalysts (mostly proteins, some RNA called ribozymes) that speed up reactions without being consumed. They lower activation energy (Ea) - the minimum energy needed to reach the transition state. The basic reaction: E + S ⇌ ES → EP → E + P. The active site is the specific region where substrate binding and catalysis occur. Enzymes do NOT change ΔG; they only reduce activation energy.

## c-enzyme-specificity
Enzymes are highly selective. Four types: (1) Absolute - acts on one substrate (urease → urea). (2) Group - acts on molecules with specific functional group (alcohol dehydrogenase → alcohols). (3) Bond - recognizes particular chemical bond (lipase → ester bonds). (4) Stereochemical - recognizes only one spatial arrangement (L-amino acid oxidase acts on L- not D-amino acids).

## c-enzyme-binding-models
Two major models: (1) Lock and Key (Emil Fischer, 1894) - active site is pre-shaped for substrate. Explains specificity but not flexibility. (2) Induced Fit (Daniel Koshland, 1958) - enzyme changes shape upon substrate binding. Better explains flexibility, catalysis, and transition state stabilization. Modern view favors induced fit.

## c-enzyme-binding-models:summary
Two models explain enzyme-substrate interaction. Lock and Key (Fischer, 1894): active site is pre-shaped like a lock for the substrate key. Explains specificity but not flexibility. Induced Fit (Koshland, 1958): enzyme changes shape when substrate binds, like a glove fitting a hand. Better explains flexibility, improved catalysis, and transition state stabilization. The induced fit model is more widely accepted.

## c-catalytic-strategies
Five main strategies: (1) General acid-base catalysis - amino acids donate/accept protons (histidine common due to pKa near pH 7). (2) Covalent catalysis - temporary covalent bond forms (serine, cysteine, lysine). (3) Metal ion catalysis - metals (Zn²⁺, Fe²⁺, Mg²⁺) stabilize charges, activate water, transfer electrons. (4) Catalysis by approximation - brings substrates close in correct orientation. (5) Cofactor catalysis - requires non-protein helpers.

## c-cofactors
Cofactors are non-protein components required for enzyme activity. Three types: (1) Cofactors - general term (metal ions like Mg²⁺). (2) Coenzymes - organic cofactors, usually vitamin-derived (NAD⁺, FAD, CoA). (3) Prosthetic groups - tightly/permanently bound (heme in cytochromes). Apoenzyme (inactive protein) + Cofactor = Holoenzyme (active).

## c-cofactors:summary
Cofactors are non-protein helpers required for enzyme function. General cofactors include metal ions (Mg²⁺, Zn²⁺, Fe²⁺). Coenzymes are organic, usually vitamin-derived (NAD⁺ from niacin, FAD from riboflavin, CoA from pantothenic acid, TPP from thiamine). Prosthetic groups are tightly bound (heme in cytochromes, FAD in succinate dehydrogenase). Apoenzyme (inactive protein portion) + cofactor = holoenzyme (complete active enzyme).

## c-enzyme-classification
Seven EC classes: (1) Oxidoreductases - oxidation-reduction (lactate dehydrogenase). (2) Transferases - transfer functional groups (hexokinase). (3) Hydrolases - break bonds with water (lipase, protease, amylase). (4) Lyases - remove groups without hydrolysis, create double bonds (pyruvate decarboxylase). (5) Isomerases - rearrangement (phosphoglucose isomerase). (6) Ligases - join molecules using ATP (DNA ligase). (7) Translocases - move molecules across membranes (Na⁺/K⁺ ATPase).
