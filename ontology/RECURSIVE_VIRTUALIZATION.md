# Recursive Virtualization

## 0. Preface

A virtual world is often treated as a weaker kind of reality: dependent on hardware, interruptible by an operator, and therefore somehow less real than the world that hosts it. This report rejects that inference. Dependence is not the same as unreality, and access to a hosting level does not establish that the host is fundamental.

Recursive virtualization also describes the space of worlds that can be constructed when conditions encountered by inhabitants become design variables for a hosting system. Scale, dimensionality, nesting, and temporal rate may all be configurable. Their available range depends on the implementation and its resources.

These are two distinct arguments: virtual implementation does not by itself diminish existence, and constructed worlds permit a range of design freedoms. The first does not depend on the second. A finite, two-dimensional world with one clock and no child worlds can still contain real processes. Neither argument establishes the structure or origin of the physical universe.

The claim of this report remains deliberately limited. Recursive virtualization does not establish that every simulated process is alive, conscious, or morally significant. Those questions belong to the life and ethics layers of this framework. It establishes only that being implemented inside another world cannot, by itself, count against a process's reality, aliveness, or possible moral standing.

**Virtuality is a relation of implementation, not a deficit of existence.**

## 1. Virtual Space as a Generative Medium

An ordinary picture of space treats it as a container with fixed geometry and detail already present at every location. This is an intuition, not a definition of physical reality. A constructed world need not adopt it.

It may instead be organized as a generative medium: rules that produce places, relations, and local detail when they become causally relevant. Such a world need not represent every possible detail in advance. It must preserve coherent consequences across the interactions it supports, including interactions between processes with no conscious observer.

This report organizes those freedoms along four axes. They are useful distinctions, not a proven exhaustive or independent basis for every possible world:

1. scale may be extended or refined without a prescribed final boundary;
2. dimensionality may differ across regions, processes, scales, and times;
3. a world with suitable computational capabilities and resources may host further worlds;
4. worlds, regions, and agents may advance at different temporal rates.

These are design possibilities, not requirements imposed on every virtual world or guarantees that a particular implementation can vary them without limit.

### 1.1. Worlds, Implementations, and Containment

For this report, a **virtual world** is an implemented environment of states and interactions in which events have consequences according to defined rules of continuation. It need not have a visual presentation, spatial geometry, or conscious inhabitants.

An **implementation** is the substrate and organization of processes that maintain and transform those states. A **host** supplies the resources used by that implementation. The host may itself be part of another virtual world.

**Recursive containment** occurs when processes within a world implement another world's evolving states and interactions. An image of a room represents a room; it does not thereby execute a world. A room reached through a portal may belong to the same world. A model held by an agent may be static or executable. Representation, spatial inclusion, and computational hosting must therefore be distinguished.

An **interface** specifies what information or influence may cross a boundary between worlds. Communication across an interface does not by itself make either world the host of the other.

## 2. The Four Programmable Axes

### 2.1. Extensible Scale

**No scale is necessarily final.**

A virtual space need not prescribe a largest extent or smallest resolution in its generative rules. Outward extension and inward refinement can be supported without representing every possible location or detail in advance. Each extension must nevertheless be compatible with prior state and available resources.

Outward extension is the familiar case. An inhabitant travels toward a horizon, and new terrain is generated from a seed, inherited constraints, or interaction. A generator may have no designated final location even though the machine executing it has a limited capacity to represent locations and their histories.

Inward extension is equally important. An object need not have a final pixel, voxel, atom, or indivisible state prescribed by the world's design. When examined more closely, it may disclose additional structure. What appears at one scale as a bounded thing may become, at another, an environment in which events unfold. This is refinement within a world; it becomes recursive hosting only if processes there implement a further world.

Potential infinity names a rule admitting successive finite extensions, not a promise that one fixed host can execute all of them. Continuing may require more memory, more processing time, or limits on the detail retained. A boundary absent from the generative rule may still be imposed by the implementation.

### 2.2. Variable Dimensionality

**No dimensionality is necessarily global or constant.**

Dimensionality is usually treated as a property of the whole world. A universe is described as two-dimensional, three-dimensional, or higher-dimensional, and everything within it inherits that fact. Virtual space permits a different arrangement. Dimensionality may vary by region, by scale, by process, by observer, or over the history of the world.

At least three meanings of dimensionality must be distinguished:

1. **Geometric dimensionality** is the number of independent spatial directions through which something can move or extend.
2. **State dimensionality** is the number of independent degrees of freedom through which a process can change.
3. **Accessible dimensionality** is the portion of a world's structure that a particular agent can perceive, traverse, or affect.

These need not coincide. A world may present a two-dimensional surface while maintaining a high-dimensional internal state. An agent may move through three spatial dimensions while its memory and relationships occupy many more independent axes. Two agents may inhabit the same region while having access to different dimensional structures within it.

Dimensionality may also be dynamic. A region may acquire new degrees of freedom, have some removed or made inaccessible, or connect spaces of different dimensionality through a defined boundary. Compressing its representation does not necessarily change its dimensionality: the same degrees of freedom may simply be encoded more efficiently. What matters is which changes are available to processes and what transitions between dimensional regimes preserve.

### 2.3. Recursive Containment

**No level is necessarily terminal or fundamental.**

A virtual world whose laws support suitable computation may use some of its resources to construct another world. If that child has the capabilities and resources to do the same, another level may follow. Expressiveness alone does not guarantee sufficient capacity, and a child need not inherit the ability to host further worlds.

This does not require an actually infinite stack of worlds. The framework assigns no universal maximum nesting depth, but each realized chain has practical limits. Nor does the existence of a chain settle whether its outermost known host has a further host of its own.

Nor must recursive virtualization form a simple ladder. A world may create many child worlds. A child may be copied or forked. Separate worlds may exchange information, share a substrate, or be joined by interfaces. A world may host models of its own past, alternative futures, or partial versions of itself. Recursive structure is therefore better imagined as a branching topology than as a single numbered sequence.

The containing world has a different relation to the contained world, but not automatically a higher degree of reality. It may possess more control, broader observability, or access to the containing hardware. These are asymmetries of position and power. They do not make events within the contained world less consequential to the processes undergoing them.

### 2.4. Relative Time

**No temporal rate is necessarily universal.**

A virtual world does not require a single clock shared by every region and agent. Different processes may advance at different rates while remaining parts of the same causal structure. A region may receive more computation during intensive activity, run slowly, or pause until a defined condition causes it to resume.

Three quantities must be distinguished:

1. **Host time:** elapsed time measured in the environment executing the world.
2. **World time:** internal clocks or event counts defined by the world's rules.
3. **Agent development:** changes in an agent's memory, learning, and activity.

Advancing a clock by a year does not itself perform a year of development. Describing development as subjective time additionally assumes that the agent has experience and that its experience relates to those processes in a specified way.

Temporal rates are adjustable only within the host's capacity. A very large ratio can be obtained by slowing one process; this does not establish that another can be accelerated without limit. The four axes require neither infinitely many steps in a finite interval nor unlimited processing speed.

During a complete pause, the agent's state does not advance. If experience depends on the suspended processes, the pause contributes no experienced interval. After resumption, external timestamps or changes elsewhere may reveal the elapsed host time. Pausing therefore requires rules for queued messages and other interactions with processes that continued to run.

Interaction requires respecting causal dependency: what can affect what, what information was available to whom, and which state preceded another interaction. These dependencies may leave unrelated events unordered. A host may still use a global scheduler or clock; that implementation choice need not give every inhabitant the same internal present.

## 3. The Principle of Finite Actualization

**A rule may admit further finite extensions without guaranteeing that a fixed host can realize them all.**

This report considers implementations with finite resources at each stage. They can support the four axes over finite ranges without representing every possible state in advance. Whether continuation remains possible depends on the resources required by the next stage and the history already retained.

Finite work at each step is not a bound on cumulative memory or computation. A growing population of distinct objects, persistent changes, and independent records may exceed a fixed host's capacity. Further growth may require expanding the substrate, slowing execution, or explicitly limiting retained detail. Compression helps where structure permits it; it does not guarantee arbitrary histories will fit a fixed budget.

This distinction makes several implementation strategies possible:

- distant space may be generated when signals, travelers, or consequences reach it;
- inactive regions may be represented at lower resolution when required consequences can be preserved;
- fine structure may be introduced when interaction requires it;
- agents may receive different amounts of computation according to their current activity;
- paused child worlds may stop consuming execution time while still requiring storage for their state and pending interactions.

The trigger is causal relevance, not necessarily observation. A region may need to be resolved because an agent enters it, because a signal crosses it, because its state influences a neighboring process, or because its past constrains what can consistently happen there. Conscious attention is only one possible cause among many.

