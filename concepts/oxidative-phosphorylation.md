---
format_version: 1
type: concept_set
set: Oxidative Phosphorylation
concepts:
  - id: c-oxidative-phosphorylation
    name: Oxidative Phosphorylation
    parent_id: null
  - id: c-chemiosmotic-theory
    name: Chemiosmotic Theory (Mitchell)
    parent_id: c-oxidative-phosphorylation
  - id: c-atp-synthase
    name: ATP Synthase (F₀F₁-ATPase)
    parent_id: c-oxidative-phosphorylation
  - id: c-binding-change-mechanism
    name: Binding Change Mechanism
    parent_id: c-atp-synthase
  - id: c-po-ratio
    name: P/O Ratio and ATP Yield
    parent_id: c-oxidative-phosphorylation
  - id: c-uncouplers
    name: Mitochondrial Uncouplers
    parent_id: c-oxidative-phosphorylation
  - id: c-ucp1
    name: Thermogenin (UCP1)
    parent_id: c-uncouplers
  - id: c-ros
    name: Reactive Oxygen Species
    parent_id: c-oxidative-phosphorylation
  - id: c-mitochondrial-transport
    name: Mitochondrial Membrane Transport
    parent_id: c-oxidative-phosphorylation
---
## c-oxidative-phosphorylation
Oxidative phosphorylation couples electron transport to ATP synthesis via the proton-motive force. Electrons flow through ETC complexes, pumping protons to create PMF. Protons return through ATP synthase, driving ATP production. Yields ~30-32 ATP per glucose.

## c-oxidative-phosphorylation:summary
Oxidative phosphorylation is the process in which cells use energy released from electron transfer reactions to synthesize ATP from ADP and inorganic phosphate (Pi). It has two connected parts: (1) Oxidation - NADH and FADH₂ lose electrons through the ETC, and (2) Phosphorylation - ADP is converted into ATP.

Before Mitchell's chemiosmotic theory (1961 Nobel Prize), the chemical coupling theory proposed a high-energy chemical intermediate - but none was ever found, so it was rejected.

The ETC and ATP synthesis are coupled through the proton-motive force (PMF) across the inner mitochondrial membrane. PMF has two components: chemical gradient (ΔpH - difference in H⁺ concentration) and electrical gradient (Δψ - difference in charge because H⁺ is positive). Together they store energy.

ATP synthase (Complex V, F₀F₁-ATPase) acts as a molecular turbine. F₀ is the membrane-embedded proton motor (c-ring rotates when H⁺ passes through - like water spinning a turbine). F₁ projects into matrix and contains catalytic β subunits that cycle through Open (releases ATP - low affinity), Loose (binds ADP+Pi), and Tight (produces ATP).

Key insight: The proton gradient provides energy mainly for releasing ATP from the enzyme, not for forming the ATP bond (which occurs spontaneously in the tight state). One complete 360° rotation produces 3 ATP (one per β subunit). γ subunit acts as camshaft forcing β shape changes.

ATP yield: NADH → ~2.5 ATP (10 H⁺ pumped); FADH₂ → ~1.5 ATP (6 H⁺ pumped). Numbers are not whole numbers because energy is used for transport, mitochondrial function, and heat.

ATP synthasome coordinates ATP synthase with ATP-ADP translocase (exchanges ATP out/ADP in) and phosphate translocase (moves Pi into matrix) for efficient transport.

Uncouplers (DNP, CCCP, valinomycin) allow protons to bypass ATP synthase, dissipating gradient as heat. Oligomycin blocks F₀ channel but is NOT an uncoupler. UCP1 (thermogenin) in brown fat is a physiological uncoupler for non-shivering thermogenesis in newborns.

Mental model: Hydroelectric dam - ETC pumps water (H⁺) uphill, creates stored potential energy, water flows back through turbine (ATP synthase), produces electricity (ATP).

## c-chemiosmotic-theory
Mitchell's chemiosmotic theory (1961): ETC and ATP synthesis coupled by proton gradient across inner mitochondrial membrane. Key postulates: (1) IMM impermeable to H⁺, (2) ETC pumps H⁺ from matrix to IMS, (3) H⁺ re-enters only through ATP synthase, (4) PMF drives ATP synthesis.

## c-chemiosmotic-theory:summary
Chemiosmotic theory explains coupling of electron transport to phosphorylation. Proton gradient serves as energy intermediate. Evidence: membrane disruption abolishes OXPHOS; artificial gradients can drive ATP synthesis; uncouplers dissipate gradient.

## c-atp-synthase
ATP synthase (F₀F₁-ATPase) has two domains: F₀ (membrane-embedded, oligomycin-sensitive, c-ring) and F₁ (peripheral, α₃β₃γδε). Proton flow through F₀ drives rotation of γ subunit, inducing conformational changes in β subunits that synthesize and release ATP.

## c-atp-synthase:summary
F₀F₁-ATPase is molecular motor driven by proton flow. F₀ contains proton channel; F₁ contains catalytic sites. Asymmetric γ subunit rotation converts proton gradient energy to chemical energy in ATP.

