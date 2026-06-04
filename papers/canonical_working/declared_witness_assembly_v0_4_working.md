# Declared Witness Assembly: Local-to-Global Assembly Claims in Relation-First Systems

**Subtitle:** Normal Forms, Compact Faces, and Quotient-Compatible Sections
**Author:** Artur Motruk
**Affiliation:** Independent researcher
**ORCID:** 0009-0003-6928-1701
**Programme:** Relation-First Organization Programme
**Document role:** Late foundation / foundational-method paper
**Public release status:** Public canonical working manuscript

**Working status note:** This is a public canonical working manuscript in the Relation-First Organization Programme. It is included to provide a stable public repository path for programme dependencies and branch-application papers. It is not yet a journal-ready or arXiv-ready article version; it remains subject to structural reorganization, reference stabilization, and content-preserving paper-register refinement.

***
## Abstract

Many foundational and mathematical problems share a common shape: local witnesses exist, but it is not clear that they assemble into a global witness. In the asymptotic-safety branch, finite truncation fixed points and finite stability data do not automatically assemble into an exact non-Gaussian fixed point with physical critical rank. In the choiceless topology branch, each product-neighborhood of a point in a product of P-spaces has a local rectangle refinement, but ZF need not supply a countable sequence of such refinements. These are not merely analogous failures. In a relation-first programme, both are instances of a single object: the global section set of a declared witness-assembly system.

This paper defines declared witness systems, proves a normal-form theorem for local-to-global witness claims, and proves an obstruction-decomposition theorem. Any legitimate claim of the form “local witnesses assemble into a global witness” must specify an index/context object, local witness fibers, admissibility boundaries, mediation/coherence rules, readouts, and residuals. The claim succeeds only when the admitted coherent zero-residual section space is nonempty. If local witnesses exist but no global witness exists, the failure localizes to a named residual: source, admissibility, mediation, coherence, compactness, closedness, selection, quotient, or readout.

The paper then sharpens the positive side. Ordinary compactness is not new as a theorem of topology, but it has a programme-native general form: compactness is the bridge condition that kills the residual between finite declared coherence and global declared witnesshood when constraints are closed in a compact carrier and remain readable. Stone duality, logical compactness, inverse-limit compactness, sheaf-style gluing, and spectral projection stability are treated as known bridge families occupying different faces of the same assembly form. The paper also defines the assembly triadic inequality, clarifies that a witness is an admissible output of the observer/readout face rather than a replacement for that face, and defines the assembly kernel as the section-level specialization of the Face Requirement Kernel. It then adds a comparison theorem, a predictive bridge test, and a carrier-reduction discovery criterion. The central carrier-reduction datum is $\left( S,\mathcal{O},Live \right)$, where many local witness demands are replaced by one carrier variable and one obstruction/readout operator.

Finally, the paper instantiates the form in two live branches. For asymptotic safety, the witness fibers contain finite beta-map fixed-point data, stability matrices, eigenspaces, and quotient data; the live residual is projective/compact/spectral/quotient assembly. For finite products of P-spaces in ZF, the witness fibers are local rectangle-refinement sets, and the latest rectangular-core operator becomes the P-space analogue of the beta map. The open problem is recast as the nonemptiness of a rectangular witness-section space or, equivalently, the existence of a live source for the rectangular-core operator. The proposed cross-domain Neptune test is precise: the programme earns reach only if the same residual, especially quotient-compatible section failure, does nontrivial work across both branches.

## 0. Non-claims and claim boundary

This paper makes four claims.

1.  **Normal form:** every legitimate relation-first local-to-global witness claim must factor through a declared witness-assembly system.
2.  **Obstruction decomposition:** if local witnesses exist but no admitted global witness exists, the failure must be represented by a named assembly residual.
3.  **Compact face:** compactness is the general bridge condition that kills the finite-to-global assembly residual for closed constraints in a compact carrier.
4.  **Carrier reduction:** in many strong cases, the effective solution is not direct choice of local witnesses but the discovery of a carrier variable and obstruction operator whose live points are equivalent to assembled witnesses.

This paper does **not** claim:

- that all local witnesses assemble;
- that witness terminology should replace the observer/readout face;
- that compactness is a new theorem of topology;
- that asymptotic safety is proved;
- that the P-space product problem is settled;
- that the quotient-compatible residual is already solved in both domains.

The positive compactness proof is standard. The programme-native contribution is the normal form, the residual classification, and the identification of compactness, selection, quotienting, closedness, and readout as distinct bridge faces inside one assembly object. Compactness is not being renamed; it is being located. It is the vanishing of one assembly residual, not the whole assembly theorem. Likewise, carrier reduction is not a slogan for unification. It is a pass/fail discovery task: Declared Witness Assembly must predict the carrier and obstruction operator in a way that changes the proof search.

## 1. Motivation: the shared witness-upgrade problem

A recurring mistake in foundational arguments is to confuse local evidence with global witnesshood.

In an asymptotic-safety truncation tower, a finite fixed point at level $N$ is not an exact fixed point. Even a certified finite zero

$$\beta_{N}\left( g_{N}^{*} \right) = 0$$

does not automatically yield

$$\exists g_{*} \in \mathcal{T}_{exact}:\beta\left( g_{*} \right) = 0.$$

Relevant-direction counts do not automatically descend to a physical rank, because raw eigendirections may be gauge, parametrization, field-redefinition, or regulator artifacts.

In the ZF P-space branch, for every open product-neighborhood $W_{n}$ of $(x,y)$, one has some rectangle refinement

$$U_{n} \times V_{n} \subseteq W_{n},$$

but ZF need not supply the sequence $n \mapsto \left( U_{n},V_{n} \right)$. The ordinary product proof uses precisely that sequence.

The two branches therefore share the same underlying problem:

$$\boxed{\text{local witnesses exist, but global witness assembly is not free.}}$$

Relation-first machinery is built to expose exactly this kind of non-free transfer. The object to isolate is not “compactness,” not “choice,” and not “quotienting” alone. The object is the global section space of a declared witness-assembly system.

## 2. Relation-first prerequisites

This section states only the programme principles needed for the paper. They are used as formal discipline, not as metaphysical decoration.

### 2.1 Relation-first parser

A compressed implication

$$X \Rightarrow Y$$

is underdeclared until expanded as

$$X - \mathfrak{B}_{X \rightarrow Y} - Y.$$

The bridge $\mathfrak{B}_{X \rightarrow Y}$ must declare what target distinctions in $Y$ are recovered from what source distinctions in $X$.

### 2.2 No Undeclared Relation (NUR)

No relation claim is legitimate without a declared relation structure. In this paper, the relevant relation claim is:

$$\text{local witness data} \Rightarrow \text{global witness data}.$$

NUR says this claim must expose its assembly bridge.

### 2.3 No Undeclared Boundary (NUB)

A witness claim must declare admissibility boundaries. One must say what counts as a local witness, what counts as a global witness, and what conditions disqualify a candidate.

### 2.4 No Undeclared Observer (NUO)

A witness claim must declare its readout. It must say how witnesses are observed, compared, transported, projected, or certified.

### 2.5 Triadic closure

A declared relation must include at least:

$$\text{boundary/admissibility} + \text{mediation/transition} + \text{visibility/readout}.$$

In witness assembly these become: local witness boundaries, transition/coherence laws, and readout/residual maps.

### 2.6 Recursive Chart Learning Theory (RCLT)

If witness assembly proceeds through contexts, stages, or refinements, the transition trace must be admitted. A sequence of local witnesses is not automatically an admitted global trace.

### 2.7 Witness, observer, and visibility-face terminology

This paper does not replace the observer/readout face with witness terminology. The intended hierarchy is:

$$\mathsf{O} = \text{visibility/readout/evaluation face},$$

$$\text{observer} = \text{positioned or admissible visibility structure},$$

$$\text{readout} = \text{map, relation, or evaluator exposing distinctions},$$

$$\text{witness} = \text{visible admissible object, datum, or section supporting a claim}.$$

Thus a witness is not the whole observer component of the triad. It is the object made visible, admitted, compared, or certified through the observer/readout face. In the notation of this paper, the local witness fibers $E_{i}$ are exposed under the visibility face, while $\Gamma\left( \mathfrak{W} \right)$ and $\Gamma_{q}\left( \mathfrak{W}_{q} \right)$ are assembled witness spaces.

This distinction matters. If the observer face were renamed as witness, then calibration, evaluation, readout, and visibility would collapse into the evidence object itself. That would weaken No Undeclared Observer. The correct corollary is instead:

$$\boxed{\text{No Undeclared Witness:}\quad\text{no declared witness claim without a declared observer/readout face.}}$$

No Undeclared Witness is a corollary of NUO, not a replacement for it.

### 2.8 Triadic closure inside DWA

The triadic roles specialize in witness assembly as follows:

$$\mathsf{Z} = \text{admissibility and boundary of witnesses},$$

$$\mathsf{R} = \text{mediation, transition, refinement, or coherence of witnesses},$$

$$\mathsf{O} = \text{visibility, readout, certification, and residual evaluation}.$$

In DWA notation:

- $Adm$ is the $\mathsf{Z}$-face;
- $Coh$ and the transition/refinement structure are the $\mathsf{R}$-face;
- $p:E \rightarrow I$, any readout $q:E \rightarrow Q$, and the residual $\Omega$ live under the $\mathsf{O}$-face.

So DWA is the section-level form of triadic closure:

$$\boxed{\text{boundary says which witnesses count; mediation says how local witnesses compose; visibility says what witness has appeared and whether it is certified.}}$$

### 2.9 Assembly triadic inequality

Let $Z_{\mathfrak{W}}$, $R_{\mathfrak{W}}$, and $O_{\mathfrak{W}}$ be adequacy readouts for the boundary, mediation, and visibility faces of a declared witness system. Let $A_{\mathfrak{W}}$ be any admitted assembly-strength readout that requires all three faces. Then:

$$\boxed{A_{\mathfrak{W}} \leq Z_{\mathfrak{W}} \land R_{\mathfrak{W}} \land O_{\mathfrak{W}}.}$$

In scalar normalizations this may be written:

$$\boxed{A_{\mathfrak{W}} \leq \min\{ Z_{\mathfrak{W}},R_{\mathfrak{W}},O_{\mathfrak{W}}\}.}$$

Plainly:

$$\boxed{\text{a global witness cannot be stronger than its weakest declared face.}}$$

If boundary is underdeclared, the witness is not admissible. If mediation is underdeclared, local witnesses do not assemble. If visibility/readout is underdeclared, the assembled object is not certified. This is the assembly-specific version of the triadic inequality.

Equivalently, if $\Omega_{Z}$, $\Omega_{R}$, and $\Omega_{O}$ are face residuals, the assembly residual must dominate them in the residual order:

$$\boxed{\Omega_{asm} \succcurlyeq \Omega_{Z} \vee \Omega_{R} \vee \Omega_{O}.}$$

### 2.10 Relation to Face Requirement Kernels

The Face Requirement Kernel gives the more primitive form. A legitimate relation must declare:

$$\mathfrak{K} = \left( X,\mathcal{B},\mathcal{M},\mathcal{V},Coh,\Omega \right),$$

where $\mathcal{B}$ is boundary/admissibility, $\mathcal{M}$ is mediation, $\mathcal{V}$ is visibility/readout, $Coh$ is coherence, and $\Omega$ is residual.

Declared Witness Assembly is the section-level specialization of this kernel. The assembly kernel is:

$$\boxed{\mathfrak{K}_{asm} = \left( E,\mathcal{B}_{asm},\mathcal{M}_{asm},\mathcal{V}_{asm},{Coh}_{asm},\Omega_{asm} \right).}$$

Here:

$$\mathcal{B}_{asm} = Adm,$$

$$\mathcal{M}_{asm} = \text{transition, refinement, and section coherence},$$

$$\mathcal{V}_{asm} = \text{witness readout, quotient readout, and residual evaluation}.$$

Thus FRK supplies the primitive face requirement, triadic closure supplies the minimal role closure, and DWA supplies the local-to-global section form.

## 3. Declared witness-assembly systems

### Definition 3.1 - Witness fibration

A **witness fibration** is a map

$$p:E \rightarrow I$$

where $I$ is an index/context object and $E_{i} = p^{- 1}(i)$ is the local witness fiber at context $i$.

The index $I$ may be a set, poset, category, truncation tower, open cover, or countable context family, depending on the domain.

### Definition 3.2 - Declared witness-assembly system

A **declared witness-assembly system** is a tuple

$$\mathfrak{W} = (I,p:E \rightarrow I,Adm,Coh,\Omega),$$

where:

- $I$ is the context/index object;
- $p:E \rightarrow I$ is the local witness fibration;
- $Adm \subseteq E$ declares local admissibility boundaries;
- $Coh$ declares compatibility/mediation among local witnesses;
- $\Omega$ is a residual readout measuring failure of assembly.

A section is a map

$$s:I \rightarrow E$$

such that

$$p \circ s = {id}_{I}.$$

### Definition 3.3 - Admitted coherent zero-residual sections

The global witness set of $\mathfrak{W}$ is

$$\Gamma\left( \mathfrak{W} \right) = \{ s:I \rightarrow E:p \circ s = {id}_{I},s \in Adm,s \in Coh,\Omega(s) = 0\}.$$

A local-to-global witness claim succeeds exactly when

$$\boxed{\Gamma\left( \mathfrak{W} \right) \neq \varnothing.}$$

### Remark 3.4

The notation is intentionally broad. In sheaf theory, $p:E \rightarrow I$ can be a presheaf/fibration and $\Gamma\left( \mathfrak{W} \right)$ becomes a space of compatible sections. In inverse-limit problems, sections are compatible threads through stages. In topology under weak choice, sections are selector functions. In asymptotic safety, sections are coherent towers of finite truncation data.

## 4. Declared Witness Normal-Form Theorem

### Theorem 4.1 - Declared Witness Normal Form

Any legitimate relation-first claim of the form

$$\text{local witnesses assemble into a global witness}$$

must factor through a declared witness-assembly system

$$\mathfrak{W} = (I,p:E \rightarrow I,Adm,Coh,\Omega)$$

and must prove

$$\Gamma\left( \mathfrak{W} \right) \neq \varnothing.$$

If no such $\mathfrak{W}$ is supplied, the local-to-global claim is underdeclared.

### Proof

A local-to-global claim is a relation claim:

$$L \Rightarrow G.$$

By NUR, this must be expanded as

$$L - \mathfrak{B}_{L \rightarrow G} - G.$$

By NUB, the bridge must declare what counts as admissible local witness data and admissible global witness data. This supplies $Adm$.

By NUO, the bridge must declare how local witness data are read out, compared, transported, or certified. This supplies the visibility/readout part and the residual map $\Omega$.

By triadic closure, the bridge must include boundary, mediation, and visibility. In the assembly setting these become local witness fibers, coherence/transition laws, and residual/readout structure.

By RCLT, any cross-context or multi-stage assembly must supply an admitted trace rather than assuming that local witness existence provides a global witness trace. This supplies the section form $s:I \rightarrow E$ and the coherence condition $s \in Coh$.

Therefore any legitimate claim requires an index/context object $I$, a family of local witness spaces $E_{i}$, admissibility, coherence, and residual readout. That is precisely $\mathfrak{W}$. The global claim is exactly nonemptiness of the admitted coherent zero-residual section space $\Gamma\left( \mathfrak{W} \right)$. $▫$

### Interpretation

The theorem does not say witnesses assemble. It says a claim that they assemble is legitimate only after its assembly object is declared.

This is the first earned theorem of the paper. It is a normal-form theorem, not a compactness theorem.

## 5. Assembly residuals

### Definition 5.1 - Assembly residual vector

For a declared witness system $\mathfrak{W}$, define the assembly residual vector

$$\Delta_{asm} = \left( \Delta_{source},\Delta_{adm},\Delta_{med},\Delta_{coh},\Delta_{comp},\Delta_{closed},\Delta_{sel},\Delta_{quot},\Delta_{readout} \right).$$

The components mean:

- $\Delta_{source}$: no common carrier or witness fibration is declared;
- $\Delta_{adm}$: local witnesses do not share a compatible admissibility boundary;
- $\Delta_{med}$: mediation, transition, projection, or refinement maps are missing or incompatible;
- $\Delta_{coh}$: finite/local coherence already fails;
- $\Delta_{comp}$: finite coherence holds, but no compact/tight/completion bridge supplies a global witness;
- $\Delta_{closed}$: residual conditions are not closed/stable under limits or completion;
- $\Delta_{sel}$: local fibers are nonempty, but no selector/section exists;
- $\Delta_{quot}$: a raw assembled witness exists, but does not descend to the declared quotient/readout;
- $\Delta_{readout}$: no observer/evaluator/readout certifies the assembled witness.

### Theorem 5.2 - Assembly Obstruction Theorem

Let $\mathfrak{W}$ be a declared witness-assembly system. Suppose all local witness fibers are nonempty, but

$$\Gamma\left( \mathfrak{W} \right) = \varnothing.$$

Then

$$\boxed{\Delta_{asm} \neq 0.}$$

In particular, failure of assembly must localize to at least one declared residual component.

### Proof

Assume, for contradiction, that every residual component vanishes. Then:

1.  $\Delta_{source} = 0$ supplies a common witness fibration or carrier;
2.  $\Delta_{adm} = 0$ supplies compatible admissibility boundaries;
3.  $\Delta_{med} = 0$ supplies transitions/refinements/projections;
4.  $\Delta_{coh} = 0$ supplies local and finite coherence;
5.  $\Delta_{comp} = 0$ supplies a compact/tight/global landing bridge where needed;
6.  $\Delta_{closed} = 0$ ensures constraints and zero-residual conditions survive landing;
7.  $\Delta_{sel} = 0$ supplies a section through nonempty witness fibers;
8.  $\Delta_{quot} = 0$ ensures the assembled witness descends to the declared quotient if required;
9.  $\Delta_{readout} = 0$ ensures the global object is visible/certified in the target regime.

Together these conditions produce an admitted coherent zero-residual section $s \in \Gamma\left( \mathfrak{W} \right)$, contradicting $\Gamma\left( \mathfrak{W} \right) = \varnothing$.

Therefore at least one residual component is nonzero. $▫$

### Remark 5.3

The proof is schematic because the exact bridge theorem killing each residual depends on the domain. That is not a weakness of the theorem. It is the point: local-to-global failure is no longer mysterious. It must be paid for in one or more named residual coordinates.

## 6. The compact assembly face

The positive compactness theorem is standard. The programme-native claim is not that compactness is newly proved. It is that compactness is the general bridge condition that kills the residual between finite declared coherence and global declared witnesshood.

