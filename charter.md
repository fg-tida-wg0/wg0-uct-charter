# FG-TIDA WG0: Use Cases, Taxonomy and Terminology (UCT)

*Working title and acronym, open for revision.*

WG0 maintains the shared terminology, taxonomy and use-case register that
every other FG-TIDA Working Group relies on.

## Charter Information

|||
|-|-|
|Charter version|0.10|
|Date|2026-11-27|
|Status|Draft, initial proposal for discussion|

## 1. Group Information

|Field|Content|
|-|-|
|Working group name and acronym|Use Cases, Taxonomy and Terminology (UCT), working title|
|Basis|The FG-TIDA Terms of Reference|
|FG-TIDA ToR items covered|ToR Objective 1 (Terminology and Definitions)|
|Chair(s) / co-chairs|Trisha Chakraborty; Lisa Bechtold|
|Editor(s) of the main deliverables|TBD|
|Reviewer(s) of use cases and main deliverables|TBD|
|Mailing list|fgtidawg0@lists.itu.int|
|Repository and issue tracker|Charter: fg-tida-wg0/wg0-uct-charter (this repository); Use-Case Register: fg-tida-wg0/use-cases; Glossary, Taxonomy and Ontology repositories: not yet created|
|Working methods|TBD, to be discussed and agreed by the Working Group|
|Charter status and version|Draft 0.10|

### Roles and Responsibilities

A reviewer is the first checkpoint for anything new, checking that a
submitted use case or term is complete and not a duplicate of something
already in the register, before it goes any further. An editor then writes
the deliverable itself, for example turning reviewed terms into Glossary
text, or reviewed use cases into Taxonomy labels. One person may hold both
roles, but the two jobs stay separate, so no one is both screening their
own submission and deciding it is ready.

The chairs run the sessions, keep the register, terminology, taxonomy and
ontology up to date, settle it when two terms or classifications collide,
align use cases to the right Working Groups, map out gap areas, seek
further contributions, represent WG0 to other Working Groups and to
FG-TIDA management, and decide when a new charter version is cut. The
community submits use cases, terms and taxonomy proposals, reviews other
contributors' submissions, and may volunteer to edit a deliverable in an
area it knows well.

## 2. Background and Problem Statement

AI agents, trust and identity are being studied in parallel by several FG-TIDA
Working Groups, each developing its own deliverables on its own timeline.

Three needs cut across all of them and belong to none of them individually.

First, a shared vocabulary. A term defined independently by two Working
Groups, each unaware of the other's definition, is a defect that only
surfaces once both deliverables are published, and fixing it then means
reopening finished text. Not every such case is a mistake to correct,
though: some terms legitimately carry more than one definition depending on
context, and the risk then is not collision but silently picking one
meaning without saying so.

Second, enough situations in view before the technical work starts. A
Working Group that scopes itself from whichever situations happen to be
top of mind risks missing entire areas and unknowns that only surface once
drafting is already underway, when reopening scope is expensive. FG-TIDA's
use-case submissions make that space visible early, deployed systems and
credible hypotheticals both count toward it, since what matters is
breadth of situations covered, not whether each one has already happened.
WG0 reviews each submission once, checking relevance, avoiding
duplication, and routing it to the right Working Group, instead of every
Working Group doing this separately.

Third, a shared way to compare situations across Working Groups. Two use
cases can depend on the exact same underlying structural problem, a chain
of independently governed registries where one broken link invalidates the
whole chain, for example, and still look unrelated because they come from
different sectors or different theme labels. Without a common taxonomy,
each Working Group would have to discover that relationship independently,
if it discovers it at all.

This terminology, taxonomy and ontology work is the foundation other agentic
AI governance efforts can build on: a shared, precise vocabulary for
identity, delegation and trust that any Working Group, inside or outside
FG-TIDA, can reuse instead of redefining. Where FG-TIDA's own usage differs
from an outside body's term, WG0 records the difference and publishes a
mapping back to it, rather than silently picking one meaning over the
other, keeping FG-TIDA's definitions compatible with outside work without
adopting that work's categories wholesale.

## 3. Goals

The Working Group maintains the shared terminology and use-case
infrastructure that every other FG-TIDA Working Group depends on, so that no
two Working Groups define the same term differently and every Working
Group can see the full range of situations relevant to its scope, not only
the ones already on its radar.

