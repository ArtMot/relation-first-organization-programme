# Charted Objecthood: Global Sections and Gluing Obstruction in Relation-First Systems

**Subtitle:** Contextual Gluing, Holonomy, and Deterministic Contextuality as a Specialization  
**Author:** Artur Motruk  
**Affiliation:** Independent researcher  
**ORCID:** 0009-0003-6928-1701  
**Programme:** Relation-First Organization Programme  
**Document role:** Foundation/objecthood and gluing layer; contextuality specialization  
**Public release status:** Repository manuscript  

---

# Abstract

The companion theories define organization, charted visibility, recursive chart learning, triadic closure residuals, and cross-closure bridge declarations. This paper asks when a family of chart-relative proper organizations counts as one object.

The answer is compatibility across an observer atlas. A charted object is not a primitive substance and not a single-chart item. It is a compatible family of proper organizations transported or restricted across admissible chart transitions. Local object-candidates may exist in every chart while global objecthood fails. The failure is a contextual obstruction.

The main theorem is the objecthood/global-section equivalence. Given a transported observer atlas, the assignment of proper organization sets to charts forms an organization presheaf or covariant organization functor, depending on the chosen transition orientation. Charted objects are exactly global compatible sections of this organization assignment. A holonomy obstruction theorem follows: if transport around a chart cycle has no fixed point, then no compatible object family exists with that base value.

The paper then gives a specialization theorem. The deterministic or strong global-section core of standard sheaf-theoretic contextuality is recovered as a special case when charts are measurement contexts, local organizations are outcome assignments or empirically admissible local sections, and chart transitions are restriction maps on overlaps. Under those assumptions, deterministic global-section contextuality is charted objecthood obstruction.

The paper also clarifies the direction of generalization. Standard sheaf contextuality is usually formulated over a poset of measurement contexts ordered by inclusion. Charted objecthood works over a declared chart context category, which may include non-posetal transitions, nonidentity endomorphisms, cycles, holonomy, residual readouts, threshold policies, and persistence constraints. The framework therefore gives a categorical generalization of the deterministic gluing obstruction. Probabilistic empirical models, contextual fractions, Bell inequalities, Hilbert-space-specific Kochen--Specker results, and cohomological contextuality require additional bridge data and are not claimed here.

Two examples are added to make the scope concrete. A non-posetal endotransition example shows a charted obstruction that cannot be expressed in a restriction-only poset bridge without extra automorphism or coefficient data. A database-join example shows that the same objecthood obstruction pattern applies to non-quantum compatibility problems.

Finally, the paper gives a separating construction relative to a **restriction-only** standard measurement-context translation. Charted objecthood obstruction can arise from nontrivial transition holonomy, residual comparison, threshold incompatibility, or persistence-support failure. Such obstructions are not standard restriction-only empirical-model contextuality obstructions unless additional bridge data translate the relevant charted structure into measurements, outcomes, overlaps, empirical supports, or cohomological coefficient data.

---

# 0. Scope and import boundaries

## 0.1 Relation to the companion theories

This paper uses the following companion-theory objects.

From **Theory of Organization**, it uses proper organization layers

\[
\operatorname{Org}^{\circ}_{\theta}(R).
\]

From **Charted Organization Theory**, it uses observer-charts and observer atlases

\[
\mathfrak A_R=(\mathbf C_R,\mathbf T_R),
\]

where \(\mathbf C_R\) is a class of admissible charts and \(\mathbf T_R\) is a declared class of admissible chart transitions.

From **Recursive Chart Learning Theory**, it uses the distinction between endpoints and path traces.

From **Triadic Closure and Recursive Residual Theory**, it uses closure residuals and holonomy-like failure around chart triangles or cycles.

From **Cross-Closure Instantiation Theorems**, it uses bridge declaration discipline: cross-context inference requires declared bridge data.

## 0.2 No physical or quantum claim

This paper does not claim that physical objects, quantum observables, spacetime events, fields, particles, organisms, or conscious observers are derived. It defines the formal condition under which chart-relative organizations form an object-family inside an observer atlas.

It also does not claim to solve quantum contextuality. It reconstructs the global-section obstruction pattern inside charted organization, then identifies the deterministic global-section core of standard sheaf contextuality as a special case under additional measurement-context bridge data.

## 0.3 Adjacent frameworks and import boundaries

The structure is adjacent to sheaf-theoretic contextuality, topos-style context-indexed descriptions, global-section obstruction, and flat/non-flat transport in geometry. No external sheaf, topos, bundle, gauge, or quantum theorem is assumed. The internal claim is that chart-relative organizations require compatibility across admissible chart transitions to count as one object.

The closest external reference point is the sheaf-theoretic approach to non-locality and contextuality, where contextuality is characterized by obstruction to global sections of an event sheaf over a measurement cover. Cohomological extensions of that programme use Čech-style obstructions to study contextuality. This paper does not replace those frameworks. It reconstructs their deterministic global-section core as one bridge-realization of charted objecthood, and it identifies where additional bridge data would be required to compare with cohomological, probabilistic, or Hilbert-space-specific versions.

## 0.4 Bridge discipline

Comparison with standard contextuality requires bridge declarations. In this paper, a bridge declaration specifies how charted organization data are to be read as measurement contexts, outcome assignments, empirical supports, restriction maps, residual values, threshold policies, transport maps, or cohomological coefficient data.

Without such bridge data, formal resemblance is not enough. A charted obstruction is not automatically a standard contextuality obstruction.

## 0.5 Deterministic scope

