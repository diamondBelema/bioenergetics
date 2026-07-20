---
format_version: 1
type: concept_set
set: Enzymes
concepts:
  - id: c-enzymes
    name: Enzymes
    parent_id: null
  - id: c-enzyme-specificity
    name: Enzyme Specificity
    parent_id: c-enzymes
  - id: c-active-site
    name: Enzyme Active Site
    parent_id: c-enzymes
  - id: c-substrate-binding
    name: Substrate Binding Models
    parent_id: c-enzymes
  - id: c-transition-state
    name: Transition State Stabilization
    parent_id: c-enzymes
  - id: c-enzyme-kinetics
    name: Enzyme Kinetics
    parent_id: c-enzymes
  - id: c-michaelis-menten
    name: Michaelis-Menten Model
    parent_id: c-enzyme-kinetics
  - id: c-lineweaver-burk
    name: Lineweaver-Burk Plot
    parent_id: c-enzyme-kinetics
  - id: c-enzyme-inhibition
    name: Enzyme Inhibition
    parent_id: c-enzymes
  - id: c-competitive-inhibition
    name: Competitive Inhibition
    parent_id: c-enzyme-inhibition
  - id: c-noncompetitive-inhibition
    name: Non-competitive Inhibition
    parent_id: c-enzyme-inhibition
  - id: c-uncompetitive-inhibition
    name: Uncompetitive Inhibition
    parent_id: c-enzyme-inhibition
  - id: c-cofactors
    name: Cofactors and Coenzymes
    parent_id: c-enzymes
  - id: c-enzyme-classification
    name: Enzyme Classification (EC System)
    parent_id: c-enzymes
  - id: c-enzyme-catalysis
    name: Enzyme Catalytic Mechanisms
    parent_id: c-enzymes
  - id: c-enzyme-regulation
    name: Enzyme Regulation
    parent_id: c-enzymes
---
## c-enzymes
Enzymes are biological catalysts (mostly proteins, some RNA) that speed up chemical reactions without being consumed. They exhibit specificity (absolute, group, bond, or stereochemical) and work by lowering activation energy through transition state stabilization. Enzyme-substrate binding follows either lock-and-key or induced-fit models.

## c-enzymes:summary
Enzymes are biological catalysts (mostly proteins, some RNA ribozymes) that increase reaction rate without being consumed. They exhibit high efficiency (millions-fold acceleration), specificity (recognize shape, charge, chemical groups), and are reused after catalysis.

Important: Enzymes do NOT provide energy, change final products, or make impossible reactions possible. They only lower activation energy (Ea) and speed up reactions. They do NOT change ΔG (Gibbs free energy).

Without enzyme: reactants face high activation energy hill. With enzyme: hill becomes smaller, reaction proceeds faster.

Components: Apoenzyme (inactive protein part) + Cofactor (non-protein helper, metal ions or organic coenzymes) = Holoenzyme (complete active enzyme).

Active site: Small pocket/cleft where substrate binds. Contains amino acid residues (His, Asp, Glu, Lys, Cys, Ser) that donate/accept protons, form temporary bonds, stabilize charges. Has two functions: (1) Binding - holds substrate, (2) Catalysis - changes substrate into product.

E + S ⇌ ES → EP → E + P. Binding through weak interactions: hydrogen bonds, ionic interactions, hydrophobic interactions, van der Waals forces.

Reaction steps: (1) Substrate approaches enzyme, (2) Substrate binds active site (E + S → ES), (3) Enzyme changes shape (induced fit), (4) Chemical reaction occurs (ES → EP), (5) Product leaves (EP → E + P), (6) Enzyme ready again.

Transition state: Short-lived, high-energy intermediate between reactants and products. Enzymes work by stabilizing this state, lowering the energy needed to reach it. This is the key concept.

Four specificity types: (1) Absolute - one substrate only (urease on urea), (2) Group - particular functional groups (alcohol dehydrogenase), (3) Bond - specific bond types (lipase on ester bonds), (4) Stereochemical - one isomer only (L-amino acid oxidase).

