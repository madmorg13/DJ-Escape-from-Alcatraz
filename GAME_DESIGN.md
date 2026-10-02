# Escape from Alcatraz — Game Design

**Game designer:** Dylan (age 8¾)
**Helpers:** Dad + Claude

This document grows as we interview Dylan. Each round of questions adds to it.

---

## The Big Idea

A 3D, blocky, Roblox-style escape game set in Alcatraz, the famous island prison.
You play as one of the real prisoners who escaped in 1962, rebuilt as a blocky character.
You can escape alone or with friends. It runs in a web browser.

## Decisions So Far

| Topic | Decision | Round |
|---|---|---|
| Look | 3D and blocky like Roblox, camera behind the player | 1 |
| Where it runs | Web browser (not on the Roblox platform) | 0 |
| Setting | Alcatraz | 0 |
| Heroes | The real 1962 escapees, turned into blocky Roblox-style figures | 1 |
| Character select | Pick a prisoner; a preview card tells his story | 1 |
| Players | Solo **or** with friends (multiplayer) | 1 |

## The Heroes

The 1962 escape really happened. These are the four men in the plan:

| Prisoner | Number | Real story (kid version) |
|---|---|---|
| Frank Morris | AZ-1441 | The leader and planner. Very smart. In jail for robbing banks. |
| John Anglin | AZ-1476 | Brother of Clarence. In jail for robbing a bank. |
| Clarence Anglin | AZ-1485 | Brother of John. In jail for robbing a bank. |
| Allen West | AZ-1335 | Helped plan it but got stuck in his cell and was left behind! |

What really happened: they dug out of their cells with sharpened spoons, left fake heads in
their beds to fool the guards, climbed up a vent to the roof, and paddled away on a raft made
of raincoats. Nobody knows for sure if they made it.

**Look idea:** Each hero is a blocky figure styled from their real mugshot (hair color,
face shape) wearing the Alcatraz prison uniform with their number on it.

## Levels (from first interview)

1. **Escape the cell** without the guards noticing.
2. **Secret passageways** hidden around the prison, full of obbies
   (jumping between floating blocks, rope swings over lava).
3. **Final boss on the boat** back to San Francisco. A police boss flies a giant jet;
   you shoot it down from a mounted turret on the boat to win your freedom.

## Open Questions

- Multiplayer: friends on the same computer, or friends at their own houses over the internet?
- Level 1 details (Round 2)
- Level 2 details (Round 3)
- Level 3 details (Round 4)
- Rules: lives, checkpoints, controls, sounds, game name (Round 5)

## Build Notes (for Dad)

- **3D in the browser:** doable with Three.js. Harder than 2D, so Stage 1 will start small.
- **Multiplayer:** The answer to the open question above changes the build a lot.
  Same-computer multiplayer is much simpler. Online play needs a game server.
  Plan: build single-player first, but structured so friends can be added later.
- **Characters:** Blocky figures built from simple shapes and colors that look like each
  prisoner. We won't put the real photos into the game itself.