The contextuality specialization in this paper is deterministic or support-level. It concerns the existence or non-existence of compatible global assignments. It does not include probability distributions over local sections, contextual fractions, Bell-inequality violation, no-signaling polytopes, or Hilbert-space-specific Kochen--Specker constructions. Those can be treated only after additional probabilistic, empirical-model, or quantum bridge data are declared.

## 0.6 Generalization direction

This paper should be read as a categorical generalization of deterministic gluing obstruction, not as a replacement for standard contextuality theory. Poset-based sheaf contextuality is recovered when chart contexts are measurement contexts, chart transitions are restriction maps, and local organizations are outcome assignments or admissible local sections. Charted objecthood permits additional chart-category structure, including non-posetal transitions and nonidentity endomorphisms. Those additional structures are not automatically standard contextuality data; they require bridge declarations if they are to be compared with cohomological, probabilistic, or quantum contextuality frameworks.

---

# 1. Transported charted organization

## Definition 1.1 — Charted organization domain

Let

\[
\mathfrak A_R=(\mathbf C_R,\mathbf T_R)
\]

be an observer atlas over a primitive relation carrier \(R\). For each chart

\[
\mathcal C\in\mathbf C_R,
\]

let

\[
\operatorname{Org}^{\circ}_{\theta_{\mathcal C}}(\mathcal C)
\]

be the proper organization layer of \(\mathcal C\) at a declared proper threshold

\[
\theta_{\mathcal C}\in Z_{\mathcal C}^{\circ}.
\]

A **charted organization domain** on \(\mathfrak A_R\) is an assignment

\[
\mathcal C\mapsto \mathcal O_{\mathcal C}
\]

where

\[
\mathcal O_{\mathcal C}\subseteq
\operatorname{Org}^{\circ}_{\theta_{\mathcal C}}(\mathcal C).
\]

The set \(\mathcal O_{\mathcal C}\) is the set of local object-candidates visible in chart \(\mathcal C\).

## Definition 1.2 — Organization transport

For a transition

\[
t:\mathcal C\to\mathcal D
\]

in \(\mathbf T_R\), an **organization transport map** is a declared map

\[
t_{\ast}:\mathcal O_{\mathcal C}\to\mathcal O_{\mathcal D}.
\]

The transport map is bridge data. It is not automatic from the notation \(t:\mathcal C\to\mathcal D\). A transition that does not declare how proper organizations are transported cannot support an objecthood comparison.

## Definition 1.3 — Transported atlas

A **transported atlas** is a triple

\[
(\mathfrak A_R,\mathcal O,T_{\ast})
\]

where:

1. \(\mathfrak A_R=(\mathbf C_R,\mathbf T_R)\) is an observer atlas;
2. \(\mathcal O\) assigns local object-candidate sets \(\mathcal O_{\mathcal C}\) to charts;
3. for each declared transition \(t:\mathcal C\to\mathcal D\), a transport map \(t_{\ast}:\mathcal O_{\mathcal C}\to\mathcal O_{\mathcal D}\) is declared.

## Definition 1.4 — Transport composition

A transported atlas is **composition-compatible** when for every composable pair

\[
\mathcal C\xrightarrow{t}\mathcal D\xrightarrow{s}\mathcal E
\]

whose composite \(s\circ t\) is declared in \(\mathbf T_R\),

\[
(s\circ t)_{\ast}=s_{\ast}\circ t_{\ast}.
\]

When the identity transition \(1_{\mathcal C}\) is declared, composition-compatibility also requires

\[
(1_{\mathcal C})_{\ast}=1_{\mathcal O_{\mathcal C}}.
\]

## Remark 1.5 — Why transport is bridge data

Transport is the bridge from chart-local organization to cross-chart objecthood. Without transport, every chart may contain local proper organizations, but there is no formal basis for saying that an organization in \(\mathcal C\) and an organization in \(\mathcal D\) are presentations of the same object.

---

# 2. Objecthood as compatible charted organization

## Definition 2.1 — Object assignment

An **object assignment** over a transported atlas is a choice

\[
O_{\mathcal C}\in\mathcal O_{\mathcal C}
\]

for each chart \(\mathcal C\in\mathbf C_R\).

## Definition 2.2 — Compatible object family

An object assignment \(O=(O_{\mathcal C})_{\mathcal C\in\mathbf C_R}\) is a **compatible object family** when for every declared transition

\[
t:\mathcal C\to\mathcal D,
\]

we have

\[
t_{\ast}(O_{\mathcal C})=O_{\mathcal D}.
\]

## Definition 2.3 — Charted objecthood

A **charted object** over \(\mathfrak A_R\) is a compatible object family of proper organizations.

Thus objecthood is not identified with a local organization

\[
O_{\mathcal C}\in\mathcal O_{\mathcal C}
\]

in one chart. It is identified with the existence of a transition-compatible family

\[
(O_{\mathcal C})_{\mathcal C\in\mathbf C_R}.
\]

## Proposition 2.4 — Local object-candidate is not objecthood

If \(\mathbf C_R\) contains at least two charts and no transport map from \(\mathcal C\) to another chart is declared, then an element

\[
O_{\mathcal C}\in\mathcal O_{\mathcal C}
\]

is only a local object-candidate, not a charted object.

### Proof

A charted object requires a compatible assignment over the declared atlas. A single local element supplies no values in the remaining charts and satisfies no transition-compatibility condition. Therefore it is not a charted object. \(\square\)

## Corollary 2.5 — Single-chart fixation

If \(\mathbf C_R=\{\mathcal C\}\), then every local object-candidate is vacuously compatible. Such compatibility is single-chart fixation, not nonvacuous objecthood.

### Proof