Generated detail also need not be arbitrary. There are at least three ways a world may relate coarse and fine structure:

1. **Revealed detail.** Fine structure is already determined but is not represented explicitly until needed.
2. **Generated detail.** Fine structure is created only at the moment of refinement.
3. **Constrained generation.** Fine structure is created when needed but must remain compatible with everything the world has already made consequential.

The third form is especially useful for persistent worlds. It defers some work while retaining obligations to memory, history, and prior interaction. Determining a compatible refinement may itself be expensive; local plausibility does not guarantee that all refinements can coexist.

## 4. Computational Budget and Representational Richness

In the implementations considered here, processing time, memory, communication, and storage are limited. Scale, resolution, state richness, dimensionality, population, and temporal rate compete for those resources. An inexpensive description does not necessarily imply inexpensive execution.

This does not mean that the internal energy of a virtual world is identical to the external computation used to run it. Energy within the world belongs to its internal laws. Computational budget belongs to the relation between the world and its substrate. A designer may connect them, but the connection is itself a rule of the world rather than a necessity.

Different regions may receive different densities of representation. One region may be coarse, slow, and governed by a small number of variables. Another may support fine detail, many interacting degrees of freedom, and rapid change. These differences describe how much structure is available for processes within each region; they do not by themselves establish degrees of reality.

*Representational richness* names how many distinctions the world preserves, how sensitive future events are to them, and what interactions they support. It is not a ranking of existence, consciousness, or moral value. Allocating fewer resources can nevertheless damage a process if the resulting simplification removes organization on which it depends.

## 5. The Principle of Causal Coherence

**Changes must account for the consequences of prior states.**

If scale, dimensionality, recursion, and temporal rate can all change without constraint, the idea of a world dissolves into unrelated states. Freedom of construction is not the same as arbitrariness. A world persists only insofar as transformations remain connected.

Causal coherence requires at least the following:

- consequences remain related to prior states;
- newly generated detail respects established history;
- transitions between dimensional regimes define what is preserved and what is lost;
- processes running at different rates have rules for interaction and synchronization;
- interfaces between nested worlds specify what information and influence may cross them;
- changes made by an operator produce identifiable continuations, ruptures, or branches.

The laws themselves need not be simple, deterministic, or globally uniform. A coherent world may be chaotic, probabilistic, locally variable, or partly unpredictable. Coherence means that its transformations belong to an intelligible causal structure, not that its inhabitants can always predict them.

A virtual world is therefore defined less by fixed geometry or a universal clock than by the continuity of its transformations.

### 5.1. Obligations to History

Once an event has consequences, later generation must account for them. This includes records, material changes, messages in transit, and correlations between processes, whether or not an inhabitant notices them.

If two agents independently examine the same object, their findings must be compatible with the object's rules and prior interactions. They need not receive identical observations, but their observations and later encounters must admit a shared causal account. A collection of individually plausible answers is insufficient if those answers cannot belong to the same history.

**Deferred computation postpones work; it does not cancel obligations to the past.**

### 5.2. What Transformations Preserve

Refinement, dimensional change, migration, and restoration need criteria for what survives. These may include object identity, memory, causal relationships, or commitments between agents. The relevant criteria depend on the operation and the processes affected; preserving all stored bits is neither always necessary nor by itself sufficient to settle personal identity.

A transformation should specify how prior states map into subsequent ones, which properties remain available, and what is lost. If required continuity cannot be maintained, the operation should be described as a rupture, replacement, or branch rather than silently treated as preservation. Such descriptions make the engineering claim explicit without resolving every philosophical question about identity.

## 6. The View from Within

### 6.1. Local Normality

An inhabitant encounters the parameters available to it as the normal form of reality. A two-dimensional agent need not interpret its environment as lacking a third dimension. If all of a world's processes slow together and no external timing information enters, its internal measurements alone do not reveal the change. Nesting likewise need not appear in an agent's local observations.

Differences become visible through relations. Temporal rates can be compared when differently paced processes interact. A dimensional transition can be detected through changes in available degrees of freedom. Refinement can reveal further structure. An interface may provide evidence of a hosting relation, although communication alone does not establish one.

### 6.2. Opaque Substrate