Two binding models: Lock-and-key (Fischer 1894, rigid complementarity) and Induced-fit (Koshland 1958, conformational change upon binding - accepted model). Induced fit allows better binding, better catalysis, and transition state stabilization.

Catalytic strategies: (A) Acid-base catalysis - histidine most versatile (pKa ~physiological pH), also Asp, Glu, Lys, Cys. (B) Covalent catalysis - temporary covalent bond with substrate (Ser, Cys, Lys). (C) Metal-ion catalysis - charge stabilization, water activation (Zn²⁺ in carbonic anhydrase), redox (Fe, Cu). (D) Approximation - positions reactants correctly. (E) Cofactor catalysis - requires helpers like PLP from vitamin B6.

Factors affecting activity: Temperature (optimum ~37°C, denaturation at high temp), pH (each enzyme has optimum - pepsin ~2, trypsin ~8), substrate concentration (increases until saturation at Vmax), cofactors, inhibitors.

## c-enzyme-kinetics
Michaelis-Menten kinetics describes the relationship between reaction velocity and substrate concentration: V = Vmax[S]/(Km + [S]). Km (Michaelis constant) is substrate concentration at half Vmax; low Km indicates high affinity. Vmax is maximum velocity when all active sites are saturated.

## c-enzyme-kinetics:summary
Enzyme kinetics is the study of the rate of enzyme-catalyzed reactions and how reaction rates change with factors such as substrate concentration, enzyme concentration, and inhibitors.

Basic reaction: E + S ⇌ ES → E + P. The speed is called reaction velocity (V).

Factors determining velocity: (1) Substrate concentration, (2) Enzyme concentration, (3) Temperature, (4) pH, (5) Presence of inhibitors or activators.

Substrate concentration effect: At low [S], few ES complexes form, reaction is slow. Increasing [S] → more collisions → more ES → faster reaction. Eventually all active sites occupied → enzyme saturated → adding more substrate does nothing.

Enzyme saturation: All active sites occupied by substrate, reaction rate at maximum. Think of a bus - when all seats occupied, more passengers cannot increase capacity.

Vmax (maximum velocity): Maximum reaction rate when all active sites saturated. Depends on enzyme amount and efficiency. Double enzyme concentration → double Vmax.

Michaelis-Menten equation: V = Vmax[S]/(Km + [S]). Explains enzyme behavior across substrate concentrations. Graph: velocity increases rapidly at low [S], approaches Vmax at high [S] as enzymes become saturated.

Km (Michaelis constant): Substrate concentration required to reach ½Vmax. Key concept - tells enzyme affinity for substrate.

Km and affinity relationship: Low Km = high affinity (only small substrate amount needed for half maximum speed, enzyme binds strongly). High Km = low affinity (much more substrate needed, enzyme binds weakly). Example: Km = 1 mM means only little substrate needed; Km = 100 mM means much more required.

Clinical importance of Km: Different enzymes have different Km values. Liver enzymes may have high Km because glucose levels fluctuate. Enzymes needing constant activity may have low Km.

Enzyme concentration effect: If substrate abundant, increasing enzyme concentration increases rate. More enzyme molecules = more active sites. 1 enzyme → 100 reactions/sec; 10 enzymes → 1000 reactions/sec.

Temperature effect: Increasing temperature → more molecular movement → more collisions → higher rate, until optimum (~37°C for human enzymes). Beyond optimum → denaturation (loss of active site shape and activity).

pH effect: Enzymes have optimum pH because amino acid side chains require specific charges. Changing pH alters protein structure, active site charge, substrate binding. Pepsin works at pH ≈ 2 (stomach), trypsin at pH ≈ 8 (intestine).

Michaelis-Menten assumptions: (1) Enzyme concentration constant, (2) Substrate much greater than enzyme, (3) ES complex reaches steady state (formation equals breakdown).

Lineweaver-Burk plot: Double reciprocal (1/V vs 1/[S]) linearizes Michaelis-Menten. 1/V = (Km/Vmax)(1/[S]) + 1/Vmax. Y-intercept = 1/Vmax, X-intercept = -1/Km. Helps determine Km, Vmax, and inhibition type.