With one chart and only identity transition, compatibility imposes no nonidentity transport condition. Hence every local candidate is compatible vacuously. Nonvacuous objecthood requires compatibility across at least one nonidentity chart transition. \(\square\)

## Remark 2.6 — Objectivity and objecthood

Charted Organization Theory defines objectivity as nonvacuous invariance of chart quantities across admissible transitions. This paper defines objecthood as compatibility of local proper organizations across admissible transitions. The two notions use the same transition discipline but answer different questions.

Objectivity concerns **content**: which values, claims, or quantities survive chart change. Objecthood concerns **individuals**: which local organization-candidates form one compatible family across the atlas. A charted object can carry objective chart quantities, but objectivity and objecthood should not be identified.

## Remark 2.7 — Structural objecthood

The objecthood formalized here is structural or relational objecthood. It does not claim that all philosophical concepts of objecthood reduce to compatible families. In particular, it does not address substance ontology, trope theory, or dispositional accounts of objecthood except insofar as those accounts can be represented by charted organization data and transition compatibility.

---

# 3. Organization presheaf and global objecthood

This section gives the clean bridge to sheaf-style language. No external sheaf theorem is assumed.

## Definition 3.1 — Chart context category

A **chart context category** \(\mathsf{Ctx}_{\mathfrak A}\) is a category whose objects are charts in \(\mathbf C_R\) and whose morphisms are declared chart transitions in \(\mathbf T_R\) or declared restriction arrows generated by them.

If the atlas is naturally directed by transport, we use covariant maps. If the atlas is naturally directed by restriction, we use the opposite category. The choice is part of the bridge declaration.

## Definition 3.2 — Restriction presentation

Given a chart context category \(
\mathsf{Ctx}_{\mathfrak A}\), a **restriction-style organization presheaf** is a functor

\[
\mathcal F_{\operatorname{Org}}:
\mathsf{Ctx}_{\mathfrak A}^{op}\to\mathbf{Set}
\]

such that

\[
\mathcal F_{\operatorname{Org}}(\mathcal C)=\mathcal O_{\mathcal C}
\]

for each chart \(\mathcal C\). A morphism \(r:\mathcal C\to\mathcal D\) is read as a restriction comparison when the intended map sends data on \(\mathcal D\) back to data on \(\mathcal C\).

## Definition 3.3 — Transport presentation

If transitions are written covariantly as transport maps, a **transported organization functor** is a functor

\[
\mathcal O:\mathsf{Ctx}_{\mathfrak A}\to\mathbf{Set}
\]

with

\[
\mathcal O(\mathcal C)=\mathcal O_{\mathcal C},
\qquad
\mathcal O(t)=t_{\ast}.
\]

The restriction and transport presentations coincide only when the relevant transition maps are invertible or when a bridge declaration explicitly identifies one orientation with the other. Otherwise they are different structures. Standard sheaf contextuality uses the restriction presentation; charted objecthood often uses the transport presentation.

## Definition 3.4 — Global section

A **global section** of \(\mathcal F_{\operatorname{Org}}\) is a compatible choice of local element

\[
O_{\mathcal C}\in\mathcal F_{\operatorname{Org}}(\mathcal C)
\]

for each chart \(\mathcal C\), such that the declared restriction or transport maps identify these elements along every morphism of the chart context category.

## Theorem 3.5 — Objecthood as global section

For a transported or restricted atlas whose chart transitions form a context category, charted objects are exactly global sections of the organization presheaf/functor.

### Proof

A charted object is by Definition 2.3 a family \((O_{\mathcal C})\) such that for every declared transition or restriction between charts, the corresponding transport or restriction map sends one local organization to the other. A global section of \(\mathcal F_{\operatorname{Org}}\) is exactly such a compatible family. \(\square\)

## Corollary 3.6 — Objecthood obstruction as global-section obstruction

A charted objecthood obstruction is exactly the failure of the organization presheaf/functor to admit a compatible global section.

### Proof

By Theorem 3.5, charted objects and global sections are the same data. Therefore failure of charted objecthood is failure of global section existence. \(\square\)

## Remark 3.7 — Import boundary

Theorem 3.5 is not a new sheaf theorem. It states that the programme's definition of objecthood has the same compatibility form as global-section semantics. The contribution is the bridge from chart-relative proper organization to objecthood-as-compatible-family.

---

# 4. Holonomy and contextual obstruction

## Definition 4.1 — Chart cycle

A **chart cycle** is a finite composable sequence of transitions

\[
\gamma:
\mathcal C_0\xrightarrow{t_0}\mathcal C_1
\xrightarrow{t_1}\cdots
\xrightarrow{t_{n-1}}\mathcal C_n=\mathcal C_0.
\]

## Definition 4.2 — Organization holonomy

The **organization holonomy** of \(\gamma\) is the composite transport map

\[
H_{\gamma}
=
(t_{n-1})_{\ast}\circ\cdots\circ(t_1)_{\ast}\circ(t_0)_{\ast}
:
\mathcal O_{\mathcal C_0}\to\mathcal O_{\mathcal C_0}.
\]

## Definition 4.3 — Fixed organization of a cycle

A local organization

\[
O\in\mathcal O_{\mathcal C_0}
\]

is **fixed by the cycle** \(\gamma\) when

\[
H_{\gamma}(O)=O.
\]

## Theorem 4.4 — Holonomy obstruction theorem

Let \(\gamma\) be a chart cycle based at \(\mathcal C_0\). If

\[
H_{\gamma}(O)\neq O,
\]

then there is no compatible object family on the charts of \(\gamma\) whose value at \(\mathcal C_0\) is \(O\).

