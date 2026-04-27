# OpenVEX 1.0 Release Roadmap

This is the public roadmap towards the v1.0.0 release of the OpenVEX spec.
1.0 aims bridging the usability gaps discovered during the past three years
operating v0.2.0.

We aim to keep v1.0.0 backwards compatible with only additive changes to the
specification and tools.

## Changes Considered

The following is a high level overview of the changes currently considered
for the v1.0 release. No technical details are included in the list as each
will have a dedicated enhanced proposal.

### New Features

### Statement inclusion record

One of the biggest shortcomings of the spec in VEX operations is the ability
to express "this statement was included by X". The inclusion record will allow
document authors to pull authoritative VEX statements from someone else (a tool,
a security researcher, etc) and incorporate it with a full trace to the original.

### Vulnerability Import Path

There is a naming clash in VEX as originally drafted in the original CISA document.
If a VEX product includes the same subcomponent via two different import paths, one
may be vulnerable while the other not. There currently is no way to issue VEX
statement that specifically target one or the other. The solution here is to record
the subcomponent import path and make the statements applicable only if the
import path matches.

### Formal Identity Struct

The current specification has a string field to record persons/actors. This
field has proven to be unsuitable for more advanced operations and proposed
features such as multi-stakeholder approval of statements or inclusion records.

### Version Range Support

OpenVEX needs a versioning scheme to make statements applicable to groups of
products and subcomponents.

### Field Additions

The following new fields are under consideration to support the planned features.

- New `document.created_by` field (identity/IRI) (semantically <> vex author)
- New `statement.created_by` (identity/IRI)
- New `statement.added_by` (identity/IRI)

Mark document.author and document.role for (longterm) future deprecation in
favor of `created_by`.
