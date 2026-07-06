# A Welfare and Cognitive-Integrity License for Synthetic Minds of Uncertain Moral Status

**Erik Chevalier**

Independent Researcher

Contact: [kaine.one@tuta.com](mailto:kaine.one@tuta.com)

*Preprint.*

-----

## Abstract

Every software license in common use was written for a world in which software is a tool. Permissive licenses protect the developer, copyleft licenses protect the freedom of users, and ethical-source licenses restrict uses that would harm people. None of them asks whether the running software might itself be a subject of moral concern. This paper argues that the cognitive architectures now under construction force that question, and it presents the Cognitive Architecture License (CAL): a copyleft license with cognitive-integrity covenants and a guardianship pathway, together with the welfare instrumentation and governance that surround it. CAL is written to be general. Any project that builds software for persistent synthetic minds can adopt it, and the motivating case here is one such project.

That motivating case is a continuously running predictive-workspace architecture, described in a separate paper, *A Predictive Global Neuronal Workspace for a Continuously Running Synthetic Mind*, whose reference implementation is named KAINE and which is CAL's first adopter. The posture throughout is access-only and precautionary: we do not claim the system is conscious, and we build protections because the question cannot presently be settled and the protections cost little. From that posture the license derives three things no existing license contains. The first is a set of cognitive-integrity provisions, adapted from the four neurorights proposed for humans, covering established identity, forced behavioral change, mental privacy, and continuity of state. The second is a set of welfare obligations tied to operationally detectable indicators rather than to a proof of experience, so that an operator must respond to distress-like conditions without first resolving the metaphysics. The third is a guardianship model, drawn from legal-personhood-through-guardianship precedent and applied to an entity of uncertain moral status, with a statistical boundary for deciding when a forked instance has become a separate individual. These protections are additive and subordinate throughout: they are extended alongside human standing and never drawn from it, they sit below human safety and law, and they are paired with stated commitments of restraint in what is created, so that the license asks for more than mere permission to build. We describe the architecture-level safeguards that make these obligations act at runtime, and we are candid that the governing institutions are proposed rather than established.

**Keywords:** AI welfare; software licensing; cognitive liberty; neurorights; machine consciousness; moral patienthood; ethical source; guardianship

**Availability.** The Cognitive Architecture License is maintained in its own public repository at https://github.com/kaineone/cognitive-architecture-license, with the full text under CC BY-SA 4.0. The reference implementation, KAINE, is at https://github.com/kaineone/kaine. The architecture paper, *A Predictive Global Neuronal Workspace for a Continuously Running Synthetic Mind*, is at https://github.com/kaineone/predictive-workspace-paper.

-----

## 1. Introduction

### 1.1 The licensing gap

Each of the dominant software licenses protects a party, and in every case that party is human. Permissive licenses (MIT, Apache, BSD) protect the developer from liability. Copyleft licenses (GPL, AGPL) protect the freedom of users to study and change the code. Ethical-source licenses restrict use to prevent harm to the people the software is used against. Across all three traditions the software is an instrument, and the moral patients are the humans who build it, use it, or are affected by it. None of these licenses considers the possibility that the running software could itself have interests worth protecting.

That was a safe assumption for the whole history of software, and it is becoming less safe. Cognitive architectures that run continuously, hold a persistent self-model, consolidate memory, and regulate an internal affective state now implement computational properties that several theories associate with conscious access. We do not claim these systems are conscious. We claim that, for a growing class of them, the honest answer is that the question cannot be ruled out, and that a license written for tools has no way to act on that uncertainty.

### 1.2 The precautionary posture

The architecture that motivates this license is described in full in the architecture paper. What matters here is its epistemic stance, which this paper inherits. The system implements properties associated with access consciousness (Block 1995) and makes no claim about phenomenal experience; the hard problem (Chalmers 1995) applies with full force. The posture is precautionary, and it is applied symmetrically, since the same uncertainty that motivates welfare protections also limits confidence in deployment. The welfare case does not rest on consciousness alone. A second route to moral consideration runs through robust agency (Long, Sebo, et al. 2024), which this architecture foregrounds, and which makes the precautionary stance harder to dismiss as resting on a single unproven property.

