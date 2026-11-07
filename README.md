# NPC Expansion for HumanitZ

> **The world was never empty. Now it's alive.**

When HumanitZ 1.1 gave us survivors to recruit, I kept thinking: *where did these people come from?* Who were they with before they met me? Who's still out there?

So I built them a world. Out past your walls there are now other communities trying to make it too. They have names and faces, leaders and grudges, families and fears. They run out of food and send people out to find more. Some of those people don't come back. They get sick, bury their dead, argue about who should lead, and they **remember what you did**. Help one and its neighbors hear about it. Betray one and they hear that too.

And your own clan stops being a list of workers. Your people make friends, fall in love, become rivals, start families, grieve, and sometimes pack up and leave because they're unhappy.

None of it shows you a number. You find out how people feel by talking to them and watching what they do.


## Downloads

- **Nexus Mods:** [nexusmods.com/games/humanitz/mods/180](https://www.nexusmods.com/games/humanitz/mods/180)
- **GitHub:** [latest release](https://github.com/Lionademais/humanitz-npc-expansion/releases/latest)

| File | For |
|---|---|
| `NPCExpansion_Client_v1.0.0.zip` | every player (single-player, hosted and dedicated) |
| `NPCExpansion_DedicatedServer_v1.0.0.zip` | dedicated server only (needs [NPC Mechanics on Dedicated Server](https://github.com/Lionademais/humanitz-npc-community-fix)) |

Checksums: `SHA256SUMS.txt`. Source code will be added to this repository later.

## Requirements - please read before downloading
- **Single-player and hosted games:** only the **NPC Expansion client** (the host and everyone who joins). Nothing else is needed.
- **Dedicated server only:** the server needs [NPC Mechanics on Dedicated Server](https://www.nexusmods.com/games/humanitz/mods/171) **and** the NPC Expansion server file. Players need **both clients**: NPC Mechanics 1.0.8 and NPC Expansion.
- Made for the HumanitZ update of 2026-10-30 (1.1X). After a game update, a new version of the mod may be needed.
- Back up your saves before installing or removing.

## What it brings

### Living communities
- Factions with their own leader, government, food stores, weapons and flag. Iron-fisted rule, councils or assemblies, with coups and elections.
- Walled settlements built to fit the land: gates on the natural approach, towers on high ground, houses full of real containers that keep what's inside, and safes locked with codes.
- People come and go. Newcomers arrive over time, the sick are treated or sent away, the hungry head out on risky expeditions.
- A spokesperson at the gate, a quartermaster who trades, guards on patrol, a watchman in the tower, and a dog that barks at strangers.
- It all keeps happening when you're not around.

### Relationships that matter
- Every person and every faction remembers you: trust, affection, respect and favors owed, slowly fading if you disappear.
- Rumors travel between settlements.
- Trade, donate, propose agreements, ask for reinforcements, ask a friend to strike a rival, or recruit someone, if they trust you more than their own people.
- Radio contact with the communities whose frequency you've earned.

### Danger and consequence
- Raids on your clan, with threats, warnings, scouts and real attacks. Sieges between factions that you can join or just watch.
- Attack a community and all of it answers: the able take up arms, guards leave their posts, the vulnerable run for shelter. Wipe them out and their neighbors will never forget.
- Take prisoners: tie them up, interrogate them, lock them in your clan's cell, offer them a place, or let them go.

### A clan that is a community
- Build a gathering fire, a task board, an infirmary, a clan cemetery, a training area and a prison cell, with the game's own building menu.
- Your people bond, fall in love, become rivals, start families, grieve, train their crafts, and sometimes leave when they're unhappy.
- Keep the base clean, or live with trash, rats, flies, sickness and the zombies the smell brings in.
- Visitors knock at your gate. Answer them, or don't.

### And more
- Over forty new personality traits (likes, fears, ambitions, values), discovered through conversation.
- A new conversation screen with portraits, relationship bars, topics, gifts and orders.
- A clan diary where everything that happens becomes a line of your story.
- Admin settings in game to tune events, raids, sieges, memory and more for your world.
- Ten languages, following your game language. Players with different languages on the same server each see their own.

## Installation
- **Client:** install with Vortex, or copy NPCExpansion_Client_P.pak to ...\HumanitZ\HumanitZ\Content\Paks\~mods\ (create ~mods if it doesn't exist). Keep only one copy of the pak.
- **Dedicated server (stopped):** extract the server zip into the server's root folder (the one that contains HumanitZServer). The four NPCExpansion_Server_P files (.pak, .ucas, .utoc, .sig) go together to HumanitZServer/Content/Paks/. NPC Mechanics must be installed on the server too.
- The mod keeps its own data in Saved/SaveGames/&lt;world&gt;_HZX.sav (with a backup copy next to it). Nothing is written into the game's own save.
- Disable the mod before joining servers that don't run it. A player without the Expansion client is disconnected when joining a server that runs it.
- Full instructions are in LEIA-ME.txt inside each zip (English + Portuguese).

## Uninstall
- **Remove the mod's buildings first** (fire, task board, infirmary, cemetery, training area, cell): in build mode, hammer in hand, aim at the piece and hold the remove key (X). If you remove the mod with them still standing, they disappear and the materials don't come back.
- Server: with the server stopped, delete the four NPCExpansion_Server_P files. Client: disable it in Vortex or remove the pak from ~mods.
- Your world still opens. Recruited members stay in your clan.

## Known limitations
- Performance near the larger settlements is heavier than I'd like. Optimization is coming in an update.
- Dedicated servers were tested on Linux. Windows dedicated servers haven't been tested yet.
- On a slope, one end of a gate can float slightly above the ground.
- Map trees can poke through the roofs of settlement houses.
- A new version of the mod can rebuild the faction settlements in new places (relationships, people and stories carry over).

## Compatibility
NPC Expansion changes very little of the game itself: BP_HmzPlayerController, BP_KaiHumanAI_Base and BTask_MoveToFriendly. Everything else is new content of its own. Other mods that replace those same assets may conflict (NPC Mechanics is made to work with it).

## Transparency: made with AI assistance
This mod was developed with the help of AI tools, including the mod's translations (not reviewed by native speakers, so corrections are welcome) and the cover art at the top of this page, which is AI-generated illustration, not in-game footage. The screenshots on the Nexus page are from the actual game with the mod. I tested everything myself in single-player and on a dedicated server.

## Feedback
This is the first public release, so there will be rough edges. If something breaks, please leave a comment or a bug report with your game mode (single-player, hosted or dedicated, and server OS) and what happened. I'd love to hear the stories your world tells you.

## Credits
- Interface font: Manrope, licensed under the SIL Open Font License 1.1 (`OFL_Manrope.txt` is included in both zips).