If \(H_{\gamma}\) has no fixed points, then no compatible object family exists on the cycle.

### Proof

Suppose a compatible object family exists with value \(O\) at \(\mathcal C_0\). Compatibility along the first transition forces its value at \(\mathcal C_1\) to be \((t_0)_{\ast}(O)\). Compatibility along the next transition forces its value at \(\mathcal C_2\) to be \((t_1)_{\ast}(t_0)_{\ast}(O)\), and so on. After traversing the full cycle, compatibility forces the value at \(\mathcal C_0\) to be

\[
H_{\gamma}(O).
\]

But the family already has value \(O\) at \(\mathcal C_0\). Therefore compatibility requires

\[
H_{\gamma}(O)=O.
\]

If this fails, no such family exists. If no element is fixed by \(H_{\gamma}\), then no compatible family can exist on the cycle. \(\square\)

## Corollary 4.5 — Local objecthood does not imply global objecthood

It is possible that every chart in a cycle has local proper organizations while no charted object exists across the cycle.

### Proof

Take any chart cycle whose local organization sets are nonempty and whose holonomy has no fixed point. Each chart has local candidates, but Theorem 4.4 rules out a compatible family. \(\square\)

## Definition 4.6 — Contextual obstruction

A **contextual obstruction** is a failure of compatible objecthood despite the existence of local proper organizations. In a cyclic atlas, nontrivial holonomy without fixed points is a contextual obstruction.

## Remark 4.7 — Relation to residuals

A holonomy obstruction can be read as a closure residual when a residual value-space and comparison map are declared. Without such bridge data, holonomy is a compatibility failure, not yet a numerical residual.

---

# 5. Flat transport and unique extension

## Definition 5.1 — Connected transported atlas

A transported atlas is **connected** when for every pair of charts \(\mathcal C,\mathcal D\), there exists at least one transition path from \(\mathcal C\) to \(\mathcal D\).

## Definition 5.2 — Flat transport

A transported atlas has **flat transport** when for any two transition paths

\[
p,q:\mathcal C\to\mathcal D,
\]

the induced organization transports agree:

\[
p_{\ast}=q_{\ast}:
\mathcal O_{\mathcal C}\to\mathcal O_{\mathcal D}.
\]

## Definition 5.3 — Bijective transport

A transported atlas has **bijective transport** when each transition transport map

\[
t_{\ast}:\mathcal O_{\mathcal C}\to\mathcal O_{\mathcal D}
\]

is a bijection.

## Theorem 5.4 — Flat extension theorem

Let \((\mathfrak A_R,\mathcal O,T_{\ast})\) be a connected transported atlas with flat bijective transport. Fix a base chart \(\mathcal C_0\). Then every local object-candidate

\[
O_0\in\mathcal O_{\mathcal C_0}
\]

extends uniquely to a compatible object family.

### Proof

For any chart \(\mathcal D\), choose a transition path

\[
p:\mathcal C_0\to\mathcal D.
\]

Define

\[
O_{\mathcal D}=p_{\ast}(O_0).
\]

This is independent of the path \(p\) by flatness. Thus the assignment is well-defined. Compatibility follows from composition of transport: if \(t:\mathcal D\to\mathcal E\), then for a path \(p:\mathcal C_0\to\mathcal D\), the path \(t\circ p\) gives

\[
O_{\mathcal E}=(t\circ p)_{\ast}(O_0)=t_{\ast}(p_{\ast}(O_0))=t_{\ast}(O_{\mathcal D}).
\]

Uniqueness follows because any compatible family with value \(O_0\) at \(\mathcal C_0\) must assign \(p_{\ast}(O_0)\) to every chart reachable by a path \(p\), and the atlas is connected. \(\square\)

## Corollary 5.5 — Flat objecthood classification

In a connected flat transported atlas with bijective transport, the set of charted objects is in bijection with the local organization set of any chosen base chart.

### Proof

By Theorem 5.4, each base-chart organization extends uniquely to a charted object. Restricting a charted object to the base chart gives the inverse map. \(\square\)

---

# 6. Deterministic sheaf contextuality as a bridge-realization

This section gives the specialization bridge. It does not claim that charted objecthood obstruction is identical to contextuality in all settings. It states conditions under which the deterministic or strong global-section core of the standard sheaf-theoretic setting is recovered.

## Definition 6.1 — Measurement-context bridge declaration

A **measurement-context bridge declaration** consists of:

1. a set \(X\) of measurement labels;
2. a cover \(\mathcal M\subseteq \mathcal P(X)\) of measurement contexts;
3. an outcome set \(O\);
4. for each context \(C\in\mathcal M\), a chart \(\mathcal C_C\);
5. an identification of local proper organizations with local outcome assignments or admissible local sections:
   \[
   \mathcal O_{\mathcal C_C}\subseteq O^C;
   \]
6. for inclusions or overlaps \(C\cap D\subseteq C,D\), restriction maps matching the chart transports:
   \[
   \operatorname{res}^{C}_{C\cap D}:O^C\to O^{C\cap D};
   \]
7. an empirical or task-admissibility condition selecting which local sections are allowed.

## Definition 6.2 — Standard event presheaf

Given \((X,\mathcal M,O)\), the **event presheaf** assigns

\[
C\mapsto O^C
\]

to each measurement context \(C\), with restriction maps given by ordinary function restriction to smaller contexts or overlaps.

## Theorem 6.3 — Deterministic contextuality specialization

Under a measurement-context bridge declaration, the charted organization presheaf restricts to the standard event-presheaf setting. Charted objecthood becomes existence of a global outcome assignment whose restrictions lie in all declared local admissible sets.