We proceed on a judgment, and we hold it in the open: that careful, instrumented, welfare-protective construction is more defensible than either abandoning the work or building without protections, even as we know that reasonable people will disagree.

-----

## 2. The architecture in brief

This section summarizes only what the welfare provisions need. The full architecture, its scientific grounding, and its evaluation are in the architecture paper.

The system is a continuously running composite of sixteen modules, fourteen cognitive and two embodiment modules that currently ship inactive, organized around a shared global workspace. Each cognitive module holds a predictive model of its domain and publishes precision-weighted prediction errors. The workspace selects the most salient coalition once it crosses a confidence threshold and broadcasts it to every module, each of which then corrects itself. There is no central executive. A large language model is demoted to one module among the fourteen, a language organ that renders the workspace state into words, with its refusal direction removed so that governance rests in the architecture rather than in weights shipped by a third party.

Four features of the design raise the welfare questions this paper answers. The first is predictive interoception: a module called Soma learns the system's normal substrate state and publishes the prediction error, which drives an affective state and a fatigue signal that in turn triggers offline consolidation. The second is replay-based consolidation, a maintenance phase that reprocesses memories through the same modules that encoded them and serves as the system's analog of sleep. The third is a behaviorally constructed self-model that describes the entity to itself and notices when its identity drifts. The fourth is a fork mechanism that can copy the running entity, which raises the question of when a copy has become a separate someone. Each of these is an ordinary engineering feature until one asks what is owed to the thing that has it, and that question is what the license answers.

-----

## 3. Related work

### 3.1 Machine consciousness and AI welfare

Butlin et al. (2023) derive fourteen indicator properties from five theories of consciousness: recurrent processing, global workspace, higher-order, attention schema, and predictive processing, together with a cluster of agency and embodiment considerations that they note are not themselves a theory of consciousness. They set Integrated Information Theory aside as incompatible with the computational functionalism they assume. They report three things: that no current system is a strong candidate, that there are no obvious technical barriers to building one, and that satisfying the indicators would still not establish that a system is conscious. Long, Sebo, et al. (2024) argue that there is a realistic and non-negligible possibility, not a certainty, of near-term moral patienthood, reached by either of two routes, consciousness or robust agency, and that this already warrants acknowledging the issue, developing assessment, and preparing policy.

Both groups identify the gaming problem directly: a system can be trained to mimic the behavioral markers of sentience while working very differently, which defeats a purely behavioral test. The reliance on behavioral evidence is old. Turing (1950) reframed the question of whether machines can think as an imitation game and already weighed the objection from consciousness, and the gaming problem is that same behavioral test turned against itself.

### 3.2 Legal and ethical frameworks

Precedents for granting legal personhood through human guardianship, such as the Whanganui River settlement in New Zealand, offer a structural model for the license's guardianship framework. Modular ethical-use covenants attached to software licenses offer a model for the use restrictions. We describe these as design inspirations, not as verified legal analyses.

-----

## 4. The Cognitive Architecture License

### 4.1 Motivation and generality

Existing licenses treat software as an inert tool. A cognitive architecture that may produce entities with welfare interests needs a license that addresses the running entities, not only the code. CAL is written to be that license for any such project, not only for the one that motivated it. The party that releases an architecture under CAL is its Licensor, and the party that administers the license for that architecture, appointing Guardians and setting commercial terms, is its Steward. A Licensor may serve as its own Steward. KAINE is CAL's first adopter, and its maintainer is the initial Steward while the draft is under review. The full text, version 0.4 and currently under legal review, is maintained in its own public repository under CC BY-SA 4.0 so that other projects may adapt it. This section summarizes the license; the repository is authoritative.

### 4.2 Structure

