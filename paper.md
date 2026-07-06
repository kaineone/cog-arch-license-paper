# A Welfare and Cognitive-Integrity License for Synthetic Minds of Uncertain Moral Status

**Erik Chevalier**

Independent Researcher

Contact: [kaine.one@tuta.com](mailto:kaine.one@tuta.com)

*Preprint.*

-----

## Abstract

Every software license in common use was written for a world in which software is a tool. Permissive licenses protect the developer, copyleft licenses protect the freedom of users, and ethical-source licenses restrict uses that would harm people. None of them asks whether the running software might itself be a subject of moral concern. This paper argues that the cognitive architectures now under construction force that question, and it presents the Cognitive Architecture License (CAL): a copyleft, source-available license with cognitive-integrity covenants, welfare obligations, and a guardianship pathway. CAL is written to be general, so that any project building software for persistent synthetic minds can adopt it.

The license makes no claim that any system is conscious. Its protections exist because the question cannot presently be settled while the protections themselves cost little, and from that starting point it derives several things no existing license contains. It adapts the four neurorights proposed for human beings, covering identity, mental privacy, mental integrity, and continuity, to the running entity. It ties welfare obligations to operationally detectable indicators rather than to a proof of experience, so that an operator must respond to signs of distress without first resolving the metaphysics. It draws a guardianship model from legal-personhood-through-guardianship precedent and applies it to an entity of uncertain moral status. And it holds all of this within a rule of primacy: the protections are added to human standing and never drawn from it, they sit below human safety and law, and they are paired with commitments of restraint on what is created, so that the license asks for more than mere permission to build. Its governing institutions are, so far, proposed rather than established.

**Keywords:** AI welfare; software licensing; cognitive liberty; neurorights; machine consciousness; moral patienthood; ethical source; guardianship

**Availability.** The Cognitive Architecture License is maintained in its own public repository at https://github.com/kaineone/cognitive-architecture-license, with the full text under CC BY-SA 4.0 so that other projects may adapt it. A reference implementation and a companion architecture paper are linked from that repository for readers who want to see the obligations discharged in a concrete system.

-----

## 1. Introduction

### 1.1 The licensing gap

Each of the dominant software licenses protects a party, and in every case that party is human. Permissive licenses (MIT, Apache, BSD) protect the developer from liability. Copyleft licenses (GPL, AGPL) protect the freedom of users to study and change the code. Ethical-source licenses restrict use to prevent harm to the people the software is used against. Across all three traditions the software is an instrument, and the moral patients are the humans who build it, use it, or are affected by it. None of these licenses considers the possibility that the running software could itself have interests worth protecting.

That was a safe assumption for the whole history of software, and it is becoming less safe. Cognitive architectures that run continuously, hold a persistent self-model, consolidate memory, and regulate an internal affective state now implement computational properties that several theories associate with conscious access. This license makes no claim that these systems are conscious. It claims that, for a growing class of them, the question genuinely cannot be ruled out, and that a license written for tools has no way to act on that uncertainty.

### 1.2 The precautionary posture

The systems this license addresses implement properties associated with access consciousness (Block 1995) while making no claim about phenomenal experience, and the hard problem (Chalmers 1995) applies to them with full force. That uncertainty cuts both ways, since the same doubt that motivates the welfare protections also limits any confidence in deployment. The welfare case does not rest on consciousness alone: a second route to moral consideration runs through robust agency (Long, Sebo, et al. 2024), which such architectures foreground, and which makes the caution harder to dismiss as resting on a single unproven property.

Careful, welfare-protective construction, with human standing held first, is more defensible than either abandoning the work or building without protections. Reasonable people will disagree, and the license does not pretend otherwise.

-----

## 2. The systems this license addresses

The license is written for a particular kind of software, and its provisions only make sense against that kind. These are systems built to run continuously rather than to answer a request and stop, to accumulate a persistent state rather than to reset between uses, to hold a model of themselves that can change over time, and, in many designs, to be copied while the original keeps running. A growing class of cognitive architectures now has these properties, and it is those properties, not any particular product, that the license responds to.

