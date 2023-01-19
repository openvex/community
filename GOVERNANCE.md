# OpenVEX Project Governance

As a nascent project, OpenVEX aims to have a quick development cycle where
decisions and community issues are resolved promptly while capturing the input
of interested stakeholders.

OpenVEX has no formal collegiate body in charge of steering. **Decisions are
guided by the consensus of community members who have achieved maintainer
status.**

While maintainer consensus shall be the process for decision making, all issues
and proposals shall be governed by the project's guiding principles.

## Guiding Governance Principles

Any issues or proposals brought to the project's maintainers shall be framed in
the OpenVEX guiding principles. Proposals not adhering to said principles shall
not be considered for consensus.

### Favor Simplicity

The goal of OpenVEX is to create a minimal VEX format that can be used with
agility and be embeddable. Simple is better.

### Dont't Break VEX

Any enhancements to the OpenVEX spec and tooling must not break the working
model of the CISA VEX Subgroup.

## OpenVEX Enhancement Proposals

To introduce a new feature into the OpenVEX specification, a user may open an
OpenVEX Enhancement Proposal (OVEP). Any OVEP opened by a community member who
has achieved maintainer status shall be automatically open for discussion if
the author so chooses. OVEPs filed by non-maintainers need to be sponsored by a
maintainer before being admitted for discussion.

OVEPs shall follow the structure set forth by the issue template in the
OpenVEX/community repository.

After an OVEP is accepted for discussion, it shall remain in under discussion
status for no longer than 30 days, after which consensus will be recorded
according to the maintainer consensus process.

## Maintainer Consensus

Each OpenVEX project (e.g. spec, vex-go, vexctl, etc.) will have a their own
set of maintainers.

To reach a decision on an issue, proposal, or formal OVEP, the proponents need
to seek maintainer consensus. In the context of this document, "maintainer
consensus" means collecting a sufficient number of favorable opinions of
community members with maintainer status in the relevant projects to move
forward with a proposal.

This document does not prescribe a method of voting. Any mechanism that enables
the collection of positive/negative votes associated with an identity may be
used.  Examples of this include voting through "thumbs up/down" emojis or with
"+1" comments in issues.

Maintainer consensus shall be reached in the following circumstances:

- Having a majority of favorable maintainer votes at the end of the proposal
  discussion term which may not be longer than thirty (30) days. The number of
  favorable opinions may never be less than two (2).

- Achieving a favorable vote of more than 50% of the total active maintainers
  at any time during the discussion period.

- In most cases, when the number of organizations with active maintainers in
  the project exceeds four (4), the total vote count shall include maintainers
  from at least two different organizations.

- A quorum for a favorable vote for spec changes must include maintainers from
  at least two (2) organizations.

- An exception to reaching maintainer consensus is when voting for proposals
  that modify the governance model (see below).

Note that when qualified, the proponents may add their favorable vote to count
towards consensus but needs to be explicitly recorded in the voting mechanism.

## Review Criteria for OpenVEX Repositories

Any changes intended to be merged in the OpenVEX repositories shall meet the
following minimal criteria:

- Commits must be signed by the author
- Commits must be signed off
- Pull requests must be approved by at least one of the project's maintainers

Any repository under the OpenVEX organization may impose additional
requirements to approve pull requests as long as these minimal requirements are
met.

## Revisions to the Governance Model

The project's governance Model shall be revisited every six months to address
the needs of the community as the project recognizes that communities need to
steer themselves according to their size, members, and other factors that shape
their complexity.

At any point, an OpenVEX Enhancement Proposal may be opened to redefine the
project's governance. To be accepted, governing model proposals shall be
approved by a qualified majority consisting of a minimum of 66% favorable votes
of all active maintainers.

## Reaching Maintainer Status

Any community member can be considered as a candidate for maintainer status
under the following conditions:

- Any community member may self-nominate as a maintainer candidate after
  actively contributing to OpenVEX constantly for six months or more.
- A sponsoring committee of maintainers that meets the qualifying criteria may

### Sponsoring Committees

To nominate a community member as a maintainer candidate, a group of
maintainers may file a nomination. The committee shall meet the following
criteria to be qualified to file the nomination:

- The number of members in the committee shall not be less than two (2).
- Whenever the number of organizations with maintainers in the project is more
  than two (2), committee members shall be from different organizations.

Once the nomination is filed and deemed valid, the regular process for
maintainer approval shall govern the decision to accept the candidate as a
maintainer.