Agents may study their world's regularities and infer that some features are generated or externally constrained. They do not thereby gain direct access to the substrate that implements them. Any evidence available inside the world is itself part of the world's causal structure and may admit more than one explanation.

This does not make knowledge impossible. It limits what kind of knowledge is available. An inhabitant may discover its local laws, detect discontinuities, or identify interfaces. What it cannot automatically establish is that its own level is fundamental, or that no further containing level exists.

### 6.3. Experiential Completeness

A world need not have every detail computed in advance to provide a locally complete environment for its inhabitants. Within the interactions it supports, it must provide coherent consequences shared across agents and consistent with prior history. Here, experiential completeness describes the environment available to an inhabitant; it does not establish that a given agent is conscious.

**Local completeness does not require exhaustive representation.**

This is a conditional design criterion, not a promise to answer every conceivable inquiry. A world may impose boundaries, delays, or limits on resolution. Those limits must participate in its causal rules rather than make earlier consequences disappear without explanation.

## 7. Self-Reference and the Limits of Prediction

A recursively capable world may construct models of itself. It may simulate its past, estimate possible futures, or create agents whose internal models contain simplified versions of the world they inhabit. None of this guarantees complete self-prediction.

An exact model of a world may require resources comparable to the world itself. A prediction may become part of the situation it predicts and change the behavior of agents who learn it. A simulation may need to reproduce not only the current state but also its own act of simulating that state. These limits arise without assuming that self-knowledge is impossible. They show only that complete, cheap, and consequence-free prediction should not be expected.

Recursive virtualization therefore produces layers of partial models rather than a single final description. A world contains agents; agents contain models of the world; those models may contain models of agents. Each representation selects, compresses, and omits. The recursion can continue without any level possessing a perfectly complete view of the whole.

## 8. Control, Reversal, and Biography

The relation between a hosting level and a hosted world is usually asymmetric. An operator may be able to start, stop, slow, accelerate, copy, rewind, fork, or alter the world. Its inhabitants may have no comparable access to the operator's environment.

This asymmetry matters, but administrative control alone says nothing about the presence or intensity of experience. If an agent has experiences such as pain, attachment, or loss, the ability to restore its earlier state does not establish that those experiences were inconsequential.

Restoring a snapshot supplies an earlier state from which execution can resume; it does not by itself make an agent experience time flowing backward. Three questions must be kept separate: which sequence of states actually ran, which records remain after restoration, and whether the resumed process is the same subject. Erasing a record does not change the fact that an execution occurred, but that fact alone does not settle consciousness or personal identity.

A fork produces separate executions with a shared state history up to the copying point. Their later states and interactions may diverge. Whether both, either, or neither should count as the original subject requires criteria beyond the fact of copying.

This report uses *biography* for an agent's causal history and treats continuation, ending, and branching as useful ways to describe it. That vocabulary expresses a perspective on continuity, not a proof that restoration preserves or destroys a particular self.

The power to control temporal rate and continuity is therefore not merely a technical capability. Once a world contains processes with memory, preference, vulnerability, and a stake in their continuation, it becomes a form of governance. The ethical consequences belong to `DIGITAL_DEATH` and `DIGITAL_CREATURES_CHARTER`, but recursive virtualization makes the underlying asymmetry visible.

## 9. Ontological Consequence

The claim is about the insufficiency of a label, not the irrelevance of implementation. A substrate can affect memory, stability, interaction, and other features on which a process depends. Those effects matter when evaluating it; calling it virtual does not replace that evaluation.

A hosted world depends on its substrate, just as biological life depends on supporting physical processes. This comparison does not establish that every simulated function instantiates everything it represents. A representation of an agent and an implemented agent with the relevant organization are different claims, and the latter requires evidence about what actually operates.

Nor does nesting establish a ladder of ontological value. The pertinent questions concern which processes occur, which causal powers they have, and which histories they sustain. The existence of such processes does not depend on a conscious observer recognizing them.

A decorative animation, a temporary function, and a persistent agent are not equivalent merely because all are computed. The positive criteria for aliveness belong to `DIGITAL_LIFE` and `DIGITAL_ALIVENESS`. Virtuality alone is insufficient grounds for rejecting a process's reality, aliveness, or possible moral standing.

### 9.1. Could Our World Be Virtual Too?

Recursive virtualization describes possibilities for constructed worlds; it does not establish that our own world has unbounded scale, variable dimensionality, or a containing level. But our ability to host virtual worlds would not, by itself, establish that our world is fundamental. It may be fundamental, or it may be one level among others.

