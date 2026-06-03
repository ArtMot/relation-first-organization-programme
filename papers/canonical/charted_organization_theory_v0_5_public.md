# Charted Organization Theory: Observers, Atlases, and Objectivity in Relation-First Systems

**Author:** Artur Motruk  
**Affiliation:** Independent researcher  
**ORCID:** 0009-0003-6928-1701  
**Programme:** Relation-First Organization Programme  
**Document role:** Core foundation / charting, observer, and atlas layer  
**Public release status:** Repository manuscript for public programme release  

---

## Foundation Statement

A charted organization structure is an observer-relative presentation of a primitive relation carrier. A chart is not an external coordinate object placed over a relation. A chart is a relation-map whose domain is a proper subrelation of the primitive carrier. Its answer, question, and zero-boundary faces are induced by the chart relation-map. An observer is an admissible positioned chart: a local relation-map inside the carrier through which organization becomes partially readable. Organization is therefore chart-relative. Information is task-visible delineation induced by a chart. Objective content is nonvacuous invariance across admissible chart transitions. Constants are common values of invariant chart quantities, not primitive objects. Objecthood is persistent proper organization across an admissible atlas. Presentation equivalence is derived from equivalence of chart-induced organization structures; it is not imported as an external Morita principle.

A selector is not a new primitive. A task selects by determining which admissible sub-chart is sufficient for its resolution. The atlas is not identical to the primitive carrier; it is the admissible chart and transition structure generated inside the carrier.

---

## 0. Scope and Relation to the Theory of Organization

### 0.1 Scope

This paper defines a mathematical companion layer to the relation-first Theory of Organization.

No physical realization map is defined in this paper.

No claim is made here about spacetime, fields, particles, measurement, dynamics, probability, Hilbert spaces, Lagrangians, physical constants, or physical law.

### 0.2 Layer Separation

The Theory of Organization defines proper organizations from a quotient-presented resolution carrier.

This paper adds observer-relative charting.

The base question is not

\[
\text{What organizations does }R\text{ have globally?}
\]

but

\[
\text{What organizations become visible under an admissible chart of }R?
\]

### 0.3 Retained Commitments

The following commitments are retained.

1. Relation is prior to independently given answer, question, and value faces.
2. Proper organization excludes both boundary extremes.
3. Trivial or boundary-collapsed presentations do not generate proper organization.
4. Evaluation and task relevance are meaningful only after the relevant preservation data are declared.
5. A relation-internal task is not an external selector; it is a demand that may induce chart selection.

### 0.4 New Commitments

This layer introduces the following commitments.

1. Organization is chart-relative.
2. A chart is a relation-map internal to the primitive relation carrier.
3. An observer is an admissible positioned chart of the primitive relation carrier.
4. A nested chart is a chart; no separate partial-chart species is introduced.
5. Information is chart-induced, task-visible delineation.
6. Objectivity is atlas-relative and means nonvacuous invariance across admissible chart transitions.
7. Constants are invariants of chart transition, not primitive objects.
8. Objecthood is persistent organization across charts, not primitive self-standing substance.
9. Presentation equivalence is derived from organization-preserving chart transitions.
10. Selector-completeness is chart-completeness of relation-internal tasks, not an independent mechanism.

### 0.5 Terminology

The word **observer** does not mean a conscious subject.

An observer is an admissible local relation-map inside the primitive carrier.

The word **chart** does not mean a passive coordinate grid.

A chart is a relation-map whose domain is a proper subrelation of the primitive carrier and whose face-readouts induce a local organization structure.

The word **atlas** is used by analogy with charted presentation. It denotes a family of admissible charts together with specified transition maps. No manifold structure is assumed.

The word **information** does not mean a substance.

Information means chart-relative delineation.

The word **selector** does not introduce a new primitive.

A selector is the chart-selecting role of a relation-internal task.

### 0.6 Adjacent Frameworks

This paper sits near several existing frameworks.

Formal Concept Analysis supplies the local Galois fixed-point machinery once a chart-induced satisfaction relation is given. The present paper does not claim novelty for the local closure operators; it uses them as the chartwise organization machinery inherited from the Theory of Organization.

Chu-space and dialectica-style structures supply a general pattern in which states and questions are paired by an evaluation map. The present paper is adjacent to that pattern because each chart induces answer and question faces paired by \(\rho_{\mathcal C}\). It differs by requiring a zero-boundary order, proper-layer excision, chart admissibility, atlas transitions, and task-induced chart selection.

Topos and presheaf approaches to quantum foundations treat context-dependent descriptions and restriction maps as primary. The analogy here is context-indexing: a chart plays the role of a local presentation, and an atlas records permitted transitions among such presentations. The present paper does not assume quantum contexts, commutative subalgebras, a spectral presheaf, or a topos-internal logic.

Sheaf-theoretic contextuality studies when local empirical data fail to glue into a global section. The analogy here is gluing versus obstruction: atlas-relative invariance resembles a global-compatible assignment across chart transitions. The present paper is not a probabilistic contextuality theory; it has no empirical-model presheaf and no probability distributions unless additional structure is added.

Fibered and indexed-category language could re-express the chart family as a structured family of local presentations over a base of chart domains and transitions. The present paper stays at the set-level and relation-map level. It does not assume a Grothendieck fibration, although an indexed-category reformulation may later be possible.

The point of these comparisons is positioning. No external topos, sheaf, Morita, or fibration theorem is assumed.

---

## 1. Conventions

For a set \(X\),

\[
\mathcal P(X):=\{S:S\subseteq X\}.
\]

A partially ordered set \((L,\leq)\) is a **complete lattice** when every subset \(S\subseteq L\) has a meet \(\bigwedge S\) and a join \(\bigvee S\).

A complete lattice \((L,\leq)\) is **bounded** by

\[
0_L:=\bigwedge L,
\qquad
1_L:=\bigvee L.
\]

For \(x,y\in L\),

\[
x<y
\]

means

\[
x\leq y\quad\text{and}\quad x\neq y.
\]

The **proper interior** of a bounded lattice \(L\) is

\[
L^{\circ}:=L\setminus\{0_L,1_L\}.
\]

For a map \(h:X\to Y\) and a subset \(S\subseteq X\),

\[
h[S]:=\{h(x):x\in S\}.
\]

For a map \(h:X\to Y\) and a subset \(T\subseteq Y\),

\[
h^{-1}[T]:=\{x\in X:h(x)\in T\}.
\]

For a map \(h:X\to Y\), define its kernel equivalence relation by

