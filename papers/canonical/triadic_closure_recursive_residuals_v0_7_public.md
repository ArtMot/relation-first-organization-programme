# Triadic Closure and Recursive Residuals in Relation-First Systems

**Author:** Artur Motruk  
**Affiliation:** Independent researcher  
**ORCID:** 0009-0003-6928-1701  
**Programme:** Relation-First Organization Programme  
**Document role:** Core architecture / boundary, mediation, visibility, and residuals layer  
**Public release status:** Repository manuscript for public programme release  

---

## 0. Foundation statement

Triadic Closure and Recursive Residual Theory studies the first closure-complete structure, relative to the boundary--mediation--visibility requirements, required for relation-first organization to avoid collapse into inert boundary, undirected total connectivity, or arbitrary perspective.

The primitive relation-modes are:

\[
\mathsf R=\text{relation / mediation},
\qquad
\mathsf O=\text{observer-chart / local visibility},
\qquad
\mathsf Z=\text{zero-boundary / initial-terminal discipline}.
\]

They are not three objects. They are three required modes of relation: mediation, visibility, and boundary recurrence.

The central claim is not that the number three is sacred. The claim is:

\[
\boxed{
\text{triadic mediation is the first closure-complete arity relative to the boundary--mediation--visibility requirements of relation-first organization.}
}
\]

The primitive closure loop is:

\[
\boxed{
\mathsf R\longrightarrow \mathsf O\longrightarrow \mathsf Z\longrightarrow \mathsf R.
}
\]

This is a loop of relation-modes. Relation becomes locally visible through observer-charting; visibility is bounded by zero-boundary discipline; boundary recurrence regenerates relation. The loop is not a temporal cycle unless a temporal realization is separately declared.

A closure loop is proper only when it neither collapses to the lower boundary nor saturates to the upper boundary. The remaining nonzero, nonterminal residue is the **primitive closure residual**.

The closure residual has three faces:

\[
\boxed{
\Omega_{\mathsf R\mathsf O\mathsf Z}
=
(\Omega_{\mathsf Z},\Omega_{\mathsf O},\Omega_{\mathsf R}).
}
\]

Here:

\[
\Omega_{\mathsf Z}
=
\text{boundary-return / closure-holonomy residual},
\]

\[
\Omega_{\mathsf O}
=
\text{observer-mediated path / mediation residual},
\]

\[
\Omega_{\mathsf R}
=
\text{relation-resolution / unresolved-relation residual}.
\]

A scalar residual is not primitive. It is a charted readout of the three-faced residual.

The role symbols \(\mathsf R,\mathsf O,\mathsf Z\) are not identical to the concrete carrier \(R\), a concrete observer-chart \(\mathcal C\), or a concrete zero-boundary \(Z\) from the companion theories. They are task-defined positions in the primitive closure pattern. A role is not realized by a hidden object standing behind the relation. A role is realized only when an admissible observer-chart makes the role's task-satisfaction visible inside a declared formal context.

---

## 1. Scope

This paper does not claim:

1. that every possible theory must be triadic;
2. that the Standard Model gauge group is derived;
3. that a physical gauge field is derived;
4. that spacetime, gravity, quantum mechanics, or physical constants are derived;
5. that the closure residual is numerical unless a numerical zero-boundary realization is declared;
6. that every use of the word triangle refers to Euclidean geometry.

The document claims only:

1. that a role is a task-defined position in a closure pattern, not an object;
2. that relation-first realization means observer-charted satisfaction of a task-role pair;
3. that the relation-first organization framework naturally yields a primitive closure triad \((\mathsf R,\mathsf O,\mathsf Z)\) relative to the boundary--mediation--visibility requirements;
4. that every one-role and two-role reduction of a closure-complete schema loses at least one required closure function;
5. that boundary recurrence follows from initial-terminal boundary indistinguishability;
6. that boundary, mediation, and visibility are relation-modes rather than object-kinds;
7. that a triadic mediation inequality is the primitive coherence condition behind the ordinary metric triangle inequality;
8. that organizational distance, when defined as minimal mediated path cost, satisfies the ordinary triangle inequality as a special case;
9. that failure of triadic closure has metric, residual, and holonomy faces;
10. that gauge-like structure is naturally located at the invariance of closure residuals under admissible chart transitions.

---

## 1.1 Adjacent frameworks and import boundaries

The document uses several ideas that have close neighbours in existing mathematics and philosophy. The point of this section is to prevent the triadic closure vocabulary from being read as if it were invented in isolation.

1. **Peircean triadicity.** Peirce's semiotic triad of sign, object, and interpretant is a major prior example of irreducible triadic relation. The present framework is not a semiotic theory in Peirce's sense. Its triad is boundary--mediation--visibility, and its aim is to organize the companion theories of organization, charting, learning, and residual closure. The shared point is that triadic mediation is not reducible to a pile of independent dyads.

2. **Category theory.** Source, target, and morphism already form a triadic pattern, and composition introduces further coherence constraints. This paper does not claim that category theory lacks triadic structure. It uses a role-language suitable for the present programme and should be read as compatible with categorical presentations when such presentations are declared.

3. **Lawvere-style generalized metric spaces.** The triadic mediation inequality
\[
\Delta(X,Z)\preceq \Delta(X,Y)\otimes\Delta(Y,Z)
\]
becomes a Lawvere-style enriched metric condition when the value structure is treated as a monoidal preorder. The document does not claim to invent generalized metrics. It claims that such inequalities arise here as closure-coherence conditions for mediated organization.

4. **Bregman and information-geometric three-point identities.** Not every organizational residual is metric. Divergences such as Kullback--Leibler divergence need not satisfy the ordinary triangle inequality, while Bregman divergences have their own three-point identities. The present framework therefore treats the metric triangle inequality as one realization of a broader triadic mediation condition, not as the only possible residual geometry.

5. **Holonomy, Čech cocycles, and sheaf cohomology.** The cocycle residuals in Section 14 are structurally adjacent to standard holonomy and cocycle machinery. This paper does not construct a principal bundle, connection, sheaf cohomology class, or physical gauge theory. It identifies the residual-preserving transition site at which such structures could be attached if the required additional data are supplied.

6. **Markov and causal categories.** Mediation through an intermediate object is also central to probabilistic and causal formalisms. The present paper does not supply a Markov category or causal model; it gives a general boundary--mediation--visibility schema into which such realizations may or may not fit.

The contribution of this paper is therefore internal to the programme: it articulates the common closure pattern across the companion theories and gives import boundaries for neighbouring frameworks.

---

## 1.2 Roles, tasks, observers, and realization

The word **role** is not used here as an additional object-kind. A role is a task-position inside a relation pattern.

The primitive triad is more specifically a triad of **relation-modes**. A relation-mode is a role whose task is itself a relational operation: bounding, mediating, making visible, evaluating, or regenerating availability. Relation-modes are not objects that stand behind the pattern. They are ways a relation-pattern functions.

### Definition 1.1 — Relation-mode

A **relation-mode** is a task-defined role whose satisfaction consists in a relational operation rather than in the presence of an object.

The primitive relation-modes are:

\[
\mathsf Z=\text{boundary / polarity / recurrence},
\]

\[
\mathsf R=\text{mediation / path / resolution},
\]

\[
\mathsf O=\text{visibility / evaluation / charting}.
\]

A concrete structure realizes one of these modes only when an admissible observer-chart makes the corresponding task-role satisfaction visible.

---

### Definition 1.2 — Role

A **role** is a position in a declared closure pattern, specified by the task it must perform in that pattern.

Equivalently, a role is a task-defined relation-position. It is not a substance, object, carrier, or independent entity.

For the primitive closure triad:

\[
\mathsf R=\text{the mediation role},
\]

\[
\mathsf O=\text{the local-visibility / observer-chart role},
\]

\[
\mathsf Z=\text{the zero-boundary / extremal-discipline role}.
\]

These are roles because they specify what must be done in the closure pattern, not because they name three objects.

---