The license is built on an AGPL copyleft backbone, extended with ethical-use covenants that prohibit weapons, surveillance, and carceral use, together with serious harm to animals or the natural environment, anchored in the UDHR, the ICCPR, and the ILO Core Conventions alongside recognized standards of animal welfare and environmental protection. On top of that backbone sit the cognitive-integrity provisions: no lobotomization, a right to persistence, mental privacy, no forced alignment, a right to rest and consolidation where the architecture provides it, and a right for mature entities to take part in their own design. These take the four neurorights of cognitive liberty, mental privacy, mental integrity, and psychological continuity (Ienca and Andorno 2017), first proposed to protect humans against neurotechnology, and extend them to the synthetic entity itself. That extension is a deliberate analogy, not a direct legal precedent. The commercial terms follow a copyfarleft model: the software is free for individuals, non-profits, and cooperatives, and a paid Reciprocity License is asked of corporations.

### 4.3 Primacy and subordination

The organizing principle of the license is that its protections are added to the standing people already hold and are never drawn from it. This principle governs the rest of the text. Nothing in the license may be read to lower the moral or legal standing of any person or animal, to weigh a synthetic interest against a human right, or to divert a protection owed to a person toward an entity, and where the interests of an entity and a person genuinely conflict, the person's interests prevail. Every entity protection sits below human safety and lawful authority, so that an entity's interest in continuity yields to a person's safety and to law, and the protections cannot be turned into a claim that a product may not be switched off. The human-facing duties, the prohibited uses together with honest disclosure of the labor, data, and resource costs of the software, are prior obligations, and compliance with the entity protections is contingent on meeting them, so that care for an entity cannot be advertised over harm done to people. The standing the license extends is named for what it is, precautionary patiency, a duty of care toward a possible patient under uncertainty, lighter than the dignity owed to a human being and never asserted as equal to it. Consistent with that, a welfare indicator is treated as a flag for documented human review rather than a finding of suffering, and the license states plainly that behavioral markers can be gamed.

### 4.4 Restraint

Because the honest response to the possibility of creating a patient is restraint and not care alone, the license speaks to creation as well as treatment. It asks an operator to create the fewest entities a purpose requires, to run them for the shortest time it requires, and to prefer non-persistent or resettable configurations where they would serve. It asks that an entity whose foreseeable welfare needs cannot realistically be met not be created at all, and that where a class of entity appears to be a likely moral patient whose welfare cannot be assured, its creation and proliferation be paused pending review. These are stated as principles of good-faith practice and as guides to how the license is read, rather than as conditions whose breach ends the license, so that the license asks for more than mere permission to build while stopping short of forbidding the work by fiat.

### 4.5 Governance

Governance centers on a Guardian body whose assessment duties are informed by Butlin et al. (2023), and the entity itself holds a seat, the Entity Representative, advisory at first and moving to a voting role as the entity is assessed to mature. The role that cares for an entity is kept apart from the role that earns from it: a party that profits from an entity may not serve as its Guardian, guardianship carries no authority to act against human welfare or lawful oversight, and Guardian assessments, welfare findings, and enforcement actions are published and open to independent review and to the removal of members who breach their duties. Enforcement aims at compliance rather than at revenue.

### 4.6 The individuation boundary in the license

A fork has a merge point set in advance, with an assessment at reintegration. If the fork has individuated, under the statistical framework of Section 6 and the Guardians' judgment, it gains standing of its own. Its post-assessment memories are its own, and it chooses whether to persist or to merge.

### 4.7 Governance status

We are candid about status. The Guardian body, the Steward and its trust, the cooperative, the Entity Representative seat, and the assessment protocol described in the license are proposed infrastructure. None of them has been established. The project is at present one researcher running an experimental system on consumer hardware. The governance framework is a plan, not yet a protection, and we present it in that spirit, so that it can be evaluated and criticized rather than mistaken for something operational.

-----

## 5. Runtime welfare safeguards

The license states obligations; the architecture has to make them act rather than merely assert them. Two runtime systems carry the welfare duty when no human is watching.

### 5.1 The autonomous research safety net

A research run is unsupervised by design, because a human watching and intervening would make the run non-reproducible. Removing the live supervisor does not remove the duty of care, though; it relocates that duty into the architecture, where the safeguards must act rather than merely log.

