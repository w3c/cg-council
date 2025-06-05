# Community Group Lifecycle

Status: This is a proposal for discussion; it does not yet represent consensus.

## Background

Today we close Community Groups for several reasons:

* They complete their work successfully
* They become inactive 
* They are creating confusion or perceived harm

When we [close a group](https://www.w3.org/community/council/wiki/Closing_a_Community_or_Business_Group), we:

* Update the description to indicate that the group has closed and (where known) indicate where the activity continues
* Deactivate the mailing lists (except where another group takes up those lists) and other tools (e.g., repos)
* Empty the list of participants

We have, on rare occasions, re-opened Community Groups when that community believes the time is right to continue their work. Although it is easy to re-open a CG in our systems, there is a cost for people to rejoin the group, primarily from needing to secure permission from legal departments to sign the CLA.

Our [practice](https://www.w3.org/community/council/wiki/Closing_a_Community_or_Business_Group) has long been to reach out to inactive CGs every six months to understand their situations. In some cases, groups say things like "We're not active now, but we expect to be in six months." or "We are awaiting a grant in order to continue the work." or "The situation is unclear right now, can we stay open a little longer?" or "Our specification is stable and we have one implementation. It may be a while before we get a second implementation."

## Goals

Below we propose a new CG status of "dormant" designed to:

* Communicate more clearly the a CG's expectation that **work has slowed, but not stopped** (and set some expectations about timing for when the group expects to become active again).
* Give us an easier way to reach a community, even if that community is not currently developing deliverables. This can be useful, for example, in situations where there might be a desire to transfer a Specification to an SDO.

In addition, because we do reopen CGs, and because some people have indicated that "closed" sounds overly negative, we propose to change the "Closed" state to "Archived" (a label borrowed from GitHub).

## Design Principles

* **Enforcement is not a goal** (e.g., by freezing group participation or tooling). The Dormant state communicates an expectation. 
* **Staff outreach will be reduced** but monitoring will continue. If the Staff detects inconsistencies with the dormant expectation we will work with the group to resolve them.

## Policy

### Entering dormant state

* Any request to make a group dormant must be acknowledged by all the chairs. 
* The request must include information that will be shared publicly:
   * Rationale for why the group is becoming dormant.
   * An estimate (even rough) of how much time the group expects to be dormant.
* The Community Development Lead the decides whether to make the group dormant. If so, the staff implements making the group dormant (see below).

### During dormant state

* While the group is dormant, people may still join or leave the group, and the chairs may change.
* W3C will not invite the group to TPAC or other events. (The group should reopen if planning that level of activity.)
* W3C staff will continue to monitor group activity but only expects to reach out to the group if regular activity is detected.

### Returning to active state

* A dormant group must have chairs to be reactivated.
* Any request to reactivate a group must be acknowledged by all the chairs. 
* The request to reactivate the group must include information that will be shared publicly:
   * Context for why the group is being reactivated
* The Community Development Lead the decides whether to reactivate the group and implements accordingly.

### Closing a dormant group

* The staff may close the group at any time, but should only do so after sending email to the group's list and allowing time for participants to respond. Some reasons staff might close a group:
   * The chairs request that the group be closed.
   * There are no longer any chairs and nobody volunteers to become chair. 
   * The group's work has been transferred to another group.
   * The staff perceives that there is no longer interest in the work.
   * The staff perceives harm or confusion with the group in its dormant state.

## Considerations

### Specifications

* The fact that a CG is dormant (and why) is an important piece of information to communicate around any Specification being developed by the CG. To avoid confusion, it would help to communicate clearly in every Specification developed by the CG what the community should expect (e.g, the specification is not likely to change while the group is dormant). This might be achieved by simple status section update.

## Implementation

* Update tools to use "Archived" instead of "Closed"
* Add "Dormant" state to state machine. It is possible to go from "Dormant" back to "Created" and also from "Dormant" to "Archived"
* It should not be possible (and is not useful) to go from "Archived" to "Dormant."
* Update relevant documentation

### CG site

* Put dormant groups lower in the sorted list (by activity)
* When someone clicks on the “Join” button, the join page should tell them that the group is dormant (with a link to the definition of dormant in the revised CG process.)
* In home pages for the CG (whether it’s the WordPress instance or the /groups/cg page) there should be a cautionary statement: "Note: this group is currently dormant” which a link to the definition of dormant.

### Differences when entering closed or dormant states

| Implementation | Archived  | Dormant |
| ------------- | ------------- | ------------- |
| Update group description | Yes (with any links to other venues)  | Yes (with rationale and estimated duration) |
| Deactivate mailing lists| Yes generally  | No generally |
| Disassociated lists from group | Only those remaining open | No |
| Update the mailing lists archive headers | Yes | No |
| Update GitHub repo(s) | Deactivate, with updated language | Set expectations about dormant state  |
| Empty participant list | Yes | No |
| Change group status in database | Yes (archived) | Yes (dormant) |