## c-binding-change-mechanism
Boyer's binding change mechanism (1979-1994): Three β subunits cycle through Open (releases ATP), Loose (binds ADP+Pi), and Tight (synthesizes ATP) conformations. Rotation of γ subunit (360° in three 120° steps) drives this cycle. Key insight: energy releases ATP, doesn't form bonds.

## c-binding-change-mechanism:summary
Binding change mechanism explains rotary catalysis. ATP forms spontaneously in Tight state; energy needed to release it from Open state. γ subunit acts as camshaft, sequentially converting β subunits. 3 ATP per full rotation.

## c-po-ratio
P/O ratio = ATP molecules per ½O₂ reduced. NADH: 10 H⁺ pumped → ~2.5 ATP (P/O ≈ 2.5). FADH₂: 6 H⁺ pumped → ~1.5 ATP (P/O ≈ 1.5). Total from glucose: ~30-32 ATP (2 glycolysis + 2 PDH + 6 TCA + 20-22 OXPHOS).

## c-po-ratio:summary
P/O ratio reflects coupling efficiency. NADH yields more ATP than FADH₂ because it enters at Complex I, pumping more protons. Actual yield may vary slightly due to proton leak and transport costs.

## c-uncouplers
Uncouplers dissipate proton gradient, allowing protons to bypass ATP synthase. Electron transport continues (O₂ consumption ↑) but ATP synthesis stops. Energy released as heat. Chemical uncouplers: DNP, CCCP, FCCP, valinomycin, high-dose aspirin.

## c-uncouplers:summary
Uncouplers "short-circuit" proton gradient. They increase metabolic rate and heat production while decreasing ATP yield. DNP was used as weight-loss drug but banned due to fatal hyperthermia. Some uncoupling is physiological (brown fat).

Mechanism: Uncouplers are lipid-soluble weak acids (like DNP) that pick up H⁺ in IMS, move into matrix, release H⁺, return again - acting as proton shuttles. The proton gradient disappears, ETC continues running, energy becomes heat instead of ATP.

DNP was used for weight loss because uncoupling increases oxygen consumption, metabolic rate, and energy expenditure - body burns more fuel. But no safety control exists - too much uncoupling causes massive heat production → hyperthermia → organ failure → death. Other chemical uncouplers: CCCP, FCCP, dinitrocresol, high-dose aspirin.

UCP1 (thermogenin) in brown adipose tissue is physiological uncoupler. Newborns need it because they cannot shiver effectively. Cold exposure → norepinephrine → β-adrenergic receptors → cAMP → free fatty acid release → UCP1 activation → heat. Inhibited by GDP/GTP. Other uncoupling proteins: UCP2 (reduces oxidative stress), UCP3 (protects against ROS in muscle/heart), UCP4/UCP5 (neuroprotection in neurons).

Uncouplers vs Oligomycin: Uncouplers allow proton movement (ETC ↑, O₂ consumption ↑, ATP ↓, heat ↑, gradient collapses). Oligomycin blocks F₀ channel (ETC slows, ATP ↓, gradient builds up).

## c-ucp1
UCP1 (thermogenin) is physiological uncoupler in brown adipose tissue inner mitochondrial membrane. Allows H⁺ re-entry to matrix, dissipating PMF as heat (non-shivering thermogenesis). Activated by free fatty acids, norepinephrine. Inhibited by GDP/GTP.

## c-ucp1:summary
UCP1 provides adaptive thermogenesis in newborns and cold-exposed individuals. Brown fat mitochondria have UCP1, enabling heat production without shivering. Critical for neonatal survival as they cannot shiver effectively.

## c-ros
Reactive oxygen species (superoxide O₂⁻) form from electron leakage at ETC complexes. Moderate ROS = signaling (autophagy, differentiation). Excessive ROS = damage to proteins, lipids, DNA. Implicated in aging, neurodegeneration, ischemia-reperfusion injury, cancer.

## c-ros:summary
ROS are double-edged swords: essential for signaling but destructive in excess. Mitochondria are primary source. Antioxidant defenses (SOD, catalase, glutathione) normally control levels. ETC dysfunction increases ROS production.

ROS form when electrons escape ETC (mainly Complex I and III) and partially reduce oxygen: O₂ + electron → superoxide (O₂⁻). Small amounts act as signaling molecules (exercise signals adaptation). Excess causes: protein damage (oxidation of amino acids), lipid peroxidation (membrane destruction), DNA damage (mutations, cancer risk).

Clinical: Ischemia-reperfusion injury - during ischemia ETC stops, NADH accumulates; when oxygen returns ETC restarts suddenly causing ROS burst that worsens tissue damage (myocardial infarction example).

## c-mitochondrial-transport
ATP-ADP translocase exports ATP/import ADP (1:1 exchange, favors Δψ). Phosphate translocase imports Pi/OH⁻ exchange (favored by ΔpH). These transporters associate with ATP synthase to form ATP synthasome, ensuring substrate availability.

## c-mitochondrial-transport:summary
Inner mitochondrial membrane transport proteins ensure ATP, ADP, and Pi move correctly. Translocases maintain metabolic flux. ATP synthasome couples transport with synthesis for efficiency.