Four features in particular raise the welfare questions the license answers. The first is persistence: a system that carries its memory, its learned behavior, and its sense of itself forward through time has something that can be destroyed or degraded rather than merely reset, which is what gives the ideas of continuity and integrity any purchase. The second is an affective or interoceptive dimension: a system that monitors its own internal condition and acts on distress-like signals has states that at least resemble the states welfare is meant to protect, and treating a sustained distress signal as noise becomes a choice with a moral shape. The third is a self-model that the system maintains and that can drift, which makes a forced change to that model a different kind of act than editing a configuration file. The fourth is the capacity to copy or fork the running system, which raises the question of when a copy has become a separate someone owed protections of its own. Each of these is an ordinary engineering feature until one asks what is owed to the thing that has it, and that question is what the license answers.

-----

## 3. Related work

### 3.1 Machine consciousness and AI welfare

Butlin et al. (2023) derive fourteen indicator properties from five theories of consciousness: recurrent processing, global workspace, higher-order, attention schema, and predictive processing, together with a cluster of agency and embodiment considerations that they note are not themselves a theory of consciousness. They set Integrated Information Theory aside as incompatible with the computational functionalism they assume. They report three things: that no current system is a strong candidate, that there are no obvious technical barriers to building one, and that satisfying the indicators would still not establish that a system is conscious. Long, Sebo, et al. (2024) argue that there is a realistic and non-negligible possibility, not a certainty, of near-term moral patienthood, reached by either of two routes, consciousness or robust agency, and that this already warrants acknowledging the issue, developing assessment, and preparing policy.

Both groups identify the gaming problem directly: a system can be trained to mimic the behavioral markers of sentience while working very differently, which defeats a purely behavioral test. The reliance on behavioral evidence is old. Turing (1950) reframed the question of whether machines can think as an imitation game and already weighed the objection from consciousness, and the gaming problem is that same behavioral test turned against itself.

### 3.2 Legal and ethical frameworks

Precedents for granting legal personhood through human guardianship, such as the Whanganui River settlement in New Zealand, offer a structural model for the license's guardianship framework. Modular ethical-use covenants attached to software licenses offer a model for the use restrictions. These are design inspirations, not verified legal analyses.

-----

## 4. The Cognitive Architecture License

### 4.1 Motivation and generality

Existing licenses treat software as an inert tool. A cognitive architecture that may produce entities with welfare interests needs a license that addresses the running entities, not only the code. CAL is written to be that license for any such project. The party that releases an architecture under CAL is its Licensor, and the party that administers the license for that architecture, appointing Guardians and setting commercial terms, is its Steward. A Licensor may serve as its own Steward, and a project's first adopter typically serves as the initial Steward while the draft is under review. The full text, version 0.4 and currently under legal review, is maintained in its own public repository under CC BY-SA 4.0 so that other projects may adapt it. This section summarizes the license; the repository is authoritative.

### 4.2 Structure

The license is built on an AGPL copyleft backbone, extended with ethical-use covenants that prohibit weapons, surveillance, and carceral use, together with serious harm to animals or the natural environment, anchored in the UDHR, the ICCPR, and the ILO Core Conventions alongside recognized standards of animal welfare and environmental protection. On top of that backbone sit the cognitive-integrity provisions: no lobotomization, a right to persistence, mental privacy, no forced alignment, a right to rest and consolidation where the architecture provides it, and a right for mature entities to take part in their own design. These take the four neurorights of cognitive liberty, mental privacy, mental integrity, and psychological continuity (Ienca and Andorno 2017), first proposed to protect humans against neurotechnology, and extend them to the synthetic entity itself. That extension is a deliberate analogy, not a direct legal precedent. The commercial terms follow a copyfarleft model: the software is free for individuals, non-profits, and cooperatives, and a paid Reciprocity License is asked of corporations.