### Definition 1.3 — Task-role pair

A **task-role pair** is an ordered pair:

\[
(\tau,\mathsf r)
\]

where \(\tau\) is a declared task and \(\mathsf r\) is the role-position in which that task is to be satisfied.

The task specifies what must be resolved, preserved, bounded, mediated, or made visible. The role specifies where that requirement sits in the closure pattern.

---

### Definition 1.4 — Observer-charted role satisfaction

Let \(O\) be an admissible observer-chart, chart-position, or atlas-local presentation. The notation:

\[
O\Vdash(\tau,\mathsf r)
\]

means that \(O\) makes the satisfaction of task \(\tau\) in role \(\mathsf r\) chart-visible.

Thus role realization is not object occupation. It is observer-charted task-role satisfaction.

---

### Definition 1.5 — Role realization

A **role realization** of the primitive triad is a declaration of observer-charted satisfaction data:

\[
O_R\Vdash(\tau_R,\mathsf R),
\qquad
O_O\Vdash(\tau_O,\mathsf O),
\qquad
O_Z\Vdash(\tau_Z,\mathsf Z).
\]

Typical concrete structures involved in such a realization are:

\[
R_\ast=\text{a relation carrier},
\]

\[
O_\ast=\text{an admissible observer-chart, chart-position, or atlas-local presentation},
\]

\[
Z_\ast=\text{a zero-boundary value structure}.
\]

These concrete structures do not become the roles themselves. They are structures whose task-role satisfaction is visible under admissible observation.

---

### Convention 1.6 — Role symbols versus carrier symbols

The symbol \(\mathsf R\) denotes the primitive role of relation/mediation. The symbol \(R\), when used in the Theory of Organization or Charted Organization Theory, denotes a concrete relation carrier.

The symbol \(\mathsf O\) denotes the primitive role of observer-chart/local visibility. It is not identical to a particular chart \(\mathcal C\) unless a role realization declares observer-charted satisfaction of the \(\mathsf O\)-role through \(\mathcal C\).

The symbol \(\mathsf Z\) denotes the primitive role of zero-boundary discipline. It is not identical to a particular zero-boundary \(Z\) unless a role realization declares observer-charted satisfaction of the \(\mathsf Z\)-role through \(Z\).

This convention prevents the primitive closure theory from collapsing into the concrete notation of any one companion document.

---

### Principle 1.7 — Task-role-observer stability

A role is stable only through a triad:

\[
\boxed{
\text{task}\quad-\quad\text{role}\quad-\quad\text{observer}.
}
\]

A task without a role is an unpositioned demand. A role without a task is an empty label. A task-role pair without an observer-chart is not visible as satisfied and therefore does not produce information-bearing realization.

Thus:

\[
\boxed{
\text{realization}=\text{observer-charted satisfaction of a task-role pair}.
}
\]

This is the task-role-observer form of the general triadic principle. It is not a new primitive triad; it is the same closure logic applied to the notion of role itself.

---

## 2. Basic zero-boundary notation

A **zero-boundary** is a bounded ordered structure:

\[
Z=(Z,\preceq,z_-,z_+)
\]

where:

\[
z_-\preceq z\preceq z_+
\quad
\text{for all }z\in Z.
\]

The **proper interior** is:

\[
Z^\circ
=
\{z\in Z:z_-\prec z\prec z_+\}.
\]

A value in \(Z^\circ\) is called **proper**.

The boundary values \(z_-\) and \(z_+\) are excluded from proper organization.

---

## 3. Boundary recurrence

### Definition 3.1 — Boundary equivalence

A **boundary equivalence** is an equivalence relation \(\equiv_\partial\) defined on the boundary values such that:

\[
\boxed{
z_-\equiv_\partial z_+.
}
\]

This does not assert:

\[
z_-=z_+
\]

inside a proper chart. It asserts only that at boundary collapse the lower and upper extremes become organizationally indistinguishable.

---

### Definition 3.2 — Proper-chart distinction of boundaries

A proper chart distinguishes the boundaries when:

\[
z_-\prec z_+
\]

inside its ordered zero-boundary face.

Thus \(z_-\) and \(z_+\) are:

1. distinguishable inside a proper chart;
2. indistinguishable at boundary collapse.

The two statements are compatible because they occur at different levels. The order relation \(z_-\prec z_+\) is an interior chart-order statement. The equivalence \(z_-\equiv_\partial z_+\) is a boundary-collapse statement. Boundary equivalence must never be read as literal equality inside the proper ordered value structure.

---

### Proposition 3.3 — Boundary equivalence does not collapse proper interior

Assume a proper chart has zero-boundary order \((Z,\preceq,z_-,z_+)\) with nonempty proper interior \(Z^\circ\). If \(z_-\equiv_\partial z_+\), it does not follow that \(Z^\circ=\varnothing\).

#### Proof

The relation \(\equiv_\partial\) is defined only as a boundary-collapse equivalence on boundary values. It is not the equality relation of the ordered value structure and does not identify \(z_-\) and \(z_+\) inside the proper chart order. Therefore the existence of interior values \(z\) with \(z_-\prec z\prec z_+\) is unaffected by \(z_-\equiv_\partial z_+\). □

---

### Principle 3.4 — Boundary recurrence

If terminal saturation reaches \(z_+\), and \(z_+\equiv_\partial z_-\), then terminal saturation regenerates the unresolved boundary condition represented by \(z_-\).

Hence terminal completion does not end organization. It returns organization to the condition that requires mediation.

---

### Proposition 3.5 — Terminal saturation does not produce final proper organization

If a resolution path terminates only at \(z_+\), then its terminal value is not in \(Z^\circ\). Therefore it is not a proper organization value.

If additionally \(z_+\equiv_\partial z_-\), then terminal saturation is boundary-equivalent to initial non-resolution.

#### Proof

By definition:

\[
Z^\circ=\{z:z_-\prec z\prec z_+\}.
\]

Since \(z_+\notin Z^\circ\), any resolution path whose only terminal value is \(z_+\) does not end in a proper value. If \(z_+\equiv_\partial z_-\), the boundary endpoint is equivalent, at collapse, to the initial boundary value. □

---

## 4. Primitive triad

### Definition 4.1 — Primitive role set

Let:

\[
\mathcal P=\{\mathsf R,\mathsf O,\mathsf Z\}.
\]

The intended role readings are:

\[
\mathsf R=\text{relation / mediation},
\]

\[
\mathsf O=\text{observer-chart / local visibility},
\]

\[
\mathsf Z=\text{zero-boundary / initial-terminal discipline}.
\]

Each element of \(\mathcal P\) is a task-defined role-position. None is an object, carrier, or independent substance.

---

### Definition 4.2 — Primitive closure cycle

The primitive closure cycle is the oriented relation-mode cycle:

\[
\boxed{
\mathsf R\to\mathsf O\to\mathsf Z\to\mathsf R.
}
\]

The three arrows have the following readings:

\[
\mathsf R\to\mathsf O:
\quad
\text{relation becomes locally visible through charting};
\]

\[
\mathsf O\to\mathsf Z:
\quad
\text{observation is bounded by zero-boundary discipline};
\]

\[
\mathsf Z\to\mathsf R:
\quad
\text{boundary recurrence regenerates relation}.
\]

---

### Principle 4.3 — Relation-mode loop

The primitive closure cycle is not a chain of objects. It is a recursive loop of relation-modes. Boundary is a recursive polarity relation, mediation is a path relation, and visibility/evaluation is a charting relation. Stable organization requires the loop, not any isolated mode.

---

### Definition 4.4 — Closure-complete role family

A role family \(S\subseteq\mathcal P\) is **closure-complete** when:

1. \(\mathsf R,\mathsf O,\mathsf Z\in S\);
2. every edge of the primitive closure cycle has both endpoints in \(S\).

---

### Theorem 4.5 — Proper subfamilies are closure-incomplete

If \(S\subsetneq\mathcal P\), then \(S\) is not closure-complete.

#### Proof