* Terminology: The Working Group starts from terminology already developed
  within FG-TIDA and by other relevant bodies, adopts it where it already
  fits, and extends it only where a gap remains for FG-TIDA's own scope,
  producing a single, versioned FG-TIDA glossary (Deliverable 1) that
  resolves collisions explicitly rather than silently picking one
  definition, and where a term genuinely needs more than one definition,
  records each one against the context it applies in (Deliverable 2).
* Use cases: The Working Group curates the FG-TIDA use-case register,
  working directly with every other Working Group so each can both
  contribute use cases into it and draw out the ones that belong to it:
  triaging new submissions, mapping each one to the theme(s) and Working
  Group(s) it belongs to, and flagging duplication against existing
  standards work (Deliverable 3).
* The Working Group keeps all its outputs discoverable and citable by
  every other Working Group's deliverable, rather than each Working Group
  maintaining its own glossary or use-case list.

## 4. Scope and Non-Goals

WG0 produces four things, built in this order:

* Use-case register: real scenarios, who is involved, what they need, and
  what's still missing.
* Terminology: one agreed meaning per term, or, where two are genuinely
  needed, both kept side by side, not silently chosen.
* Taxonomy: a fixed set of labels for sorting use cases, so two different
  ones can be compared on the same terms. Started only once the register
  has enough to sort.
* Ontology: a small, formal statement of how taxonomy concepts relate,
  built only as far as a real specification or tool will use it.

In short: the register holds the scenarios; the terminology names the
concepts inside them; the taxonomy sorts them; the ontology states
precisely how they connect. Each one depends on the one before it, so none
of the later three is started before the register has enough real
scenarios to work from.

### Why each one matters

* The register matters because without real scenarios, every later layer
  is guesswork.
* The terminology matters because without it, "agent identity" means a
  cryptographic key to one group, a legal principal to another, and a
  running process to a third.
* The taxonomy matters because without it, every use case has to be read
  individually to tell whether it's actually similar to another.
* The ontology matters because without it, a statement like "an agent acts
  for a principal" has no fixed meaning two different systems could both
  check against.

### In Scope

* Terminology: Adopting terminology already developed by other Focus Groups
  and external bodies where it already covers FG-TIDA's needs and drafting
  new definitions only where a gap remains for concepts specific to
  FG-TIDA's own scope, published as a single harmonized FG-TIDA glossary.
* Terminology: Resolving naming collisions between FG-TIDA Working Groups,
  and between FG-TIDA and other Focus Groups, where the same term is used
  differently.
* Terminology: Where a term carries more than one legitimate definition
  depending on context, recording every candidate definition considered,
  the context each applies in, and which one FG-TIDA uses in that context,
  instead of forcing a single definition where more than one is genuinely
  needed.
* Taxonomy: Sorting every use case and term by actor type, identity layer,
  lifecycle stage, authority, verification method, trust posture, and
  governance role, so use cases can be compared on the same terms instead
  of read one at a time. Started only once the register holds enough use
  cases to sort meaningfully, not in parallel with the register and
  terminology, but after them.
* Ontology: Stating precisely how a small number of concepts relate, for
  example, that a delegation has a grantor, a grantee, a scope and a
  validity period, and that an "owner" is a different role from an
  "operator" or a "deployer." Built only as far as a real specification,
  registry or test will use it. A complete, general-purpose ontology is
  explicitly not something WG0 commits to; later contributors are free to
  build one on this foundation.
* Use cases: Taking over the existing FG-TIDA use-case register as a single
  repository, transferred into this Working Group rather than duplicated,
  its history, existing submissions and tooling carry over unchanged, and
  it is never maintained in two places at once.
* Use cases: Operating the intake process, review workflow and curated
  register for use-case submissions, open for every Working Group to
  submit into and to draw its own tagged use cases back out of, tagging
  each one to the theme(s) and Working Group(s) it belongs to; where no
  Working Group yet covers it, marking it openly as not yet actionable
  rather than leaving it untagged.
* Use cases: Flagging duplication against existing ITU-T study group or
  other standards body work, per ITU-T Recommendation A.7 clause 7.

### Out of Scope / Non-Goals

* The Working Group does not write technical specifications whose subject
  matter belongs to another Working Group's charter (for example, remote
  attestation mechanisms belong to WG1; policy enforcement mechanisms belong
  to WG2). It states the shared vocabulary those specifications use.
* The Working Group does not decide whether a use case is "accepted" into a
  deliverable, that decision belongs to the receiving Working Group. The
  Working Group's role ends at an accurate, curated mapping.