Big picture: Low substrate → more substrate → more ES → faster reaction → all sites occupied → Vmax → no further increase. Km tells how much substrate needed before factory reaches half capacity.

Turnover number (Kcat) = Vmax/[E], the number of substrate molecules converted per enzyme per second at saturation. Enzyme efficiency = Kcat/Km; high values indicate fast catalysis with strong binding. Catalase has Kcat ~10⁷ s⁻¹; acetylcholinesterase ~10⁴ s⁻¹.

Enzyme regulation: (1) Allosteric regulation - activators/inhibitors bind non-active sites (e.g., ATP inhibits PFK-1, AMP activates it). (2) Covalent modification - phosphorylation activates/deactivates enzymes. (3) Zymogen activation - inactive precursors (pepsinogen→pepsin, trypsinogen→trypsin).

Clinical markers: ALT/AST (liver), amylase/lipase (pancreas), troponin (myocardial infarction), CK-MB (cardiac).

## c-enzyme-inhibition
Three types: (1) Competitive - inhibitor competes for active site, increases apparent Km, Vmax unchanged, overcome by more substrate; (2) Non-competitive - binds allosteric site, decreases Vmax, Km unchanged; (3) Uncompetitive - binds only ES complex, decreases both Km and Vmax.

## c-enzyme-inhibition:summary
Enzyme inhibition occurs when molecules decrease or prevent enzyme activity. Three major reversible types:

(1) Competitive: Inhibitor competes for active site. Km increases (more substrate needed), Vmax unchanged (enough substrate outcompetes). Can be overcome by excess substrate. Example: methotrexate inhibiting dihydrofolate reductase.

(2) Noncompetitive: Inhibitor binds allosteric site (not active site), affects both free enzyme and ES complex. Km unchanged (substrate binding unaffected), Vmax decreases (functional enzyme reduced). Cannot be overcome by more substrate. Example: heavy metals (Hg, Pb).

(3) Uncompetitive: Inhibitor binds only to ES complex, not free enzyme. Km decreases (ES stabilized), Vmax decreases (less active enzyme). Cannot be overcome by more substrate. Produces parallel lines on Lineweaver-Burk plot.

Comparison: Competitive = Km↑, Vmax same; Noncompetitive = Km same, Vmax↓; Uncompetitive = Km↓, Vmax↓.

Clinical importance: Statins inhibit HMG-CoA reductase (cholesterol), ACE inhibitors lower blood pressure, HIV protease inhibitors prevent viral maturation. Diagnostic markers: ALT/AST (liver), amylase/lipase (pancreas), troponin (myocardial infarction).

## c-enzyme-classification
IUBMB classifies enzymes into 7 classes: EC 1 Oxidoreductases (redox reactions), EC 2 Transferases (group transfer), EC 3 Hydrolases (hydrolysis), EC 4 Lyases (bond breaking without hydrolysis/redox), EC 5 Isomerases (rearrangement), EC 6 Ligases (joining using ATP), EC 7 Translocases (membrane transport).

## c-enzyme-classification:summary
Enzymes are classified by reaction type into 7 EC classes. Each enzyme has a unique 4-number code (EC X.Y.Z.W) indicating class, subclass, sub-subclass, and serial number. This system provides standardized nomenclature.

Memory trick: O T H L I L T (Oxidoreductases, Transferases, Hydrolases, Lyases, Isomerases, Ligases, Translocases).

Class 1 - Oxidoreductases: Catalyze oxidation-reduction reactions. Many use NAD⁺, FAD, FMN. Examples: lactate dehydrogenase, cytochrome oxidase.

Class 2 - Transferases: Transfer functional groups (phosphate, methyl, amino) from one molecule to another. Example: hexokinase transfers phosphate from ATP to glucose.

Class 3 - Hydrolases: Break bonds using water (hydrolysis). Digestive enzymes are mainly hydrolases. Examples: lipase, protease, amylase.