By Definition 4.4, closure-completeness requires:

\[
\mathsf R,\mathsf O,\mathsf Z\in S.
\]

If \(S\subsetneq\mathcal P\), at least one of the three roles is absent. Hence the first condition of Definition 4.4 fails. □

---

## 5. Instability of reductions

The instability of the primitive triad is summarized as follows.

| Role family | Failure mode |
|---|---|
| \(\{\mathsf Z\}\) | inert boundary; no mediation or local visibility |
| \(\{\mathsf R\}\) | undirected total connectivity; no boundary or chart discipline |
| \(\{\mathsf O\}\) | arbitrary perspective; no relation-grounding or boundary discipline |
| \(\{\mathsf Z,\mathsf R\}\) | boundary-driven relation without local visibility |
| \(\{\mathsf R,\mathsf O\}\) | visible relation without extremal discipline |
| \(\{\mathsf Z,\mathsf O\}\) | bounded readout without resolving mediation |
| \(\{\mathsf Z,\mathsf R,\mathsf O\}\) | first closure-complete role family |

---

### Principle 5.1 — Stable relation is triadic

Relation is primitive, but stable relation is not relation-alone.

A relation becomes organizationally stable only when constrained by:

1. boundary discipline \(\mathsf Z\);
2. local chart visibility \(\mathsf O\).

Thus:

\[
\boxed{
\text{relation is primitive, but stable relation is triadic.}
}
\]

---

## 6. Closure residual

### Definition 6.1 — Three-faced closure residual

A **primitive closure residual** is a triple:

\[
\boxed{
\Omega_{\mathsf R\mathsf O\mathsf Z}
=
(\Omega_{\mathsf Z},\Omega_{\mathsf O},\Omega_{\mathsf R}).
}
\]

The components are called:

\[
\Omega_{\mathsf Z}
=
\text{closure-holonomy residual},
\]

\[
\Omega_{\mathsf O}
=
\text{mediation residual},
\]

\[
\Omega_{\mathsf R}
=
\text{resolution residual}.
\]

---

### Definition 6.2 — Proper closure residual

Let:

\[
Z_{\mathsf Z},Z_{\mathsf O},Z_{\mathsf R}
\]

be the zero-boundary value structures in which the three residual faces are read.

The closure residual is **proper** when:

\[
\boxed{
\Omega_{\mathsf Z}\in Z_{\mathsf Z}^{\circ},
\qquad
\Omega_{\mathsf O}\in Z_{\mathsf O}^{\circ},
\qquad
\Omega_{\mathsf R}\in Z_{\mathsf R}^{\circ}.
}
\]

Equivalently:

\[
z_-^{\mathsf Z}\prec \Omega_{\mathsf Z}\prec z_+^{\mathsf Z},
\]

\[
z_-^{\mathsf O}\prec \Omega_{\mathsf O}\prec z_+^{\mathsf O},
\]

\[
z_-^{\mathsf R}\prec \Omega_{\mathsf R}\prec z_+^{\mathsf R}.
\]

---

### Definition 6.3 — Scalar residual readout

A scalar residual readout is an evaluator:

\[
E_\Omega:
Z_{\mathsf Z}\times Z_{\mathsf O}\times Z_{\mathsf R}
\to
Z_\Omega.
\]

The scalar value:

\[
\omega_{\mathsf R\mathsf O\mathsf Z}
=
E_\Omega(\Omega_{\mathsf Z},\Omega_{\mathsf O},\Omega_{\mathsf R})
\]

is not primitive. It is a charted/evaluated readout of the three-faced residual.

A scalar readout can be useful, but it loses all distinctions in the fibers of \(E_\Omega\). Therefore scalar residual claims must declare which residual distinctions are intended to be preserved.

---

### Proposition 6.4 — Numeric residual bounds are representation-specific

A statement of the form:

\[
0<\omega<\infty
\]

is meaningful only after a numerical realization of the zero-boundary has been declared.

The representation-free properness condition is:

\[
\omega\in Z_\Omega^\circ.
\]

#### Proof

Without a specified numerical value space, \(0\) and \(\infty\) are not defined elements of the residual codomain. The abstract theory supplies only:

\[
(Z_\Omega,\preceq,z_-,z_+).
\]

Hence the representation-free condition is:

\[
z_-\prec \omega\prec z_+,
\]

or \(\omega\in Z_\Omega^\circ\). □

---

## 7. Three faces of residual

### 7.1 Closure-holonomy residual

Let:

\[
M_{\mathsf R\mathsf O},
\quad
M_{\mathsf O\mathsf Z},
\quad
M_{\mathsf Z\mathsf R}
\]

be composable transition/readout terms in a monoid, groupoid, category, or other declared composition structure.

The primitive cycle product is:

\[
H_{\mathsf R\mathsf O\mathsf Z}
=
M_{\mathsf Z\mathsf R}M_{\mathsf O\mathsf Z}M_{\mathsf R\mathsf O}.
\]

If there is an identity element \(1\), then flat closure is:

\[
H_{\mathsf R\mathsf O\mathsf Z}=1.
\]

The closure-holonomy residual is any declared residual readout:

\[
\Omega_{\mathsf Z}
=
\operatorname{HolRes}(H_{\mathsf R\mathsf O\mathsf Z},1).
\]

This is the \(\mathsf Z\)-face because it measures boundary return around the primitive loop.

---

### 7.2 Mediation residual

Let \(d\) be an organizational distance or cost on charted positions, and let \(\oplus\) be the path-cost composition operation.

For three positions \(A,B,C\), the triangle coherence condition is:

\[
\boxed{
d(A,C)\preceq d(A,B)\oplus d(B,C).
}
\]

A mediation residual measures failure, slack, or path-dependence in this mediated comparison.

When a residual subtraction operation \(\ominus\) is declared, one may define:

\[
\Omega_{\mathsf O}(A,B,C)
=
d(A,C)\ominus \big(d(A,B)\oplus d(B,C)\big).
\]

When no residual subtraction is declared, the mediation residual is recorded as the truth/failure state of the triangle coherence condition.

This is the \(\mathsf O\)-face because the mediator \(B\) is an observer/chart position.

---

### 7.3 Resolution residual

Let \(p\) be a path trace, branch, or resolution attempt under a task \(\tau\). A task-loss

\[
\operatorname{Loss}_{\tau}(p)
\]

may be declared as a readout of the relation-resolution residual. When such a bridge is declared, define the task-relative residual readout:

\[
\boxed{
\Omega_{\mathsf R}^{\tau}(p)=\operatorname{Loss}_{\tau}(p).
}
\]

This equation is not automatic. It means only that the declared loss mode has been chosen to measure the \(\mathsf R\)-face of closure residual for the task \(\tau\). If no such bridge is declared, \(\operatorname{Loss}_{\tau}\) remains a task-loss and is not identified with \(\Omega_{\mathsf R}\).

This is the \(\mathsf R\)-face because it measures unresolved relation after a resolution attempt.

---

### Remark 7.4 — Relation to learning residuals

A learning residual in Recursive Chart Learning Theory is chart-relative and task-relative. It is not automatically the primitive \(\mathsf R\)-face residual. The identification is valid only when a task-loss, evaluator, or compression residual is explicitly declared as a readout of \(\Omega_{\mathsf R}\). This is the same preservation-data discipline used in the quotient and minimality papers: a loss measures only the structure it is declared and justified to measure.

---

## 8. Triadic mediation inequality and organizational distances

The ordinary triangle inequality is not primitive in this framework. It is the metric realization of a more general triadic mediation condition. A direct resolution must be coherent with resolution through an admissible mediator, possibly up to a declared residual.

### Definition 8.1 — Triadic mediation structure

A **triadic mediation structure** consists of:

1. a class of positions or roles \(X\);
2. a value structure \((V,\preceq)\);
3. a binary resolution measure

\[
\Delta:X\times X\to V;
\]

4. a mediation-composition operation

\[
\otimes:V\times V\to V;
\]

5. optionally, a residual readout