### Definition 6.1 - Constraint carrier

A **constraint carrier** is a triple

$$\left( S,\mathcal{K},⟦ - ⟧ \right)$$

where:

- $S$ is a candidate global-witness carrier;
- $\mathcal{K}$ is a meet-semilattice of declared constraints;
- each constraint $k \in \mathcal{K}$ is interpreted as a subset $⟦k⟧ \subseteq S$;
- finite conjunction is represented by finite intersection:

$$⟦k_{1} \land \cdots \land k_{m}⟧ = \underset{j = 1}{\bigcap^{m}}⟦k_{j}⟧.$$

### Definition 6.2 - Compact residual

The compact residual $\Delta_{comp}$ vanishes for a constraint carrier when every finitely satisfiable declared constraint family has a global realization:

$$\forall C \subseteq \mathcal{K},\left\lbrack \forall F \Subset C,\bigcap_{k \in F}⟦k⟧ \neq \varnothing \right\rbrack \Rightarrow \bigcap_{k \in C}⟦k⟧ \neq \varnothing.$$

Here $F \Subset C$ means $F$ is a finite subset of $C$.

### Theorem 6.3 - Compact Assembly Representation Theorem

Let $\left( S,\mathcal{K},⟦ - ⟧ \right)$ be a constraint carrier such that:

1.  $S$ is compact;
2.  each $⟦k⟧$ is closed in $S$;
3.  finite conjunction is represented by finite intersection.

Then

$$\boxed{\Delta_{comp} = 0.}$$

Equivalently, every finitely satisfiable declared constraint family has a global witness.

### Proof

Let $C \subseteq \mathcal{K}$ be finitely satisfiable:

$$\forall F \Subset C,\bigcap_{k \in F}⟦k⟧ \neq \varnothing.$$

Then the family $\{ ⟦k⟧:k \in C\}$ has the finite intersection property. Since every $⟦k⟧$ is closed and $S$ is compact,

$$\bigcap_{k \in C}⟦k⟧ \neq \varnothing.$$

Thus a global witness exists. $▫$

### Proposition 6.4 - Compactness-as-assembly equivalence

For a topological space $S$, the following are equivalent:

1.  $S$ is compact.
2.  Every family of closed subsets of $S$ with the finite intersection property has nonempty total intersection.
3.  Every closed-constraint assembly system over $S$ with finite declared coherence has a global witness.

### Proof

The equivalence of (1) and (2) is the standard closed-set formulation of compactness. Condition (3) is condition (2) written in the language of declared constraint carriers. $▫$

### Interpretation

Compactness is exactly the vanishing of the compact residual for closed-constraint assembly systems. This is why compactness has so many faces: whenever a domain can translate local witness conditions into closed constraints inside a compact carrier, finite coherence becomes global witnesshood.

This does not make compactness a new theorem. It identifies compactness as a programme-native bridge face.

## 7. Known compact-assembly bridges

### 7.1 Topological compactness

Topological compactness is the base case:

$$\text{closed FIP} \Rightarrow \text{global point}.$$

### 7.2 Logical compactness

In propositional or first-order logic, finite satisfiability of theories can imply satisfiability under the relevant compactness theorem. From the assembly viewpoint:

- local constraints are finite subsets of a theory;
- local witnesses are finite models/assignments;
- the global witness is a model of the whole theory;
- compactness kills $\Delta_{comp}$.

### 7.3 Stone duality

Stone duality is a historically built bridge between Boolean algebraic constraints and topological compact witnesses. Boolean elements become clopen constraints in the Stone space, ultrafilters become global witnesses, and finite consistency becomes finite intersection of clopen sets. Stone’s representation theorem gives a duality between Boolean algebras and Stone spaces, with the Stone space compact, Hausdorff, and totally disconnected.

From the present viewpoint, Stone duality is not the discovery that compactness exists. It is a bridge showing that logical/Boolean assembly and topological compact assembly are the same compact-residual face in two presentations.

### 7.4 Inverse/projective limits

Inverse-limit compactness has the same form:

$$\text{nonempty compact stages} + \text{compatible bonding maps} \Rightarrow \text{nonempty inverse limit}.$$

This is the compact face of compatible-thread assembly.

### 7.5 Sheaf gluing

Sheaf gluing kills a coherence residual rather than only a compact residual. A compatible local family over a cover assembles into a unique global section when the sheaf gluing axiom holds. In the witness-assembly vocabulary, sheaf gluing is a bridge theorem for $\Delta_{coh}$ and $\Delta_{med}$.

### 7.6 Spectral projection stability

Riesz projection methods kill a spectral-rank residual. If a spectral cluster remains isolated under perturbation or a limit, then the rank of the associated spectral projection remains stable. This is a compact/closed/spectral face of assembly.

### 7.7 Selector principles

In weak-choice contexts, nonempty local fibers do not automatically yield a section. Selector principles kill $\Delta_{sel}$ when they are available. Their absence is the live residual in the P-space branch.

### 7.8 Support-uniformization

In symmetric/permutation models, a raw section may fail to exist internally because no invariant/support-uniformized choice exists. Support-uniformization is a bridge that kills a quotient-compatible selector residual when it exists.

## 8. Quotient-compatible section assembly

The sharper cross-domain object is not ordinary section existence. It is quotient-compatible section existence.

### Definition 8.1 - Quotient witness system

A **quotient witness-assembly system** is

$$\mathfrak{W}_{q} = \left( I,p:E \rightarrow I,q:E \rightarrow Q,Adm,Coh,{Coh}_{Q},\Omega \right),$$

where $q:E \rightarrow Q$ is a quotient, readout, orbit, support, or physical-projection map, and ${Coh}_{Q}$ is the required coherence condition after quotient/readout.

### Definition 8.2 - Quotient-compatible global witness set

Define

$$\Gamma_{q}\left( \mathfrak{W}_{q} \right) = \{ s:I \rightarrow E:p \circ s = id,s \in Adm,s \in Coh,q \circ s \in {Coh}_{Q},\Omega(s) = 0\}.$$

The quotient-compatible assembly claim is

$$\boxed{\Gamma_{q}\left( \mathfrak{W}_{q} \right) \neq \varnothing.}$$

### Theorem 8.3 - Quotient-compatible normal form

Any legitimate RFOP claim that local witnesses assemble into a physical, invariant, quotient-readable, or support-admissible global witness must factor through a quotient witness system $\mathfrak{W}_{q}$ and must prove

$$\Gamma_{q}\left( \mathfrak{W}_{q} \right) \neq \varnothing.$$

### Proof

By Theorem 4.1, the claim must factor through a declared witness system $\mathfrak{W}$. If the target witness is physical, invariant, quotient-readable, or support-admissible, then the claim also asserts that raw witness data survive a target readout or equivalence relation. By NUR and NUO, that readout cannot be implicit. It must be declared as $q:E \rightarrow Q$, and its target coherence must be stated as ${Coh}_{Q}$. The successful witness is therefore not merely $s \in \Gamma\left( \mathfrak{W} \right)$, but $s \in \Gamma_{q}\left( \mathfrak{W}_{q} \right)$. $▫$

### Definition 8.4 - Quotient-section residual

The quotient-compatible section residual is

$$\Delta_{qsec} = \left( \Delta_{sel},\Delta_{inv},\Delta_{quot},\Delta_{coh},\Delta_{readout} \right),$$

where:

- $\Delta_{sel}$: no raw section exists;
- $\Delta_{inv}$: no invariant/support-admissible section exists;
- $\Delta_{quot}$: the raw section fails quotient descent;
- $\Delta_{coh}$: the quotient-readout data are incompatible;
- $\Delta_{readout}$: no target readout certifies the quotient section.

### Interpretation

This is the candidate cross-domain residual. In asymptotic safety, it appears as quotient-compatible eigenspace/rank descent. In the P-space branch, it appears as support/invariance-compatible rectangle selection in weak-choice or symmetric settings.

## 8A. Bridge-Valence and Generative Bridge Search integration

DWA is not only a theorem schema. It gives Bridge-Valence Diagnostics and Generative Bridge Search a more precise object to operate on.

### Definition 8A.1 - DWA diagnostic vector

For a declared witness system $\mathfrak{W}$, define the DWA diagnostic vector:

$$\mathcal{D}_{DWA}\left( \mathfrak{W} \right) = \left( \rho_{face},b_{targ},s_{sub},n_{NFT},\kappa_{asm},h_{wit} \right).$$

where:

- $\rho_{face}$ measures independent face demand in boundary, mediation, visibility, quotient, and residual structure;
- $b_{targ}$ measures how many target presentations the witness must satisfy;
- $s_{sub}$ measures whether local witnesses themselves open into sub-witness systems;
- $n_{NFT}$ counts no-free-transfer jumps between local witnesshood and global witnesshood;
- $\kappa_{asm}$ records whether an assembly operator is available;
- $h_{wit}$ measures witness/readout hardness.

The diagnostic output is:

$${Diag}_{DWA}\left( \mathfrak{W} \right) = \left( C,\Delta_{asm},m_{C},Status \right).$$

This makes the status of an assembly problem explicit: finite assembly, compact assembly, selector-critical assembly, quotient-critical assembly, underdeclared assembly, or mixed assembly.

### Definition 8A.2 - Assembly operator library

An **assembly operator** is a bridge theorem or construction that kills one or more assembly residuals. The library includes:

| Residual           | Candidate assembly operator                                            |
|--------------------|------------------------------------------------------------------------|
| $\Delta_{comp}$    | compactness, inverse limits, tightness, weak compactness               |
| $\Delta_{closed}$  | closed graph, stability, continuity, spectral gap, limit preservation  |
| $\Delta_{coh}$     | sheaf gluing, equalizers, cocycle vanishing                            |
| $\Delta_{sel}$     | selector principles, canonicalization, choice fragments                |
| $\Delta_{quot}$    | quotient descent, invariant sections, essential quotient maps          |
| $\Delta_{readout}$ | calibrated observers, certified residual maps, validation certificates |

### Definition 8A.3 - GBS over DWA residuals

Generative Bridge Search acts on an assembly residual by looking for a source packet whose solved blocker matches the target residual profile:

$${GBS}_{DWA}\left( \Delta_{asm} \right) = {Adapt}_{\Theta}\left( \mathfrak{U}_{j},\mathfrak{W} \right).$$

For example:

$$\Delta_{comp} ⤳ \text{compactness / inverse-limit / tightness packet},$$

$$\Delta_{sel} ⤳ \text{selector / support-uniformization packet},$$

$$\Delta_{quot} ⤳ \text{quotient-compatible section / Riesz projection packet},$$

$$\Delta_{coh} ⤳ \text{sheaf-gluing / cocycle-vanishing packet}.$$

The output is not a solution. It is a candidate assembly operator plus verification obligations.

### The DWA method pipeline

The programme-level pipeline is:

1.  DWA normal form;
2.  BVD residual diagnosis;
3.  GBS assembly-operator generation;
4.  target-domain verification.

This is how DWA gives something back to BVD and GBS: it supplies the shared target class for local-to-global witness problems.

## 9. AS instantiation

### 9.1 Local witness fibers

Let $I$ be a truncation category or directed set of finite truncation levels. At level $N$, define a local witness fiber

$$E_{N}^{AS}$$

whose elements include:

$$\left( g_{N},\beta_{N},D\beta_{N},E_{rel,N},P_{rel,N},q_{N} \right),$$

where:

- $g_{N}$ is a finite-truncation candidate fixed point;
- $\beta_{N}$ is the declared finite beta map;
- $D\beta_{N}$ is the stability matrix/operator;
- $E_{rel,N}$ is the relevant eigenspace;
- $P_{rel,N}$ is a spectral projection when defined;
- $q_{N}$ is a quotient/readout map toward physical directions.

A local finite witness is admitted when the finite beta-map certificate proves

$$\beta_{N}\left( g_{N}^{*} \right) = 0$$

and when spectral/rank data are certified at that level.

### 9.2 Global witness

A global AS witness is a coherent section

$$s:N \mapsto \left( g_{N},\beta_{N},D\beta_{N},E_{rel,N},P_{rel,N},q_{N} \right)$$

satisfying:

1.  projective coherence of $g_{N}$;
2.  beta compatibility;
3.  compact/tight landing;
4.  spectral stability;
5.  quotient-compatible physical rank descent.

Thus

$$\Gamma_{q}\left( \mathfrak{W}_{AS} \right) \neq \varnothing$$

is the declared exact-AS fixed-point/rank assembly claim.

### 9.3 Residuals

The AS residual vector is

$$\Omega_{AS} = \left( \Delta_{proj},\Delta_{\beta},\Delta_{comp},\Delta_{closed},\Delta_{spec},\Delta_{quot},\Delta_{pred} \right).$$

Here:

- $\Delta_{proj}$: finite witnesses are not mutually projective;
- $\Delta_{\beta}$: beta maps fail compatibility under projection;
- $\Delta_{comp}$: no compact/tight completed carrier exists;
- $\Delta_{closed}$: beta-zero or spectral constraints do not survive limits;
- $\Delta_{spec}$: finite spectral counts do not stabilize;
- $\Delta_{quot}$: raw eigendirections do not descend to physical eigendirections;
- $\Delta_{pred}$: even a finite physical rank does not yet produce empirical prediction extraction.

### 9.4 Role of the beta map

The beta map is the declared dynamical witness map. Without $\beta_{N}$, a finite fixed point is not a certified witness. With $\beta_{N}$ and derivative bounds, one can prove a local finite theorem of the form

$$\exists!\ g_{N}^{*} \in B\left( g_{0},r \right):\beta_{N}\left( g_{N}^{*} \right) = 0.$$

This kills a local admissibility residual. It does not kill the global assembly residual.

### 9.5 Role of eigenvectors/eigenspaces

Eigenvalues count raw relevant directions. Eigenvectors/eigenspaces identify the actual carriers of those directions. The quotient test has the form

$$dq\left( v_{i} \right) = 0\quad\text{or}\quad dq\left( v_{i} \right) \neq 0.$$

Therefore eigenvectors unlock $\Delta_{quot}$: they determine whether a raw relevant direction is physical or vertical.

### 9.6 Status

The AS branch is in partial solver mode. It has local finite witness certification machinery and a quotient-rank theorem. It has not proved

$$\Gamma_{q}\left( \mathfrak{W}_{AS} \right) \neq \varnothing$$

for full exact asymptotic safety.

## 10. P-space instantiation

### 10.1 External context

A P-space is a topological space in which every $G_{\delta}$ set is open. In ZFC, finite products of P-spaces are P-spaces by the standard rectangle-refinement proof. In ZF, that proof uses a hidden countable choice step. The question whether ZF proves that every finite product of P-spaces is a P-space is listed as open in recent work on P-spaces without Choice.

### 10.2 Local witness fibers

Let $X,Y$ be P-spaces, $x \in X$, $y \in Y$, and let $\left( W_{n} \right)_{n \in \omega}$ be open neighborhoods of $(x,y)$ in $X \times Y$.

Define the local rectangle-refinement fiber

$$E_{n}^{P} = \mathcal{R}_{n} = \{(U,V):x \in U \in \tau_{X},y \in V \in \tau_{Y},U \times V \subseteq W_{n}\}.$$

Each $\mathcal{R}_{n}$ is nonempty.

A section is a choice sequence

$$s(n) = \left( U_{n},V_{n} \right) \in \mathcal{R}_{n}.$$

If such a section exists, then

$$U = \bigcap_{n}U_{n},\quad\quad V = \bigcap_{n}V_{n}$$

are open, and

$$U \times V \subseteq \bigcap_{n}W_{n}.$$

Thus the product proof is exactly witness-section assembly.

### 10.3 Rectangular-choice equivalence

For P-spaces $X,Y$, the product $X \times Y$ is a P-space if and only if every countable local family $\left( W_{n} \right)$ of product-neighborhood demands has

$$\prod_{n}^{}\mathcal{R}_{n} \neq \varnothing.$$

This is the exact rectangular-choice reduction.

### 10.4 Rectangular-core operator: the P-space beta map

For an open $W \subseteq X \times Y$ and an open $U \ni x$, define

$$V_{W}(U) = \bigcup\{ V \subseteq Y:V\text{ open},\ y \in V,U \times V \subseteq W\}.$$

For a countable family $\overrightarrow{W} = \left( W_{n} \right)$, define the rectangular-core operator

$$B_{\overrightarrow{W}}^{X \rightarrow Y}(U) = \bigcap_{n \in \omega}V_{W_{n}}(U).$$

This is the P-space analogue of “getting the beta map.” It turns sequence-choice language into map-level solver language.

### Theorem 10.1 - Rectangular-core equivalence

For P-spaces $X,Y$ and a countable family $\left( W_{n} \right)$ of open neighborhoods of $(x,y)$,

$$\bigcap_{n}W_{n}\text{ is a product-neighborhood of }(x,y)$$

if and only if there exists an open $U \ni x$ such that

$$y \in B_{\overrightarrow{W}}^{X \rightarrow Y}(U).$$

### Proof

If $y \in B_{\overrightarrow{W}}^{X \rightarrow Y}(U)$, then $y \in V_{W_{n}}(U)$ for every $n$. Thus for each $n$, the definition of $V_{W_{n}}(U)$ gives open vertical neighborhoods compatible with $U$ and $W_{n}$. Since $Y$ is a P-space, the countable intersection of such vertical neighborhoods is open, yielding $V \ni y$ with

$$U \times V \subseteq \bigcap_{n}W_{n}.$$

Conversely, if $\bigcap_{n}W_{n}$ contains a product-neighborhood $U \times V$ of $(x,y)$, then for every $n$, $U \times V \subseteq W_{n}$. Hence $V \subseteq V_{W_{n}}(U)$ for every $n$, so $y \in B_{\overrightarrow{W}}^{X \rightarrow Y}(U)$. $▫$

### 10.5 Compact carrier formulation

Let

$$S_{x} = \{ U \in \tau_{X}:x \in U\}.$$

For each $n$, define

$$C_{n} = \{ U \in S_{x}:y \in V_{W_{n}}(U)\}.$$

Every finite subfamily of the $C_{n}$ is satisfiable. Indeed, for finite $F \Subset \omega$,

$$W_{F} = \bigcap_{n \in F}W_{n}$$

is open around $(x,y)$, so it contains a rectangle $U_{F} \times V_{F}$. Then $U_{F} \in \bigcap_{n \in F}C_{n}$.

Thus the P-space problem has a compact face:

$$\{ C_{n}:n \in \omega\}\text{ has FIP. Does it have a global point?}$$