\[
x\equiv_h x'
\quad\Longleftrightarrow\quad
h(x)=h(x').
\]

A map between posets

\[
k:L\to M
\]

is **monotone** when

\[
x\leq_L y\Rightarrow k(x)\leq_M k(y).
\]

It is an **order embedding** when

\[
x\leq_L y\Longleftrightarrow k(x)\leq_M k(y).
\]

An order embedding is injective.

---

## 2. Primitive Relation Carrier and Sub-Charts

### Definition 2.1: Primitive Relation Carrier

A **primitive relation carrier** is a nonempty set

\[
R.
\]

Elements of \(R\) are called **relation-occurrences**.

No answer face, question face, zero-boundary face, observer, chart, information, object, constant, atlas, task, or selector is primitive at this level.

### Definition 2.2: Subrelation

A **subrelation** of \(R\) is a nonempty subset

\[
C\subseteq R.
\]

A subrelation \(C\) is **proper** when

\[
C\subsetneq R.
\]

### Definition 2.3: Nested Subrelation

If

\[
D\subseteq C\subseteq R,
\]

then \(D\) is a **nested subrelation** of \(C\).

When both inclusions are proper,

\[
D\subsetneq C\subsetneq R,
\]

\(D\) is a **proper nested subrelation** of \(C\).

### Convention 2.4: No Separate Partial-Chart Type

This paper does not introduce a second species called a partial chart.

A restricted chart is treated as a nested chart.

Admissibility is not inherited automatically by nested charts.

### Definition 2.5: Global Subrelation

The subrelation \(C=R\) is called **global**.

A global subrelation is not an observer-chart in this paper.

### Remark 2.6

The exclusion of \(C=R\) from observer-charts is not a claim that global mathematical study is impossible.

It is a definition of observer-chart: an observer-chart is a proper local presentation, not the carrier itself.

---

## 3. Charts as Relation-Maps

### Principle 3.1: Chart Relation Principle

A chart is not an external coordinate object placed over \(R\).

A chart is a relation-map whose domain is a proper subrelation of \(R\).

The chart's answer, question, and zero-boundary faces are not independently primitive. They are induced by the chart relation-map.

### Definition 3.2: Prechart Relation-Map

A **prechart relation-map** on \(R\) is a tuple

\[
\mathcal C=(C,A_{\mathcal C},Q_{\mathcal C},Z_{\mathcal C},
\alpha_{\mathcal C},\chi_{\mathcal C},\zeta_{\mathcal C},\preceq_{\mathcal C})
\]

such that:

1. \(C\subseteq R\) is a nonempty subrelation;
2. \(A_{\mathcal C}\), \(Q_{\mathcal C}\), and \(Z_{\mathcal C}\) are nonempty sets;
3. \(\alpha_{\mathcal C}:C\to A_{\mathcal C}\), \(\chi_{\mathcal C}:C\to Q_{\mathcal C}\), and \(\zeta_{\mathcal C}:C\to Z_{\mathcal C}\) are surjective maps;
4. \(\preceq_{\mathcal C}\) is a partial order on \(Z_{\mathcal C}\);
5. \((Z_{\mathcal C},\preceq_{\mathcal C})\) is a complete lattice.

Surjectivity in clause 3 says that the chart faces contain no unused answer, question, or zero-boundary values. Equivalently, the faces may be read as the images of the face-readout maps. This keeps chart data tied to the relation-map rather than allowing extraneous face elements.

### Definition 3.3: Chart Faces

For a prechart relation-map \(\mathcal C\), define:

\[
A_{\mathcal C}=\text{the answer face of }\mathcal C,
\]

\[
Q_{\mathcal C}=\text{the question face of }\mathcal C,
\]

and

\[
Z_{\mathcal C}=\text{the zero-boundary face of }\mathcal C.
\]

The maps

\[
\alpha_{\mathcal C}:C\to A_{\mathcal C},
\qquad
\chi_{\mathcal C}:C\to Q_{\mathcal C},
\qquad
\zeta_{\mathcal C}:C\to Z_{\mathcal C}
\]

are called the **face-readout maps** of \(\mathcal C\).

### Definition 3.4: Kernel Equivalence Relations of a Chart

The answer, question, and zero-boundary kernel equivalence relations induced by \(\mathcal C\) are:

\[
r\equiv_A^{\mathcal C}s
\quad\Longleftrightarrow\quad
\alpha_{\mathcal C}(r)=\alpha_{\mathcal C}(s),
\]

\[
r\equiv_Q^{\mathcal C}s
\quad\Longleftrightarrow\quad
\chi_{\mathcal C}(r)=\chi_{\mathcal C}(s),
\]

and

\[
r\equiv_Z^{\mathcal C}s
\quad\Longleftrightarrow\quad
\zeta_{\mathcal C}(r)=\zeta_{\mathcal C}(s).
\]

Thus quotient faces may be recovered as

\[
A_{\mathcal C}\cong C/{\equiv_A^{\mathcal C}},
\qquad
Q_{\mathcal C}\cong C/{\equiv_Q^{\mathcal C}},
\qquad
Z_{\mathcal C}\cong C/{\equiv_Z^{\mathcal C}}.
\]

### Definition 3.5: Chart Incidence Fiber

For \(a\in A_{\mathcal C}\) and \(q\in Q_{\mathcal C}\), define

\[
C_{a,q}:=\{r\in C:\alpha_{\mathcal C}(r)=a\text{ and }\chi_{\mathcal C}(r)=q\}.
\]

### Definition 3.6: Functional Prechart

A prechart relation-map \(\mathcal C\) is **functional** when for every \(a\in A_{\mathcal C}\) and every \(q\in Q_{\mathcal C}\), the set

\[
\zeta_{\mathcal C}[C_{a,q}]
\]

has exactly one element.

### Definition 3.7: Chart Resolution Map

If \(\mathcal C\) is functional, define

\[
\rho_{\mathcal C}:A_{\mathcal C}\times Q_{\mathcal C}\to Z_{\mathcal C}
\]

by

\[
\rho_{\mathcal C}(a,q)=z
\]

if and only if

\[
\zeta_{\mathcal C}[C_{a,q}]=\{z\}.
\]

### Proposition 3.8: Well-Definedness of Chart Resolution

If \(\mathcal C\) is functional, then \(\rho_{\mathcal C}\) is a well-defined total function.

#### Proof

Let \(a\in A_{\mathcal C}\) and \(q\in Q_{\mathcal C}\). By functionality, \(\zeta_{\mathcal C}[C_{a,q}]\) has exactly one element. Therefore there exists a unique \(z\in Z_{\mathcal C}\) such that \(\zeta_{\mathcal C}[C_{a,q}]=\{z\}\). Hence \(\rho_{\mathcal C}(a,q)=z\) is defined uniquely for every pair \((a,q)\). □

### Definition 3.9: Chart

A **chart** on \(R\) is a functional prechart relation-map whose carrier \(C\) is proper:

\[
C\subsetneq R.
\]

### Remark 3.10: Chart Readout and Relation-First Status

A chart may select face-readouts that are not uniquely determined by \(R\) alone. This is not an additional primitive object. It is chart data carried by a relation-map on a subrelation of \(R\).

Relation-first status is preserved in the following bounded sense: chart faces are induced by maps on a relation carrier, not given as independent substances. The framework does not claim that \(R\) uniquely determines every admissible chart.

### Remark 3.11: Total Pair Coverage

Functionality includes total pair coverage: for every \((a,q)\in A_{\mathcal C}\times Q_{\mathcal C}\), the fiber \(C_{a,q}\) must be nonempty and must have a unique zero-boundary value.

This is inherited from the total presentation used in the Theory of Organization.

Nested charts replace a separate partial-function formalism. A nested chart may fail admissibility even when the larger chart is admissible.

---

## 4. Chart-Relative Organization

Let \(\mathcal C\) be a chart.

### Definition 4.1: Threshold Cut

For \(\theta\in Z_{\mathcal C}\), define

\[
a\Vdash^{\theta}_{\mathcal C}q
\]

if and only if

\[
\theta\preceq_{\mathcal C}\rho_{\mathcal C}(a,q).
\]

### Definition 4.2: Upward Derivation

For \(S\subseteq A_{\mathcal C}\), define

\[
S^{\uparrow_{\theta}}
:=
\{q\in Q_{\mathcal C}:\forall a\in S,\ a\Vdash^{\theta}_{\mathcal C}q\}.
\]

### Definition 4.3: Downward Derivation

For \(T\subseteq Q_{\mathcal C}\), define

\[
T^{\downarrow_{\theta}}
:=
\{a\in A_{\mathcal C}:\forall q\in T,
\ a\Vdash^{\theta}_{\mathcal C}q\}.
\]

### Theorem 4.4: Chart Galois Law

For all \(S\subseteq A_{\mathcal C}\) and \(T\subseteq Q_{\mathcal C}\),

\[
S\subseteq T^{\downarrow_{\theta}}
\quad\Longleftrightarrow\quad
T\subseteq S^{\uparrow_{\theta}}.
\]

#### Proof

The statement \(S\subseteq T^{\downarrow_{\theta}}\) means

\[
\forall a\in S,\forall q\in T,
\ a\Vdash^{\theta}_{\mathcal C}q.
\]

The statement \(T\subseteq S^{\uparrow_{\theta}}\) means

\[
\forall q\in T,\forall a\in S,
\ a\Vdash^{\theta}_{\mathcal C}q.
\]

These are the same condition with quantifiers reordered. □

### Definition 4.5: Chart-Relative Organization

A **chart-relative organization** at threshold \(\theta\) is a pair

\[
(S,T)
\]

with

\[
S\subseteq A_{\mathcal C},
\qquad
T\subseteq Q_{\mathcal C},
\]

such that

\[
S=T^{\downarrow_{\theta}}
\]

and

\[
T=S^{\uparrow_{\theta}}.
\]

The set of chart-relative organizations is denoted

\[
\operatorname{Org}_{\theta}(\mathcal C).
\]

### Definition 4.6: Boundary Organizations

The **lower boundary organization** is

\[
\bot_{\theta}^{\mathcal C}:=(Q_{\mathcal C}^{\downarrow_{\theta}},Q_{\mathcal C}).
\]

The **upper boundary organization** is

\[
\top_{\theta}^{\mathcal C}:=(A_{\mathcal C},A_{\mathcal C}^{\uparrow_{\theta}}).
\]

This convention matches the boundary convention used in the Theory of Organization, with order by answer-face inclusion.

### Definition 4.7: Proper Organization Layer

The **proper organization layer** is

\[
\operatorname{Org}^{\circ}_{\theta}(\mathcal C)
:=
\operatorname{Org}_{\theta}(\mathcal C)
\setminus
\{\bot_{\theta}^{\mathcal C},\top_{\theta}^{\mathcal C}\}.
\]

### Remark 4.8: Boundary-Excision Rationale

The proper layer removes both extremal fixed points because each extremum is insensitive to the internal pattern of \(\rho_{\mathcal C}\) in a different way. The lower boundary collects the fully saturated question side; the upper boundary collects the fully saturated answer side. Neither boundary records a proper intermediate delineation between unresolved collapse and total saturation.

Thus boundary excision is not an additional metaphysical decoration. It is the chartwise version of the parent theory's rule that organization lives in the non-boundary layer where resolution patterns can make a difference.

### Definition 4.9: Observer-Relative Organization

If \(O\) is an observer-chart represented by \(\mathcal C_O\), then

\[
\operatorname{Org}^{\circ}_{\theta,O}(R)
:=
\operatorname{Org}^{\circ}_{\theta}(\mathcal C_O).
\]

---

## 5. Observer-Charts and Admissibility

### Definition 5.1: Formal Observer-Chart

A **formal observer-chart** of \(R\) is a chart \(\mathcal C\) on \(R\).

### Definition 5.2: Pre-Admissible Observer-Chart

A chart \(\mathcal C\) is **pre-admissible** when:

1. \(C\subsetneq R\);
2. \(A_{\mathcal C}\) and \(Q_{\mathcal C}\) each contain at least two elements;
3. \(\operatorname{Im}(\rho_{\mathcal C})\cap Z_{\mathcal C}^{\circ}\neq\varnothing\);
4. \(\rho_{\mathcal C}\) is not constant.

### Definition 5.3: Organization-Bearing Observer-Chart

A chart \(\mathcal C\) is **organization-bearing** when there exists \(\theta\in Z_{\mathcal C}^{\circ}\) such that

\[
\operatorname{Org}^{\circ}_{\theta}(\mathcal C)\neq\varnothing.
\]

### Definition 5.4: Admissible Observer-Chart

An **admissible observer-chart** is a chart that is pre-admissible and organization-bearing.

An **observer** is an admissible observer-chart considered in its positioned role inside \(R\).

### Remark 5.5

The admissibility definition is intentionally two-stage. Pre-admissibility removes immediate formal degeneracies. Organization-bearing status requires that the chart actually induce a nonempty proper organization layer.

### Proposition 5.6: Admissibility Is Not Inherited by Nested Charts

There exist charts \(\mathcal D\subseteq\mathcal C\subsetneq R\) such that \(\mathcal C\) is admissible and \(\mathcal D\) is not admissible.

#### Proof

Let \(\mathcal C\) be any admissible chart with at least two relation-occurrences. Choose a singleton subrelation \(D=\{r\}\subseteq C\) and let \(\mathcal D\) be the induced singleton chart. Then \(A_{\mathcal D}\) and \(Q_{\mathcal D}\) each have one element. Hence \(\mathcal D\) is single-sided and not pre-admissible. Therefore admissibility is not inherited by nested charts. □

---

## 6. Degeneracy and No-Go Results

### Theorem 6.1: Single-Boundary Charts Have Empty Proper Organization

Let \(\mathcal C\) be a chart such that

\[
\operatorname{Im}(\rho_{\mathcal C})=\{0_{\mathcal C}\}
\]

or

\[
\operatorname{Im}(\rho_{\mathcal C})=\{1_{\mathcal C}\}.
\]

Then for every \(\theta\in Z_{\mathcal C}^{\circ}\),

\[
\operatorname{Org}^{\circ}_{\theta}(\mathcal C)=\varnothing.
\]

#### Proof

Assume \(\operatorname{Im}(\rho_{\mathcal C})=\{0_{\mathcal C}\}\). For \(\theta\in Z_{\mathcal C}^{\circ}\), no pair \((a,q)\) satisfies \(\theta\preceq_{\mathcal C}\rho_{\mathcal C}(a,q)\), since \(\theta\not\preceq 0_{\mathcal C}\). Thus the satisfaction relation is empty.

For the empty satisfaction relation, the only closed pairs are the two boundary pairs. Hence the proper layer is empty.

Assume \(\operatorname{Im}(\rho_{\mathcal C})=\{1_{\mathcal C}\}\). For every \(\theta\in Z_{\mathcal C}^{\circ}\), every pair \((a,q)\) satisfies \(\theta\preceq_{\mathcal C}\rho_{\mathcal C}(a,q)\). Thus the satisfaction relation is universal. For the universal satisfaction relation, the only closed pairs are again the two boundary pairs. Hence the proper layer is empty. □

### Theorem 6.2: Constant Resolution Gives Empty Proper Organization

If \(\rho_{\mathcal C}\) is constant, then for every \(\theta\in Z_{\mathcal C}^{\circ}\), the threshold cut is either empty or universal. Therefore

\[
\operatorname{Org}^{\circ}_{\theta}(\mathcal C)=\varnothing.
\]

#### Proof

Let \(\rho_{\mathcal C}(a,q)=z\) for all \((a,q)\). If \(\theta\preceq z\), the threshold cut is universal. If not, the threshold cut is empty. Empty and universal cuts have only boundary organizations. □

### Theorem 6.3: Single-Sided Charts Have Empty Proper Organization

If \(|A_{\mathcal C}|=1\) or \(|Q_{\mathcal C}|=1\), then for every \(\theta\),

\[
\operatorname{Org}^{\circ}_{\theta}(\mathcal C)=\varnothing.
\]

#### Proof

Assume \(|A_{\mathcal C}|=1\). Then any closed extent is either \(\varnothing\) or \(A_{\mathcal C}\). Therefore any organization is one of the two boundary organizations. Hence the proper layer is empty. The argument for \(|Q_{\mathcal C}|=1\) is dual. □

### Corollary 6.4: Self-Loop-Only Charts Are Organizationally Sterile

A chart with one answer face and one question face has empty proper organization layer at every threshold.

#### Proof

Immediate from Theorem 6.3. □

### Theorem 6.5: Boundary or Constant Charts Are Not Admissible

If \(\mathcal C\) satisfies the hypothesis of Theorem 6.1 or Theorem 6.2, then \(\mathcal C\) is not an admissible observer-chart.

#### Proof

By Theorems 6.1 and 6.2, no proper organization layer is nonempty. Hence \(\mathcal C\) is not organization-bearing. □

---

## 7. Information as Chart-Relative Delineation

### Definition 7.1: Face-Induced Indistinguishability

For \(r,s\in C\), define

\[
r\sim_{A,Q}^{\mathcal C}s
\]

when

\[
\alpha_{\mathcal C}(r)=\alpha_{\mathcal C}(s)
\quad\text{and}\quad
\chi_{\mathcal C}(r)=\chi_{\mathcal C}(s).
\]

### Definition 7.2: Face Delineation

A chart \(\mathcal C\) **face-delineates** \(r,s\in C\) when

\[
\neg(r\sim_{A,Q}^{\mathcal C}s).
\]

### Definition 7.3: Threshold Delineation

A chart \(\mathcal C\) **threshold-delineates** \(r,s\in C\) at \(\theta\) when their induced face-pair statuses differ at threshold \(\theta\).

Equivalently, if

\[
a_r=\alpha_{\mathcal C}(r),
\quad
q_r=\chi_{\mathcal C}(r),
\]

and similarly for \(s\), then

\[
\theta\preceq_{\mathcal C}\rho_{\mathcal C}(a_r,q_r)
\]

and

\[
\theta\preceq_{\mathcal C}\rho_{\mathcal C}(a_s,q_s)
\]

have different truth values.

### Definition 7.4: Chart Information

The **information carried by a chart** is its induced delineation structure:

1. its face-delineation relation;
2. its threshold-delineation relations over \(\theta\in Z_{\mathcal C}^{\circ}\);
3. its proper organization layers.

### Definition 7.5: Information

In charted organization theory, **information** means task-visible delineation induced by a chart.

### Theorem 7.6: Universal Indistinguishability Carries No Face Information

If

\[
r\sim_{A,Q}^{\mathcal C}s
\]

for all \(r,s\in C\), then \(\mathcal C\) carries no face-delineation information.

#### Proof

Face-delineation is the negation of \(\sim_{A,Q}^{\mathcal C}\). If \(\sim_{A,Q}^{\mathcal C}\) is universal, its negation is empty. □

### Theorem 7.7: Constant Resolution Carries No Threshold Information

If \(\rho_{\mathcal C}\) is constant, then no threshold \(\theta\) separates face-pair statuses.

#### Proof

This is the cut part of Theorem 6.2. For any threshold, the induced cut is empty or universal. Hence no two face-pairs differ in threshold status. □

---

## 8. Chart Transitions

### Definition 8.1: Chart Transition

Let \(\mathcal C\) and \(\mathcal D\) be charts. A **chart transition**

\[
\tau:\mathcal C\to\mathcal D
\]

is a triple

\[
\tau=(f,g,k)
\]

where

\[
f:A_{\mathcal C}\to A_{\mathcal D},
\]

\[
g:Q_{\mathcal D}\to Q_{\mathcal C},
\]

and

\[
k:Z_{\mathcal C}\to Z_{\mathcal D}
\]

is monotone, such that for all

\[
a\in A_{\mathcal C},
\qquad
q'\in Q_{\mathcal D},
\]

one has

\[
\rho_{\mathcal D}(f(a),q')=k\big(\rho_{\mathcal C}(a,g(q'))\big).
\]