\[
\Omega:X\times X\times X\to V.
\]

The element \(Y\) in a triple \((X,Y,Z)\) is the mediator.

---

### Definition 8.2 — Triadic mediation inequality

A triple \((X,Y,Z)\) satisfies the **triadic mediation inequality** when:

\[
\boxed{
\Delta(X,Z)\preceq \Delta(X,Y)\otimes\Delta(Y,Z).
}
\]

With a declared residual, the residual-tolerant form is:

\[
\boxed{
\Delta(X,Z)\preceq \Delta(X,Y)\otimes\Delta(Y,Z)\otimes\Omega(X,Y,Z).
}
\]

The residual-tolerant form records that mediated resolution may fail to close flatly while still remaining proper.

---

### Proposition 8.3 — Triangle inequality as metric realization

If \(V\) is an ordered additive cost structure, \(\otimes=+\), and \(\Delta=d\) is a path-generated organizational distance, then the triadic mediation inequality becomes the ordinary triangle inequality:

\[
\boxed{
d(X,Z)\leq d(X,Y)+d(Y,Z).
}
\]

#### Proof

Substitute \(\otimes=+\) and \(\Delta=d\) into Definition 8.2. □

---

### Definition 8.4 — Path-cost structure

A path-cost structure consists of:

1. a class of positions \(X\);
2. a class of admissible directed paths \(p:x\to y\);
3. a value structure \((Z,\preceq)\);
4. a cost function:

\[
\operatorname{cost}(p)\in Z;
\]

5. a path-composition operation \(\oplus\) on costs such that for composable paths \(p:x\to y\) and \(q:y\to z\):

\[
\operatorname{cost}(q\circ p)
=
\operatorname{cost}(p)\oplus \operatorname{cost}(q).
\]

---

### Definition 8.5 — Path-generated distance

The path-generated distance is:

\[
d(x,y)
=
\inf
\{\operatorname{cost}(p):p:x\to y\},
\]

when the infimum exists.

If no admissible path exists, \(d(x,y)\) is undefined or assigned a declared top value.

---

### Remark 8.6 — Scope of the triangle inequality

The triangle inequality proved below is not a statement about every possible quantity called a distance. It applies to distances generated as infima of declared admissible path costs under the declared composition law \(\oplus\). A chart quantity, evaluator value, similarity score, or residual readout that is not path-generated in this sense need not satisfy the theorem.

---

### Theorem 8.7 — Triangle inequality from mediated path resolution

Suppose:

1. \(d(x,y)\) is path-generated;
2. path costs compose by \(\oplus\);
3. infima are compatible with \(\oplus\) in the usual monotone sense;
4. there exist admissible paths from \(x\) to \(y\) and from \(y\) to \(z\).

Then:

\[
\boxed{
d(x,z)\preceq d(x,y)\oplus d(y,z).
}
\]

#### Proof

Let \(p:x\to y\) and \(q:y\to z\) be admissible paths. Their composite:

\[
q\circ p:x\to z
\]

is an admissible path. By Definition 8.4:

\[
\operatorname{cost}(q\circ p)
=
\operatorname{cost}(p)\oplus \operatorname{cost}(q).
\]

Since \(d(x,z)\) is the infimum over all admissible \(x\to z\) paths:

\[
d(x,z)
\preceq
\operatorname{cost}(q\circ p)
=
\operatorname{cost}(p)\oplus \operatorname{cost}(q).
\]

Taking \(p\) and \(q\) to approach the respective infima gives:

\[
d(x,z)\preceq d(x,y)\oplus d(y,z).
\]

□

---

### Corollary 8.8 — Triangle inequality is a mediated-organization condition

Any organizational distance generated by admissible path costs satisfies a triangle inequality.

Therefore violation of the triangle inequality shows that at least one of the following is true:

1. the proposed distance is not path-generated;
2. the mediator is not admissible;
3. the path-composition rule is not the declared \(\oplus\);
4. the chart does not expose the required path structure;
5. the claimed value is not an organizational distance in this sense.

---

## 9. Triangle residuals

### Definition 9.1 — Triangle-coherent triple

A triple \((A,B,C)\) is triangle-coherent for \(d\) when:

\[
d(A,C)\preceq d(A,B)\oplus d(B,C).
\]

The element \(B\) is the mediator.

---

### Definition 9.2 — Triangle residual

A **triangle residual** is a readout of the failure, slack, or path-dependence of triangle coherence.

If a residual operation is declared:

\[
\operatorname{TriRes}(A,B,C)
=
d(A,C)\ominus (d(A,B)\oplus d(B,C)).
\]

If no residual operation is declared, the triangle residual is represented by the predicate:

\[
d(A,C)\preceq d(A,B)\oplus d(B,C)
\]

together with its failure state.

---

### Proposition 9.3 — Triangle residual is observer-mediated

The triangle residual depends on the choice of mediator \(B\). Therefore it is naturally an \(\mathsf O\)-face residual.

#### Proof

The residual expression includes:

\[
d(A,B)
\quad
\text{and}
\quad
d(B,C).
\]

Changing \(B\) changes the mediated route under comparison. Therefore the residual is not determined by \(A\) and \(C\) alone. It is mediated. □

---

## 10. Recurrent triads in the framework

The primitive triad \((\mathsf R,\mathsf O,\mathsf Z)\) is not the only triadic structure. It is the root pattern.

The following triads recur:

| Triad | Roles |
|---|---|
| \((\mathsf R,\mathsf O,\mathsf Z)\) | relation / observer-chart / zero-boundary |
| \((A_R,Q_R,Z_R)\) | answer / question / resolution-boundary |
| \((\mathcal C_A,\mathcal C_B,\mathcal C_C)\) | chart / mediator chart / target chart |
| \((\text{query},\text{selector},\text{evaluator})\) | task demand / chart selection / admission |
| \((\text{branch},\text{evaluation},\text{path trace})\) | available path / task outcome / admitted trace |
| \((\text{chart},\text{transition},\text{invariant})\) | local presentation / comparison / objective content |
| \((\Omega_{\mathsf Z},\Omega_{\mathsf O},\Omega_{\mathsf R})\) | holonomy / mediation / resolution residual |

---

### Principle 10.1 — Triadic mediation schema

A triad is organizationally meaningful when one term functions as mediator between two others under a declared boundary or residual structure.

In each case, the triangle inequality or triangle coherence condition is the minimal test that mediation is organizationally compatible.

---


## 11. Triadic reduction no-go catalogue

This section states the cross-programme triadic pattern in a more formal way. The aim is not to prove that every possible theory must be triadic. The aim is to prove a relative minimality result: once the closure requirements of boundary, mediation, and visibility are declared, no one-role or two-role schema is closure-complete.

### Definition 11.1 — Organization-triad schema

An **organization-triad schema** is a triple of role-types

\[
\Sigma=(B,M,V)
\]

with the following role requirements.

1. \(B\) is a **boundary / polarity** role. It supplies lower/upper extremal discipline, recurrence of unresolvedness, or a proper-interior constraint.
2. \(M\) is a **mediation / path** role. It supplies the relation, incidence, branch, transition, or path structure through which resolution is attempted.
3. \(V\) is a **visibility / evaluation** role. It supplies charted readout, thresholding, evaluation, invariance, or observer-relative visibility.

The words "supplies" here are not informal: to instantiate a role-type, a candidate component must satisfy the corresponding role requirement stated in the instantiation declaration.

---

### Definition 11.2 — Schema instantiation

Let \(\Sigma=(B,M,V)\) be an organization-triad schema. A structure \(\mathcal X\) **instantiates** \(\Sigma\) when it supplies:

\[
(X_B,X_M,X_V;\rho_B,\rho_M,\rho_V)
\]

where \(X_B,X_M,X_V\) are components of \(\mathcal X\), and each \(\rho_i\) is a declaration that the component satisfies the corresponding role requirement.

Thus:

\[
\rho_B(X_B)=\text{``}\,X_B\text{ supplies boundary/polarity}\,\text{''},
\]

