# FG-TIDA WG0: Use Cases and Terminology (UCT)

*Working title and acronym — open for revision.*

WG0 maintains the shared terminology and the shared use-case register that
every other FG-TIDA Working Group relies on.

## Charter Information

|||
|-|-|
|Charter version|0.9|
|Date|2026-11-09|
|Status|Draft, initial proposal for discussion|

## 1. Group Information

|Field|Content|
|-|-|
|Working group name and acronym|Use Cases and Terminology (UCT), working title|
|Basis|The FG-TIDA Terms of Reference|
|FG-TIDA ToR items covered|ToR Objective 1 (Terminology and Definitions)|
|Chair(s) / co-chairs|Trisha Chakraborty|
|Editor(s) of the main deliverables|TBD|
|Mailing list|TBD|
|Repository and issue tracker|TBD|
|Working methods|TBD — to be discussed and agreed by the Working Group|
|Charter status and version|Draft 0.9|

## 2. Background and Problem Statement

AI agents, trust and identity are being studied in parallel by several FG-TIDA
Working Groups, each developing its own deliverables on its own timeline.

Two needs cut across all of them and belong to none of them individually.

First, a shared vocabulary. A term defined independently by two Working
Groups, each unaware of the other's definition, is a defect that only
surfaces once both deliverables are published — and fixing it then means
reopening finished text. Not every such case is a mistake to correct,
though: some terms legitimately carry more than one definition depending on
context, and the risk then is not collision but silently picking one
meaning without saying so.

Second, enough situations in view before the technical work starts. A
Working Group that scopes itself from whichever situations happen to be
top of mind risks missing entire areas and unknowns that only surface once
drafting is already underway, when reopening scope is expensive. FG-TIDA's
use-case submissions make that space visible early — deployed systems and
credible hypotheticals both count toward it, since what matters is
breadth of situations covered, not whether each one has already happened.
WG0 reviews each submission once — checking relevance, avoiding
duplication, and routing it to the right Working Group — instead of every
Working Group doing this separately.

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
  definition — and where a term genuinely needs more than one definition,
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
* Use cases: Taking over the existing FG-TIDA use-case register as a single
  repository, transferred into this Working Group rather than duplicated —
  its history, existing submissions and tooling carry over unchanged, and
  it is never maintained in two places at once.
* Use cases: Operating the intake process, review workflow and curated
  register for use-case submissions — open for every Working Group to
  submit into and to draw its own tagged use cases back out of — tagging
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
  deliverable — that decision belongs to the receiving Working Group. The
  Working Group's role ends at an accurate, curated mapping.
* The Working Group does not adjudicate intellectual-property disputes
  between contributors; it applies the confidentiality and IP fields already
  captured at submission.

## 5. Programme of Work and Deliverables

|#|Deliverable|Short description|Input documents|
|-|-|-|-|
|1|FG-TIDA Glossary (Technical Specification, versioned)|A harmonized set of terms and definitions for trust, identity and agentic AI, reconciling contributed source material and flagging unresolved collisions between communities.|Terminology proposals contributed within FG-TIDA and from adjacent Focus Groups; terms drawn from other Working Groups' charters and the use-case register|
|2|Context-Sensitive Terminology Report (Technical Report)|For terms that legitimately carry more than one definition depending on context, records every candidate definition considered, the context each applies in, and which definition FG-TIDA uses in that context.|Candidate definitions surfaced during Deliverable 1's harmonization work and from Working Groups' own use of contested terms|
|3|FG-TIDA Use-Case Register (continuously maintained register, not a one-off document)|A curated, themed, Working-Group-tagged register of submitted use cases, with a reviewer workflow and a public dashboard.|Use-case submissions via the FG-TIDA use-case intake repository|
|4|Use-Case Review and Mapping Guidance (short process document)|How a submission is triaged, what it means for a use case to be fully mapped and handed to a Working Group as input, and how a Working Group can request use cases be routed to it.|Deliverable 3's existing reviewer workflow|

## 6. Milestones

|Target date|Milestone|
|-|-|
|2026-12 (Paris)|Charter presented; use-case register repository stewardship formally transferred to WG0; Working Group seed data covers all chartered Working Groups.|

## 7. Coordination, Dependencies and Liaisons

|Group / Organization|Coordination or dependency|
|-|-|
|Every other FG-TIDA Working Group|Consumer of the glossary and the use-case register; source of terms and use cases that need harmonizing or mapping.|
|Other ITU-T Focus Groups studying related terminology|Candidate liaison for terminology alignment, as needed.|
|ITU-T SG17|Eventual recipient of the glossary as base material, alongside other Working Groups' deliverables.|

## 8. Terminology

This Working Group's own charter intentionally does not define new terms
here — Deliverable 1 is the authoritative place for FG-TIDA terminology, and
duplicating definitions in this charter would itself recreate the problem
the Working Group exists to prevent.

## 9. Working Methods

TBD — to be discussed and agreed by the Working Group.

## 10. Security and Privacy Considerations

Use-case submissions can contain confidential business scenarios. The
Working Group applies the confidentiality level already captured at
submission (Public / FG-internal only / Redact before publication) when
curating and publishing the register, and does not publish redact-flagged
material in the dashboard or any derived export.

## 11. Success Criteria and Conclusion

The chartered work is ongoing rather than one-shot for Deliverable 3 (the
register), and complete for Deliverables 1 and 2 (the glossary and the
context-sensitive terminology report) once each is agreed by the Working
Group and in active citation by at least one other Working Group's
deliverable. The Working Group continues operating the use-case register
for the lifetime of the Focus Group.
