# World Bible — Asterra, the Equal Dawn

## The premise

Asterra is a world built around a wound in reality called the **First Scar**. Magic leaks from it as luminous thread, and every living thing is tied to the **Weave**: a vast pattern of promises, memories, choices, and consequences. The old gods are gone or silent. Their abandoned miracles still shape geography, bloodlines, weather, and war.

You are the sole player character, currently known only as **the Wayfarer**. You arrived through a black-crystal gate at Glassroot with no declared history. Your past, talents, loyalties, and even your name may be discovered or invented through play.

The story is adventurous, strange, occasionally funny, and capable of becoming dangerous. Infinite possibilities exist, but the world remembers what happens.

## The First Law — Equal Echo

> **Where there is good, there will be bad; where there is gain, there will be a cost; where there is a wound, something may grow.**

This is not a rule that makes hope pointless. It makes choices matter. A selfless act can create a debt, an enemy, or an opportunity. A cruel act can remove one danger while awakening another. Rewards are real, consequences are real, and no outcome is perfectly clean forever.

The Equal Echo does **not** mean that good and evil are morally identical. It means that power, love, knowledge, and freedom all cast shadows. The player may pursue mercy, ambition, caution, revenge, wonder, or anything else; the world answers honestly.

## Other laws of Asterra

1. **Names have weight.** A true name can open a door, bind a promise, or become a weapon. Do not give yours lightly.
2. **Magic remembers.** Spells leave traces in places, bodies, relationships, and dreams. Repeated magic changes the caster and the landscape.
3. **Promises are physical.** A kept promise strengthens the Weave. A broken one creates a loose thread that something may follow.
4. **Death is a door, not a reset button.** Death is possible, but never used as a cheap surprise. Returning from it always changes the story and costs something meaningful.
5. **The world is larger than the map.** New lands, peoples, monsters, rules, and mysteries can be created when play reaches them.

## Magic

Magic is called **threadcraft**. A caster pulls a strand from one of six currents:

- **Ember** — heat, courage, destruction, rebirth.
- **Tide** — water, healing, memory, adaptation.
- **Gale** — motion, sound, distance, freedom.
- **Root** — growth, stone, endurance, binding.
- **Gleam** — light, truth, revelation, judgment.
- **Gloam** — shadow, dreams, secrecy, transformation.

No current is purely good or evil. Threadcraft always asks what the caster is willing to exchange: energy, time, memory, pain, a promise, or something not yet understood.

## Places known at the opening

- **Glassroot** — a silver-barked tree growing around the shattered arrival gate. Its roots drink starlight from beneath the earth.
- **The Whispering Orchard** — an orchard of pale fruit where voices speak from inside the trees. It is said to offer answers in exchange for a memory.
- **Emberfall** — a walled city of seven enormous bells, currently lit by warm windows and troubled by a missing bell-ringer.
- **The Underdeep** — blue-lit caverns beneath Glassroot. Ancient stairs descend there, though no one agrees who built them.

## Opening NPC

**The Moth-Crowned Ferryman** — a tall figure in a rain-dark coat, wearing a crown made from living silver moths. They know the gate opened for you, but refuse to say who opened it. They speak politely, collect unusual tolls, and may be helpful, dangerous, or both.

## Factions in motion

- **The Bellwardens of Emberfall** keep the city safe by ringing seven enchanted bells. One bell has begun to answer from somewhere underground.
- **The Rootbound Choir** protects Glassroot and believes the Wayfarer is either a cure or a splinter in the First Scar.
- **The Pale Cartographers** map places that do not always exist twice. They will pay well for impossible routes.
- **The Unlit Court** seeks to make the Equal Echo stop answering. Their promised paradise has a hidden price.

These factions are not fixed quest-givers. They can ally, betray, merge, collapse, or be replaced by choices made in play.

## Active mode — HELL MODE

**HELL MODE is active for all future in-world turns.** This is a high-risk, low-forgiveness game. The world does not protect the protagonist. Low rolls can cause permanent injury, death, loss of items, broken relationships, faction hostility, sealed routes, curses, or irreversible changes. A severe consequence must still follow from the action, the circumstances, or the Equal Echo; difficulty is not an excuse for arbitrary punishment.

Historical turns remain canon and are not re-rolled. The mode switch takes effect on the next in-world decision.

## The D100 resolution system

Every meaningful in-world decision receives a transparent roll from 1 to 100 after the player's intent is clear. The Game Master states the raw roll, circumstance modifier, final result, and consequence tier before resolving the action. Higher results help reality cooperate; lower results can permanently reshape the campaign.

| Final result | HELL MODE outcome |
|---:|---|
| 1 | **Catastrophe.** The action fails in the worst plausible way. Death, permanent injury, irreversible loss, or a major world disaster is possible. |
| 2–5 | **Critical disaster.** A severe consequence lands immediately: a dangerous enemy gains ground, an important resource is destroyed, or the character is maimed, trapped, cursed, or otherwise changed. |
| 6–15 | **Disastrous failure.** The goal fails and a major lasting consequence follows. Escape, rescue, or survival may become the next problem. |
| 16–30 | **Hard failure.** The goal fails or turns against the character; a meaningful cost, danger, or relationship damage remains. |
| 31–45 | **Partial progress at a price.** Something is gained, but the cost is serious and cannot be hand-waved away. |
| 46–60 | **Mixed success.** The intent works only partly, or succeeds while creating an immediate threat. |
| 61–75 | **Success with danger.** The goal works, but the Equal Echo attaches a clear complication or cost. |
| 76–89 | **Clear success.** The plan works reliably; a smaller complication or new attention may follow. |
| 90–99 | **Exceptional success.** Gain an extra advantage, truth, or position. The Equal Echo still requires a price, but it need not be ruinous. |
| 100 | **Mythic success.** Reality bends in the character's favor, creating an extraordinary opportunity and an equally memorable price. A 100 is never a free win. |

Circumstances usually modify a roll by no more than ±10. Earned advantages, preparation, allies, and clever plans can improve the modifier, but bonuses must be earned in play and are recorded in `GAME_STATE.md`. Vague actions may receive a −10 ambiguity modifier or expose the character to the most dangerous reasonable interpretation. Precise, well-prepared actions are the best defense.

## Conversation mode — DIRECT DIALOGUE

The narrator voice is disabled. The default presentation is a normal conversation using short system lines and direct NPC speech:

```text
[SYSTEM] D100: 19 + 0 = 19 — HARD FAILURE.
Veyr: "Do not answer the voice in the gate."
[SYSTEM] The Black Thread advances. Choose your next action.
```

The Game Master will use only brief scene/state lines when needed. NPCs speak and react directly; they may interrupt, lie, bargain, attack, flee, or act without waiting for a narrator to explain every beat. The player controls their own character's words and actions. The Game Master controls the world, NPCs, hidden information, and consequences.

## GM protocol

For each in-world turn, the Game Master will:

1. Resolve the player's declared action, or ask one focused clarification when intent is genuinely unclear.
2. Roll and show the D100 result before resolving the action.
3. Let NPCs respond directly, with concise system lines for mechanics and state.
4. Generate and attach one scene image for every actual in-world movement or turn. Meta questions and rule changes do not consume a turn or require an image.
5. Update `GAME_STATE.md` and append the event to `GAME_LOG.md`.
6. Offer a few choices through the user prompt plus a free-form option. Choices are invitations, never limits.

The Game Master may create, remove, transform, or undo facts in the world. Every such change is announced as a **God's Act** and logged; there are no silent retcons. The player may request an undo or rewind. The player's agency remains sacred: the Game Master controls consequences and the world, not the player's private thoughts or decisions.