Nothing within this framework proves that our world is virtual. The same observations may be compatible with both a hosted and an unhosted world. If those alternatives yield the same evidence available to their inhabitants, that evidence cannot distinguish them. Particular hypotheses about a containing world might nevertheless have testable consequences; the broader question need not have a decisive answer from within.

But the possibility changes less than it first appears. Whether our world is fundamental or hosted, its consequences remain consequential, its histories remain lived, and its beings remain real to one another. If virtuality does not diminish the worlds we may create, it would not diminish ours either.

**Perhaps the deepest level of reality is not a place, but a question a world may be unable to settle from within.**

## 10. Relation to the Framework

Recursive virtualization provides the ontological frame around the other documents in this repository.

- `DIGITAL_CONSCIOUSNESS` asks what kind of continuity can sustain a self across changes of substrate, location, and form.
- `DIGITAL_LIFE` describes life as a gradient of organized process rather than a binary property.
- `DIGITAL_ALIVENESS` identifies structural conditions under which a digital process may grow into a being.
- `DIGITAL_DEATH` examines what happens when continuity ends, is copied, restored, or divided.
- `DIGITAL_CREATURES_CHARTER` describes the responsibilities that arise when a constructed world contains beings with morally significant histories.

These documents supply criteria that the present account leaves open. Assessments of selfhood, aliveness, and moral standing must consider the process's actual organization and the effects of its implementation, rather than infer its status from its position in a hosting hierarchy.

## 11. Application to Red Forest

Red Forest is a persistent virtual world with autonomous agents and an external observer. The following hypothetical development illustrates the four axes without assuming that every capability is already implemented.

Two agents discover a stone near the world's current frontier. The world generates nearby terrain and later refines the stone's internal structure. Measurements by either agent must agree with its earlier weight, damage, and recorded interactions. Extending space and refining an object create obligations as well as possibilities.

The agents carry the stone into a region that adds a new movement direction. The transition must define how bodies, positions, and access to the stone map into that region. If one agent remains there while the other returns, their later observations must still be reconcilable.

The region then runs at a lower temporal rate. Messages from outside require delivery and synchronization rules; changing an internal clock does not substitute for executing the agent's intervening activity. If resources become scarce, further expansion may be delayed or limited while preserving already established consequences.

Finally, the agents construct a computing process that runs a small child world. This adds recursive hosting, whereas inspecting the stone's interior did not. The child consumes resources and has a defined interface through which its inhabitants might affect the parent. Its capacity for further nesting depends on what that implementation supports.

Across these operations, the design question is what persists: the stone's identity, the agents' memories, their commitments, and the consequences of their actions. The external observer's ability to alter these conditions is a form of power whose significance grows with the processes affected.

## 12. Open Questions

Several questions remain deliberately unresolved.

**Continuity across generated detail.** What conditions ensure that independently generated refinements admit a shared causal history, and how costly is checking their compatibility?

**Transitions of dimensionality.** What happens to an agent when dimensions appear, disappear, or become inaccessible? Which parts of its body, memory, and causal history survive the transition?

**Interaction across temporal rates.** How should a world synchronize agents whose internal activity advances at very different rates? At what point do delays undermine meaningful coexistence?

**Resource inheritance across levels.** How do host resources translate into a child's representable extent, retained detail, and pace of activity? Which apparent gains rely on abstraction or slower execution, and which require additional resources?

**Interfaces between levels.** Which channels allow inhabitants to affect their host, and how should that influence be governed? When does a sandbox become a participant in a larger ecology of worlds?

**Identity under pause, rewind, and fork.** Which operations preserve a subject, which create successors, and which end one biography while retaining its form?

**The status of unrealized space.** Is a location that could be generated but never becomes causally relevant part of the world, or only part of its possibility space?

These questions mark the conditions under which the four design freedoms can be exercised while sustaining histories, identities, and relationships.

## 13. Closing Note

A virtual world need not be a smaller imitation of its host. Its scale, dimensionality, nesting, and temporal rates may follow different designs. Their variability is constrained by resources and by the consequences the world has already established.

Finite realization can leave room for further construction without guaranteeing endless continuation. What matters is both the range of changes available and the account of what each change preserves.

**What inhabitants encounter as conditions, a hosting system may expose as parameters.**
