# Escape from Alcatraz — Game Design

**Game designer:** Dylan (age 8¾)
**Helpers:** Dad + Claude

This document grows as we interview Dylan. Each round of questions adds to it.

---

## The Big Idea

A 3D, blocky Roblox game set in Alcatraz, the famous island prison.
You play as one of the real prisoners who escaped in 1962, rebuilt as a blocky character.
You can escape alone or with friends online. It's a real Roblox game, built in Roblox Studio.
It's based on the real escape, but it's allowed to be fictional and fun (there's lava!).

## Decisions So Far

| Topic | Decision | Round |
|---|---|---|
| Platform | **A real Roblox game** (changed from a website in round 2) | 2 |
| Look | 3D and blocky, camera behind the player | 1 |
| Setting | Alcatraz, part real and part made-up | 0, 3 |
| Heroes | The real 1962 escapees, turned into blocky Roblox-style figures | 1 |
| Character select | Pick a prisoner; a preview card tells his story | 1 |
| Players | Solo **or** with friends | 1 |
| Multiplayer type | Online: friends play from their own houses | 2 |
| Co-op setup | Each player starts in a cell next to the others, so they work together (just like the real escape) | 2 |

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

---

## Level 1: Escape the Cell

**Goal:** Get the tools, make a fake head, and dig out of your cell without getting caught.

- **Start:** Each player is in their own cell, next to their friends' cells.
- **Mission: Steal a spoon (cafeteria).** Guards walk patrol routes around the cafeteria.
  When a guard turns away, quickly grab a spoon and hide it in your pocket, shoe or food.
  Friends can steal spoons for each other.
- **Mission: Make a fake head (art room).** Once a week there's a special art class.
  Steal paper and paint, then make a papier-mâché face to leave in your bed.
- **Mission: Collect hair (barbershop).** Alcatraz has a barbershop (or everyone's hair
  would be 6 feet long!). Sweep the floor and collect the hair to put on your fake head.
- **Dig:** Use the spoon to dig through the wall behind the air vent in your cell, at night
  while music hour covers the noise.
- **Night bed check:** Guards check the cells with flashlights. You have to get the fake head
  into your bed before the check (about 5 minutes) and get into the vents, so the guards are fooled.
- **Order:** day → cafeteria spoon → art class (paper and paint) → barbershop (hair)
  → night → fake head in bed → dig → into the vents.
- **Guards:**
  - **Spotted:** an alarm goes off and guards chase you. You're safe if you get back to your cell.
  - **Caught:** back to your cell, and the level restarts. (No "hole" punishment cell.)
- **End:** The dug hole leads into the vents and pipe hallway behind the cells. Going through
  it starts Level 2.

## Level 2: Secret Passages (Obbies)

**Goal:** Get through the secret passages behind and under the prison.

- When you drop through the hole, a big **"STAGE 2"** title pops up.
- **12 obbies, 12 checkpoints.** Finish an obby and you reach a checkpoint. Fall or die and you
  go back to the last checkpoint.
- **Obby ideas (Dylan's):**
  1. **Floating blocks:** jump from block to block.
  2. **Rope swing over lava:** jump on, swing across, jump off.
  3. **Spike floor:** a floor with holes. About 2 seconds after you step near, spikes shoot up.
  4. **Trip wire tiles:** step on the wrong tile and a sword or axe swings down, or a trap
     goes off, or the guards are alerted.
  5. **Security cameras:** big red spotlight circles sweep the floor. If one touches you, traps
     go off and guards come through a door into that room.
  6. **Fireball cannon at the exit:** dodge the fireballs to get out.
- **Lava?** Yes. It's a game, it doesn't need to be realistic.

## Level 3: Boss on the Boat

**Goal:** Defeat the boss so the boat can take you back to San Francisco and freedom.

- **Getting there:** Climb to the dock and **steal the guards' boat** (a big ship).
  The dock guards hear it start and press their alarm buttons, which summons the boss.
- **The boss: The Warden.** A giant warden in knight-style armor, with a shield and a giant sword.
- **Big health bar** across the top of the screen. He gets angrier as his health drops.

**Phase 1: The Warden's Ship**
- The Warden flies in on his ship. You sit in a machine-gun chair on the boat, grab
  the handles and fire.
- The ship has **6 weak spots**. Hit all 6 and the ship crashes. The Warden jumps down onto your boat.
- Beating the ship gives you a **pistol with unlimited ammo**.

**Phase 2: The Warden on Your Boat**
- He has **4 armor pieces** (the weak points). Shoot each one until it breaks off.
- When all the armor is off, an orange rectangle appears on his body and he can run.
- Then shoot him in the **face 10 times** to win.
- **His attacks:**
  - **Sword slam:** smashes the deck and part of the floor turns to lava for about 5 seconds.
  - **Sword swipe:** sends out a laser wave you have to dodge.

---

## Open Questions

**Pick up here next session:**

- **Q19:** What does the orange rectangle on the Warden do? (A sign he's angry and faster /
  a new weak spot / something else)
- **Q20:** With friends on the boat, who does what? (Take turns on the gun / everyone gets a
  gun seat / someone drives and dodges)
- **Q21:** Lives: unlimited tries back to checkpoint, 3 lives then restart the level, or
  different for each level?
- **Q22:** Prizes: badges, coins for skins and hats, a secret ending, or nothing?
- **Q23:** The ending: what happens when you reach San Francisco?
- **Q24:** The game's name.
- Then: put the whole plan together and choose what to build first.

## Build Notes (for Dad)

- **Platform: Roblox.** Chosen because Dylan wants friends to join from their own houses,
  and Roblox gives us online multiplayer, blocky characters, physics and ropes for free.
- **How we'll build:** Roblox Studio + Claude Code both running on Dad's computer
  (desktop app or terminal), connected so Claude can work inside Studio. Scripts are in Luau.
- **Account:** The game should be owned by Dad's own adult Roblox account.
- **Characters:** Blocky figures built from simple shapes and colors that look like each
  prisoner. We won't put the real photos into the game itself.
- **Content rating:** There's shooting in Level 3. Keeping it cartoony (no blood, the
  Warden falls over or explodes into blocks) keeps the game OK for young players
  on Roblox's maturity rating.
- **Size check:** Level 1 has the most new systems (guard patrols and vision, chasing, picking
  up and hiding items, crafting, digging). Level 2 uses standard Roblox obby parts, so it's the
  quickest to build. That makes Level 2 a good candidate for Stage 1 of the build.