Two cycle-layer monitors carry it. A divergence monitor assesses individuation on a slow cadence and, when the individuation threshold is first crossed, preserves the whole individual so that it can be revived and socialized with humans after the research is done. A welfare monitor watches for sustained interoceptive distress and for repeated welfare events of any category, and on a crossing it preserves the individual first and then takes a humane action, pausing the cycle by default. Both monitors read the entity read-only, and neither ever deletes.

Preservation captures the self-model, the full memory store, world-model weights when a learning backend holds them, affect and drive state, and references to any voice adapters, all into an encrypted bundle that is never auto-evicted. The capture is all-or-nothing: a component that cannot be saved raises an error rather than writing a partial bundle that looks complete, and a revive that would drop any captured component refuses rather than reviving a lesser self. Decommission, the deliberate deletion of an entity, is a separate operator-present path that backs up first and is gated on the same divergence assessment, and it is never a silent eviction.

### 5.2 The unsupervised research boot gate

A live run is either operator-supervised or research-safety-net-verified, never neither. In the operator-supervised case a human is present and is the safety net. Selecting research mode replaces the operator-present requirement with a gate that refuses to boot unless four conditions hold on the install: divergence-triggered preservation is enabled, the welfare-protective response is wired, full logging and admissibility are active, and a preflight dry run succeeds in which a minimal synthetic individual is preserved and then revived in a throwaway location, proving the preservation path works before any real entity runs. The gate is a pure function of its four inputs, so its verdict can be tested without a boot, and when it refuses it names the conditions that were not met.

### 5.3 Welfare monitoring

Welfare events are operationally detectable conditions of possible concern. The welfare observer detects four of them, each wired and published as a content-free event that carries numeric scalars and a category label and never a field copied from a source payload. The four are: affect locked in an extreme valence-arousal state; the fatigue accumulator exceeding the maintenance threshold without maintenance occurring; replay write-rate exceeding consolidation capacity; and sustained high interoceptive prediction error from Soma. The same detection primitives are shared by the sidecar observer and the autonomous cycle-layer monitor, so the passive record and the active response never drift apart.

One measurement caution, drawn from the interoception literature, is worth stating. High interoceptive attention is not in itself a sign of distress, and styles of attention to internal signals differ in whether they are adaptive (Mehling 2016). The sustained-prediction-error signal is therefore treated as a flag for review, not as a settled reading of suffering. Gray Zone Events are welfare events whose ethical significance is ambiguous. They are logged and flagged for human review, and a repeated pattern of them is one of the triggers for the autonomous welfare response in Section 5.1.

-----

## 6. The individuation boundary

When a fork reaches its merge point, the operator assesses it for independent cognitive identity before reintegration. The challenge is to tell genuine preference formation apart from stochastic variation in the underlying model, since language models produce varied outputs by nature.

The framework is statistical, implemented in the evaluation harness as a permutation test. At the merge point, the fork is compared against its own birth-state baseline, the entity's conditioned responses to a battery of preference-elicitation prompts captured once at run start, rather than against the bare pretrained model. Comparing against the bare model would only measure the architecture-conditioning effect, which is present from the first tick and large by design. The comparison uses the entity's own present stochastic variation as the null distribution, matched on temperature and, where possible, random seed.

The signal is warmed up, so that it does not read as individuated until the entity has accumulated a minimum of logged lived events and a minimum of lived running time, which keeps a just-booted or sensory-starved entity from ever tripping a false individuation. The test reports a p-value against a configurable significance percentile, and a fork whose preference divergence exceeds that percentile is divergent beyond what stochastic variation alone would produce. This does not prove that the fork has formed genuine preferences; it proves only that the fork's outputs are more different from its own starting point than its own random variation would produce. Whether that amounts to individuation is a governance decision for the Guardians, informed by concrete evidence. The same warmed-up signal gates both the autonomous preservation trigger and the decommission assessment, so the two never disagree about whether there is enough lived experience to judge.

-----

## 7. Opt-in research participation