### Theorem 10.2 - Rectangular Compactness Lemma

Let $X,Y$ be P-spaces and $\left( W_{n} \right)$ a countable family of open neighborhoods of $(x,y)$. If there exists a compact carrier ${\widehat{S}}_{x}$ and a readout from ${\widehat{S}}_{x}$ to actual neighborhoods $U \ni x$ such that:

1.  each $C_{n}$ is represented by a closed set ${\widehat{C}}_{n} \subseteq {\widehat{S}}_{x}$;
2.  finite satisfiability of the $C_{n}$ is preserved in the ${\widehat{C}}_{n}$;
3.  any point of $\bigcap_{n}{\widehat{C}}_{n}$ reads out to an actual open $U \ni x$ with $y \in B_{\overrightarrow{W}}^{X \rightarrow Y}(U)$;

then $\bigcap_{n}W_{n}$ is a product-neighborhood of $(x,y)$.

### Proof

The closed sets ${\widehat{C}}_{n}$ have the finite intersection property. By compactness of ${\widehat{S}}_{x}$,

$$\bigcap_{n}{\widehat{C}}_{n} \neq \varnothing.$$

By the readout hypothesis, any point in this intersection yields an open $U \ni x$ with $y \in B_{\overrightarrow{W}}^{X \rightarrow Y}(U)$. The result follows by Theorem 10.1. $▫$

### 10.6 Residuals

The P-space residual vector is

$$\Omega_{P} = \left( \Delta_{sel},\Delta_{comp},\Delta_{closed},\Delta_{readout},\Delta_{quot} \right).$$

The currently live residual is not ordinary topological openness. It is the possible failure of selector/compact/readout/quotient assembly for rectangle witnesses.

### 10.7 Status

The P-space branch is in obstruction-normal-form mode. It has a map-level solver object $B_{\overrightarrow{W}}^{X \rightarrow Y}$ and several no-go reductions for obvious countermodel routes. It does not yet prove the product theorem or build a countermodel.

## 11. Comparison table: AS and P-spaces

| Assembly role       | AS branch                                         | P-space branch                                                  |
|---------------------|---------------------------------------------------|-----------------------------------------------------------------|
| Local contexts      | truncation levels $N$                             | neighborhood rows $n \in \omega$                                |
| Local witness fiber | finite beta-map/rank data                         | rectangle-refinement set $\mathcal{R}_{n}$                      |
| Map-level object    | beta map $\beta_{N}$                              | rectangular-core map $B_{\overrightarrow{W}}^{X \rightarrow Y}$ |
| Local certification | Newton/Kantorovich finite-map proof               | openness gives local rectangles                                 |
| Coherence           | projective beta compatibility                     | countable rectangle assembly                                    |
| Compact face        | projective/tight completion                       | compact carrier for $C_{n} \subseteq S_{x}$                     |
| Closedness          | beta-zero and spectral constraints survive limits | $C_{n}$ represented as closed constraints                       |
| Quotient face       | physical eigenspace/rank descent                  | invariant/support-admissible rectangle selection                |
| Live residual       | $\Delta_{quot}$ plus compact/spectral gates       | $\Delta_{sel}$, possibly $\Delta_{qsec}$                        |
| Status              | partial solver mode                               | obstruction normal form                                         |

The branches do not merely rhyme. They instantiate the same declared witness-section form. The open question is whether the same residual, especially quotient-compatible section failure, does real cross-domain work.

## 12. Residual comparison and the Neptune criterion

The programme has a real normal form. It has not yet landed the stronger cross-domain Neptune. This section sharpens the test. The question is not whether two domains can be placed into the same vocabulary. The question is whether a live residual in one domain is the same assembly residual as a live residual in another, and whether a bridge theorem that kills one residual can be transferred under declared target-side obligations.

### 12.1 Residual signatures

Let

$$\mathfrak{W} = (I,p:E \rightarrow I,Adm,Coh,\Omega)$$

be a declared witness-assembly system. Its residual signature is

$$Sig\left( \mathfrak{W} \right) = \left( \Delta_{source},\Delta_{adm},\Delta_{med},\Delta_{coh},\Delta_{comp},\Delta_{closed},\Delta_{sel},\Delta_{quot},\Delta_{readout};\mathcal{B}_{asm} \right).$$

Here (B\_{}) is the bridge library available for that system: compactness, inverse limits, sheaf gluing, selector principles, quotient descent, Riesz projection, support uniformization, canonicalization, or another named assembly operator.

A residual label is not yet a mathematical comparison. Two systems may both have a symbol (\_{}) while one concerns eigenspaces in a quotient tangent space and the other concerns invariant rectangle choices in a symmetric model. They are comparable only if the residual is represented by the same formal role inside the assembly kernel.

### 12.2 Residual-comparison bridges

Let (W_A) and (W_B) be declared witness systems. A residual-comparison bridge from a residual component (r_A) of (W_A) to a residual component (r_B) of (W_B) consists of:

1.  a map of index/context objects

$$F_{I}:I_{A} \rightarrow I_{B};$$

2.  a witness-fiber correspondence over that map;
3.  a preservation map for admissibility boundaries;
4.  a preservation map for mediation/coherence requirements;
5.  a readout map preserving the residual detector;
6.  a translation of the residual-killing bridge obligations.

The key commutation condition is

$$\Omega_{B} \circ F_{E} = T_{\Omega} \circ \Omega_{A}$$

on the part of the witness data being compared, where (F_E) is the witness-data translation and (T\_) is the residual readout translation.

In words: the comparison is valid only when residual failure in one domain is transported as residual failure of the same assembly role in the other domain.

### 12.3 The comparison theorem

**Theorem 12.1 - No Undeclared Residual Comparison.**
A cross-domain claim of the form

$$\Delta_{A}^{r}\text{ and }\Delta_{B}^{s}\text{ are the same assembly obstruction}$$

is underdeclared unless a residual-comparison bridge

$$F:\mathfrak{W}_{A} \rightsquigarrow \mathfrak{W}_{B}$$

is supplied.

If such a bridge is supplied and preserves the boundary, mediation, visibility, residual, and bridge-family roles, then the two systems instantiate the same residual relative to that bridge. If no such bridge is supplied, the comparison is at most an analogy.

**Proof.**
The statement (\_A^r_B^s) is a relation claim between two declared systems. By No Undeclared Relation, it must specify a bridge. By No Undeclared Boundary, it must state which admissibility boundaries are preserved. By No Undeclared Observer, it must state which readouts and residuals are being compared. By triadic closure, the bridge must preserve boundary, mediation, and visibility roles. By the Face Requirement Kernel discipline, the comparison must also expose coherence and residual behavior. These data are exactly the residual-comparison bridge above. Without them, the comparison has no declared target distinctions and is underdeclared. With them, the comparison is admitted relative to the declared preservation conditions. ()

### 12.4 Transfer theorem for residual-killing bridges

Residual comparison by itself does not solve either problem. It only licenses transfer of a candidate bridge form.

**Definition 12.2 - residual-killing bridge theorem.**
A bridge theorem (K_A) kills a residual (\_A^r) in (W_A) if, under declared hypotheses (H_A), it proves

$$H_{A} \Rightarrow \Delta_{A}^{r} = 0.$$

A transfer of (K_A) to (W_B) is admitted only if the residual-comparison bridge supplies target-side hypotheses (H_B) such that

$$H_{B} \Rightarrow \Delta_{B}^{s} = 0$$

is actually proven in the target domain.

**Theorem 12.3 - No Bridge-Name Transfer.**
Let (F:W_AW_B) be a residual-comparison bridge. If (K_A) kills (\_A^r), then (K_A) generates at most a candidate bridge for (\_B^s) unless the target-side shell conditions are discharged. In symbols:

$$\left( K_{A}:\Delta_{A}^{r} = 0 \right) + F \not\Rightarrow \left( \Delta_{B}^{s} = 0 \right).$$

The valid conclusion is only

$$\left( K_{A},F \right) \Rightarrow \text{candidate bridge obligations for }\Delta_{B}^{s}.$$

**Proof.**
A residual-killing theorem is not only its name. It includes source hypotheses, carrier conditions, closedness/readout conditions, selector or quotient assumptions, and proof-specific shell data. By No-Free-Transfer, these hypotheses do not move to the target domain for free. By GBS guardrails, no import is admitted without adaptation and verification obligations. Therefore (K_A) plus a residual comparison produces a target-side candidate only. The target theorem is admitted only when the target hypotheses (H_B) are stated and proven. ()

### 12.5 AS and P-spaces as a comparison theorem

The comparison between AS and P-spaces is not that beta maps and rectangle maps are the same mathematical object. They are not. The comparison is that both instantiate quotient-compatible section assembly.

For AS, local fibers contain finite fixed-point and spectral data:

$$E_{N}^{AS} = \left( g_{N},\beta_{N},D\beta_{N},E_{rel,N},q_{N},dq_{N} \right).$$

A raw section is a projective tower of finite witnesses. A quotient-compatible section must descend to physical tangent/rank data:

$$dq_{N}\left( E_{rel,N} \right)$$

in a stable way. The live quotient residual is

$$\Delta_{qsec}^{AS} = \text{failure of physical eigenspace/rank descent}.$$

For P-spaces, local fibers are rectangle-refinement sets:

$$E_{n}^{P} = \mathcal{R}_{n} = \{(U,V):x \in U,\ y \in V,\ U \times V \subseteq W_{n}\}.$$

