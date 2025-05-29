# Process Enhancements for CG Specifications with Traction
Status: This is a proposal for discussion; it does not yet represent consensus.

## Background

Once a specification has gained traction, we anticipate that
implementers and users of the specification will naturally start to
prefer stability due to their investments. A group may still want to
change a specification based on implementation or deployment
experience, but we expect that group consensus will increasingly favor
stability (and many CGs operate under consensus decision processes,
such as WICG, Web Assembly, Social Web, and GPU for the Web, and
Solid).  We have not observed significant demand for additional
process protections related to CG decisions around specifications with
traction.

Such protections are integral to a standardization process. Thus, the
W3C Process for Working Groups includes protections such as:

* Decisions by consensus
* Right to express reasonable position
* Requiring that decisions and formal objections be recorded publicly
* Appeal paths

Our goal is that Community Groups remain lightweight for incubation
and that for full protections, a specification should advance to
standardization.

However, in practice there is often a delay between when a
specification has gained traction and when a W3C Working Group or
other SDO has taken up the specification. In parallel with other
activities to reduce obstacles to advancing to standardization, we
propose here to incrementally enhance process protections in CGs,
especially once a specification has traction.

## Goals

* Keep the CG process lightweight overall, and particularly during the early phases of incubation.
* Encourage, but do not require, decision-making processes that offer protections for participants.

## Proposal

* Add to the CG Process a working definition of Traction:

> A Specification with Traction is one that fulfills any of the following criteria:
> * It is implemented in at least two products (e.g., browser engines) with large-scale distribution in the Specification ecosystem
> * Significant changes to it would disrupt the ecosystem of the Specification (e.g., in terms of adoption or references).


* Add to the CG Process a **default decision-making process** with these provisions:
  * The group **should** make decisions by consensus, especially once a specification has gained Traction.
  * Participants have a right to express reasonable positions.
  * (We can then remove this Note: "W3C encourages groups adopt decision-making policies that promote consensus.")

* Add to the CG Process that a CG **may** define its own decision-making process and it **may** differ 
  from the default decision-making process. If a group defines its own decision-making process:
  * It **must** be documented in an operational agreement.
  * It **should** encourage consensus decisions, especially once a specification has gained Traction.
  * It **must** describe how formal objections will be handled.

* Amend the CG Process to say that CG **should** (instead of **may**) have an operational agreement (charter) to cover decision processes and other matters.
  * (We should keep in place the existing rules governing operational agreements.)

* Add to the CG process that when a participant wishes to contest a **process matter**, they may escalate to the Community Development Lead, who will work with the participant and Chairs tounderstand the situation and pursue a fair resolution.

* Clarify in the CG Process that there is no formal appeal path outside a Community Group for **technical decisions** made by the Community Group. (Thus, there is no appeal to the staff, or the TAG, or a Council.) Instead:
  * Participants **should** record formal objections (publicly) within the  Community Group and **should** bring them to the attention of a group that takes up the specification for standardization.
  * Participants who want to develop alternative proposals can do so in other Community Groups.

## Implementation Notes

* The [CG Charter template](https://w3c.github.io/cg-charter/CGCharter.html) includes relevant provisions, but these should be reviewed.