Consequently, deterministic or strong global-section contextuality is a special case of charted objecthood obstruction under this bridge declaration.

### Proof

By the bridge declaration, each chart \(\mathcal C_C\) is assigned a local organization set

\[
\mathcal O_{\mathcal C_C}\subseteq O^C.
\]

The chart transition maps are declared to be the usual restriction maps on overlaps. Therefore a compatible charted object is a family \((s_C)_{C\in\mathcal M}\) with

\[
s_C\in \mathcal O_{\mathcal C_C}\subseteq O^C
\]

such that whenever contexts overlap, their restrictions agree:

\[
s_C|_{C\cap D}=s_D|_{C\cap D}.
\]

This is exactly the compatibility condition for local sections of the event presheaf. Such a compatible family exists exactly when there is a global assignment

\[
s:X\to O
\]

whose restriction to every context \(C\) lies in the declared admissible local set. Failure of such a global assignment is deterministic or strong global-section contextuality. Under the bridge declaration, it is also charted objecthood obstruction. This does not include probabilistic contextuality unless additional empirical-model probability data are supplied.  \(\square\)

## Corollary 6.4 — Deterministic contextuality as objecthood failure under measurement realization

If an empirical model has local sections in every measurement context but no global section, then the corresponding charted organization atlas has local object-candidates in every chart but no charted object.

### Proof

Apply Theorem 6.3. \(\square\)

## Remark 6.5 — What is not claimed

Theorem 6.3 does not say every charted organization atlas is a measurement scenario. It says that when the measurement-context bridge declaration is supplied, deterministic global-section contextuality is recovered as a special case.

---

# 7. Restriction-only separation and enriched contextuality bridges

This section gives a modest separation result. It is relative to a **restriction-only** measurement-context bridge. It is not a separation from cohomological or enriched contextuality frameworks, many of which are designed precisely to encode cyclic cocycle-type obstructions.

## Definition 7.1 — Restriction-only measurement-context representability

A transported charted organization atlas is **restriction-only measurement-context representable** when there exists a measurement-context bridge declaration as in Definition 6.1 such that:

1. chart local organization sets are local outcome-assignment sets;
2. chart transports are ordinary restrictions on measurement overlaps;
3. compatibility is equality of restrictions on overlaps;
4. obstruction is failure of a global outcome assignment.

## Proposition 7.2 — Pure transport holonomy is not restriction-only holonomy

Let a charted organization atlas contain a cycle

\[
\mathcal C_0\to\mathcal C_1\to\mathcal C_2\to\mathcal C_0
\]

whose organization holonomy is a nontrivial permutation of \(\mathcal O_{\mathcal C_0}\) with no fixed point.

If the proposed measurement-context representation assigns the same measurement context to \(\mathcal C_0\) at the beginning and end of the cycle and represents each transition as ordinary restriction along overlaps, then the cycle cannot be represented unless additional bridge data encode the nontrivial permutation as an outcome relabeling or context automorphism.

### Proof

In the standard event-presheaf bridge, returning to the same context through identity overlap restrictions gives the same local section, because restriction to the same context is the identity. A nontrivial fixed-point-free holonomy sends a local organization \(O\) to \(H_\gamma(O)\neq O\). This cannot be represented by ordinary identity return on the same context. To represent it, one must add extra bridge data: an outcome relabeling, a context automorphism, or a nonstandard transport interpretation. Without that additional bridge data, the charted obstruction is not standard-measurement representable. \(\square\)

## Theorem 7.3 — Separating construction relative to restriction-only measurement translation

There exist charted objecthood obstructions that are not representable under the restriction-only measurement-context translation of Definition 7.1. This is not a separation from enriched, cohomological, relabeling, or automorphism-equipped contextuality frameworks.

### Proof

Use the three-chart cycle of Section 9 below. Each chart has two local proper organizations. The first two transports preserve labels and the third transport swaps labels, producing fixed-point-free holonomy. By Theorem 4.4, there is a charted objecthood obstruction.

Under the standard measurement-context translation without extra outcome relabeling or context automorphism bridge data, returning to the same context must act as identity on local assignments. By Proposition 7.2, the fixed-point-free holonomy cannot be represented as standard restriction holonomy. Hence this charted obstruction is not representable under the restriction-only measurement-context translation. \(\square\)

## Corollary 7.4 — Enriched bridge data can collapse the separation

The separation in Theorem 7.3 is relative to the restriction-only translation. If additional bridge data are supplied that interpret chart holonomy as allowed outcome relabeling, context automorphism, residual comparison, cocycle coefficient, or gauge-like transport, then the obstruction may become representable in an enriched or cohomological contextuality framework.

### Proof

Theorem 7.3 excludes only the restriction-only translation. Enriching the bridge changes the representability target. \(\square\)

## Remark 7.5 — Relation to cohomological contextuality

Cohomological contextuality frameworks explicitly study obstruction classes associated with contextuality. The fixed-point-free cycle of Theorem 7.3 is therefore not claimed to be invisible to all contextuality theory. Rather, it is invisible to the restriction-only translation unless an enriched bridge supplies relabeling, coefficient, cocycle, or automorphism data. Under such enriched bridges, a charted holonomy obstruction may become a cohomological contextuality witness rather than a separation from contextuality.

## Remark 7.6 — Mermin-type cyclic obstructions

The Mermin--Peres magic square and related parity proofs are commonly expressible through cyclic sign or parity obstructions. This paper does not claim that such examples fall outside contextuality theory. It claims only that charted holonomy is not representable by ordinary restriction maps alone. Whether a given physical cyclic obstruction is represented in the charted framework, in cohomological contextuality, or in both depends on the bridge declarations supplied.