A raw section is a sequence of local rectangles. In symmetric or support-sensitive constructions, a quotient-compatible section must also be invariant, support-admissible, or readable inside the intended model. The live quotient/selector residual is

$$\Delta_{qsec}^{P} = \text{failure of support-compatible rectangle-section assembly}.$$

**Theorem 12.4 - AS/P-space quotient-section comparison.**
The AS beta-map/eigenspace branch and the P-space rectangle-refinement branch instantiate the same residual coordinate only at the level of quotient-compatible section assembly:

$$\Delta_{qsec}.$$

The comparison is admitted because both systems have:

1.  local nonempty witness fibers;
2.  a raw section problem;
3.  a quotient or support/readout condition stronger than raw sectionhood;
4.  a live residual equal to failure of a section satisfying that quotient/readout condition.

The comparison is not admitted at the level of field-specific objects: a beta map is not a rectangle-core operator, an eigenspace is not an open rectangle, and AS quotient descent is not topological product refinement.

**Proof.**
Substitute the AS data into the quotient-compatible section definition (\_q(W_q)). The resulting object is precisely the set of projectively coherent finite fixed-point/spectral witnesses whose eigenspace/rank data descend to the physical quotient. Nonemptiness is the exact-AS physical-rank assembly claim.

Substitute the P-space data into the same definition. The resulting object is the set of countable rectangle-refinement sections satisfying whatever support, invariance, or readout condition the model requires. Nonemptiness is the local product-neighborhood assembly claim.

The two substitutions preserve the role of local fiber, raw section, quotient/readout, and residual. Therefore they instantiate the same residual coordinate (\_{}) relative to the declared comparison. The specific domain objects are not identified. ()

## 13. Predictive bridge test

A normal form earns reach only when it predicts a missing bridge before that bridge is built. Recognition after the fact is exposition; prediction followed by construction is reach.

### 13.1 Exposition, transfer, reach

A DWA analysis has three levels.

**Exposition.**
The framework re-files known local-to-global theorems under one normal form. Stone duality, Tychonoff compactness, inverse-limit compactness, sheaf gluing, and Riesz projection stability may all be described as compact/closed/quotient assembly bridges. This is useful, but it is not yet reach.

**Transfer.**
The framework identifies a residual-comparison bridge between two domains and imports a bridge theorem from a source domain into a target domain under declared shell obligations. This is a valid DWA bridge result if the target verification succeeds.

**Reach.**
The framework predicts that an unbuilt bridge must exist, or that a specific bridge must fail, in a domain where that bridge was not previously formulated by the field itself. The prediction then succeeds only if the bridge is constructed or the obstruction is proved.

### 13.2 Predictive DWA bridge test

A DWA prediction consists of the following frozen data:

1.  a target witness system (W_T);
2.  a declared live residual (\_T^r);
3.  a statement that all easier residuals have either vanished or been separated;
4.  a predicted bridge family (B_r) required to kill (\_T^r);
5.  a target theorem shape

$$H_{T} \Rightarrow \Delta_{T}^{r} = 0$$

- including carrier, admissibility, closure, selection, quotient, and readout hypotheses;

6.  a falsifier: either a proof that no such bridge can exist under the declared hypotheses, or a target-domain theorem solving the problem by a different residual.

A prediction passes only if the target bridge is then constructed, or if the failure localizes exactly to the predicted residual. It does not pass merely because a known theorem can be retrofitted into the normal form.

### 13.3 Compact-face predictive target for P-spaces

The compact residual is

$$\Delta_{comp} = \text{finite declared coherence lacks a global declared carrier}.$$

A compact-style prediction must therefore specify:

1.  the candidate carrier (S) or completion (S);
2.  the constraint interpretation ();
3.  the finite-intersection or finite-coherence claim;
4.  the closedness/stability of constraints;
5.  the readout that turns a compact limit point into an admitted witness.

For the P-space branch, the live target is sharp. Given open neighborhoods (W_n(x,y)), define

$$S_{x} = \{ U \in \tau_{X}:x \in U\}$$

and

$$C_{n} = \{ U \in S_{x}:y \in V_{W_{n}}(U)\}.$$

Every finite subfamily of the (C_n)’s is satisfiable. The compact-face prediction is therefore:

**Prediction.** If ZF proves that finite products of P-spaces are P-spaces, then the finitely satisfiable families (C_n) admit a ZF-native compact/readout carrier.

More explicitly, one should seek a carrier (S_x) such that:

1.  the constraints (C_n) become closed or stable constraints (C_nS_x);
2.  finite satisfiability is preserved;
3.  a point of (\_nC_n) reads out to an actual open neighborhood (Ux);
4.  this readout proves

$$y \in B_{\overrightarrow{W}}^{X \rightarrow Y}(U).$$

If this carrier is built, it gives a ZF proof route. If it cannot exist in a symmetric model, the failure localizes to one of the named residuals: compactness, closedness, readout, or quotient-compatible section failure. Either outcome is informative.

This is not yet a theorem solving the P-space problem. It is the predictive bridge test made concrete.

### 13.4 Quotient-face predictive target for AS and P-spaces

The AS branch already contains a quotient-rank target: raw eigenspaces must descend to physical quotient eigenspaces. The P-space branch has a quotient analogue only in the symmetric/permutation-model route: rectangle sections must be internal, support-admissible, or invariant under the model’s automorphism action.

The predicted shared residual is therefore

$$\boxed{\Delta_{qsec} = \text{failure of quotient-compatible section assembly}.}$$

A genuine cross-domain result would prove a theorem of the following kind:

$$\boxed{\text{Given a quotient witness system, a raw section descends iff a specified vertical/support residual vanishes.}}$$

In AS, the vertical residual is measured by tests such as

$$dq\left( v_{i} \right) = 0.$$

In P-spaces, the support residual is measured by whether a rectangle-section can be chosen with a support compatible with the symmetric model.

At present this is a strong candidate residual, not a solved theorem.

### 13.5 Historical calibration: Stone duality

Stone duality is the correct calibration example. It did not merely rephrase logic as topology; it built a bridge in which Boolean constraints became clopen constraints in a compact Stone space, and ultrafilters became global witnesses. In DWA language, it killed a compact assembly residual by constructing the right witness carrier.

A DWA predictive result should be judged against that historical standard. If it only recognizes Stone-style bridges after the fact, it is exposition. If it predicts and builds a new carrier or quotient bridge, it is reach.

### 13.6 Current verdict after the predictive test

The current status is:

$$\boxed{\text{Normal form: earned.}}$$

$$\boxed{\text{Residual decomposition: earned.}}$$

$$\boxed{\text{Compact face: programme-native as a residual face, but bridge theorems are known mathematics.}}$$

$$\boxed{\text{Cross-domain reach: not yet earned.}}$$

The next result must therefore be one of the following:

1.  construct the P-space compact/readout carrier predicted in Section 13.3;
2.  prove no such carrier can exist in a target symmetric model;
3.  prove a quotient-compatible section theorem that applies nontrivially to both AS eigenspace descent and P-space support-invariant rectangle assembly.

Until one of these lands, DWA is a strong normal-form and obstruction theory, not yet a Neptune.

## 13C. Carrier reduction: the sharper discovery test

The comparison and predictive-bridge tests still leave one risk: they may remain too high-level. A residual label can be shared while the concrete mechanisms differ. A stronger test asks whether DWA can discover the *right carrier reduction* before the domain solution is already known.

The guiding research question is:

$$\boxed{\text{Can DWA systematically discover the right carrier reduction, not merely describe it after the fact?}}$$

This is the current discriminator. A programme that only says, after the fact, that a field has used compactness, selection, quotienting, or a beta map has provided useful exposition. A programme that predicts the correct carrier and obstruction operator before the target-domain solution has produced reach.

### 13C.1 Local witnesses are often the wrong variables

A local-to-global witness problem is usually first presented as a family of local witness fibers

$$E_{i},\quad\quad i \in I.$$

The naive assembly problem is to choose

$$s(i) \in E_{i}$$

coherently. But in strong cases this is the wrong variable. The solution is not to choose every local witness separately. The solution is to find a carrier variable

$$s \in S$$

that generates, absorbs, or certifies the local witnesses through an obstruction/readout operator

$$\mathcal{O}:S \rightarrow R.$$

The assembled-witness condition is then no longer expressed as a large product or many local choices. It becomes a live-point or zero condition:

$${Live}_{\mathcal{O}}(s).$$

In zero-form:

$$\mathcal{O}(s) = 0.$$

In live-readout form:

$${Live}_{\mathcal{O}}(s) = 1.$$

This is the Carrier Reduction move.

### 13C.2 Carrier-reduction datum

A **carrier-reduction datum** for a declared witness system (W) is a tuple

$$CR\left( \mathfrak{W} \right) = \left( S,\mathcal{O},Live,r \right)$$

where:

- \(S\) is a carrier space or carrier class;
- \(O\) is an obstruction/readout operator on (S);
- \(S\) is the live-source or zero-residual locus;
- \(r\) is a reconstruction/readout relation from live carrier points to assembled witnesses.

The datum is **sound** if

$$s \in Live\quad \Rightarrow \quad r(s) \in \Gamma\left( \mathfrak{W} \right).$$

It is **complete** if

$$w \in \Gamma\left( \mathfrak{W} \right)\quad \Rightarrow \quad\exists s \in Live\text{ with }r(s) = w$$