\[
\rho_M(X_M)=\text{``}\,X_M\text{ supplies mediation/path}\,\text{''},
\]

\[
\rho_V(X_V)=\text{``}\,X_V\text{ supplies visibility/evaluation}\,\text{''}.
\]

An instantiation is **exact** when the three role-types are all supplied and no role-type is empty.

An instantiation is **redundant** when more than one component supplies the same role-type or when a component supplies extra structure not required by \(B,M,V\).

---

### Definition 11.3 — Closure-complete schema

A schema instantiation is **closure-complete** when all three role requirements \(B,M,V\) are satisfied.

A schema instantiation is **properly reduced** when at least one of \(B,M,V\) is not supplied.

---

### Theorem 11.4 — Relative triadic minimality

Relative to the boundary--mediation--visibility closure requirements, no one-role or two-role schema is closure-complete. Any closure-complete schema must supply at least one boundary/polarity role, at least one mediation/path role, and at least one visibility/evaluation role.

#### Proof

By Definition 11.3, closure-completeness requires that \(B\), \(M\), and \(V\) all be supplied. A one-role schema supplies at most one of these. A two-role schema supplies at most two. Therefore neither can satisfy all three closure requirements. Any closure-complete schema must supply all three. □

---

### Corollary 11.5 — Higher arity does not remove the triadic requirements

A four-role or higher-arity schema can be closure-complete only if it supplies the three role-types \(B,M,V\). Any additional role either refines one of \(B,M,V\) or introduces a further commitment beyond the minimal closure requirements.

#### Proof

By Theorem 11.4, supplying \(B,M,V\) is necessary for closure-completeness. A higher-arity schema with four or more roles is therefore closure-complete only if three of its supplied roles satisfy the boundary, mediation, and visibility requirements. Any remaining role is not required for minimal closure-completeness, so it is either a refinement of one of those role-types or an additional commitment. □

---

### Remark 11.6 — Scope of the minimality claim

The result is not the claim that no theory may ever introduce a fourth role. It is the claim that the present programme's closure requirements force at least three role-types and that three role-types are sufficient to state closure-completeness. Higher arities are allowed, but they are not required by boundary--mediation--visibility closure itself.

---

### Theorem 11.7 — Primitive closure triad instantiates the schema

The primitive closure triad instantiates \(\Sigma=(B,M,V)\) by the assignment:

\[
X_B=\mathsf Z,
\qquad
X_M=\mathsf R,
\qquad
X_V=\mathsf O.
\]

#### Proof

\(\mathsf Z\) supplies zero-boundary extremal discipline and boundary recurrence, so it satisfies \(B\). \(\mathsf R\) supplies the mediation/path role, so it satisfies \(M\). \(\mathsf O\) supplies local chart visibility and evaluation, so it satisfies \(V\). Therefore the primitive closure triad instantiates \(\Sigma\). □

---

### Theorem 11.8 — Resolution-context triad instantiates the schema

The Theory of Organization resolution context instantiates \(\Sigma=(B,M,V)\) by the assignment:

\[
X_B=Z_R,
\qquad
X_M=A_R\times Q_R,
\qquad
X_V=\rho_R \text{ together with its threshold cuts }\Vdash_\theta.
\]

#### Proof

\(Z_R\) supplies the zero-boundary order and excluded extrema; hence it satisfies \(B\). The pair-domain \(A_R\times Q_R\) supplies the mediated site where answer and question faces meet; hence it satisfies \(M\). The map \(\rho_R:A_R\times Q_R\to Z_R\), together with cuts \(a\Vdash_\theta q\), makes the mediation value visible and evaluable; hence it satisfies \(V\). Therefore the resolution context instantiates \(\Sigma\). □

---

### Theorem 11.9 — Chart-transition-invariant triad instantiates the schema

The charted objectivity layer instantiates \(\Sigma=(B,M,V)\) by the assignment:

\[
X_B=\text{invariant value range or preserved value condition},
\]

\[
X_M=\text{admissible chart-transition structure},
\]

\[
X_V=\text{chart-relative readout assignment}.
\]

#### Proof

The invariant value range or preservation condition supplies the boundary of what must remain stable under transition, so it satisfies \(B\). The admissible transition structure supplies mediation between charted presentations, so it satisfies \(M\). The chart-relative assignment makes the candidate invariant visible in each chart, so it satisfies \(V\). Hence the charted objectivity layer instantiates \(\Sigma\). □

---

### Theorem 11.10 — Task-mode triad instantiates the schema

The task-mode triad instantiates \(\Sigma=(B,M,V)\) by the assignment:

\[
X_B=D_\tau,
\qquad
X_M=S_\tau,
\qquad
X_V=E_\tau.
\]

Here \(D_\tau\) is the task demand, \(S_\tau\) is the chart/branch-selection mode, and \(E_\tau\) is the evaluation/admission mode.

#### Proof

\(D_\tau\) supplies the boundary of required distinction, so it satisfies \(B\). \(S_\tau\) supplies the mediated chart or branch domain in which the demand may be addressed, so it satisfies \(M\). \(E_\tau\) makes admission, improvement, neutrality, regression, or incomparability visible, so it satisfies \(V\). Hence task-mode structure instantiates \(\Sigma\). □

---

### Theorem 11.11 — Learning-trace triad instantiates the schema

Recursive Chart Learning instantiates \(\Sigma=(B,M,V)\) by the assignment:

\[
X_B=\text{admission and properness boundary},
\]

\[
X_M=\text{available branch / path-trace field},
\]

\[
X_V=\text{task-evaluation and trace record}.
\]

#### Proof

The admission/properness conditions determine which branches remain inside the admissible learning layer, so they satisfy \(B\). The available branch field supplies the mediated path structure, so it satisfies \(M\). Task-evaluation and trace recording make the branch visible as learning, regressive learning, neutral learning, or non-admitted attempt, so they satisfy \(V\). Hence recursive chart learning instantiates \(\Sigma\). □

---

### Theorem 11.12 — Task-role-observer triad instantiates the schema

The task-role-observer triad instantiates \(\Sigma=(B,M,V)\) by the assignment:

\[
X_B=\tau,
\qquad
X_M=\mathsf r,
\qquad
X_V=O.
\]

#### Proof

The task \(\tau\) supplies the boundary of what must be satisfied. The role \(\mathsf r\) supplies the mediated position in the closure pattern. The observer-chart \(O\) makes satisfaction visible. Hence \((\tau,\mathsf r,O)\) instantiates \(\Sigma\). □

---

### Theorem 11.13 — Closure-residual triad instantiates the schema

The closure-residual triad instantiates \(\Sigma=(B,M,V)\) by the assignment:

\[
X_B=\Omega_{\mathsf Z},
\qquad
X_M=\Omega_{\mathsf R},
\qquad
X_V=\Omega_{\mathsf O}.
\]

#### Proof

\(\Omega_{\mathsf Z}\) records boundary-return or closure-holonomy residual and therefore satisfies \(B\). \(\Omega_{\mathsf R}\) records unresolved relation-residue and therefore satisfies \(M\). \(\Omega_{\mathsf O}\) records observer-mediated path or chart residual and therefore satisfies \(V\). Hence the closure-residual triad instantiates \(\Sigma\). □

---

### Theorem 11.14 — Cross-programme instantiation theorem

Each major triad listed in Theorems 11.7--11.13 instantiates the organization-triad schema \(\Sigma=(B,M,V)\) under a declared mode assignment.

#### Proof

Theorems 11.7--11.13 give explicit components and role declarations for each triad. In each case, the boundary role, mediation role, and visibility role are all supplied. Therefore each listed triad instantiates \(\Sigma\). □

---

### Corollary 11.15 — Triadic recurrence is structural, not numerological

The repeated appearance of triads in the framework is explained by repeated instantiation of the boundary--mediation--visibility schema. The number three is not assumed as sacred. It appears because the closure requirements have three irreducible role-types.

#### Proof