### Definition 8.2: Cut-Preserving Transition

A chart transition \(\tau=(f,g,k):\mathcal C\to\mathcal D\) is **cut-preserving at \(\theta\in Z_{\mathcal C}\)** when for all \(a\in A_{\mathcal C}\) and \(q'\in Q_{\mathcal D}\),

\[
a\Vdash^{\theta}_{\mathcal C}g(q')
\quad\Longleftrightarrow\quad
f(a)\Vdash^{k(\theta)}_{\mathcal D}q'.
\]

### Proposition 8.3: Order-Embedding Transitions Preserve Cuts

If \(\tau=(f,g,k)\) is a chart transition and \(k\) is an order embedding, then \(\tau\) is cut-preserving at every \(\theta\in Z_{\mathcal C}\).

#### Proof

For \(a\in A_{\mathcal C}\) and \(q'\in Q_{\mathcal D}\),

\[
f(a)\Vdash^{k(\theta)}_{\mathcal D}q'
\]

if and only if

\[
k(\theta)\preceq_{\mathcal D}\rho_{\mathcal D}(f(a),q').
\]

By the transition equation, this is equivalent to

\[
k(\theta)\preceq_{\mathcal D}k(\rho_{\mathcal C}(a,g(q'))).
\]

Since \(k\) is an order embedding, this is equivalent to

\[
\theta\preceq_{\mathcal C}\rho_{\mathcal C}(a,g(q')),
\]

which is

\[
a\Vdash^{\theta}_{\mathcal C}g(q').
\]

□

### Definition 8.4: Isomorphic Chart Transition

A chart transition \(\tau=(f,g,k)\) is **isomorphic** when \(f\), \(g\), and \(k\) are bijections and \(k\) is an order isomorphism.

### Definition 8.5: Nonidentity Transition

A chart transition \(\tau:\mathcal C\to\mathcal D\) is **nonidentity** when either

\[
\mathcal C\neq\mathcal D
\]

or the transition is not the identity triple.

### Definition 8.6: Admissible Chart Transition

An **admissible chart transition** is a chart transition whose source and target are admissible observer-charts and whose transition type is among the transition types declared by the atlas.

The default transition types used in this paper are:

1. chart transitions;
2. cut-preserving chart transitions;
3. isomorphic chart transitions.

### Definition 8.7: Transition Composition

Let

\[
\tau_1=(f_1,g_1,k_1):\mathcal C\to\mathcal D
\]

and

\[
\tau_2=(f_2,g_2,k_2):\mathcal D\to\mathcal E.
\]

Define

\[
\tau_2\circ\tau_1
:=
(f_2\circ f_1,
\ g_1\circ g_2,
\ k_2\circ k_1).
\]

### Proposition 8.8: Chart Transitions Compose

The composite of chart transitions is a chart transition.

#### Proof

Let \(a\in A_{\mathcal C}\) and \(q''\in Q_{\mathcal E}\). Then

\[
\rho_{\mathcal E}(f_2(f_1(a)),q'')
=
k_2(\rho_{\mathcal D}(f_1(a),g_2(q'')))
\]

by \(\tau_2\). By \(\tau_1\),

\[
\rho_{\mathcal D}(f_1(a),g_2(q''))
=
k_1(\rho_{\mathcal C}(a,g_1(g_2(q'')))).
\]

Therefore

\[
\rho_{\mathcal E}(f_2(f_1(a)),q'')
=
(k_2\circ k_1)(\rho_{\mathcal C}(a,(g_1\circ g_2)(q''))).
\]

Thus the composite satisfies the transition equation. □

### Corollary 8.9: Isomorphic Chart Transitions Compose

The composite of isomorphic chart transitions is isomorphic.

#### Proof

Composites of bijections are bijections, and composites of order isomorphisms are order isomorphisms. Apply Proposition 8.8. □

---

## 9. Observer Atlases

### Definition 9.1: Relation-Map Class

Let \(\operatorname{RelMap}(R)\) denote the class of all charts on \(R\).

### Definition 9.2: Admissible Chart Class

The **admissible chart class** of \(R\) is

\[
\operatorname{AdmChart}(R):=\{\mathcal C\in\operatorname{RelMap}(R):\mathcal C\text{ is an admissible observer-chart}\}.
\]

Every element of \(\operatorname{AdmChart}(R)\) has carrier contained in \(R\), but \(\operatorname{AdmChart}(R)\) is not the same type of object as \(R\).

### Definition 9.3: Observer Atlas

An **observer atlas** on \(R\) is a pair

\[
\mathfrak A_R=(\mathbf C_R,\mathbf T_R)
\]

where:

1. \(\mathbf C_R\subseteq\operatorname{AdmChart}(R)\);
2. \(\mathbf T_R\) is a specified class of admissible chart transitions between elements of \(\mathbf C_R\);
3. \(\mathbf T_R\) contains identity transitions;
4. \(\mathbf T_R\) is closed under composition when the composite is defined.

### Definition 9.4: Nontrivial Atlas

An observer atlas \(\mathfrak A_R\) is **nontrivial** when \(\mathbf T_R\) contains at least one nonidentity transition.

### Definition 9.5: Single-Chart Atlas

A **single-chart atlas** is an atlas of the form

\[
(\{\mathcal C\},\{\operatorname{id}_{\mathcal C}\}).
\]

### Definition 9.6: Charted Organization Structure

A **charted organization structure** is a pair

\[
(R,\mathfrak A_R)
\]

where \(R\) is a primitive relation carrier and \(\mathfrak A_R\) is an observer atlas on \(R\).

### Remark 9.7: Atlas Internality

The atlas is internal to \(R\) in the sense that every chart in \(\mathbf C_R\) is a relation-map with domain a subrelation of \(R\).

The atlas is not identical to \(R\). The carrier \(R\) consists of relation-occurrences. The atlas consists of admissible relation-maps and transitions among them.

### Remark 9.8: Atlas Non-Uniqueness

A primitive carrier \(R\) may admit many atlases. An atlas is part of the declared charted organization structure, not a uniquely forced object.

When tasks are present, tasks may select charts or chart families from an atlas. When no tasks are declared, atlas choice is presentation data.

---

## 10. Transport of Organizations

### Definition 10.1: Organization Transport

Let \(\tau=(f,g,k):\mathcal C\to\mathcal D\) be an isomorphic cut-preserving chart transition. Define

\[
\tau_*(S,T):=(f[S],g^{-1}[T])
\]

for \((S,T)\in\operatorname{Org}_{\theta}(\mathcal C)\).

### Theorem 10.2: Isomorphic Cut-Preserving Transitions Transport Organizations

Let \(\tau=(f,g,k):\mathcal C\to\mathcal D\) be an isomorphic chart transition with \(k\) an order isomorphism. If

\[
(S,T)\in\operatorname{Org}_{\theta}(\mathcal C),
\]

then

\[
\tau_*(S,T)
\in
\operatorname{Org}_{k(\theta)}(\mathcal D).
\]

#### Proof

By Proposition 8.3, \(\tau\) is cut-preserving. Since \(f\) and \(g\) are bijective, universal quantification over \(S\) and \(T\) transports exactly along \(f\) and \(g^{-1}\). Therefore the Galois closure equations

\[
S=T^{\downarrow_{\theta}},
\qquad
T=S^{\uparrow_{\theta}}
\]

are carried to

\[
f[S]=(g^{-1}[T])^{\downarrow_{k(\theta)}},
\qquad
g^{-1}[T]=(f[S])^{\uparrow_{k(\theta)}}.
\]

Thus \(\tau_*(S,T)\) is an organization in \(\mathcal D\) at threshold \(k(\theta)\). □

### Corollary 10.3: Proper Organizations Transport to Proper Organizations

Under the hypotheses of Theorem 10.2, if

\[
(S,T)\in\operatorname{Org}^{\circ}_{\theta}(\mathcal C),
\]

then

\[
\tau_*(S,T)\in\operatorname{Org}^{\circ}_{k(\theta)}(\mathcal D).
\]

#### Proof

Boundary organizations are transported to boundary organizations by bijectivity. Hence non-boundary organizations transport to non-boundary organizations. □

### Proposition 10.4: Organization Transport Respects Composition

If \(\tau_1:\mathcal C\to\mathcal D\) and \(\tau_2:\mathcal D\to\mathcal E\) are isomorphic cut-preserving transitions, then

\[
(\tau_2\circ\tau_1)_*=\tau_{2*}\circ\tau_{1*}.
\]

#### Proof

By Definition 8.7, transition composition is componentwise composition. Therefore the induced image and inverse-image operations on organization components compose in the stated order. □

---

## 11. Tasks as Chart Selection and Local Constraint

### Definition 11.1: Relation-Internal Task

A **relation-internal task** on \(R\) is a tuple

\[
\tau=(P_{\tau},N_{\tau},D_{\tau})
\]

where:

1. \(P_{\tau},N_{\tau}\subseteq R\) are finite and disjoint;
2. \(D_{\tau}\subseteq R\times R\) is a finite relation of required delineations.

Elements of \(P_{\tau}\) are positive task occurrences.

Elements of \(N_{\tau}\) are negative task occurrences.

Pairs in \(D_{\tau}\) are distinctions that the task requires to remain chart-visible.

### Definition 11.2: Chart Contains a Task

A chart \(\mathcal C\) with carrier \(C\) **contains** \(\tau\) when

\[
P_{\tau}\cup N_{\tau}\subseteq C
\]

and

\[
D_{\tau}\subseteq C\times C.
\]

### Definition 11.3: Chart Delineates a Required Distinction

A chart \(\mathcal C\) **delineates** a required pair \((r,s)\in D_{\tau}\) when either \(\mathcal C\) face-delineates \(r,s\) or \(\mathcal C\) threshold-delineates \(r,s\) for some \(\theta\in Z_{\mathcal C}^{\circ}\).

### Definition 11.4: Local Task Constraint Induced by a Task

Let \(\mathcal C\) contain \(\tau\). The **local task constraint** induced by \(\tau\) in \(\mathcal C\) is

\[
\lambda_{\tau}^{\mathcal C}
:=
(P_{\tau},N_{\tau})
\]

viewed as finite disjoint subsets of the chart carrier \(C\).

The positive face data are

\[
A^+_{\lambda}:=\alpha_{\mathcal C}[P_{\tau}],
\qquad
Q^+_{\lambda}:=\chi_{\mathcal C}[P_{\tau}],
\]

and the negative face data are

\[
A^-_{\lambda}:=\alpha_{\mathcal C}[N_{\tau}],
\qquad
Q^-_{\lambda}:=\chi_{\mathcal C}[N_{\tau}].
\]

### Definition 11.5: Task-Satisfying Organization

Let \(\mathcal C\) contain \(\tau\). A proper organization

\[
(S,T)\in\operatorname{Org}^{\circ}_{\theta}(\mathcal C)
\]

**satisfies** \(\tau\) in \(\mathcal C\) when:

\[
A^+_{\lambda}\subseteq S,
\qquad
Q^+_{\lambda}\subseteq T,
\]

\[
A^-_{\lambda}\cap S=\varnothing,
\qquad
Q^-_{\lambda}\cap T=\varnothing,
\]

where \(\lambda=\lambda_{\tau}^{\mathcal C}\).

### Remark 11.6: Independence of the Four Task Conditions

The four task-satisfaction conditions are stated symmetrically because a task may constrain both faces directly. In special cases, some conditions may imply others through the Galois closure equations \(S=T^{\downarrow_\theta}\) and \(T=S^{\uparrow_\theta}\). In general they are not eliminated from the definition, because positive and negative task occurrences are relation-occurrences, and their answer and question projections may impose independent chart-visible requirements.

### Definition 11.7: Task-Admissible Proper Organization Layer

Define

\[
\operatorname{Org}^{\circ}_{\theta,\tau}(\mathcal C)
\]

as the subset of \(\operatorname{Org}^{\circ}_{\theta}(\mathcal C)\) whose elements satisfy \(\tau\) in \(\mathcal C\).

### Definition 11.8: Chart Resolves a Task

A chart \(\mathcal C\in\mathbf C_R\) **resolves** \(\tau\) when:

1. \(\mathcal C\) contains \(\tau\);
2. \(\mathcal C\) delineates every required pair in \(D_{\tau}\);
3. there exists \(\theta\in Z_{\mathcal C}^{\circ}\) such that

\[
\operatorname{Org}^{\circ}_{\theta,\tau}(\mathcal C)\neq\varnothing.
\]

### Definition 11.9: Resolving Chart Class

For an atlas \(\mathfrak A_R=(\mathbf C_R,
\mathbf T_R)\), define

\[
\operatorname{Res}_{\mathfrak A_R}(\tau)
:=
\{\mathcal C\in\mathbf C_R:\mathcal C\text{ resolves }\tau\}.
\]

### Definition 11.10: Chart-Complete Task

A task \(\tau\) is **chart-complete in \(\mathfrak A_R\)** when

\[
\operatorname{Res}_{\mathfrak A_R}(\tau)\neq\varnothing.
\]

### Definition 11.11: Minimal Resolving Charts

Let \(\preceq_{\rm ch}\) be a declared preorder on \(\mathbf C_R\). The **minimal resolving charts** for \(\tau\) are

\[
\operatorname{MinRes}_{\mathfrak A_R}^{\preceq_{\rm ch}}(\tau)
:=
\{\mathcal C\in\operatorname{Res}_{\mathfrak A_R}(\tau):
\text{ no }\mathcal D\in\operatorname{Res}_{\mathfrak A_R}(\tau)
\text{ satisfies }\mathcal D\prec_{\rm ch}\mathcal C\}.
\]

The default preorder is carrier inclusion:

\[
\mathcal D\preceq_{\rm car}\mathcal C
\quad\Longleftrightarrow\quad
D\subseteq C.
\]

### Definition 11.12: Task-Induced Selector

The **task-induced selector** is the multivalued assignment

\[
\tau\longmapsto
\operatorname{MinRes}_{\mathfrak A_R}^{\preceq_{\rm ch}}(\tau).
\]

This is not a new primitive. It is the chart-selecting role of a task relative to an atlas and a chart preorder.

### Definition 11.13: Selector-Complete Task

A task \(\tau\) is **selector-complete** when

\[
\operatorname{MinRes}_{\mathfrak A_R}^{\preceq_{\rm ch}}(\tau)\neq\varnothing.
\]

### Proposition 11.14: Selector-Completeness Is Task-Internal

Selector-completeness is determined by the relation-internal task \(\tau\), the atlas \(\mathfrak A_R\), and the chart preorder \(\preceq_{\rm ch}\). It does not require an external selector object.

#### Proof

By Definitions 11.8--11.13, selector-completeness depends on whether admissible charts in \(\mathbf C_R\) resolve \(\tau\), and on minimality under \(\preceq_{\rm ch}\). The task \(\tau\) is a finite substructure of \(R\). No additional selector primitive appears. □

### Theorem 11.15: Selector-Incompleteness No-Go

Let \(\tau\) be a relation-internal task. If every chart in \(\mathbf C_R\) containing \(\tau\) fails to delineate at least one required pair in \(D_{\tau}\), then \(\tau\) is not selector-complete.

#### Proof

If every chart containing \(\tau\) fails to delineate at least one required pair in \(D_{\tau}\), then no chart resolves \(\tau\) by Definition 11.8. Hence

\[
\operatorname{Res}_{\mathfrak A_R}(\tau)=\varnothing.
\]

Therefore

\[
\operatorname{MinRes}_{\mathfrak A_R}^{\preceq_{\rm ch}}(\tau)=\varnothing,
\]

so \(\tau\) is not selector-complete. □

### Corollary 11.16: Valid Charts Need Not Be Valid for a Task

An admissible chart may fail to resolve a task.

#### Proof

A chart may be admissible while failing to contain \(\tau\), failing to delineate \(D_{\tau}\), or failing the task-satisfaction condition in Definition 11.8. Hence chart admissibility alone does not imply task resolution. □

### Remark 11.17

The role of selector-completeness is to block task smuggling. A task is not allowed to count as resolved merely because some chart exists. The chart must preserve the delineations required by the task and support a task-satisfying proper organization.

---

## 12. Objective Content

### Definition 12.1: Chart Quantity

Let \(Y\) be a set. A **chart quantity** on an atlas \(\mathfrak A_R=(\mathbf C_R,\mathbf T_R)\) is an assignment

\[
\nu_{\mathcal C}\in Y
\]

for every \(\mathcal C\in\mathbf C_R\).

### Definition 12.2: Transition-Invariance

A chart quantity \(\nu\) is **invariant under a transition**

\[
\tau:\mathcal C\to\mathcal D
\]

when

\[
\nu_{\mathcal C}=\nu_{\mathcal D}.
\]

It is **atlas-invariant** when it is invariant under every transition in \(\mathbf T_R\).

### Definition 12.3: Nonvacuous Invariance

An atlas-invariant chart quantity \(\nu\) is **nonvacuously invariant** when there exists at least one nonidentity transition

\[
\tau:\mathcal C\to\mathcal D
\]

in \(\mathbf T_R\) under which \(\nu\) is invariant.

### Definition 12.4: Objective Content

**Objective content relative to an atlas** is nonvacuous invariance under the atlas transition class \(\mathbf T_R\).

### Theorem 12.5: Single-Chart Invariance Is Vacuous

Let \(\mathfrak A_R=(\{\mathcal C\},\{\operatorname{id}_{\mathcal C}\})\) be a single-chart atlas with only the identity transition. Then every chart quantity is atlas-invariant, and no chart quantity is nonvacuously invariant.

#### Proof

Every chart quantity \(\nu\) satisfies

\[
\nu_{\mathcal C}=\nu_{\mathcal C}
\]

under the identity transition. Hence every chart quantity is atlas-invariant.

There is no nonidentity transition in the atlas. Hence no chart quantity satisfies the definition of nonvacuous invariance. □

### Corollary 12.6: Nonvacuous Objectivity Requires Transition

If a chart quantity is objective in the sense of Definition 12.4, then the atlas contains a nonidentity chart transition.

#### Proof

Immediate from Definition 12.3. □

### Remark 12.7

A single encoding does not produce objectivity. It produces untested fixation.

### Remark 12.8: Atlas-Relative Objectivity

Objective content is not absolute in this paper. It is relative to the declared atlas and transition class. Changing \(\mathbf T_R\) can change which chart quantities count as objective.

---

## 13. Constants

### Definition 13.1: Invariant Assignment

Let \(Y\) be a set of values. An **invariant assignment** on an observer atlas \(\mathfrak A_R\) is an atlas-invariant chart quantity

\[
\mathcal C\mapsto \kappa_{\mathcal C}\in Y.
\]

### Definition 13.2: Constant

A **constant** on an observer atlas is the common value of a nonvacuously invariant assignment.

Thus if

\[
\kappa_{\mathcal C}=y
\]

for every \(\mathcal C\in\mathbf C_R\), and the invariance is nonvacuous, then \(y\) is the associated constant.

### Proposition 13.3: Constants Are Not Primitive Objects

In this theory, a constant is a common value of an invariant assignment over chart transitions. It is not an element of the primitive relation carrier \(R\) unless a separate chart explicitly represents it as such.

#### Proof

By Definition 13.2, a constant is obtained from an assignment

\[
\mathcal C\mapsto\kappa_{\mathcal C}
\]

satisfying nonvacuous invariance. This definition does not require an element \(r\in R\) corresponding to the common value. Therefore constants are not primitive objects of \(R\). □

### Remark 13.4

A constant may be represented inside a chart. Representation inside a chart is not the same as primitive objecthood.

---

## 14. Objecthood

### Definition 14.1: Chart-Local Object Candidate

A **chart-local object candidate** in \(\mathcal C\) at threshold \(\theta\) is a proper organization

\[
O_{\mathcal C}\in\operatorname{Org}^{\circ}_{\theta}(\mathcal C).
\]

### Definition 14.2: Persistent Object Family

Let \(\mathfrak A_R=(\mathbf C_R,\mathbf T_R)\) be an observer atlas. A **persistent object family** over \(\mathfrak A_R\) is an assignment

\[
\mathcal C\mapsto O_{\mathcal C}
\]

such that:

1. for each \(\mathcal C\),

\[
O_{\mathcal C}\in\operatorname{Org}^{\circ}_{\theta_{\mathcal C}}(\mathcal C)
\]

for some \(\theta_{\mathcal C}\in Z_{\mathcal C}^{\circ}\);

2. for every isomorphic transition

\[
\tau:\mathcal C\to\mathcal D
\]

in \(\mathbf T_R\),

\[
\tau_*(O_{\mathcal C})=O_{\mathcal D}.
\]

### Definition 14.3: Objecthood

**Objecthood** is persistent organization across admissible chart transitions.

### Theorem 14.4: Objecthood Implies Proper Organization in Every Chart

If \(\mathcal C\mapsto O_{\mathcal C}\) is a persistent object family over \(\mathfrak A_R\), then every \(O_{\mathcal C}\) is a proper organization in its chart.

#### Proof

This is condition 1 of Definition 14.2. □

### Theorem 14.5: Single-Chart Objecthood Is Unchecked

In a single-chart atlas with only the identity transition, every chart-local object candidate determines a persistent object family, but none is tested against a nonidentity transition.

#### Proof

Let \(\mathfrak A_R=(\{\mathcal C\},\{\operatorname{id}_{\mathcal C}\})\). Let

\[
O_{\mathcal C}\in\operatorname{Org}^{\circ}_{\theta}(\mathcal C).
\]

The assignment \(\mathcal C\mapsto O_{\mathcal C}\) satisfies the transport condition for the identity transition. Since there is no nonidentity transition, no further invariance is tested. □

### Remark 14.6

Single-chart fixation can imitate objecthood. It cannot establish nonvacuous objecthood.

---

## 15. Presentation Equivalence

### Definition 15.1: Organization Poset

For a chart \(\mathcal C\) and threshold \(\theta\), define a partial order on \(\operatorname{Org}^{\circ}_{\theta}(\mathcal C)\) by

\[
(S,T)\leq_{\mathcal C}(S',T')
\quad\Longleftrightarrow\quad
S\subseteq S'.
\]

### Definition 15.2: Organization Equivalence at a Cut

Two charts \(\mathcal C\) and \(\mathcal D\) are **organization-equivalent at cuts \(\theta\) and \(\eta\)** when there exists a poset isomorphism

\[
\Phi:
\operatorname{Org}^{\circ}_{\theta}(\mathcal C)
\to
\operatorname{Org}^{\circ}_{\eta}(\mathcal D).
\]

### Definition 15.3: Transition-Induced Organization Equivalence

An organization equivalence is **transition-induced** when

\[
\Phi=\tau_*
\]

for some isomorphic chart transition

\[
\tau:\mathcal C\to\mathcal D
\]

in the atlas transition class.

### Proposition 15.4: Transition-Induced Organization Equivalence Is an Equivalence Relation

On the class of charts connected by isomorphic transitions in \(\mathbf T_R\), transition-induced organization equivalence is reflexive, symmetric, and transitive.

#### Proof

Reflexivity is induced by the identity transition.

Symmetry follows because an isomorphic transition has an inverse transition, and the induced organization transport maps are inverse poset isomorphisms.

Transitivity follows from Corollary 8.9 and Proposition 10.4: the composite of two isomorphic transitions is an isomorphic transition, and organization transport respects composition. □

### Remark 15.5

This is the internal source of the Morita-like idea. Charts are compared by equivalence of the organization structures they present, not by literal equality of their carriers or labels.

No external Morita theorem is assumed.

---

## 16. Charted Realization

### Definition 16.1: Charted Realization

A **charted realization** of a relation carrier \(R\) is an observer atlas

\[
\mathfrak A_R=(\mathbf C_R,\mathbf T_R)
\]

together with the chart-induced organization structures

\[
\{\operatorname{Org}^{\circ}_{\theta}(\mathcal C):
\mathcal C\in\mathbf C_R,
\ \theta\in Z_{\mathcal C}^{\circ}\}.
\]

### Definition 16.2: Adequate Charted Realization

A charted realization is **adequate** when:

1. every chart in \(\mathbf C_R\) is admissible;
2. \(\mathfrak A_R\) is nontrivial;
3. there exists at least one nonvacuously invariant chart quantity;
4. every declared relation-internal task is selector-complete, if a task family is declared.

### Proposition 16.3: Adequate Charted Realization Implies Nonvacuous Objective Content

An adequate charted realization has nonvacuous objective content.

#### Proof

By Definition 16.2, an adequate charted realization contains at least one nonvacuously invariant chart quantity. By Definition 12.4, such a quantity is objective content. □

### Remark 16.4

A charted realization is not a single global map into an object. It is an atlas of admissible relation-maps and transitions among them.

---

## 17. Persistence in Charts

### Definition 17.1: Chart-Relative Persistence

For each chart \(\mathcal C\), the threshold-indexed family

\[
\{\operatorname{Org}^{\circ}_{\theta}(\mathcal C):\theta\in Z_{\mathcal C}^{\circ}\}
\]

is the **chart-relative persistence family** of \(\mathcal C\).

### Proposition 17.2: Chartwise Inheritance of Persistence Machinery

Fix a chart \(\mathcal C\). The tuple

\[
(A_{\mathcal C},Q_{\mathcal C},Z_{\mathcal C},\preceq_{\mathcal C},\rho_{\mathcal C})
\]

has the same formal type as an organization structure in the Theory of Organization. Therefore every theorem of the parent theory that uses only this tuple and the proper-layer convention applies chartwise to \(\mathcal C\).

#### Proof

By Definitions 3.7 and 4.1--4.7, a functional chart supplies answer, question, zero-boundary, order, resolution, threshold cut, derivation operators, organization fixed points, and the proper layer. These are precisely the data used by the parent theory's persistence, barcode, and stability theorems. Substituting \((A_{\mathcal C},Q_{\mathcal C},Z_{\mathcal C},\rho_{\mathcal C})\) for \((A_R,Q_R,Z_R,\rho_R)\) gives the chartwise statements. □

### Corollary 17.3: Chartwise Persistence-Support Formula

If \(A_{\mathcal C}\times Q_{\mathcal C}\) is finite and \(Z_{\mathcal C}\) is a chain, then the parent theory's persistence-support interval formula applies to every candidate proper organization in \(\mathcal C\).

### Corollary 17.4: Chartwise Barcode and Stability

If \(Z_{\mathcal C}\) is a finite chain, the chart-relative barcode of \(\mathcal C\) is defined by the parent barcode construction. If \(Z_{\mathcal C}\) is an order-convex metric chain, the endpoint and persistence-length stability bounds apply chartwise.

### Remark 17.5

This section does not add new persistence machinery. It records that chart-relative organization is a local instance of the parent organization theory. Questions about transport of persistence diagrams across chart transitions require additional compatibility assumptions on the transition maps.

---

## 18. Self-Limitation and Invariance No-Gos

### Proposition 18.1: Chart-Invisibility No-Go

Let \(r,s\in R\). If every chart \(\mathcal C\in\mathbf C_R\) containing \(r,s\) satisfies

\[
r\sim_{A,Q}^{\mathcal C}s
\]

and no threshold delineates \(r,s\), then no chart-relative information structure in \(\mathfrak A_R\) distinguishes \(r\) and \(s\).

#### Proof

By Definition 7.4, chart information consists of face-delineation, threshold-delineation, and proper organization layers. If no chart face-delineates or threshold-delineates \(r,s\), then no chart-relative delineation distinguishes them. □

### Definition 18.2: Atlas Isomorphism

Let

\[
\mathfrak A_R=(\mathbf C_R,\mathbf T_R)
\]

and

\[
\mathfrak A_{R'}=(\mathbf C_{R'},\mathbf T_{R'})
\]

be observer atlases. An **atlas isomorphism** consists of:

1. a bijection

\[
F:\mathbf C_R\to\mathbf C_{R'},
\]

2. for each \(\mathcal C\in\mathbf C_R\), an isomorphic chart transition

\[
\psi_{\mathcal C}:\mathcal C\to F(\mathcal C),
\]

3. a bijection

\[
\widehat F:\mathbf T_R\to\mathbf T_{R'}
\]

such that, for every transition \(\tau:\mathcal C\to\mathcal D\) in \(\mathbf T_R\),

\[
\widehat F(\tau):F(\mathcal C)\to F(\mathcal D)
\]

and

\[
\widehat F(\tau)=\psi_{\mathcal D}\circ \tau\circ \psi_{\mathcal C}^{-1}
\]

whenever the displayed composite is defined.

### Theorem 18.3: Atlas-Isomorphism Self-Limitation

Any chart quantity, objective-content claim, constant claim, or objecthood claim definable only from the atlas structure is invariant under atlas isomorphism.

Consequently, this framework cannot distinguish atlas-isomorphic charted organization structures using only atlas-internal definitions.

#### Proof

An atlas isomorphism preserves the chart class, transition class, isomorphic chart presentations, organization transport, and transition-induced organization equivalence by Definition 18.2. Any construction using only those data is carried to the corresponding construction in the isomorphic atlas. Therefore atlas-internal claims are invariant under atlas isomorphism. □

### Theorem 18.4: Chart-Internality No-Go

A quantity definable from a single chart \(\mathcal C\) alone cannot detect whether \(\mathcal C\) belongs to a nontrivial atlas.

#### Proof

Let \(\nu_{\mathcal C}\) be definable only from the internal data of \(\mathcal C\). Place the same chart in the single-chart atlas

\[
(\{\mathcal C\},\{\operatorname{id}_{\mathcal C}\})
\]

and in any nontrivial atlas containing \(\mathcal C\). The internal data of \(\mathcal C\) are identical in both cases. Hence \(\nu_{\mathcal C}\) has the same value in both cases. Therefore a single-chart quantity cannot detect nontrivial atlas membership. □

---


## 19. Integrated Worked Atlas Example

This section gives a single end-to-end example. It uses one primitive carrier, three charts, a nontrivial atlas, a relation-internal task, chart selection, transported organizations, a chart-invariant quantity, and a failed chart for the same task.

### 19.1 Primitive Carrier

Let

\[
R=\{r_{11},r_{12},r_{21},r_{22},r_{00},r_{\ast}\}.
\]

The symbols are relation-occurrences only. They are not yet answers, questions, objects, or observations.

Define the following subrelations of \(R\):

\[
C=\{r_{11},r_{12},r_{21},r_{22}\},
\]

\[
D=\{r_{11},r_{12},r_{21},r_{22}\},
\]

and

\[
E=\{r_{11},r_{12},r_{21},r_{22},r_{00}\}.
\]

Each is a proper subrelation of \(R\).

All charts below use

\[
Z=[0,1]
\]

with the usual order.

### 19.2 First Chart

Define chart \(\mathcal C\) on carrier \(C\) by

\[
A_{\mathcal C}=\{a_1,a_2\},
\qquad
Q_{\mathcal C}=\{q_1,q_2\},
\qquad
Z_{\mathcal C}=[0,1].
\]

The face maps are

\[
\alpha_{\mathcal C}(r_{ij})=a_i,
\qquad
\chi_{\mathcal C}(r_{ij})=q_j
\]

for \(i,j\in\{1,2\}\). The zero-boundary readout is

\[
\zeta_{\mathcal C}(r_{11})=0.9,
\qquad
\zeta_{\mathcal C}(r_{22})=0.8,
\]

and

\[
\zeta_{\mathcal C}(r_{12})=\zeta_{\mathcal C}(r_{21})=0.2.
\]

Thus

\[
\rho_{\mathcal C}(a_1,q_1)=0.9,
\qquad
\rho_{\mathcal C}(a_2,q_2)=0.8,
\]

and

\[
\rho_{\mathcal C}(a_1,q_2)=\rho_{\mathcal C}(a_2,q_1)=0.2.
\]

At threshold

\[
\theta=0.5,
\]

one has

\[
a_i\Vdash^{0.5}_{\mathcal C}q_j
\quad\Longleftrightarrow\quad
 i=j.
\]

Therefore the two proper organizations are

\[
O^{1}_{\mathcal C}=(\{a_1\},\{q_1\})
\]

and

\[
O^{2}_{\mathcal C}=(\{a_2\},\{q_2\}).
\]

The first organization has persistence interval

\[
(0.2,0.9]
\]

and persistence length

\[
0.7.
\]

The second has persistence interval

\[
(0.2,0.8]
\]

and persistence length

\[
0.6.
\]

### 19.3 Second Chart: Same Carrier, Different Readout Labels

Define chart \(\mathcal D\) on carrier \(D\) by

\[
A_{\mathcal D}=\{b_1,b_2\},
\qquad
Q_{\mathcal D}=\{p_1,p_2\},
\qquad
Z_{\mathcal D}=[0,1].
\]

The face maps are

\[
\alpha_{\mathcal D}(r_{ij})=b_i,
\qquad
\chi_{\mathcal D}(r_{ij})=p_j,
\]

and the zero-boundary values are the same as in \(\mathcal C\):

\[
\zeta_{\mathcal D}(r_{11})=0.9,
\qquad
\zeta_{\mathcal D}(r_{22})=0.8,
\]

with off-diagonal values equal to \(0.2\).

Thus \(\mathcal D\) is a relabelled chart presentation of the same local resolution pattern. At threshold \(0.5\), the proper organizations are

\[
O^{1}_{\mathcal D}=(\{b_1\},\{p_1\})
\]

and

\[
O^{2}_{\mathcal D}=(\{b_2\},\{p_2\}).
\]

### 19.4 Third Chart: Organization-Equivalent but Task-Incomplete

Define chart \(\mathcal E\) on carrier \(E\) by

\[
A_{\mathcal E}=\{u_1,u_2\},
\qquad
Q_{\mathcal E}=\{v_1,v_2\},
\qquad
Z_{\mathcal E}=[0,1].
\]

The face and zero-boundary maps are:

\[
r_{11}\mapsto(u_1,v_1,0.9),
\]

\[
r_{22}\mapsto(u_1,v_1,0.9),
\]

\[
r_{12}\mapsto(u_1,v_2,0.2),
\]

\[
r_{21}\mapsto(u_2,v_1,0.2),
\]

and

\[
r_{00}\mapsto(u_2,v_2,0.8).
\]

Then

\[
\rho_{\mathcal E}(u_1,v_1)=0.9,
\qquad
\rho_{\mathcal E}(u_2,v_2)=0.8,
\]

and

\[
\rho_{\mathcal E}(u_1,v_2)=\rho_{\mathcal E}(u_2,v_1)=0.2.
\]

At threshold \(0.5\), the proper organizations are

\[
O^{1}_{\mathcal E}=(\{u_1\},\{v_1\})
\]

and

\[
O^{2}_{\mathcal E}=(\{u_2\},\{v_2\}).
\]

Thus \(\mathcal E\) is organization-equivalent to \(\mathcal C\) and \(\mathcal D\) at the level of chart faces and thresholded organizations. But \(\mathcal E\) does not delineate \(r_{11}\) from \(r_{22}\), because both occurrences have the same answer face, question face, and zero-boundary value in \(\mathcal E\).

This is the point of the example: organization-equivalence is not the same as task-completeness for every relation-internal task.

### 19.5 Atlas and Transitions

Let

\[
\mathbf C_R=\{\mathcal C,\mathcal D,\mathcal E\}.
\]

Let \(\mathbf T_R\) contain the identity transitions and the isomorphic chart transitions generated by the following maps.

From \(\mathcal C\) to \(\mathcal D\), define

\[
f_{CD}(a_i)=b_i,
\qquad
 g_{CD}(p_i)=q_i,
\qquad
 k_{CD}=\operatorname{id}_{[0,1]}.
\]

From \(\mathcal C\) to \(\mathcal E\), define

\[
f_{CE}(a_i)=u_i,
\qquad
 g_{CE}(v_i)=q_i,
\qquad
 k_{CE}=\operatorname{id}_{[0,1]}.
\]

These satisfy the chart transition equation. For example,

\[
\rho_{\mathcal E}(f_{CE}(a_i),v_j)
=
\rho_{\mathcal C}(a_i,g_{CE}(v_j))
\]

for all \(i,j\). Hence \((f_{CD},g_{CD},k_{CD})\) and \((f_{CE},g_{CE},k_{CE})\) are isomorphic chart transitions.

Let

\[
\mathfrak A_R=(\mathbf C_R,\mathbf T_R).
\]

This is a nontrivial observer atlas.

### 19.6 Transported Organizations and Invariant Quantity

The transition \(\mathcal C\to\mathcal D\) transports

\[
O^{1}_{\mathcal C}=(\{a_1\},\{q_1\})
\]

to

\[
O^{1}_{\mathcal D}=(\{b_1\},\{p_1\}),
\]

and transports

\[
O^{2}_{\mathcal C}
\]

to

\[
O^{2}_{\mathcal D}.
\]

The transition \(\mathcal C\to\mathcal E\) transports

\[
O^{1}_{\mathcal C}
\]

to

\[
O^{1}_{\mathcal E}=(\{u_1\},\{v_1\}),
\]

and similarly for the second organization.

Define a chart quantity \(\nu\) by assigning to each chart the persistence length of its first diagonal organization:

\[
\nu_{\mathcal C}=0.7,
\qquad
\nu_{\mathcal D}=0.7,
\qquad
\nu_{\mathcal E}=0.7.
\]

Since the atlas contains nonidentity transitions and \(\nu\) is preserved by those transitions, the common value

\[
0.7
\]

is a nonvacuous atlas-invariant value in this example. It is therefore a constant in the sense of Definition 13.2.

This constant is not an object. It is the common value of a chart-transition-invariant assignment.

### 19.7 Relation-Internal Task and Selector-Completeness

Define the task

\[
\tau=(P_{\tau},N_{\tau},D_{\tau})
\]

by

\[
P_{\tau}=\{r_{11}\},
\qquad
N_{\tau}=\{r_{22}\},
\]

and

\[
D_{\tau}=\{(r_{11},r_{22})\}.
\]

The task requires the chart to keep \(r_{11}\) and \(r_{22}\) delineated and to admit a proper organization that includes the positive occurrence while excluding the negative occurrence.

In \(\mathcal C\), the organization

\[
O^{1}_{\mathcal C}=(\{a_1\},\{q_1\})
\]

satisfies \(\tau\): the positive occurrence \(r_{11}\) contributes the faces \((a_1,q_1)\), and the negative occurrence \(r_{22}\) contributes \((a_2,q_2)\), which is excluded.

Similarly, \(O^{1}_{\mathcal D}\) satisfies \(\tau\) in \(\mathcal D\).

In \(\mathcal E\), however,

\[
\alpha_{\mathcal E}(r_{11})=\alpha_{\mathcal E}(r_{22})=u_1
\]

and

\[
\chi_{\mathcal E}(r_{11})=\chi_{\mathcal E}(r_{22})=v_1.
\]

Therefore the positive and negative task data coincide in \(\mathcal E\):

\[
A^+_{\lambda}=A^-_{\lambda}=\{u_1\},
\qquad
Q^+_{\lambda}=Q^-_{\lambda}=\{v_1\}.
\]

No proper organization can both include and exclude the same answer and question faces. Hence \(\mathcal E\) does not resolve \(\tau\).

Thus

\[
\mathcal C,\mathcal D\in\operatorname{Res}(\tau),
\qquad
\mathcal E\notin\operatorname{Res}(\tau).
\]

The task-induced chart selector is therefore not primitive. It is the relation-internal selection

\[
\tau\mapsto\operatorname{MinRes}(\tau),
\]

and in this example

\[
\operatorname{MinRes}(\tau)=\{\mathcal C,\mathcal D\}
\]

under the default carrier-inclusion preorder.

### 19.8 What the Example Shows

The example demonstrates the following claims in one carrier:

1. A chart is a relation-map on a proper subrelation of \(R\).
2. Multiple admissible charts may present equivalent organization structures.
3. A nonidentity atlas transition can transport proper organizations.
4. A chart-invariant persistence length can define a constant without making the constant an object.
5. Organization-equivalence does not imply task-completeness.
6. A relation-internal task induces chart selection without introducing a selector primitive.
7. A chart may be admissible and organization-equivalent to another chart while still failing a specific task.

---
## 20. Diagnostic Examples

### Example 20.1: Boundary-Collapsed Chart

Let

\[
A_{\mathcal C}=\{a_1,a_2\},
\qquad
Q_{\mathcal C}=\{q_1,q_2\},
\]

and let

\[
Z_{\mathcal C}=\{0<z<1\}.
\]

If

\[
\rho_{\mathcal C}(a_i,q_j)=0
\]

for all \(i,j\), then \(\mathcal C\) is single-boundary collapsed. By Theorem 6.1,

\[
\operatorname{Org}^{\circ}_{z}(\mathcal C)=\varnothing.
\]

### Example 20.2: Nontrivial Chart

Let

\[
A_{\mathcal C}=\{a_1,a_2\},
\qquad
Q_{\mathcal C}=\{q_1,q_2\},
\]

and

\[
Z_{\mathcal C}=\{0<z<1\}.
\]

Define

\[
\rho_{\mathcal C}(a_1,q_1)=z,
\qquad
\rho_{\mathcal C}(a_2,q_2)=z,
\]

and

\[
\rho_{\mathcal C}(a_1,q_2)=0,
\qquad
\rho_{\mathcal C}(a_2,q_1)=0.
\]

At threshold \(z\), the proper organizations include

\[
(\{a_1\},\{q_1\})
\]

and

\[
(\{a_2\},\{q_2\}).
\]

Thus \(\mathcal C\) is organization-bearing.

### Example 20.3: Nested Chart That Fails Admissibility

Let \(\mathcal C\) be the chart in Example 20.2. Let \(\mathcal D\) be the nested chart containing only the relation-occurrences supporting \((a_1,q_1)\).

Then \(\mathcal D\) has one answer face and one question face. By Theorem 6.3,

\[
\operatorname{Org}^{\circ}_{\theta}(\mathcal D)=\varnothing.
\]

Thus nested charts need not inherit admissibility.

### Example 20.4: Continuous-Z Two-Chart Atlas

Let two charts \(\mathcal C\) and \(\mathcal D\) have

\[
A_{\mathcal C}=\{a_1,a_2\},
\quad
Q_{\mathcal C}=\{q_1,q_2\},
\quad
Z_{\mathcal C}=[0,1],
\]

and

\[
A_{\mathcal D}=\{b_1,b_2\},
\quad
Q_{\mathcal D}=\{p_1,p_2\},
\quad
Z_{\mathcal D}=[0,1].
\]

Define

\[
\rho_{\mathcal C}(a_1,q_1)=0.9,
\quad
\rho_{\mathcal C}(a_2,q_2)=0.8,
\]

and all off-diagonal values equal to \(0.2\).

Define \(\rho_{\mathcal D}\) by

\[
\rho_{\mathcal D}(b_1,p_1)=0.9,
\quad
\rho_{\mathcal D}(b_2,p_2)=0.8,
\]

and all off-diagonal values equal to \(0.2\).

Let

\[
f(a_i)=b_i,
\qquad
g(p_i)=q_i,
\qquad
k=\operatorname{id}_{[0,1]}.
\]

Then \((f,g,k):\mathcal C\to\mathcal D\) is an isomorphic chart transition. It transports the proper organization

\[
(\{a_1\},\{q_1\})
\]

to

\[
(\{b_1\},\{p_1\})
\]

and similarly for the second diagonal organization.

The chart quantity assigning the diagonal persistence length of the first organization has common value \(0.7\) across these two charts.

### Example 20.5: Task with No Resolving Chart

Let \(\tau\) require a delineation between relation-occurrences \(r,s\in R\). If every admissible chart containing \(r,s\) identifies them under both face and threshold delineation, then \(\tau\) has no resolving chart by Theorem 11.14.

### Example 20.6: Single-Chart Fixation

Let \(\mathfrak A_R=(\{\mathcal C\},\{\operatorname{id}_{\mathcal C}\})\). Any proper organization in \(\mathcal C\) is chart-local. It is not nonvacuously objective and does not establish nonvacuous objecthood.

---

## 21. Claims and Limitations

### 21.1 Claims

This paper claims:

1. charted organization is the observer-relative layer of the Theory of Organization;
2. a chart is a relation-map internal to a primitive carrier, not an external coordinate object;
3. observer-charts are admissible positioned charts;
4. information is chart-relative delineation;
5. objective content is nonvacuous atlas-relative invariance;
6. constants are common values of nonvacuously invariant assignments;
7. objecthood is persistent proper organization across chart transitions;
8. tasks induce chart selection without introducing a selector primitive;
9. presentation equivalence is derived internally from organization-preserving chart transitions;
10. chartwise persistence follows from the parent organization theory;
11. atlas-internal claims cannot distinguish atlas-isomorphic structures.

### 21.2 Non-Claims

This paper does not claim:

1. that observer-charts are conscious observers;
2. that physical measurement has been derived;
3. that spacetime, fields, or constants of physics have been derived;
4. that the atlas is uniquely determined by \(R\);
5. that Morita equivalence is imported as a theorem;
6. that topos, sheaf, fibration, or contextuality machinery is assumed;
7. that chart-local fixation is objective content.

### 21.3 Self-Limitation

Any claim made using only charted organization data is limited to what the declared charts and transitions preserve.

If a distinction is invisible to all admissible charts in an atlas, this framework cannot recover it from that atlas.

If two atlases are isomorphic as chart-transition structures, this framework cannot distinguish them by atlas-internal definitions.

---

## 22. Compact Summary

\[
R
=
\text{primitive relation carrier.}
\]

\[
\mathcal C
=
\text{relation-map on a proper subrelation of }R.
\]

\[
O
=
\text{admissible positioned chart.}
\]

\[
\operatorname{Org}^{\circ}_{\theta}(\mathcal C)
=
\text{proper organization visible in chart }\mathcal C.
\]

\[
\mathfrak A_R=(\mathbf C_R,\mathbf T_R)
=
\text{observer atlas.}
\]

\[
\text{information}
=
\text{task-visible chart delineation.}
\]

\[
\text{objective content}
=
\text{nonvacuous invariance across chart transitions.}
\]

\[
\text{constant}
=
\text{common value of a nonvacuously invariant assignment.}
\]

\[
\text{objecthood}
=
\text{persistent proper organization across an atlas.}
\]

\[
\text{selector}
=
\text{task-induced chart selection, not a primitive.}
\]

\[
\boxed{
\text{A chart is the relation becoming locally legible.}
}
\]

---

## AI-assistance disclosure

This manuscript was developed with AI-assisted drafting and review support. The author directed the research programme, selected and revised the mathematical and methodological content, and is responsible for all claims and errors.