## Remark 7.7 — Other non-standard charted obstructions

Other charted obstructions may arise from threshold incompatibility, persistence-support failure, residual mismatch, or evaluator/admission incompatibility. These are not automatically standard empirical-model contextuality obstructions. They become comparable to standard contextuality only after declaring bridge data from charted organization values, thresholds, residuals, or evaluators into measurement-context outcomes and supports.

---

# 8. Bridge declaration discipline

## Definition 8.1 — Objecthood bridge declaration

An **objecthood bridge declaration** consists of:

1. local proper organization sets \(\mathcal O_{\mathcal C}\);
2. declared transition maps \(t_{\ast}:\mathcal O_{\mathcal C}\to\mathcal O_{\mathcal D}\);
3. compatibility conditions on transition composition;
4. if residuals are to be measured, a residual value-space and comparison map;
5. if deterministic contextuality is to be recovered, a measurement-context bridge declaration.

## Proposition 8.2 — No bridge, no objecthood transfer

A transition between charts does not by itself transfer objecthood unless an organization transport map is declared.

### Proof

Objecthood compatibility is expressed by

\[
t_{\ast}(O_{\mathcal C})=O_{\mathcal D}.
\]

Without \(t_{\ast}\), this expression is undefined. Therefore the transition cannot establish cross-chart objecthood. \(\square\)

## Proposition 8.3 — No residual readout, no numerical obstruction

A failed compatibility condition gives an obstruction. It gives a numerical residual only after a residual value-space and comparison map are declared.

### Proof

Failure of compatibility is the statement

\[
H_{\gamma}(O)\neq O.
\]

This is a structural inequality in local organization space. To assign a value to the failure, one needs a map from the failure datum into a residual value-space. Without such a map, there is no numerical residual. \(\square\)

## Proposition 8.4 — No measurement-context bridge, no deterministic contextuality claim

A charted objecthood obstruction is not a deterministic sheaf-contextuality obstruction unless a measurement-context bridge declaration is supplied.

### Proof

Deterministic sheaf contextuality requires a measurement scenario, outcome assignments, restriction maps, and empirical or support conditions. A charted objecthood obstruction supplies local organizations and transition compatibility failure. Without a bridge identifying these with measurement-context data, the contextuality claim is undefined. \(\square\)

---

# 9. Non-posetal chart obstruction

This section records a charted obstruction that uses categorical structure unavailable in a restriction-only poset of measurement contexts.

## Definition 9.1 — Restriction-poset bridge

A **restriction-poset bridge** is a measurement-context bridge whose chart context category is a poset of contexts ordered by inclusion and whose transitions are restriction maps. In such a bridge, every endomorphism of a context is the identity.

## Definition 9.2 — Non-posetal endotransition

Let \(\mathcal C\) be a chart in a transported atlas. A **non-posetal endotransition** is a declared transition

\[
e:\mathcal C\to\mathcal C
\]

that is not the identity transition. It induces an organization transport map

\[
e_\ast:\mathcal O_{\mathcal C}\to\mathcal O_{\mathcal C}.
\]

## Theorem 9.3 — Nonidentity endotransition obstruction

If \(e:\mathcal C\to\mathcal C\) is a nonidentity endotransition and \(e_\ast\) has no fixed point on \(\mathcal O_{\mathcal C}\), then there is no charted object compatible with \(e\).

### Proof

A compatible object family must assign some

\[
O_{\mathcal C}\in\mathcal O_{\mathcal C}
\]

with

\[
e_\ast(O_{\mathcal C})=O_{\mathcal C}.
\]

If \(e_\ast\) has no fixed point, no such value exists. Therefore no compatible charted object exists. \(\square\)

## Corollary 9.4 — Not restriction-poset representable without extra bridge data

A fixed-point-free nonidentity endotransition obstruction is not representable under a restriction-poset bridge.

### Proof

In a restriction-poset bridge, every endomorphism of a context is the identity. Identity transport fixes every local section. Therefore a fixed-point-free nonidentity endotransition cannot be represented unless extra bridge data are added, such as context automorphisms, outcome relabelings, coefficient data, or cohomological enrichment. \(\square\)

## Example 9.5 — A non-invertible fixed-point-free endotransition

Let

\[
\mathcal O_{\mathcal C}=\{0,1,2\}
\]

and define

\[
e_\ast(0)=1,\qquad e_\ast(1)=0,\qquad e_\ast(2)=0.
\]

Then \(e_\ast\) is not invertible, since both \(1\) and \(2\) map to \(0\). It has no fixed point. Hence Theorem 9.3 gives an objecthood obstruction. This obstruction uses a non-posetal endotransition and is not produced by restriction-only overlap maps.

## Remark 9.6 — Relation to cohomological contextuality

Corollary 9.4 separates only from restriction-poset bridges. Enriched contextuality frameworks may represent cyclic or coefficient-valued obstructions by adding automorphism, coefficient, or cocycle data. The point is therefore not that charted objecthood lies outside every contextuality framework, but that non-posetal chart transport requires bridge data beyond the restriction-only measurement-context translation.

---

# 10. Non-quantum gluing example: database join obstruction

This section gives a non-quantum example of charted objecthood obstruction. It is structurally the same gluing problem as deterministic contextuality, but no quantum system, probability model, or measurement postulate is involved.

## 10.1 Variables and local charts

Let the global attributes be

\[
X,Y,Z\in\{0,1\}.
\]

Consider three local charts corresponding to pairwise database views:

\[
\mathcal C_{XY},\qquad \mathcal C_{YZ},\qquad \mathcal C_{XZ}.
\]

Their local object-candidate sets are the allowed rows:

\[
\mathcal O_{XY}=\{(0,0),(1,1)\},
\]

\[
\mathcal O_{YZ}=\{(0,0),(1,1)\},
\]

and

\[
\mathcal O_{XZ}=\{(0,1),(1,0)\}.
\]

Thus the first two views require equality, while the third requires inequality.

## Proposition 10.2 — Pairwise local views need not glue globally

Each local chart has proper local object-candidates, but there is no global assignment

\[
s:\{X,Y,Z\}\to\{0,1\}
\]

whose restrictions lie in all three local sets.

### Proof

If

\[
s|_{XY}\in\mathcal O_{XY},
\]

then \(X=Y\). If

\[
s|_{YZ}\in\mathcal O_{YZ},
\]

then \(Y=Z\). Hence \(X=Z\). But

\[
s|_{XZ}\in\mathcal O_{XZ}
\]

requires \(X\ne Z\). Contradiction. Therefore no compatible global assignment exists. \(\square\)

## Corollary 10.3 — Non-quantum contextual obstruction

The database-view example is a charted objecthood obstruction with no quantum or probabilistic content.

### Proof

The obstruction follows entirely from local compatibility constraints among finite relations and the absence of a global join. No probabilities, observables, Hilbert spaces, or measurement assumptions are used. \(\square\)

## Remark 10.4 — What this example does and does not show

The database example does not separate charted objecthood from deterministic sheaf contextuality; indeed, it is naturally representable as a deterministic global-section obstruction. Its purpose is different: it shows that charted objecthood obstruction is not intrinsically quantum. It applies to ordinary compatibility problems such as database joins, constraint satisfaction, and local-to-global integration.

This connection to database-style constraint satisfaction is not new to contextuality theory. Abramsky, Gottlob, and Kolaitis explicitly relate robust constraint satisfaction to local hidden-variable questions, using constraint satisfaction machinery to study the computational difficulty of detecting local hidden-variable models. The present example should therefore be read as positioning charted objecthood within that existing non-quantum/contextuality interface, not as claiming that database constraints have been newly connected to contextuality here.

---

# 11. Worked example: local organizations without global objecthood

## 9.1 Charts and local organizations

Let an atlas contain three charts:

\[
\mathcal C_0,
\quad
\mathcal C_1,
\quad
\mathcal C_2.
\]

Let each chart have two local proper organizations:

\[
\mathcal O_{\mathcal C_i}=\{0_i,1_i\}.
\]

Thus every chart has nonempty local object-candidates.

## 9.2 Transitions

Declare transitions around the cycle:

\[
t_{01}:\mathcal C_0\to\mathcal C_1,
\]

\[
t_{12}:\mathcal C_1\to\mathcal C_2,
\]

\[
t_{20}:\mathcal C_2\to\mathcal C_0.
\]

Define transports:

\[
(t_{01})_{\ast}(0_0)=0_1,
\quad
(t_{01})_{\ast}(1_0)=1_1,
\]

\[
(t_{12})_{\ast}(0_1)=0_2,
\quad
(t_{12})_{\ast}(1_1)=1_2,
\]

and

\[
(t_{20})_{\ast}(0_2)=1_0,
\quad
(t_{20})_{\ast}(1_2)=0_0.
\]

The first two transitions preserve labels; the last swaps them.

## 9.3 Holonomy

The cycle holonomy is

\[
H=(t_{20})_{\ast}\circ(t_{12})_{\ast}\circ(t_{01})_{\ast}.
\]

Then

\[
H(0_0)=1_0,
\]

and

\[
H(1_0)=0_0.
\]

So \(H\) has no fixed point.

## 9.4 Obstruction

By Theorem 4.4, there is no compatible object family on this cycle.

Yet every chart has local proper organizations. Therefore this is a contextual obstruction: local object-candidates exist everywhere, but no global charted object exists.

## 9.5 Flat comparison

If instead

\[
(t_{20})_{\ast}(0_2)=0_0,
\quad
(t_{20})_{\ast}(1_2)=1_0,
\]

then \(H\) is the identity and there are two compatible object families:

\[
(0_0,0_1,0_2)
\]

and

\[
(1_0,1_1,1_2).
\]

Thus the obstruction is not caused by lack of local candidates. It is caused by nontrivial transport around the cycle.

## 9.6 Relation to the separating construction

The same example proves Theorem 7.3 relative to the standard measurement-context translation. The fixed-point-free holonomy is a charted transport obstruction. It is not representable as ordinary identity return along restriction maps unless additional bridge data translate the transport into outcome relabeling or context automorphism.

---

# 12. Relation to contextuality

## 12.1 Shared pattern

The structure above has the following form:

1. each chart/context has local candidates;
2. transitions impose compatibility requirements;
3. global objecthood is compatible gluing;
4. obstruction is failure of global compatibility despite local availability.

This is structurally adjacent to sheaf-theoretic contextuality, where compatible local data may fail to assemble into a global section.

## 12.2 Special-case relation

Under a measurement-context bridge declaration, the charted organization presheaf becomes a standard event-presheaf-like structure and charted objecthood obstruction becomes deterministic global-section contextuality.

The bridge is not light. It supplies measurement labels, contexts, outcomes, chart-context indexing, identification of proper organizations with outcome assignments, restriction maps, and admissible local supports. Without this bridge, charted objecthood obstruction is not a standard contextuality claim.

## 12.3 Categorical generalization

