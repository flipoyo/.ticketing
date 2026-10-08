# .ticketing

*Created: 2026-09-22*

The planning-ticket lifecycle every project conforming to **DevSpecs**
follows: the two-state model (open/implemented), the
`<branch>_<priority>-<rank>_<Name>_DevPlanTicket.md` naming rule, and
short tickets. See `TICKETLIFECYCLE.md`.

Split out from `.agentSpec`, where `TICKETLIFECYCLE.md` used to live
directly (in the same repository `DevSpec` was nested inside) — a
project's ticket convention and its development philosophy happened to
share a repository, not because they were one thing. `AgentSkillsSplit`
gives each its own.

## Where the tickets go

`DevTickets/` is the project's own and private; this repository holds only
the rule. A project's `DevTickets/README.md` fills in §6.1 with where its
tickets sit and which branches it has (`SpecTree.md` §2 in `DevSpec`).
