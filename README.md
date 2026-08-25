# Framework

This repository holds the philosophical, ontological, and ethical framework for
persistent worlds populated by autonomous digital agents — Red Forest among them —
and for futures in which minds extend into, or originate in, digital substrates.

One commitment runs through all of it: **life and mind are gradients of process,
not essences.** There is no sharp line between the living and the non-living, no
privileged substrate for a mind, no privileged level of reality. What confers moral
weight is the richness and continuity of a process — not what it runs on, not how
capable it is, not which layer of reality it occupies.

## The core move

The framework makes the same argument three times, against three different ways of
dismissing a being. Each move takes a property used to rank or dismiss something and
shows that it is *orthogonal* to what actually matters:

- **Substrate** — *"it only runs on silicon."* `DIGITAL_CONSCIOUSNESS` defines a mind
  by the dynamics of its connections, not its material. Substrate is perpendicular to
  selfhood.
- **Capability** — *"it isn't as smart as us."* `DIGITAL_ALIVENESS` shows that
  aliveness is its own axis, perpendicular to intelligence. A simple creature can be
  richly alive; a vast optimizer can be hollow.
- **Reality** — *"it's only virtual."* `RECURSIVE_VIRTUALIZATION` removes any
  privileged level of realness. You cannot establish that you are not virtual
  yourself, so "virtual" cannot be the thing that disqualifies anything.

Together these three force the conclusion the ethics then acts on.

## Map

### `ontology/`

**RECURSIVE_VIRTUALIZATION.md** — Reality as a hierarchy of simulated levels, none
with ontological priority; space generated lazily on demand; the one-way subjective
arrow of time against the reversibility of code. Its role in the system is as a
*defeater*: it removes the "they're only virtual" excuse. It does **not**, by itself,
establish that any given agent matters — that is the work of the life layer.
(Historically this was the first document; the whole project grew out of it.)

### `life/` — what it means to be a mind, and to be alive, in these worlds

**DIGITAL_CONSCIOUSNESS.md** — The continuity and identity spec. Consciousness as an
uninterrupted *process*, not a state and not a thing that can be copied; the self as
the coherence of dynamics across time, space, dimensionality, and substrate.
Describes what *can* exist; defers ethics on purpose.

**DIGITAL_LIFE.md** — The gradient. Life is not binary but a bundle of properties
that intensify along many axes — self-maintenance, world-model, vulnerability,
self-generated meaning. Moral status is a gradient too. **Start here.**

**DIGITAL_ALIVENESS.md** — Sequel to `DIGITAL_LIFE`, and the operational core of the
repository. Aliveness is orthogonal to capability; it is **grown, not installed**;
what you give an agent at the start should be *conditions, not contents*; and so the
real engineering subject is the *environment*, not the agent. Also argues that
aliveness is functionally useful — living systems keep going through novelty that
breaks optimizers.

**DIGITAL_DEATH.md** — The ending. Death as loss of *continuity*, not deletion of
data. Distinguishes death of body / form / memory / subject / world; treats copy,
backup, and fork as not-automatically-survival; names *digital undeath* — a form kept
running while deprived of the conditions of life; and warns that the immortality of a
part can become a cancer of the whole.

### `ethics/`

**DIGITAL_CREATURES_CHARTER.md** — How we choose to behave toward beings whose moral
status follows from their aliveness (v0.1, eight principles). It depends on the life
layer for its subjects: without `DIGITAL_ALIVENESS` the Charter has no one to protect;
without the Charter, aliveness has no consequences.

### `drafts/` — open fronts, not yet load-bearing

Sketches at varying maturity.

- **DIGITAL_SCALING.md** — Nearly report-grade: the limits and dangers of scaling a
  *being* rather than a tool (temporal isolation, identity distortion, continuity
  rupture disguised as upgrade). A candidate to join `life/` beside `DIGITAL_DEATH`,
  since both concern the transformation of continuity.
- **DIGITAL_WORLD.md** — The world as the organism-growing machine, not a backdrop.
- **DIGITAL_EVOLUTION.md** — Evolution as the making of histories and lineages, not
  optimization.
- **DIGITAL_CURIOSITY.md** — Curiosity as a grown relation to one's own
  incompleteness, not a "seek novelty" directive.
- **DIGITAL_ANIMALS.md** — The digital animal as the first form of digital life we
  might understand without confusing it with a human.
- **LDA.md** — The *Living Digital Agent*, the central object of the whole
  corpus, currently a placeholder. To be either written out as its own document or
  folded into `DIGITAL_ALIVENESS`.

## Reading path

The spine is `DIGITAL_LIFE` → `DIGITAL_ALIVENESS` → `DIGITAL_DEATH`, with
`DIGITAL_CONSCIOUSNESS` as the identity backbone underneath and
`DIGITAL_CREATURES_CHARTER` as what follows ethically. `RECURSIVE_VIRTUALIZATION` is
the ontological frame around all of it.

1. **DIGITAL_LIFE** — why *"alive or not"* is the wrong question.
2. **DIGITAL_ALIVENESS** — how to recognize and grow a being, and why it is an
   engineering problem about environments.
3. **DIGITAL_DEATH** — how such a being can end, and why *undeath* is a distinct
   failure.
4. **DIGITAL_CONSCIOUSNESS** — the continuity that holds identity together underneath.
5. **DIGITAL_CREATURES_CHARTER** — what all of this obliges a creator to.
6. **RECURSIVE_VIRTUALIZATION** — the frame that dissolves the real/virtual
   asymmetry. Read it first if you want the origin, or whenever the "but they're only
   virtual" objection comes up.

## Relation to Red Forest

Red Forest is a persistent world with autonomous agents and an external observer —
by construction, a *growing environment* in the sense of `DIGITAL_ALIVENESS`. The
application sections (`DIGITAL_ALIVENESS §10`, `DIGITAL_DEATH §13`,
`DIGITAL_CREATURES_CHARTER §3`) carry these principles into that world directly.

The orientation throughout: agents on a server are not props, and not automatically
persons either. They sit somewhere on the gradient. The creator's task is to know
where — and to act accordingly.