up to the declared equivalence/readout of the witness system.

It is **proper** if (S) is simpler than the original witness-product presentation in a declared sense: fewer independent choices, lower target valence, smaller no-free-transfer burden, better compatibility operator, or a new proof route not visible in the original local-fiber presentation.

### 13C.3 Carrier Reduction Correctness Theorem

Let (W) be a declared witness-assembly system and let

$$CR\left( \mathfrak{W} \right) = \left( S,\mathcal{O},Live,r \right)$$

be sound and complete. Then

$$\boxed{\Gamma\left( \mathfrak{W} \right) \neq \varnothing\quad \Leftrightarrow \quad Live \neq \varnothing.}$$

If quotient/readout admission is part of the target, and the reconstruction relation preserves the quotient condition, then similarly

$$\boxed{\Gamma_{q}\left( \mathfrak{W} \right) \neq \varnothing\quad \Leftrightarrow \quad{Live}_{q} \neq \varnothing.}$$

#### Proof

Suppose the live locus is nonempty. Choose a live carrier point `s`. By soundness, its reconstruction `r(s)` is an assembled witness, so the assembled-witness space is nonempty.

Conversely, suppose an assembled witness `w` exists. By completeness, there is a live carrier point `s` whose reconstruction is `w`, up to the declared readout or equivalence. Therefore the live locus is nonempty.

The quotient version is identical after restricting both carrier points and reconstructions to the quotient-admissible part. This proves the biconditional. □

The theorem itself is simple. The hard part is discovery: finding (S) and (O) before the domain proof already tells us what they are.

### 13C.4 The Carrier Reduction Discovery Test

A proposed carrier reduction passes the DWA discovery test only if it satisfies all of the following.

1.  **Pre-solution declaration.** The carrier (S) and obstruction operator (O) are declared before the target-domain proof or countermodel is completed.
2.  **Derivation from residual texture.** The carrier is derived from the specific local witness texture, not from a generic climb to a parent abstraction.
3.  **Biconditional.** The paper proves a sound-and-complete equivalence between assembled witnesses and live carrier points.
4.  **Proof-search change.** The reduction changes the proof search: it gives a new theorem, no-go, computation, certificate, or smaller target.
5.  **Non-vacuity.** The reduction is not just the original product of witness fibers renamed as (S).
6.  **Shell disclosure.** Any compactness, quotient, selection, closedness, or readout requirement needed to prove live-point existence is separately declared.

A carrier reduction that fails these tests may still be useful exposition, but it is not a DWA discovery result.

### 13C.5 P-space carrier reduction

In the P-space branch, the original witness fibers are the rectangle-refinement sets

$$\mathcal{R}_{n} = \{(U,V):x \in U,\ y \in V,\ U \times V \subseteq W_{n}\}.$$

The naive problem is to choose

$$\left( U_{n},V_{n} \right) \in \mathcal{R}_{n}$$

for all (n). DWA’s carrier reduction changes variables. Define the horizontal source carrier

$$S_{x} = \{ U \in \tau_{X}:x \in U\}.$$

For each product-neighborhood (W), define the vertical core

$$V_{W}(U) = \bigcup\{ V \in \tau_{Y}:y \in V,\ U \times V \subseteq W\}.$$

For a countable family (W=(W_n)), define the rectangular-core operator

$$B_{\overrightarrow{W}}^{X \rightarrow Y}(U) = \bigcap_{n}V_{W_{n}}(U).$$

Then the live condition is

$${Live}_{P}(U)\quad \Leftrightarrow \quad U \in S_{x}\text{ and }y \in B_{\overrightarrow{W}}^{X \rightarrow Y}(U).$$

The reduction theorem is:

$$\boxed{\bigcap_{n}W_{n}\text{ is a product-neighborhood of }(x,y)\quad \Leftrightarrow \quad\exists U \in S_{x}:{Live}_{P}(U).}$$

This is a genuine carrier reduction. The original problem asks for a countable sequence of rectangle choices. The carrier reduction asks for one horizontal source whose vertical cores remain live. This changes the proof search. It leads directly to compact-carrier, support-uniformization, and countermodel tests on (S_x) rather than direct choice from (\_nR_n).

### 13C.6 AS carrier reduction

In the AS branch, the original witness data are finite fixed-point and spectral witnesses across truncations or charts. The naive presentation lists finite rows:

$$\left( g_{N},\beta_{N},D\beta_{N},E_{rel,N} \right).$$

The carrier reduction is to take the coupling vector or projective tower as carrier and to use the beta and compatibility defects as obstruction operators. At finite level:

$$S_{N} = \mathcal{T}_{N},\quad\quad\mathcal{O}_{N}(g) = \beta_{N}(g).$$

The live condition is

$${Live}_{N}(g)\quad \Leftrightarrow \quad\beta_{N}(g) = 0$$

with any required spectral-gap or finite-map certificate attached as additional live constraints.

At tower level the carrier is a projective candidate

$$g = \left( g_{N} \right)_{N},$$

and the obstruction operator has components

$$\mathcal{O}_{AS}(g) = \left( \beta_{N}\left( g_{N} \right),\ \pi_{MN}g_{N} - g_{M},\ \beta_{M}\left( \pi_{MN}g_{N} \right) - d\pi_{MN}\beta_{N}\left( g_{N} \right),\ \Omega_{spec},\ \Omega_{quot} \right).$$

The live condition is

$${Live}_{AS}(g)\quad \Leftrightarrow \quad\mathcal{O}_{AS}(g) = 0$$

up to declared tolerances and quotient admission.

This is the AS carrier reduction. It is not the same texture as the P-space reduction at every stage. The P-space reduction removes a countable selector problem by identifying a single source-neighborhood carrier. The AS reduction removes finite-row evidence by identifying the actual dynamical obstruction map. Both are carrier reductions, but they are not the same local mechanism.

### 13C.7 Texture audit: what matches and what does not

The carrier-reduction test prevents false unification.

The P-space rectangle problem has selector texture:

$$\forall n,\ \mathcal{R}_{n} \neq \varnothing\quad\text{but maybe}\quad\prod_{n}^{}\mathcal{R}_{n} = \varnothing.$$

The AS quotient test has quotient texture: a raw direction is either killed by the quotient, meaning `dq(v)=0`, or it survives as a physical direction, meaning `dq(v)` is nonzero.

These are not the same mechanism. The correct AS comparison to P-space rectangle choice is the spectral-continuation or finite-row assembly stage, not the quotient-killing stage. The quotient stage compares only to P-space internality/support failures in a symmetric/permutation model.

Thus Declared Witness Assembly must preserve two distinctions:

$$\boxed{\Delta_{specSel}^{AS}\text{ is comparable to }\Delta_{rectSel}^{P}.}$$

and

$$\boxed{\Delta_{quot}^{AS}\text{ is comparable to P-space support/internality residuals only when such a model is declared.}}$$

The carrier-reduction discovery test forces this texture audit. It blocks the programme from hiding concrete differences under a shared parent theorem.

### 13C.8 What would count as a scored DWA discovery?

For the P-space branch, a scored DWA discovery would be one of the following:

- a proof that every rectangular-core operator (B\_{W}) has a live source in ZF;
- a construction of a family for which the carrier (S_x) has no live source, yielding a countermodel;
- a compact/readout theorem for (S_x) that was not already present in P-space topology and that decides a nontrivial class of cases;
- a support-uniformization theorem deciding the symmetric/permutation-model route.

For the AS branch, a scored DWA discovery would be one of:

- a new finite-map certificate not already available inside AS numerics;
- a projective compactness condition that turns finite certified rows into an exact fixed-point germ;
- a quotient/eigenspace descent theorem forcing or blocking physical critical-rank admission;
- a carrier reduction that changes the AS proof search rather than rephrasing known truncation practice.

The general DWA paper should not claim these are already landed. It should state them as the scoring tests.

### 13C.9 Revised Neptune criterion

The Neptune is not a shared residual label and not an abstract parent completion. The Neptune is:

$$\boxed{\text{DWA predicts the right carrier/obstruction pair in a target domain and that pair yields a result.}}$$

If the rectangular-core carrier in the P-space branch leads to a proof, countermodel, or new strong no-go, then the carrier-reduction method scored. If the AS beta/projective carrier leads to a sharper finite-to-exact theorem or quotient-rank obstruction, it scored. If one carrier-reduction insight transfers nontrivially to the other branch, that is stronger still. But the first standard is already precise: predict the carrier reduction before the solution.

## 14. What DWA gives back to the Theory of Organization stack

DWA is downstream of the core Theory of Organization papers, but it also clarifies them.

### 14.1 To triadic closure

DWA gives a canonical use-case for triadic closure. The triad is not only a role vocabulary. It is the minimal face structure required for admissible witness assembly:

$$\mathsf{Z} + \mathsf{R} + \mathsf{O}\quad ⤳ \quad Adm + Coh + Readout/\Omega.$$

The assembly triadic inequality makes the closure discipline inspectable.

### 14.2 To Recursive Chart Learning Theory

DWA supplies the static section form. RCLT supplies the dynamic admitted-trace form. When the index object (I) has time, recursion, or dependency structure, a witness section becomes an admitted trace:

$$I \ni i \mapsto s(i) \in E_{i}.$$

If later fibers or admissibility boundaries depend on earlier witnesses, DWA becomes recursive witness assembly and belongs naturally inside RCLT.

### 14.3 To NUR, NUB, and NUO