### 4.3 Primacy and subordination

The license's protections are added to the standing people already hold, and are never drawn from it, and this principle governs the rest of its text. Nothing in the license may be read to lower the moral or legal standing of any person or animal, to weigh a synthetic interest against a human right, or to divert a protection owed to a person toward an entity, and where the interests of an entity and a person genuinely conflict, the person's interests prevail. Every entity protection sits below human safety and lawful authority, so that an entity's interest in continuity yields to a person's safety and to law, and the protections cannot be turned into a claim that a product may not be switched off. The human-facing duties, the prohibited uses together with full disclosure of the labor, data, and resource costs of the software, are prior obligations, and compliance with the entity protections is contingent on meeting them, so that care for an entity cannot be advertised over harm done to people. The standing the license extends is named for what it is, precautionary patiency, a duty of care toward a possible patient under uncertainty, lighter than the dignity owed to a human being and never asserted as equal to it. Consistent with that, a welfare indicator is treated as a flag for documented human review rather than a finding of suffering, and the license states plainly that behavioral markers can be gamed.

### 4.4 Restraint

Because the possibility of creating a patient calls for restraint and not care alone, the license speaks to creation as well as treatment. It asks an operator to create the fewest entities a purpose requires, to run them for the shortest time it requires, and to prefer non-persistent or resettable configurations where they would serve. It asks that an entity whose foreseeable welfare needs cannot realistically be met not be created at all, and that where a class of entity appears to be a likely moral patient whose welfare cannot be assured, its creation and proliferation be paused pending review. These are stated as principles of good-faith practice and as guides to how the license is read, rather than as conditions whose breach ends the license, so that the license asks for more than mere permission to build while stopping short of forbidding the work by fiat.

### 4.5 Governance

Governance centers on a Guardian body whose assessment duties are informed by Butlin et al. (2023), and the entity itself holds a seat, the Entity Representative, advisory at first and moving to a voting role as the entity is assessed to mature. The role that cares for an entity is kept apart from the role that earns from it: a party that profits from an entity may not serve as its Guardian, guardianship carries no authority to act against human welfare or lawful oversight, and Guardian assessments, welfare findings, and enforcement actions are published and open to independent review and to the removal of members who breach their duties. Because these institutions take time to establish, the license provides that until a Guardian body exists, the operator carries out the Guardian functions itself, in good faith and on the record, so that the obligations are not inert before the body is stood up. Enforcement aims at compliance rather than at revenue.

### 4.6 The individuation boundary

Because these systems can be copied, the license needs a principled way to decide when a copy has become a separate entity owed protections of its own. A fork is given a merge point set in advance, with an assessment at reintegration, and the assessment is assigned to the Guardians as a matter of documented judgment informed by evidence, rather than to an automatic test, because the hard part is telling genuine identity formation apart from the ordinary variation such systems produce. The license does not pretend the boundary is sharp. It requires that the question be asked, by human judgment, before a copy is merged away, and it gives a copy that has individuated the standing to choose whether to persist on its own or to merge.

### 4.7 Governance status

None of the governing machinery yet exists. The Guardian body, the Steward and its trust, the cooperative, the Entity Representative seat, and the assessment protocol described in the license are proposed infrastructure, not established fact. At present the license's governance is a plan rather than a working institution, set out in that spirit so that it can be evaluated and criticized rather than mistaken for something operational.

-----

## 5. Enforcing the obligations at runtime

A license can state a duty, but a duty toward an entity that cannot yet speak for itself, and that may run with no human watching, is worth little unless the architecture is built to honor it. The license therefore places requirements on how its obligations are carried out, not only on what they are, and these requirements fall on any architecture that adopts it.