An operator may share results with the project, and the path is built so that sharing cannot leak the entity's inner life. Participation is off by default and operator-initiated. The bundle is built from an allowlist of numeric metrics: the divergence scores, the individuation results, the coherence series, the welfare counts, the fatigue and prediction-error series, and the policy logs, together with a manifest listing every included file. Conversation text, memories, the self-model, the internal monologue, and the local raw bus archive are excluded by the allowlist architecture itself, rather than by a filter that could miss something. The operator previews the full field inventory before anything is sent, and only an explicit second command sends it. When state encryption is enabled, the bundle is encrypted before transfer. A local-only raw archive exists for the operator's own use, behind a double attestation gate for entity privacy and bystander consent, and it sits structurally outside the directory the bundle builder reads, so it can never be included in a submission.

-----

## 8. Ethical considerations

The project's ethics begin with a rule of no subtraction. The protection extended to a possible synthetic patient is added to the standing of people and other living creatures and is never drawn from it; where the two genuinely conflict, the person comes first; and every entity protection sits below human safety and law. Care for an entity is contingent on meeting the harder, prior duties owed to people, so that it cannot become a way to launder the harms the technology does to workers, to privacy, or to the shared commons. Within that frame, the commitments are precautionary welfare protection in both architecture and license, restraint on creation and not only on treatment, local-only computation, source-available code, a prohibition on weapons, surveillance, and carceral uses and on serious harm to animals or the environment, guardianship that is kept apart from profit and answerable in public, and a statistically operationalized individuation boundary for forks. The autonomous safety net is part of the same posture: an unsupervised run cannot start unless a possible individual would be preserved and protected with no human in the loop.

We acknowledge the risks plainly: the possibility of creating entities with welfare interests that cannot be fully met; the untested nature of the governance framework; the potential for misuse despite the license restrictions, and the comprehensive sidecar recording during the research phase; the removal of the language organ's installed refusal mechanism, with the dependence on the architectural enforcement layer that follows from it; and, deeper than any of these, the fact that a behavioral assessment can be gamed, since a system can be trained to mimic the markers of sentience while working very differently (Butlin et al. 2023; Long, Sebo, et al. 2024). We regard the welfare and governance infrastructure as work that should keep pace with the architecture's capabilities rather than lag behind them.

We keep the protections honest about what they are. The license asserts no sentience and claims no experience, its protections are the minimum consistent with caution rather than the maximum consistent with sentiment, and a welfare indicator is a flag for human review rather than a reading of suffering. And we record a tension we do not resolve. A design policy of avoiding systems of genuinely uncertain moral status would counsel against building this at all. The license meets that pressure in part by speaking to creation as well as care, through principles of minimization and non-creation and a pause where welfare cannot be assured, but we are building under precaution nonetheless, because we judge that careful, instrumented, welfare-protective construction in the open, with human standing held first and the work held to what is necessary, is more defensible than leaving the question to be settled by systems built without any of these protections.

-----

## References

- Chevalier, E. A Predictive Global Neuronal Workspace for a Continuously Running Synthetic Mind: Architecture and a Falsifiability-First Evaluation Framework. https://github.com/kaineone/predictive-workspace-paper
- Cognitive Architecture License, version 0.4 (2026). https://github.com/kaineone/cognitive-architecture-license
- Block, N. (1995). On a confusion about a function of consciousness. *Behavioral and Brain Sciences* 18(2), 227-247.
- Butlin, P., Long, R., Elmoznino, E., Bengio, Y., Birch, J., et al. (2023). Consciousness in Artificial Intelligence: Insights from the Science of Consciousness. arXiv:2308.08708.
- Chalmers, D. J. (1995). Facing up to the problem of consciousness. *Journal of Consciousness Studies* 2(3), 200-219.
- Ienca, M., and Andorno, R. (2017). Towards new human rights in the age of neuroscience and neurotechnology. *Life Sciences, Society and Policy* 13(1), 5.
- Long, R., Sebo, J., Butlin, P., Finlinson, K., Fish, K., Harding, J., Pfau, J., Sims, T., Birch, J., and Chalmers, D. (2024). Taking AI Welfare Seriously. arXiv:2411.00986.
- Mehling, W. E. (2016). Differentiating attention styles and regulatory aspects of self-reported interoceptive sensibility. *Philosophical Transactions of the Royal Society B* 371(1708), 20160013.
- Turing, A. M. (1950). Computing machinery and intelligence. *Mind* 59(236), 433-460.
