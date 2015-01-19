---
title: Fantasy Sports League Rules
---

Every game has well defined rules so I decided the first step in the project should be to define the rules of the fantasy league which will determine the type of interactions that I need to account for when designing the data model.

## Fantasy League Rules
1. User needs to be part of a league.
2. Each league has a maximum of 10 users.
3. Within a single league there cannot be users that own the same pro player.
4. Each user can only be part of 1 league [*].
5. Each user has a roster.
6. Each roster is composed of 16 players (9 Starters, 7 Bench)
  * 1 Quarterback (QB)
  * 2 Running Backs (RB)
  * 2 Wide Receivers (WR)
  * 1 RB/WR
  * 1 Kicker (K)
  * 1 Defense (D)

Time Permitting:
7. A substituion means a player from the bench replaces a starter player.
8. Only 1 substitution per posion is allowed [*].
9. The substituion can be implemented real-time (scoring gets divided).
10. Notification system for the users ?