Class 4 - Lyases: Remove or add groups without hydrolysis or oxidation, often create/remove double bonds. Example: pyruvate decarboxylase (pyruvate → acetaldehyde + CO₂).

Class 5 - Isomerases: Rearrange atoms within same molecule. Same molecular formula, different arrangement. Example: glucose-6-phosphate → fructose-6-phosphate.

Class 6 - Ligases: Join two molecules together, usually require ATP. Example: DNA ligase joins DNA fragments.

Class 7 - Translocases: Move molecules or ions across membranes using energy. Examples: Na⁺/K⁺ ATPase, proton pumps.

Connection to metabolism: Glycolysis uses hexokinase, phosphofructokinase, pyruvate kinase. TCA cycle uses citrate synthase, isocitrate dehydrogenase, succinate dehydrogenase. ETC uses NADH dehydrogenase, cytochrome oxidase.

## c-enzyme-catalysis
Five major catalytic strategies: (1) General acid-base catalysis - proton donation/acceptance, (2) Covalent catalysis - transient covalent bond with substrate, (3) Metal-ion catalysis - charge stabilization or water activation, (4) Catalysis by approximation - proper orientation, (5) Cofactor catalysis - requires nonprotein helper.

## c-enzyme-catalysis:summary
Enzymes use multiple catalytic strategies to lower activation energy:

(1) General acid-base catalysis: Enzyme groups transfer protons to/from substrates. Histidine most versatile (pKa ~6, near physiological pH) - can easily accept or donate H⁺. Other residues: Asp, Glu, Lys, Cys. Acid catalysis donates H⁺ (makes leaving groups easier to remove). Base catalysis accepts H⁺ (makes substrates more reactive).

(2) Covalent catalysis: Enzyme forms temporary covalent bond with substrate, creating intermediate that lowers activation energy. Divides one large energy barrier into smaller steps. Nucleophilic groups attack electron-poor areas: Serine (-OH), Cysteine (-SH), Lysine (-NH₂). Example: Trypsin (serine protease) - serine attacks peptide bond.

(3) Metal-ion catalysis: Three major roles - (A) Charge stabilization (Mg²⁺ stabilizes negative charges), (B) Water activation (Zn²⁺ in carbonic anhydrase binds H₂O → OH⁻ which attacks CO₂), (C) Oxidation-reduction (Fe²⁺/Fe³⁺ in cytochromes for electron transfer).

(4) Catalysis by approximation: Enzyme positions substrates close together in correct orientation. Increases effective collisions. Random collisions inefficient - molecules must collide at correct angle with correct atoms aligned. Example: DNA polymerase brings DNA template + nucleotide together.

(5) Cofactor catalysis: Requires nonprotein helpers. Inorganic (metal ions: Mg²⁺, Zn²⁺, Fe²⁺) or organic (coenzymes: NAD⁺, FAD, CoA, PLP from vitamin B6). Example: PLP transfers amino groups in amino acid metabolism.

Real enzymes often combine strategies. Carbonic anhydrase uses metal-ion + acid-base. Trypsin uses covalent + acid-base.

## c-enzyme-specificity
Enzymes exhibit four types of specificity: (1) Absolute - acts on one substrate only (urease on urea), (2) Group - acts on substrates with particular functional groups (alcohol dehydrogenase on alcohols), (3) Bond - recognizes specific bond types (lipase on ester bonds), (4) Stereochemical - acts on specific isomers (L-amino acid oxidase on L-isomers only).

## c-enzyme-specificity:summary
Specificity arises from structural complementarity between enzyme active site and substrate. Different enzymes show different specificity levels, from absolute to stereochemical. This ensures metabolic precision and prevents unwanted side reactions.

## c-active-site
The active site is a small cleft or pocket on the enzyme surface relative to overall protein size. It binds substrate and orients cofactors/prosthetic groups. Active site amino acid residues interact with substrate through hydrogen bonds, ionic interactions, and hydrophobic contacts.

## c-active-site:summary
The active site is the catalytic region where substrate binds and reaction occurs. It's disproportionately small compared to whole protein. Residues in active site can serve as nucleophiles (Cys, Ser, Thr, Tyr, Glu, Asp, Lys, Arg, His).