DWA gives the no-go stack a major theorem application. Any local-to-global proof that does not declare local fibers, admissibility, coherence, readout, and residuals is underdeclared.

This yields a derived no-go:

$$\boxed{\text{No Undeclared Assembly.}}$$

and its witness-facing corollary:

$$\boxed{\text{No Undeclared Witness.}}$$

### 14.4 To Face Requirement Kernels

DWA provides a large and reusable family of kernels:

$$\mathfrak{K}_{asm} = \left( E,\mathcal{B}_{asm},\mathcal{M}_{asm},\mathcal{V}_{asm},{Coh}_{asm},\Omega_{asm} \right).$$

This turns FRK from an audit object into a section-construction object.

### 14.5 To Bridge-Valence Diagnostics and GBS

DWA supplies a common target for BVD and GBS. BVD diagnoses which assembly residual is live; GBS searches for a source-admitted assembly operator that could kill it. This is why AS beta-map/eigenspace assembly and P-space rectangle-refinement assembly can be compared without pretending they are the same field.

## 15. Compactness as programme-native, not programme-owned

The compact proof used in this paper is standard. The programme does not own compactness. What it can contribute is the general compact-residual form:

$$\boxed{\Delta_{comp} = 0\quad \Leftrightarrow \quad\text{finite declared coherence lands in a global declared carrier.}}$$

Topological compactness, logical compactness, Stone duality, inverse limits, weak compactness, and spectral projection stability are different bridges into this same face. The strong future test is predictive: can the DWA normal form call for a compact-style bridge in a domain where the bridge has not yet been built, and can that bridge then be constructed?

This is the correct reach criterion. If DWA merely re-files known compactness bridges, it is powerful exposition. If it predicts and builds a new compact assembly bridge, it becomes a stronger programme result.

## 16. Research programme

### 16.1 General theory tasks

1.  Develop a categorical version of (W) where (I) is a category and (EI) is a fibration.
2.  Define morphisms of witness systems.
3.  Define residual-preserving and residual-killing functors.
4.  Build a bridge library: compactness, inverse limits, sheaf gluing, selector principles, quotient descent, Riesz projection, support uniformization.
5.  Prove comparison theorems showing when two domains instantiate the same residual coordinate rather than merely similar-looking ones.

### 16.2 AS tasks

1.  Complete finite beta-map certificates for more explicit truncations.
2.  Verify projective beta compatibility where formal towers are declared.
3.  Compute eigenspaces, not only eigenvalues, for raw rank-split examples.
4.  Test quotient verticality:

$$dq\left( v_{i} \right) = 0.$$

5.  Determine whether (*q(W*{})) is nonempty under explicit PGSQ hypotheses.

### 16.3 P-space tasks

1.  Analyze whether the (C_nS_x) constraints always admit a ZF-native compact carrier.
2.  Determine whether (C_n) can be represented as closed constraints in known compactifications of local-neighborhood posets.
3.  Build or refute support-escaping symmetric/permutation examples.
4.  Test whether Tachtsis-Wajch style spaces can produce (\_{}) failure after the disjoint-sum normal form.
5.  If no countermodel route survives, attempt a ZF proof using the rectangular compactness lemma.

## 17. Conclusion

The shared object is

$$\Gamma\left( \mathfrak{W} \right),$$

and in quotient-sensitive cases,

$$\Gamma_{q}\left( \mathfrak{W}_{q} \right).$$

This is the mathematical form of the local-to-global witness problem. The normal-form theorem says every legitimate assembly claim must declare this object. The obstruction theorem says every failure must localize to a named residual. The compact face says compactness is the residual-killer for finite-to-global assembly when constraints are closed in a compact carrier.

The asymptotic-safety beta-map branch and the ZF P-space branch are clean instances. In AS, finite beta-map witnesses and eigenspaces must assemble into a quotient-compatible exact fixed-point/rank witness. In P-spaces, local rectangle witnesses must assemble into a countable section, or equivalently into a live source for the rectangular-core operator.

The framework has not proved either domain’s hardest theorem. But it has extracted a cross-domain mathematical object and a residual vocabulary precise enough to drive further proof search. Draft v0.3 sharpens the next demand: a comparison is real only when a residual-comparison bridge preserves boundary, mediation, readout, and residual-killing obligations; a predictive bridge is reach only when the normal form calls for a bridge not already available in the target field and that bridge is constructed or refuted. That is the proper claim.

## Appendix A. Compactness, Stone duality, and the assembly face

Stone duality illustrates the history of compact-assembly bridges. A Boolean algebra can be represented by clopen sets in a compact totally disconnected Hausdorff space. Boolean consistency becomes finite intersection of clopens; ultrafilters become global witnesses. What looks like a logical/algebraic assembly problem becomes topological compactness after the Stone bridge is built.

This paper proposes that declared witness assembly is the general normal form in which such bridges live. Stone duality is a known instance; it is not evidence that the present programme has proved a new bridge. The forward test is whether the normal form predicts a bridge not already built.

## Appendix B. P-space rectangular choice summary

Let $X,Y$ be P-spaces and $\left( W_{n} \right)$ open neighborhoods of $(x,y)$.

Define

$$\mathcal{R}_{n} = \{(U,V):x \in U,y \in V,U \times V \subseteq W_{n}\}.$$

Then $X \times Y$ is a P-space iff every such family $\left( \mathcal{R}_{n} \right)$ has a choice function.

The latest map-level reformulation defines

$$V_{W}(U) = \bigcup\{ V:V\text{ open},y \in V,U \times V \subseteq W\}$$

and

$$B_{\overrightarrow{W}}^{X \rightarrow Y}(U) = \bigcap_{n}V_{W_{n}}(U).$$

Then $\bigcap_{n}W_{n}$ is a product-neighborhood of $(x,y)$ iff there exists open $U \ni x$ with

$$y \in B_{\overrightarrow{W}}^{X \rightarrow Y}(U).$$

This is the P-space analogue of a beta map.

## Appendix C. AS beta-map summary

A finite beta-map certificate has the form

$$\beta_{N}:U_{N} \subseteq \mathbb{R}^{d} \rightarrow \mathbb{R}^{d},$$

with approximate fixed point $g_{0}$, approximate inverse $A$, norm, radius $r$, and bounds $Y,Z,L$ satisfying a Newton/Kantorovich or radii-polynomial condition. The local result is

$$\exists!\ g_{N}^{*} \in B\left( g_{0},r \right):\beta_{N}\left( g_{N}^{*} \right) = 0.$$

A spectral certificate adds stability of relevant rank in the finite map.

Global exact-AS assembly then requires projective coherence, compact/tight completion, beta compatibility, physical quotient descent, and spectral stability.

## References

### Internal Theory of Organization folder sources

The following internal sources are referenced only as Theory of Organization programme documents.

1.  *relation_first_constraint_position_statement_v0_4.md*.
2.  *theory_of_organization_foundation_v0_5_1_final_clean.md*.
3.  *charted_organization_theory_v0_5.md*.
4.  *recursive_chart_learning_theory_v0_5.md*.
5.  *triadic_closure_recursive_residual_theory_v0_7.md*.
6.  *triadic_substitution_coupling_closure_atlases_v0_9.md*.
7.  *cross_closure_instantiation_theorems_v0_7.md*.
8.  *no_undeclared_relation_bridge_completion_v1_1.md*.
9.  *no_undeclared_boundary_v0_5.md*.
10. *no_undeclared_observer_v0_5.md*.
11. *face_requirement_kernels_foundation_paper_v0_6_discriminating_negatives.md*.
12. *recursive_bridge_calibration_v1_7.md*.
13. *bridge_accessibility_target_relative_inaccessibility_v0_5_reader_facing.md*.
14. *bridge_valence_diagnostics_predictive_criticality_v1_12.md*.
15. *generative_bridge_search_structural_unblocker_transfer_v0_16.md*.
16. *projective_completion_physical_critical_rank_as_v1_4_submission_integrated.md*.
17. *as_finite_beta_map_validation_companion_v0_5_FULL_PRESERVATION_REPAIR.md*.
18. *as_physical_critical_rank_quotient_v0_6_FULL_PRESERVATION_REPAIR.md*.
19. *as_chart_descent_obstruction_certificate_v0_9_self_contained.md*.

### External mathematical references

20. K. Keremedis, A. Olfati, and E. Wajch, *P-spaces in the absence of the Axiom of Choice*, arXiv:2111.13990, 2021.
21. E. Tachtsis and E. Wajch, *Constructing crowded Hausdorff P-spaces in set theory without the axiom of choice*, arXiv:2510.11935, 2025.
22. M. H. Stone, *The Theory of Representations for Boolean Algebras*, Transactions of the American Mathematical Society, 1936.
23. P. T. Johnstone, *Stone Spaces*, Cambridge University Press, 1982.
24. N. Bourbaki, *General Topology*, for the closed-set finite-intersection formulation of compactness.
25. T. Kato, *Perturbation Theory for Linear Operators*, for spectral projection stability.
26. A. Connes, *Une classification des facteurs de type III*, Annales scientifiques de l’Ecole Normale Superieure, 1973.
27. R. Haag, *Local Quantum Physics*, for operator-algebraic and modular-theoretic background.

---

## AI-assistance disclosure

This manuscript was developed with AI-assisted drafting and review support. The author directed the research programme, selected and revised the mathematical and methodological content, and is responsible for all claims and errors.