* The Working Group does not adjudicate intellectual-property disputes
  between contributors; it applies the confidentiality and IP fields already
  captured at submission.

## 5. Programme of Work and Deliverables

|#|Deliverable|Short description|Input documents|
|-|-|-|-|
|1|FG-TIDA Glossary (Technical Specification, versioned)|A harmonized set of terms and definitions for trust, identity and agentic AI, reconciling contributed source material and flagging unresolved collisions between communities.|Terminology proposals contributed within FG-TIDA and from adjacent Focus Groups; terms drawn from other Working Groups' charters and the use-case register|
|2|Context-Sensitive Terminology Report (Technical Report)|For terms that legitimately carry more than one definition depending on context, records every candidate definition considered, the context each applies in, and which definition FG-TIDA uses in that context.|Candidate definitions surfaced during Deliverable 1's harmonization work and from Working Groups' own use of contested terms|
|3|FG-TIDA Use-Case Register (continuously maintained register)|A curated, themed, Working-Group-tagged register of submitted use cases, with a reviewer workflow and a public dashboard (fg-tida-wg0.github.io/use-cases).|Use-case submissions via the FG-TIDA use-case intake repository|
|4|Use-Case Review and Mapping Guidance (short process document)|How a submission is triaged, what it means for a use case to be fully mapped and handed to a Working Group as input, and how a Working Group can request use cases be routed to it.|Deliverable 3's existing reviewer workflow|
|5|Taxonomy for Agentic AI Identity and Trust (Technical Report)|A fixed set of labels for sorting use cases, identity mechanisms, delegation models and lifecycle stages, so any Working Group can compare submissions on the same terms.|The use-case register (Deliverable 3), once populated; terminology from Deliverables 1–2|
|6|Ontology for Agentic AI Identity and Trust (built incrementally)|A small, formal statement of how taxonomy concepts relate to each other, extended only as far as a specification, registry, or test will actually use it. Full completeness is explicitly not a WG0 commitment.|Deliverable 5's labels; real use cases from the register that need the relationship stated precisely|

## 6. Milestones

|Target date|Milestone|
|-|-|
|2026-12 (Paris)|Charter presented; use-case register repository stewardship formally transferred to WG0; Working Group seed data covers all chartered Working Groups.|
|2027-01 (Geneva)|Glossary v0.1 draft published, reconciling terminology proposals contributed to date; first list of terms needing a context-sensitive entry.|
|2027-01 (Geneva)|Taxonomy labels agreed and published for comment; reviewer and editor roles filled.|
|2027-Q1 end|First draft of the Taxonomy deliverable.|
|2027-Q3 end|Taxonomy deliverable finalized.|
|TBD (3rd FG-TIDA meeting)|Glossary and Context-Sensitive Terminology Report agreed by the Working Group.|
|TBD (within the FG-TIDA lifetime)|Glossary maintained at the current FG-TIDA vocabulary.|

## 7. Coordination, Dependencies and Liaisons

|Group / Organization|Coordination or dependency|
|-|-|
|Every other FG-TIDA Working Group|Consumer of the glossary and the use-case register; source of terms and use cases that need harmonizing or mapping.|
|Other ITU-T Focus Groups studying related terminology|Candidate liaison for terminology alignment, as needed.|
|ITU-T SG17|Eventual recipient of the glossary as base material, alongside other Working Groups' deliverables.|

## 8. Terminology

This Working Group's own charter intentionally does not define new terms
here, Deliverable 1 is the authoritative place for FG-TIDA terminology, and
duplicating definitions in this charter would itself recreate the problem
the Working Group exists to prevent.

## 9. Working Methods

TBD, to be discussed and agreed by the Working Group.

## 10. Security and Privacy Considerations

Use-case submissions can contain confidential business scenarios. The
Working Group applies the confidentiality level already captured at
submission (Public / FG-internal only / Redact before publication) when
curating and publishing the register, and does not publish redact-flagged
material in the dashboard or any derived export.

## 11. Success Criteria and Conclusion

The chartered work is ongoing rather than one-shot for Deliverable 3 (the
register), and complete for Deliverables 1, 2, 5 and 6 (the glossary, the
context-sensitive terminology report, the taxonomy and the ontology) once
each is agreed by the Working Group and in active citation by at least one
other Working Group's deliverable. The Working Group continues operating
the use-case register for the lifetime of the Focus Group.