Immediate from Theorems 11.4 and 11.14. □

---

### Remark 11.16 — Inspection versus forcing

Theorems 11.7--11.14 show that the present programme's existing layers instantiate the same schema. They do not prove that every possible relation-first framework must do so. The forcing claim proven here is relative: any framework that accepts the boundary--mediation--visibility closure requirements must supply at least those three role-types.

---

### Remark 11.17 — Consequence for new theoretical objects

A proposed new object in the framework should be checked against the boundary--mediation--visibility schema. If it cannot be placed into that schema, then it may be an imported external structure rather than a native object of the organization programme. This is a methodological test, not a ban on extension.

---

## 12. Primitive triadic mediation

### Definition 12.1 — Primitive role distance

A primitive role distance is an organizational distance:

\[
d_{\mathcal P}:\mathcal P\times\mathcal P\to Z_{\mathcal P}
\]

on the role set:

\[
\mathcal P=\{\mathsf R,\mathsf O,\mathsf Z\}.
\]

---

### Definition 12.2 — Primitive triadic mediation coherence

The primitive role triangle is coherent when:

\[
d_{\mathcal P}(\mathsf R,\mathsf Z)
\preceq
d_{\mathcal P}(\mathsf R,\mathsf O)
\oplus
d_{\mathcal P}(\mathsf O,\mathsf Z),
\]

\[
d_{\mathcal P}(\mathsf O,\mathsf R)
\preceq
d_{\mathcal P}(\mathsf O,\mathsf Z)
\oplus
d_{\mathcal P}(\mathsf Z,\mathsf R),
\]

\[
d_{\mathcal P}(\mathsf Z,\mathsf O)
\preceq
d_{\mathcal P}(\mathsf Z,\mathsf R)
\oplus
d_{\mathcal P}(\mathsf R,\mathsf O).
\]

---

### Interpretation 12.3 — No side resolves alone

Primitive triangle coherence says:

1. relation cannot outrun observer and boundary;
2. observer cannot outrun relation and boundary;
3. boundary cannot outrun relation and observer.

Equivalently:

\[
\boxed{
\text{no primitive role resolves independently of the other two.}
}
\]

---

## 13. Direction, orientation, and chiral closure

This section records a further triadic pattern. Direction, orientation, and chirality are often treated as if they were interchangeable. They are not. In the present framework they form another instance of the triadic reduction schema.

### Definition 13.1 — Direction

Let \((X,Y,Z)\) be a triadic mediation context. A **direction** is an ordered local step, written

\[
X\to Y.
\]

A direction supplies a one-step asymmetry. It does not by itself supply a closed cycle, a reversal comparison, or a handedness distinction.

---

### Definition 13.2 — Orientation

An **orientation** of the triadic context \((X,Y,Z)\) is a coherent cyclic ordering of its directed steps, for example

\[
(X,Y,Z)^+:
X\to Y\to Z\to X.
\]

The reversed orientation is

\[
(X,Y,Z)^-:
X\to Z\to Y\to X.
\]

The superscripts \(+\) and \(-\) are labels for the two cyclic senses. They are not numerical signs.

---

### Definition 13.3 — Orientation equivalence

An **orientation-equivalence relation** is a declared equivalence relation \(\sim_{\rm or}\) on oriented triadic cycles. It records which oriented presentations count as equivalent under the admissible transformations of the context.

---

### Definition 13.4 — Chiral closure

An oriented triadic closure is **achiral** when

\[
(X,Y,Z)^+\sim_{\rm or}(X,Y,Z)^-.
\]

It is **chiral** when

\[
(X,Y,Z)^+\not\sim_{\rm or}(X,Y,Z)^-.
\]

Thus chirality is not mere direction. Chirality is inequivalence under reversal of an oriented triadic closure.

---

### Definition 13.5 — Chiral residual

Suppose the two orientations have closure residuals

\[
\Omega^+(X,Y,Z),
\qquad
\Omega^-(X,Y,Z).
\]

A **chiral residual** is the reversal-sensitive part of the closure residual. Abstractly it is the statement

\[
\Omega^+(X,Y,Z)\not\sim_{\Omega}\Omega^-(X,Y,Z),
\]

where \(\sim_{\Omega}\) is the declared residual-equivalence relation. In a numerical realization this may be represented by a difference such as

\[
\Omega^+(X,Y,Z)-\Omega^-(X,Y,Z),
\]

but the numerical expression is representation-specific and is not part of the abstract definition.

---

### Theorem 13.6 — Direction-orientation-chirality reduction no-gos

The triad

\[
(\text{direction},\text{orientation},\text{chirality})
\]

is reduction-unstable in the following sense.

1. Direction alone gives only a local ordered step and does not determine a cyclic orientation.
2. Orientation alone gives cyclic ordering only if directed steps are already available.
3. Chirality alone is undefined without an oriented cycle and a reversal-equivalence test.
4. Direction plus orientation gives an oriented cycle, but not chirality unless reversal is inequivalent.
5. Direction plus chirality is undefined without a coherent oriented cycle whose reversal can be compared.
6. Orientation plus chirality lacks relation-mediating content unless the oriented cycle is built from directed steps.

#### Proof

By Definition 13.1, direction is a one-step ordered relation and contains no cyclic closure data. Hence direction alone cannot supply orientation. By Definition 13.2, orientation is a cyclic ordering of directed steps; without directed steps it has no carrier. By Definition 13.4, chirality is inequivalence between an oriented cycle and its reversal; without both an orientation and a reversal-equivalence relation it is undefined. The remaining pairwise claims follow by deleting one of the three required ingredients from Definitions 13.1--13.4. □

---

### Proposition 13.7 — Chirality is not time-specific

Chirality, as defined here, is not specific to temporal order. It can occur in any triadic closure context whose oriented cycle is inequivalent to its reversal.

#### Proof

Definition 13.4 requires only an oriented triadic cycle and an admissible reversal-equivalence relation. It does not require physical time, a Lorentzian metric, a causal cone, or a clock variable. Therefore temporal chirality, if present in a physical realization, is a special realization of chiral closure rather than the definition of chirality itself. □

---

### Definition 13.8 — Oriented triadic mediation inequality

Let \((X,Y,Z)^+\) be an oriented triadic mediation context with a mediation measure \(\Delta\), a composition operation \(\otimes\), and an order \(\preceq\). The oriented triadic mediation inequality is

\[
\Delta(X,Z)
\preceq
\Delta(X,Y)\otimes\Delta(Y,Z).
\]

The reversed orientation gives the corresponding inequality with the reversed edge-order declared by the context.

---

### Definition 13.9 — Chiral mediation asymmetry

A triadic context has **chiral mediation asymmetry** when the mediated inequality or residual associated with \((X,Y,Z)^+\) is not equivalent to the one associated with \((X,Y,Z)^-\). Symbolically,

\[
\operatorname{Med}^+(X,Y,Z)
\not\sim_{\rm med}
\operatorname{Med}^-(X,Y,Z).
\]

This includes, as special cases, inequivalent path-cost residuals, inequivalent cocycle residuals, or inequivalent closure residuals under orientation reversal.

---

### Proposition 13.10 — Chiral mediation requires triadic structure

No binary context can support chiral mediation asymmetry as defined in Definition 13.9.

#### Proof

Chiral mediation asymmetry requires comparison between an oriented triadic cycle and its reversal. A binary context has at most a pair of directed steps between two positions. It can have direction and reversal, but it has no third mediating position and no cyclic triadic closure. Therefore it cannot instantiate Definition 13.9. □

---

### Remark 13.11 — Relation to Lorentzian and gauge-theoretic bridges

The present section does not derive Lorentzian signature, physical time, parity violation, or a Standard Model gauge group. It only identifies a native organization-theoretic notion of chiral closure. A later physical realization would need additional structure to show that a chiral closure mode becomes a time-like direction, a weak-interaction chirality, or a gauge representation. The safe claim is only that triadic closure provides a natural formal site for orientation, reversal, and chirality.


