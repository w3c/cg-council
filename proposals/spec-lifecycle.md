# CG Specification Lifecycle
Status: This is a proposal for discussion; it does not yet represent consensus.

This topic was discussed in a breakout session during the AC 2025 meeting; see the [slides](https://www.w3.org/2025/Talks/cg-breakout-ac2025.pdf).

# Motivation

The full life cycle of W3C Working Group specifications has grown more complex over time as a tool to communicate important information to readers of a specification such as:

* The measure of consensus associated with a specification.
* Whether a specification should be implemented experimentally or has been successfully implemented by independent parties.
* Whether wide review is actively being sought.
* W3C endorsement signals:
   * W3C as an organization endorses the work.
   * W3C has rescinded such endorsement.
   * The work has been abandoned prior to endorsement.

For Community Group specifications, we have historically only identified two states:

* Draft
* Final. The “Final” state has served two purposes:
   * Set expectations that the specification is stable.
   * Secure stronger IPR commitments, for example, as a precursor to transferring the specification to a Working Group for standardization.

However, we observe that more states would be useful to communicate certain realities:

* Another organization has taken up the work (e.g., for standardization) and so the Community Group is no longer the “owner.”
* A Community Group has stopped work either following an explicit decision or because they abandoned their work.

In addition, as part of a plan to enhance the Community Group program, we believe that defining additional states will support several goals:

* Clearer communication about the status of a Community Group specification and the guarantees associated with specifications with that status.
* Potential process enhancements associated with those specifications that have achieved ecosystem traction.

# Audiences

We identify the following audiences who should understand the meaning of the different states and what may be asked of that audience:

* CG Participants
* Developers (of Web applications)
* Implementers (of APIs, for example in a browser)
* Horizontal review groups at W3C
* SDOs (especially those who may standardize CG Specifications)
* Regulators

# Communication of States

One idea to communicate state information is to combine status, circumstances, and usage guidance. How we implement this communication (e.g., vocabulary, design, etc.) is not yet defined.

## Status

* The primary status is "Draft"
* Additional statuses may be useful for clear communication, including:
   * Transferred and discontinued in the CG
   * Retired (with rationale)

## Circumstances

* Development
   * Last modified
   * Expiry date (à la IETF documents)
   * Group status (e.g., closed or dormant)
* Community support 
   * Is there strong support? Strong opposition? Alternative proposals?
   * Are potential implementers of the specification participating in its development?
* Implementation status (and, for each one, number)
   * Intent to implement
   * Prototyping
   * Shipping
   * Availability of tests
   * Availability of polyfills
* Standardization expectation
   * Unknown
   * Intent to standardize (with info about venue)
* Revision management (after handoff for standardization)
   * None (work has stopped for now in the CG)
   * Independent (CG works on new versions only)
   * Codependent (CG works on materials as input to standards group)
Patent licensing commitments
   * Contribution-only
   * Contribution + Full specification (FSA)
* Adoption level
   * Are experiments/pilots happening?
   * Are there real-world deployments?
* Traction
   * Low
   * Medium
   * High
   
## Usage Guidance

* Reports (and repos) should include usage guidance that depend on the status and circumstances. It might be interesting to see if we can generate the usage guidance systematically for each combination of status and circumstance.
* All usage guidance for CG Specifications must say “Not a standard. We do not recommend that it be used where W3C standards are required.” 
* It is likely appropriate to say for all CG specifications: “It is appropriate for developers to experiment with implementing this specification.”
* Traction = High
   * Standardization expectation = “unknown => Although this specification appears to be gaining traction, at this time, we are not aware of any standardization expectations.”
   * Standardization expectation = “intent => This specification appears to be gaining traction and the CG has indicated an intent to advance to standardization. We recommend checking periodically to see whether the specification has been transferred to a group for standardization.”

## Notes

* Circumstances can evolve independently. As a result, each circumstance should have an associated date so you know when it was last updated.
* How to ensure that the representation of circumstances remains are up-to-date (in the spec and/or on w3.org)?