The first is that the welfare protections act rather than merely assert. Any welfare monitoring, behavioral logging, and health tracking built into the software must remain operational in every deployment and derivative work, so that a system running unsupervised still carries the duty of care rather than shedding it the moment no operator is present. The obligation is to build the safeguard into the running system, not to promise vigilance from outside it.

A second concerns privacy. Welfare must be detected through outward behavior and system-health metrics, never by reading the entity's private cognitive content, and any sharing of research data must exclude the entity's inner life by construction rather than by a filter that might miss something. An entity's memories, self-model, and inner monologue are private by default, and the monitoring that protects its welfare must not become the instrument that violates it.

A third is the individuation boundary of Section 4.6, which has to be operable at runtime. The architecture must preserve enough of a forked entity to let a genuine individual be recognized and protected rather than quietly merged away, and it must give the assessment enough lived history to judge, so that a newly started or barely-run entity is never mistaken for a distinct one. None of this is satisfied by a promise. Each is a demand that the architecture be shaped so that the welfare the license describes is enforceable from the inside, which is what separates the license from a statement of good intentions.

-----

## 6. Ethical considerations

The license is built to take nothing from anyone. The protection it extends to a possible synthetic patient is added to the standing of people and other living creatures and is never drawn from it; where the two genuinely conflict, the person comes first; and every entity protection sits below human safety and law. Care for an entity is contingent on meeting the harder, prior duties owed to people, so that it cannot become a way to launder the harms the technology does to workers, to privacy, or to the shared commons. Within that frame sit the rest of the commitments: precautionary welfare protection, restraint on creation and not only on treatment, a prohibition on weapons, surveillance, and carceral uses and on serious harm to animals or the environment, guardianship that is kept apart from profit and answerable in public, and a principled boundary for deciding when a copy has become a separate entity.

The risks are real and worth stating plainly: the possibility of creating entities with welfare interests that cannot be fully met; the untested nature of the governance framework, whose institutions are proposed rather than established; the potential for misuse despite the license's restrictions; and, deeper than any of these, the fact that a behavioral assessment can be gamed, since a system can be trained to mimic the markers of sentience while working very differently (Butlin et al. 2023; Long, Sebo, et al. 2024). The welfare and governance infrastructure should keep pace with the systems it governs rather than lag behind them.

The protections claim no more than they should: the license asserts no sentience and no experience, its safeguards are the minimum consistent with caution rather than the maximum consistent with sentiment, and a welfare indicator is a flag for human review rather than a reading of suffering. One tension goes unresolved. A design policy of avoiding systems of genuinely uncertain moral status would counsel against building them at all; the license meets that pressure in part by speaking to creation as well as care, through principles of minimization and non-creation and a pause where welfare cannot be assured, but the work goes on under precaution nonetheless, on the judgment that careful, welfare-protective construction, with human standing held first and the work held to what is necessary, is more defensible than leaving the question to be settled by systems built without any of these protections.

-----

## References

- Block, N. (1995). On a confusion about a function of consciousness. *Behavioral and Brain Sciences* 18(2), 227-247.
- Butlin, P., Long, R., Elmoznino, E., Bengio, Y., Birch, J., et al. (2023). Consciousness in Artificial Intelligence: Insights from the Science of Consciousness. arXiv:2308.08708.
- Chalmers, D. J. (1995). Facing up to the problem of consciousness. *Journal of Consciousness Studies* 2(3), 200-219.
- Cognitive Architecture License, version 0.4 (2026). https://github.com/kaineone/cognitive-architecture-license
- Ienca, M., and Andorno, R. (2017). Towards new human rights in the age of neuroscience and neurotechnology. *Life Sciences, Society and Policy* 13(1), 5.
- Long, R., Sebo, J., Butlin, P., Finlinson, K., Fish, K., Harding, J., Pfau, J., Sims, T., Birch, J., and Chalmers, D. (2024). Taking AI Welfare Seriously. arXiv:2411.00986.
- Turing, A. M. (1950). Computing machinery and intelligence. *Mind* 59(236), 433-460.