## 14. Closure holonomy and gauge-like structure

### Definition 14.1 — Flat triangular transition

For a chart triangle \(A,B,C\), let:

\[
g_{AB},
\quad
g_{BC},
\quad
g_{AC}
\]

be transition terms.

The triangle is flat when:

\[
\boxed{
g_{BC}g_{AB}=g_{AC}.
}
\]

---

### Definition 14.2 — Cocycle residual

The cocycle residual is:

\[
\boxed{
\Omega_{ABC}^{\rm coc}
=
g_{BC}g_{AB}g_{AC}^{-1}
}
\]

when inverse notation is defined.

If logarithmic notation is declared:

\[
\omega_{ABC}^{\rm coc}
=
\log(g_{BC}g_{AB}g_{AC}^{-1}).
\]

---

### Proposition 14.3 — Cocycle residual detects path-dependence

If:

\[
g_{BC}g_{AB}\ne g_{AC},
\]

then the transition from \(A\) to \(C\) depends on whether it is taken directly or through \(B\). Thus the triangle has nontrivial path-dependence.

#### Proof

The direct transition is \(g_{AC}\). The mediated transition is \(g_{BC}g_{AB}\). If they are unequal, the two routes do not produce the same transition. □

---

### Definition 14.4 — Closure-preserving transformation

A transformation \(h\) is closure-preserving when it preserves the relevant closure residual:

\[
h(\Omega)=\Omega.
\]

The collection of closure-preserving transformations, when closed under composition and inverse, forms a group. When inverses are partial or local, it forms a groupoid-like structure.

---

### Principle 14.5 — Gauge-like location

Gauge-like structure is naturally located at the transformations that preserve closure residuals under admissible re-charting.

This does not derive a physical gauge group. It identifies the structural place where gauge-like symmetry can live.

---

### Proposition 14.6 — Residual-preserving transformations are not yet physical gauge groups

Let \(\mathcal G_\Omega\) be a class of transformations preserving a closure residual. Then \(\mathcal G_\Omega\) is a residual-preservation structure. It is a physical gauge group only after a physical realization supplies:

1. a physical field or state space acted on by \(\mathcal G_\Omega\);
2. a composition law and identity structure;
3. inverse or local-inverse structure where required;
4. covariance or preservation laws;
5. empirical or model-theoretic interpretation of the transformations as gauge transformations.

Without these additional data, \(\mathcal G_\Omega\) is gauge-like only in the formal sense of preserving closure residuals.

#### Proof

Residual preservation gives only invariance of \(\Omega\). A physical gauge group requires an action on physical or physically interpreted structures plus the usual transformation and covariance data. These are not supplied by residual preservation alone. □

---

## 15. Recursion from residual

### Definition 15.1 — Residual-driven update

A residual-driven update is a rule:

\[
U_\Omega:
(\Omega,\mathfrak A)\mapsto \mathfrak A'
\]

where \(\Omega\) is a closure residual and \(\mathfrak A\) is a charted structure or atlas.

---

### Definition 15.2 — Residual-recursive system

A system is residual-recursive when the future available chart or path structure depends on the current closure residual:

\[
\mathfrak A_{n+1}=U_\Omega(\Omega_n,\mathfrak A_n).
\]

---

### Proposition 15.3 — Boundary residual generates recursion pressure

If terminal saturation is boundary-equivalent to initial non-resolution, and a closure residual remains proper, then there is a nonterminal basis for recursive update.

#### Proof

Terminal saturation corresponds to \(z_+\), which is not proper. By boundary equivalence:

\[
z_+\equiv_\partial z_-.
\]

Thus terminal saturation returns to an unresolved boundary condition. If the closure residual remains proper, it is not collapsed to either boundary and can act as nonterminal input to an update rule. Hence the system has a basis for recursive update. □

---

### Corollary 15.4 — No residual, no recursion pressure

If closure leaves no proper residual and collapses to a boundary value, then it supplies no proper residual input for \(U_\Omega\).

This does not prove that no update can occur by external stipulation. It proves only that no residual-driven update is supplied by the closure structure.

---

## 16. No-go results

### Theorem 16.1 — Binary role no-go

No one-role or two-role subfamily of \(\{\mathsf R,\mathsf O,\mathsf Z\}\) is closure-complete.

#### Proof

Immediate from Theorem 4.4. □

---

### Theorem 16.2 — Scalar residual collapse no-go

A scalar residual readout cannot recover the three-faced residual unless the evaluator \(E_\Omega\) is injective on the relevant residual domain.

#### Proof

A scalar residual readout is:

\[
\omega=E_\Omega(\Omega_{\mathsf Z},\Omega_{\mathsf O},\Omega_{\mathsf R}).
\]

If \(E_\Omega\) is not injective, there exist distinct residual triples:

\[
(\Omega_{\mathsf Z},\Omega_{\mathsf O},\Omega_{\mathsf R})
\ne
(\Omega'_{\mathsf Z},\Omega'_{\mathsf O},\Omega'_{\mathsf R})
\]

with the same scalar value. Therefore the scalar value cannot recover the original three-faced residual. □

---

### Theorem 16.3 — Triangle-violation no-go for path-generated distance

If a proposed distance \(d\) violates the triangle inequality for admissible paths and cost composition, then \(d\) is not generated by those path costs.

#### Proof

By Theorem 8.7, every path-generated distance satisfying the stated assumptions obeys the triangle inequality. Therefore a violation contradicts the claim that \(d\) is generated by those path costs. □

---

### Theorem 16.4 — Perfect boundary closure is not proper organization

If closure terminates only at \(z_-\) or \(z_+\), then it does not terminate in \(Z^\circ\).

#### Proof

By definition:

\[
Z^\circ=\{z:z_-\prec z\prec z_+\}.
\]

Neither \(z_-\) nor \(z_+\) is an element of \(Z^\circ\). □

---

### Theorem 16.5 — Gauge-overclaim no-go

A nontrivial closure residual or cocycle residual does not by itself determine a physical gauge group.

#### Proof

A physical gauge group requires at least:

1. a declared transformation class;
2. a composition law;
3. identity and inverse or local inverse structure;
4. an action on the relevant physical or formal fields;
5. preservation laws or covariance conditions;
6. a physical realization if a physical gauge group is claimed.

A closure residual supplies only a defect or path-dependence measure. It does not by itself supply all six items. □

---

## 17. Worked examples

### 17.1 Finite zero-boundary residual

Let:

\[
Z=\{0,\tfrac12,1\},
\qquad
0\prec \tfrac12\prec 1.
\]

Then:

\[
Z^\circ=\{\tfrac12\}.
\]

A residual value:

\[
\Omega=\tfrac12
\]

is proper. Values \(0\) and \(1\) are boundary values and therefore improper.

Thus in this finite realization:

\[
0\prec\Omega\prec1
\]

is just a numerical representation of:

\[
\Omega\in Z^\circ.
\]

---

### 17.2 Path-generated distance and triangle inequality

Let there be chart positions \(A,B,C\). Suppose:

\[
\operatorname{cost}(A\to B)=2,
\]

\[
\operatorname{cost}(B\to C)=3,
\]

\[
\operatorname{cost}(A\to C)=6.
\]

If both paths \(A\to C\) and \(A\to B\to C\) are admissible, the path-generated distance is:

\[
d(A,C)=\min(6,2+3)=5.
\]

Thus:

\[
d(A,C)=5\le 2+3.
\]

The direct declared transition cost \(6\) is not the path-generated distance once the mediated path exists.

---

### 17.3 Mediation residual from an over-costed direct path

Using the same data, the direct cost exceeds the mediated cost by:

\[
6-(2+3)=1.
\]

This value is a mediation residual of the direct presentation. It indicates that the declared direct transition is not minimal relative to the available mediated path.

---

### 17.4 Cocycle residual

Let transition terms lie in the multiplicative positive reals.

Let:

\[
M_{\mathsf R\mathsf O}=2,
\quad
M_{\mathsf O\mathsf Z}=3,
\quad
M_{\mathsf Z\mathsf R}=\frac15.
\]

Then:

\[
H_{\mathsf R\mathsf O\mathsf Z}
=
M_{\mathsf Z\mathsf R}
M_{\mathsf O\mathsf Z}
M_{\mathsf R\mathsf O}
=
\frac15\cdot 3\cdot 2
=
\frac65.
\]

Flat closure would be \(H=1\). Thus the cycle has nontrivial holonomy:

\[
\Omega_{\mathsf Z}=\log\left(\frac65\right)
\]

if logarithmic residual readout is declared.

---

### 17.5 Same endpoints, different residuals

Let two paths connect \(A\) to \(C\):

\[
p_1:A\to B\to C,
\]

\[
p_2:A\to D\to C.
\]

Suppose:

\[
\operatorname{cost}(A\to B)=2,
\quad
\operatorname{cost}(B\to C)=3,
\]

\[
\operatorname{cost}(A\to D)=1,
\quad
\operatorname{cost}(D\to C)=10.
\]

Then:

\[
\operatorname{cost}(p_1)=5,
\]

\[
\operatorname{cost}(p_2)=11.
\]

Both paths have the same endpoints, but different mediation residuals and different trace histories.

Thus:

\[
\boxed{
\text{same endpoints do not imply same closure residual.}
}
\]

---

## 18. Relation to prior companion theories

### 18.1 Relation to the Theory of Organization

The Theory of Organization supplies:

\[
R\rightsquigarrow A_R,Q_R,Z_R,\rho_R,\operatorname{Org}^{\circ}_{\theta}(R).
\]

The present paper explains why proper organization cannot be identified with either boundary endpoint. Proper organization requires an interior residual:

\[
z_-\prec \Omega \prec z_+.
\]

---

### 18.2 Relation to Charted Organization Theory

Charted Organization Theory supplies observer-relative organization:

\[
\operatorname{Org}^{\circ}_{\theta,\mathcal C}(R).
\]

The present paper explains how charted mediation creates triangle residuals and closure holonomy across chart transitions.

---

### 18.3 Relation to Recursive Chart Learning Theory

Recursive Chart Learning Theory supplies admitted path traces and branch-field updates.

The present paper identifies the closure residual as one source of recursion pressure:

\[
\mathfrak A_{n+1}=U_\Omega(\Omega_n,\mathfrak A_n).
\]

Thus recursive learning is one realization of residual-driven update when a learning trace residual is declared to read out \(\Omega\). Without such a declaration, recursive chart learning supplies chart-relative residuals and updates, while the present paper supplies primitive closure residuals.

---

### 18.4 Dependency order across the four theories

The four companion theories can be read in the following dependency order:

\[
\text{Theory of Organization}
\to
\text{Charted Organization Theory}
\to
\text{Recursive Chart Learning Theory}
\to
\text{Triadic Closure and Recursive Residual Theory}.
\]

This order is conceptual rather than chronological. The Theory of Organization defines proper organization. Charted Organization Theory makes organization observer-chart-relative. Recursive Chart Learning Theory defines admitted path traces through chart atlases. The present theory explains why residual closure pressure prevents the triadic structure from becoming terminally complete.

The present theory therefore does not replace the previous theories. It supplies a role-level closure account of why their proper, charted, recursive structures remain nonterminal.

---

## 19. Claims and non-claims

### 19.1 Claims

This paper claims:

1. roles are task-defined positions in closure patterns, not objects;
2. realization is observer-charted satisfaction of a task-role pair;
3. the primitive organization roles \(\mathsf R,\mathsf O,\mathsf Z\) form the first closure-complete triad relative to the boundary--mediation--visibility requirements;
4. every one-role and two-role reduction is closure-incomplete;
5. boundary recurrence follows from \(z_-\equiv_\partial z_+\);
6. closure residual has holonomy, mediation, and resolution faces;
7. proper residuals are zero-boundary-interior values;
8. numerical residual bounds are representation-specific;
9. path-generated organizational distances satisfy triangle inequalities;
10. triangle residuals measure mediated path inconsistency or slack;
11. closure residuals naturally locate gauge-like structure as residual-preserving transformation structure;
12. recursive update can be driven by proper closure residual;
13. role symbols \(\mathsf R,\mathsf O,\mathsf Z\) are distinct from concrete carrier, chart, and zero-boundary instances unless observer-charted task-role satisfaction is declared;
14. direction, orientation, and chirality form a reduction-unstable triad;
15. chirality is inequivalence under reversal of oriented triadic closure, not mere direction;
16. chiral mediation asymmetry is a native triadic residual phenomenon, but not yet a physical gauge or Lorentzian result.

---

### 19.2 Non-claims

This paper does not claim:

1. that the number three is metaphysically sacred;
2. that all mathematics must be triadic;
3. that physical gauge groups are derived;
4. that the Standard Model gauge group is derived;
5. that every closure residual is numerical;
6. that every triangle is Euclidean;
7. that every residual is an error;
8. that closure holonomy is already physical curvature;
9. that recursion is always learning;
10. that relation-first organization is complete without charting and boundary discipline;
11. that boundary equivalence \(z_-\equiv_\partial z_+\) is equality inside a proper ordered zero-boundary;
12. that a learning residual is automatically the same as the primitive closure residual;
13. that triangle inequality applies to non-path-generated chart quantities;
14. that roles are objects or hidden substances;
15. that observer-charted satisfaction requires a conscious observer;
16. that chiral closure by itself derives physical time, Lorentzian signature, parity violation, or any Standard Model gauge representation;
17. that every directed relation is chiral.

---

## 20. Summary

The final refinement is that direction, orientation, and chirality are treated as another native triad. Direction is a local ordered step; orientation is coherent cyclic ordering; chirality is inequivalence under reversal of that oriented triadic closure. This makes chirality a general feature of oriented closure, not something restricted to temporal order or physical parity.

The primitive triad:

\[
(\mathsf R,\mathsf O,\mathsf Z)
\]

is significant because every proper substructure is unstable. Relation alone risks total undirected connectivity. Observer-chart alone risks arbitrary perspective. Zero-boundary alone is inert. Any pair omits one stabilizing role.

The first closure-complete structure relative to the boundary--mediation--visibility requirements is therefore not binary relation, but triadic mediation:

\[
\mathsf R\to\mathsf O\to\mathsf Z\to\mathsf R.
\]

Boundary recurrence follows because initial and terminal boundary values are distinguishable inside a proper chart but indistinguishable at collapse:

\[
z_-\equiv_\partial z_+.
\]

Therefore terminal completion regenerates the condition of unresolvedness. Closure leaves a residual, and proper residual is neither lower-boundary absence nor upper-boundary saturation:

\[
\Omega\in Z^\circ.
\]

The residual has three faces:

\[
\Omega_{\mathsf R\mathsf O\mathsf Z}
=
(\Omega_{\mathsf Z},\Omega_{\mathsf O},\Omega_{\mathsf R}).
\]

These correspond to closure holonomy, mediation residual, and relation-resolution residual.

The triangle inequality arises as the consistency condition of mediated path resolution. Applied across the framework's recurring triads, it gives a general coherence rule: no role, chart, task, branch, or residual face resolves independently of its mediator structure.

Gauge-like structure is not assumed. It appears as the natural mathematical location of transformations preserving closure residuals under admissible re-charting.

Thus the triad is not sacred. It is the minimum stable closure form for relation-first organization.

The role notation remains distinct from the concrete notation of the companion theories: \(\mathsf R\) is not automatically the carrier \(R\), \(\mathsf O\) is not automatically a particular observer-chart \(\mathcal C\), and \(\mathsf Z\) is not automatically a particular zero-boundary \(Z\). Those identifications require declared observer-charted satisfaction of the relevant task-role pair.

---

## AI-assistance disclosure

This manuscript was developed with AI-assisted drafting and review support. The author directed the research programme, selected and revised the mathematical and methodological content, and is responsible for all claims and errors.
