---
format_version: 1
type: concept_set
set: Electron Transport Chain
concepts:
  - id: c-electron-transport-chain
    name: Electron Transport Chain
    parent_id: null
  - id: c-etc-complexes
    name: The Four ETC Complexes
    parent_id: c-electron-transport-chain
  - id: c-complex-i
    name: Complex I - NADH Dehydrogenase
    parent_id: c-etc-complexes
  - id: c-complex-ii
    name: Complex II - Succinate Dehydrogenase
    parent_id: c-etc-complexes
  - id: c-complex-iii
    name: Complex III - Cytochrome bc₁
    parent_id: c-etc-complexes
  - id: c-complex-iv
    name: Complex IV - Cytochrome Oxidase
    parent_id: c-etc-complexes
  - id: c-proton-pumping
    name: Proton Pumping and PMF
    parent_id: c-electron-transport-chain
  - id: c-etc-inhibitors
    name: ETC Inhibitors
    parent_id: c-electron-transport-chain
---
## c-electron-transport-chain
The electron transport chain transfers electrons from NADH and FADH₂ to O₂ through four membrane-bound complexes. Electrons flow from negative to positive reduction potentials, releasing energy used to pump protons from matrix to intermembrane space, creating the proton-motive force.

## c-electron-transport-chain:summary
The electron transport chain (ETC) is a series of protein complexes in the inner mitochondrial membrane that transfer electrons from NADH and FADH₂ to oxygen, releasing energy used to pump protons and generate ATP. The mitochondrion has four regions: outer membrane (porins allow small molecules), intermembrane space (stores pumped H⁺), inner membrane (highly impermeable, contains ETC + ATP synthase), and matrix (TCA cycle, fatty acid oxidation).

The inner membrane must be impermeable - if protons freely crossed, no gradient would form and no ATP would be produced.

Electron flow: NADH → Complex I → CoQ → Complex III → Cyt c → Complex IV → O₂ → H₂O. FADH₂ enters at Complex II → CoQ → same path. NADH enters earlier, produces more ATP. FADH₂ enters later, produces less ATP.

Electron carriers in ETC: FMN (Complex I), iron-sulfur proteins ([2Fe-2S], [4Fe-4S] clusters), Coenzyme Q (lipid-soluble, mobile between Complex I/II → III), Cytochrome c (small protein, intermembrane space, carries e⁻ Complex III → IV), copper/heme proteins (Complex IV).

Reduction potential (E°') is tendency to accept electrons. Electrons flow from low E°' (NADH -0.32V) to high E°' (O₂ +0.82V). Oxygen has very high reduction potential, strongly attracting electrons - this is why it's the final electron acceptor.

Complex I (NADH dehydrogenase): accepts e⁻ from NADH via FMN → Fe-S → CoQ. Pumps 4 H⁺. Inhibited by rotenone, amytal, metformin.

Complex II (succinate dehydrogenase): connects TCA to ETC. Succinate → fumarate, FAD → FADH₂. Does NOT pump protons. Inhibited by carboxin, TTFA.

Complex III (cytochrome bc₁): transfers e⁻ from CoQ to cyt c. Contains cyt b, cyt c₁, Rieske Fe-S. Pumps 4 H⁺. Inhibited by antimycin A, myxothiazol.

Complex IV (cytochrome oxidase): transfers e⁻ from cyt c to O₂ (final electron acceptor). Pumps 2 H⁺. Contains cyt a, cyt a₃, copper centers. Inhibited by CN⁻, CO, H₂S, N₃⁻.

Total: 10 H⁺ per NADH (→ ~2.5 ATP), 6 H⁺ per FADH₂ (→ ~1.5 ATP).

Mental model: Waterfall - high-energy electrons fall through ETC proteins, energy released pumps H⁺ uphill, H⁺ flows back downhill through ATP synthase to make ATP.

## c-etc-complexes
Four major protein complexes: Complex I (NADH:ubiquinone oxidoreductase), Complex II (succinate:ubiquinone reductase), Complex III (ubiquinone:cytochrome c oxidoreductase), Complex IV (cytochrome c oxidase). Complexes I, III, and IV pump protons; Complex II does not.

## c-etc-complexes:summary
The four ETC complexes work in sequence to transfer electrons to oxygen. Three of four pump protons. Electrons can enter via Complex I (NADH) or Complex II (FADH₂), converging at ubiquinone.

## c-complex-i
Complex I (NADH:ubiquinone oxidoreductase) accepts 2e⁻ from NADH via FMN, passes through Fe-S clusters to ubiquinone. Pumps 4 H⁺ from matrix to IMS per NADH. Inhibited by rotenone, metformin, amytal.

## c-complex-i:summary
Complex I is the entry point for NADH electrons. Uses FMN and Fe-S clusters to transfer electrons to CoQ. The energy released drives proton translocation. Most NADH-derived electrons enter here.

## c-complex-ii
Complex II (succinate:ubiquinone reductase) oxidizes succinate to fumarate, reducing FAD to FADH₂. Electrons pass through Fe-S clusters to ubiquinone. Does NOT pump protons - fewer ATP from FADH₂. Inhibited by carboxin, TTFA.

## c-complex-ii:summary
Complex II links TCA cycle to ETC. No proton pumping explains lower ATP yield from FADH₂ (~1.5 ATP) vs NADH (~2.5 ATP). Electrons enter downstream of first proton pump.

## c-complex-iii
Complex III (ubiquinone:cytochrome c oxidoreductase) is a dimer containing cyt b, cyt c₁, and Rieske Fe-S protein. Transfers electrons from ubiquinol to cyt c. Pumps 4 H⁺ per pair of electrons via Q cycle. Inhibited by antimycin A, myxothiazol.

## c-complex-iii:summary
Complex III uses Q cycle to transfer electrons from lipid-soluble CoQ to water-soluble cyt c. This step also contributes significantly to proton gradient. The complex functions as dimer.

## c-complex-iv
Complex IV (cytochrome oxidase) contains cyt a, cyt a₃, and Cu centers. Transfers electrons from cyt c to O₂, reducing it to H₂O. Pumps 4 H⁺ per O₂ reduced. Inhibited by CN⁻, CO, H₂S, N₃⁻.

## c-complex-iv:summary
Complex IV is terminal oxidase - final electron acceptor is O₂. Four electrons needed to reduce O₂ to 2H₂O. Highly exergonic reaction provides energy for proton pumping. Site of cyanide/CO poisoning.

## c-proton-pumping
Proton pumping creates proton-motive force (PMF) = Δp = Δψ - (2.303RT/F)ΔpH. Complex I pumps 4 H⁺, Complex III pumps 4 H⁺, Complex IV pumps 2 H⁺ per electron pair. Total: 10 H⁺ per NADH, 6 H⁺ per FADH₂.

## c-proton-pumping:summary
PMF has two components: electrical potential (Δψ, charge difference) and chemical potential (ΔpH, concentration difference). This electrochemical gradient stores energy for ATP synthesis. Protons can only return through ATP synthase.

## c-etc-inhibitors
Specific inhibitors block ETC at defined points: Complex I (rotenone, metformin, amytal), Complex II (carboxin, TTFA), Complex III (antimycin A, myxothiazol), Complex IV (CN⁻, CO, H₂S, N₃⁻). Oligomycin blocks ATP synthase, not ETC directly.

## c-etc-inhibitors:summary
ETC inhibitors are research tools and toxins. Cyanide/CO poisoning blocks electron flow to O₂, stopping ATP production. Rotenone/insecticides target Complex I. Understanding inhibition patterns reveals ETC organization.