## c-substrate-binding
Two models explain substrate binding: (1) Lock-and-Key (Fischer, 1894) - rigid complementarity between enzyme and substrate; (2) Induced-Fit (Koshland, 1958) - substrate binding induces conformational change in active site. Most enzymes show features of both models.

## c-substrate-binding:summary
Substrate binding involves structural complementarity. Lock-and-key assumes rigid shapes; induced-fit allows conformational changes. Real enzymes combine both mechanisms to varying degrees for optimal catalysis.

## c-transition-state
For reactions to occur, substrates must reach transition state - the highest energy level between substrate and product. Enzymes lower activation energy by stabilizing transition state. Rate depends on how easily reactants reach this state.

## c-transition-state:summary
Transition state is the high-energy intermediate between substrate and product. Enzymes catalyze reactions by preferentially binding and stabilizing this state, thereby lowering the energy barrier (activation energy) needed for reaction to proceed.

## c-michaelis-menten
Michaelis-Menten model describes enzyme kinetics: V = Vmax[S]/(Km + [S]). Vmax = maximum velocity at saturation. Km = substrate concentration at ½Vmax (reflects affinity). At low [S], rate is linear; at high [S], rate plateaus at Vmax.

## c-michaelis-menten:summary
Michaelis-Menten equation relates reaction velocity to substrate concentration. Km indicates substrate affinity (low Km = high affinity). Vmax represents enzyme capacity when fully saturated. This model applies to most simple enzyme systems.

## c-lineweaver-burk
Lineweaver-Burk plot is double reciprocal (1/V vs 1/[S]). Linearizes Michaelis-Menten equation: 1/V = (Km/Vmax)(1/[S]) + 1/Vmax. Y-intercept = 1/Vmax, X-intercept = -1/Km. Used to determine Km and Vmax graphically and identify inhibition type.

## c-lineweaver-burk:summary
Lineweaver-Burk plot transforms hyperbolic Michaelis-Menten curve to straight line. Intercepts reveal kinetic parameters. Different inhibition patterns produce characteristic line shifts, making it useful for inhibitor classification.

## c-competitive-inhibition
Competitive inhibitor resembles substrate and competes for active site. Increases apparent Km (lower apparent affinity). Does not affect Vmax (can be overcome by excess substrate). Examples: malonate inhibiting succinate dehydrogenase, statins inhibiting HMG-CoA reductase.

## c-competitive-inhibition:summary
Competitive inhibition is overcome by increasing substrate concentration. The inhibitor binds reversibly to active site, preventing substrate binding. Vmax unchanged but Km increases. Common mechanism for many drugs.

## c-noncompetitive-inhibition
Non-competitive inhibitor binds allosteric site (not active site). Decreases Vmax (fewer functional enzymes). Does not affect Km (substrates still bind with same affinity). Cannot be overcome by excess substrate.

## c-noncompetitive-inhibition:summary
Non-competitive inhibition reduces maximum velocity without changing substrate affinity. Inhibitor binds enzyme or ES complex at site distinct from active site. Vmax decreases, Km unchanged. Examples include heavy metal ions.

## c-uncompetitive-inhibition
Uncompetitive inhibitor binds only to enzyme-substrate complex, not free enzyme. Decreases both Km and Vmax. Cannot be overcome by excess substrate. Results in parallel lines on Lineweaver-Burk plot.

## c-uncompetitive-inhibition:summary
Uncompetitive inhibition is unique - requires substrate binding first. Both Km and Vmax decrease proportionally. Rare in practice but important in multi-substrate reactions. Produces characteristic parallel lines on Lineweaver-Burk plot.

## c-cofactors
Cofactors are nonprotein helpers for enzyme activity. Types: (1) Inorganic ions (Zn²⁺, Fe²⁺, Mg²⁺), (2) Coenzymes - organic, often vitamin-derived (NAD⁺, FAD, TPP), (3) Prosthetic groups - covalently attached (heme, FAD). Holoenzyme = apoenzyme + cofactor.

