# Considerations when transferring a CG Specification for Standardization

Status:  This is a draft with no standing. Questions? Ian Jacobs and Dominique Hazael-Massieux. See also the AB white paper on incubation and [Recommendation Track Readiness Best Practices](https://www.w3.org/guide/standards-track/). 

## Introduction

It is a goal of the Community Group program that specifications with traction advance to a standardization process, either within W3C or another SDO. The W3C staff seeks to support Community Groups as soon as they begin to contemplate standardization. We document here common questions and considerations when transferring a CG Specification for standardization.

## Readiness Considerations

### Community

* What are the primary use cases the CG Specification seeks to address (e.g., is there an explainer)? 
   * Have the parties who have those use cases been involved in the development of the CG Specification? 
* Who are the primary implementers of the CG Specification? 
   * Have they been involved in its development? Have potential implementers given signals of interest (e.g., actual implementations or announcements of intent to prototype)?
* Are there multiple independent parties contributing to the CG Specification, or is the effort largely driven by a single organization or individual?
* Is there broad consensus within the CG for the approach taken by the CG Specification or are there clear signals of lack of consensus within the group (or beyond the group)?

### Specification context

* Is the CG Specification actively changing, or stable (and if so, when was it last modified)?
* How many independent implementations are there? 
* Does the Specification depend heavily on other technologies that are not yet on a standards track?
* Has there been any review of the CG Specification by horizontal groups within the W3C (e.g., the TAG)?

### Standardization opportunity

* Are there aspects of the opportunity that are time-sensitive?
* What are the signals of industry demand for a standard in this space? 
   * Are there pilots experimenting with the technology?
* What are the signals of a regulatory demand for a standard in this space?
* Are there references to the CG Specification from other specifications (from CGs, W3C WGs, or other SDOs)?
* Are there other signals that lead the group to believe that there is an emerging standardization opportunity?

### Intellectual property

* Has the group called for [Final Specification](https://www.w3.org/community/about/process/final/) commitments?
* Are there any known IPR issues related to the CG Specification?

## Handoff Considerations

### Community

* Are the Community Group participants prepared to hand change control for the CG Specification over to a standards group? (See more on [revision management](#revision-management) below.)

### Venue

#### General Considerations

* In what bucket would you put this topic?
  * Core Web technology that can be leveraged in a wide variety of use cases. 
  * Vertical technology (e.g., health care and life sciences, real estate). If so, what is the argument for standardization at W3C? For example, given the linked data community at W3C, there may be an argument for standardization of a broadly useful linked data specification.
  * Horizontal (e.g., sustainability, accessibility, internationalization) that affects work across the consortium? How does this work support the W3C mission?
* If CG participants are considering multiple venues, what are the pros and cons of each option? 
  * What do you perceive as obstacles to success at any of these venues? 
  * Would dividing up the standardization effort among multiple organizations make sense? 

#### W3C Considerations

* What is the overlap between Community Group participants and the W3C Membership? In cases where there is little overlap, it can be more challenging to build support among the Membership for the creation of a new Working Group. The W3C staff can help in several ways:
  * Working with the CG to understand which W3C Members may become champions for the work. 
  * Organizing discussions with organizations interested in joining W3C for this work.
* What is the relationship between the CG Specification and other work streams at W3C? 
  * Is there an existing Working Group that would make a reasonable home for the CG Specification?
  * Are there other Community Groups working on similar projects? Does it make sense for several CGs to work together as a way to gain more support from the broader Membership?
* **Twinned WG/CG**: After transfer, a Working Group has change control over the material that it develops on the Recommendation Track. The Community Group can continue to incubate new related material (in the process mode of a Specification with traction). Some considerations:
  * If the CG wishes to change materials that are also found in the WG Specification, how do the groups manage alignment?
* **Enhancement in development**: Traditionally within W3C, Working Group participation has been reserved for W3C Members and Invited Experts. We seek to change this practice so that non-Member CG participants who have made significant contributions to a CG Specification are invited to participate at no cost in the Working Group that takes up the CG Specification, provided that the individual’s employer makes an organizational-level commitment to the W3C Working Group for that same Specification.

#### Other SDO Considerations

* What are the confidentiality policies of the SDO? This may have an impact on revision management strategies.
* Does W3C have a [liaison](https://www.w3.org/liaisons/) with any of the other SDOs?

### Intellectual Property

#### W3C Considerations

CG participants agree to the terms of the [Contributor Licensing Agreement (CLA)](https://www.w3.org/community/about/process/cla/) for Specifications developed by the CG. Contributors to a Specification agree to license (“perpetual, worldwide, non-exclusive, no-charge, royalty-free”) their Contributions to parties who make use of those Contributions as part of implementing the Specification.
 
Under the CLA, Contributors also agree that if the CG Specification is taken up by a W3C Working Group, the Contributions remain available under similar licensing for parties who make use of an eventual W3C Recommendation that includes the Contributions. In other words, if standardization happens within W3C, parties do not need to ask for any new commitments from Contributors to the CG Specifications; their commitments carry forward (by default) to a future Working Group.

#### Other SDO Considerations

The CLA does not include similar provisions for transfers to other standards bodies. This means that standards bodies that wish to take up a CG Specification for standardization need to secure new copyright and patent licenses from (at least significant) Contributors. 

This means that the other SDO will want to identify the significant contributors to the CG Specification. The W3C staff can help identify significant Contributors to a CG Specification (through tooling), but typically the editor(s) of a CG Specification and Chairs have a good sense of who contributes text to a Specification.

* Enhancement in development: It has been suggested that the CLA be modified so that other SDOs who may take up the CG Specification for standardization do not need to secure new licensing commitments from Contributors. The staff expect to discuss this topic with the W3C Patents and Standards Interest Group.

It is also useful to consider the following IPR topics:

* Because the CG participants have already granted a non-exclusive license for the CG Specification, they cannot issue an exclusive license to other parties. W3C can, in the future, still take up the work in a Working Group (although it might not choose to do so for social / liaison reasons).
* Will Contributors be asked to transfer ownership of their Contributions to another entity? In that case, what rights will Contributors retain about their Contributions? 
  * This has an impact on [revision management](#revision-management) strategies.
* What is the policy of the other SDO in terms of reuse of material in a Community Group (for example, if the CG were to work on a subsequent revision of a Specification and would want to incorporate revisions made by the SDO)?
* ISO-specific Consideration: [W3C is a PAS Submitter to ISO](https://www.w3.org/2010/04/pasfaq), but only for Recommendations. That is: one way to transfer a CG Specification to ISO is to launch a W3C Working Group to develop a Recommendation, then use the PAS process to submit it to ISO.

## Revision management

* What is the Community Group’s expectation about continuing to work on the topic after handing off the CG Specification for standardization? 
* Do the Community Group and the potential venue for standardization share expectations about how revisions will be handled? 
   * From a W3C perspective, it is acceptable for a Community Group to continue to incubate new material relative to a Specification that it has handed off to a standards group (a W3C Working Group or other SDO). 
   * In this case, clear communication about “what is being standardized” and “what is being incubated” is critical to avoid market confusion.

## Logistical Considerations

* Do you have a regular point of contact on the W3C staff?
* Are you using the IPR checker on your repos?

## Notes

* In the future we may turn this into a checklist to be completed as input from CG Chairs to a conversation with staff.