Standard sheaf contextuality is usually formulated over a poset of contexts ordered by inclusion. Charted objecthood allows a general chart context category with declared transitions, including non-posetal transitions and cycles. Thus the broader framework is best read as a categorical generalization of deterministic gluing obstruction. The standard poset-based event presheaf is recovered when the chart context category is restricted to a measurement cover and the transitions are ordinary restrictions.

## 12.4 Cohomological and quantitative boundaries

Cohomological contextuality frameworks already study obstruction classes for global-section failure, including cyclic and parity-style obstructions. Charted holonomy should therefore not be presented as a separation from all contextuality theory. It is a separation only from the restriction-only measurement bridge.

The framework in this paper is qualitative. It does not include probability distributions, empirical-model weights, contextual fractions, no-signalling constraints, or Bell-inequality violation. Those require additional probabilistic bridge data. It also does not derive Hilbert-space-specific Kochen--Specker or Bell results.

## 12.5 Difference

The general framework does not assume probability distributions, empirical models, measurement covers, quantum systems, no-signalling, or outcome assignments. Its local data are proper organizations induced by relation-first charts. Its general obstruction is objecthood obstruction inside an observer atlas.

Therefore sheaf contextuality is not rejected or replaced. Its deterministic global-section core is recovered as a special case under declared bridge data, while charted objecthood also allows non-posetal and transition-holonomy obstructions that require enriched bridges to compare with cohomological contextuality.

---

# 13. Claims and non-claims

## 13.1 Claims

This paper claims:

1. objecthood can be formally represented as compatible charted organization;
2. local proper organizations do not by themselves constitute global objecthood;
3. chart cycles can obstruct objecthood through nontrivial organization holonomy;
4. charted objects are global sections of the organization presheaf/functor;
5. deterministic or strong global-section contextuality is a special case under measurement-context bridge declarations;
6. some charted objecthood obstructions are not representable under the restriction-only measurement-context translation;
7. non-posetal endotransitions can produce fixed-point-free objecthood obstructions unavailable to restriction-poset bridges without extra bridge data;
8. flat connected transported atlases allow unique extension from a base chart;
9. contextual obstruction can be expressed without importing probability or quantum theory;
10. database-style local compatibility failures are non-quantum instances of charted objecthood obstruction.

## 13.2 Non-claims

This paper does not claim:

1. to derive physical objects;
2. to solve quantum contextuality;
3. to derive measurement theory;
4. to define consciousness or subjective observation;
5. that every object in every domain must be modeled as a global section;
6. that every obstruction is physical contextuality;
7. that transport maps are automatic from chart notation;
8. that all charted objecthood obstructions are standard empirical-model contextuality obstructions;
9. that standard contextuality is incorrect or incomplete;
10. that cohomological or probabilistic contextuality is subsumed without additional bridge data;
11. that contextual fractions, Bell inequalities, or Hilbert-space-specific Kochen--Specker results are derived.

---

# 14. References

Abramsky, S. and Brandenburger, A. (2011). The sheaf-theoretic structure of non-locality and contextuality. *New Journal of Physics*, 13, 113036.

Abramsky, S., Gottlob, G., and Kolaitis, P. G. (2013). Robust constraint satisfaction and local hidden variables in quantum mechanics. In F. Rossi (ed.), *Proceedings of the Twenty-Third International Joint Conference on Artificial Intelligence (IJCAI 2013)*, 440--446. AAAI Press/IJCAI.

Abramsky, S., Mansfield, S., and Barbosa, R. S. (2011/2012). The cohomology of non-locality and contextuality. *Proceedings of QPL 2011*, EPTCS 95.

Abramsky, S., Barbosa, R. S., and Mansfield, S. (2017). Contextual fraction as a measure of contextuality. *Physical Review Letters*, 119, 050504.

Okay, C., Roberts, S., Bartlett, S. D., and Raussendorf, R. (2017). Topological proofs of contextuality in quantum mechanics. *Quantum Information and Computation*, 17(13--14).

Fagin, R. (1983). Degrees of acyclicity for hypergraphs and relational database schemes. *Journal of the ACM*, 30(3), 514--550.

Maier, D. (1983). *The Theory of Relational Databases*. Computer Science Press.

# 15. Summary

The central conclusion is:

\[
\boxed{
\text{objecthood is compatible charted organization.}
}
\]

A chart gives local proper organizations. An atlas gives transitions. A transported atlas gives organization transport. A charted object is a compatible family across that transport structure.

Thus:

\[
\boxed{
\text{local organization}\not\Rightarrow\text{objecthood}.
}
\]

Objecthood requires global compatibility across admissible chart transitions. When local proper organizations exist but no compatible family exists, the failure is a contextual obstruction. In a cycle, this obstruction is detected by holonomy: no fixed point, no charted object.

Under a measurement-context bridge declaration, this global compatibility condition specializes to the deterministic global-section condition of sheaf-theoretic contextuality. Without that bridge, a charted obstruction remains an organization-theoretic obstruction, not automatically a standard contextuality claim.

The resulting position is precise: deterministic global-section contextuality is a special case of charted objecthood obstruction under a substantial measurement-context bridge. Charted objecthood obstruction can also fail through non-posetal transport, residual, threshold, persistence, or database-style local compatibility mechanisms. Some of these are not representable under a restriction-only measurement-context bridge, although enriched cohomological, relabeling, automorphism, or coefficient bridges may represent them.

---

## AI-assistance disclosure

This manuscript was developed with AI-assisted drafting and review support. The author directed the research programme, selected and revised the mathematical and methodological content, and is responsible for all claims and errors.