## c-cofactors:summary
Many enzymes require nonprotein cofactors for activity. These can be simple metal ions (Zn²⁺ in carbonic anhydrase, Mg²⁺ in kinases, Fe²⁺/³⁺ in electron transfer, Cu²⁺ in oxidation-reduction) or complex organic coenzymes derived from vitamins.

Apoenzyme (inactive protein part) + Cofactor (non-protein helper) = Holoenzyme (complete active enzyme). Think: Apoenzyme = car without fuel, Holoenzyme = working car.

How metals help: (1) Stabilize charges (Mg²⁺ stabilizes DNA phosphate groups in DNA polymerase), (2) Activate molecules (Zn²⁺ activates water to OH⁻ in carbonic anhydrase), (3) Transfer electrons (Fe²⁺/Fe³⁺ in cytochromes, iron-sulfur proteins).

Coenzyme types: (1) Cosubstrates - bind temporarily, leave after reaction (NAD⁺ → NADH, then carries electrons elsewhere). (2) Prosthetic groups - tightly/permanently bound (FAD in succinate dehydrogenase, heme in cytochromes).

B vitamins as coenzymes: B1 (thiamine) → TPP (pyruvate dehydrogenase, α-ketoglutarate dehydrogenase, transketolase); deficiency causes beriberi, Wernicke-Korsakoff. B2 (riboflavin) → FAD/FMN (succinate dehydrogenase, Complex II); deficiency causes angular cheilitis, dermatitis. B3 (niacin) → NAD⁺/NADP⁺ (catabolic/anabolic electron transfer); deficiency causes pellagra (dermatitis, diarrhea, dementia). B5 (pantothenic acid) → CoA (acyl group transfer in β-oxidation, TCA). B6 (pyridoxine) → PLP (amino acid metabolism, transaminases ALT/AST). B7 (biotin) → carboxylation (pyruvate carboxylase, acetyl-CoA carboxylase); raw egg whites contain avidin that binds biotin. B9 (folate) → THF (one-carbon transfers, DNA synthesis); deficiency causes megaloblastic anemia, neural tube defects. B12 (cobalamin) → methyl transfers (methionine synthase, methylmalonyl-CoA mutase); deficiency causes megaloblastic anemia + neurological damage.

Clinical enzyme deficiencies: PKU (phenylalanine hydroxylase defect → phenylalanine accumulation → intellectual disability), galactosemia (galactose-1-phosphate uridyltransferase defect → galactose accumulation → cataracts, liver damage), lactose intolerance (lactase deficiency → bacterial fermentation → gas, bloating, diarrhea).

Diagnostic enzymes: ALT/AST (liver injury), amylase/lipase (pancreatitis - lipase more specific), CK (muscle damage), troponin (myocardial infarction - most specific).

Drug-enzyme interactions: statins (HMG-CoA reductase inhibitors → ↓ cholesterol), ACE inhibitors (↓ angiotensin II → ↓ blood pressure), aspirin (COX inhibitor → ↓ prostaglandins → pain/inflammation reduction).

## c-enzyme-regulation
Cells control metabolism through enzyme regulation. Three mechanisms: (1) Allosteric regulation - activators/inhibitors bind non-active sites, changing enzyme conformation (ATP inhibits PFK-1, AMP activates it). (2) Covalent modification - phosphorylation by kinases activates or deactivates enzymes. (3) Zymogen activation - inactive precursors cleaved to active forms (pepsinogen→pepsin, trypsinogen→trypsin).

## c-enzyme-regulation:summary
Enzyme regulation maintains metabolic control. Allosteric regulation: molecules bind regulatory sites, altering enzyme activity (feedback inhibition). Covalent modification: phosphorylation is most common, can activate or deactivate. Zymogen activation: irreversible cleavage of inactive precursors (digestive enzymes, blood clotting cascade). Example: PFK-1 is key regulatory enzyme in glycolysis - ATP inhibits (high energy = slow glycolysis), AMP activates (low energy = speed up glycolysis).
