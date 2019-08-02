# Open-CYOA

# Overview
- OCYOA is an open choose your own adventure game. The premise is to create a series of prompts with actions available, that point to different prompts with possible actions to tell a story.
- Unique to this project is to allow the participants to actually write in responses and grow the story together, with certain archetypical outcomes and beginnings, to allow for the addition of narrative and puzzles that mesh stories together to be as long or short as anyone adventures.

# Proof of concept
- Each prompt must have a minimum of 2 options to choose from, and ideally will have around 4.
- Checkpoints should exist and remain unlocked for accounts as reference points.
- Fast travel through the story should allow for reverting and skipping to previously visited points.
- There should always be a Create Your Own Action prompt to write your own node as a new point to visit.
- The ability to vote and promote the prompt and the actions. This will determine the order of the actions when read.
- The ability to report actions (adding a category to filter out NWS and NLS prompts/actions)

Creating a prompt
- Has the following fields:
1. Series Title (optional)
2. Parent node(s): by default where this action was created, but may be linked together later
3. Actions (child node(s)): 
4. Checkpoints (references outside of a series or previous popular nodes that are a beginning or ending)
5. Story text
6. Action text 
7. Series Category (optional)
8. External media* optional and only available to a premium / popular series (could benefit puzzles tremendously, as well as entertainment and prizes)


BONUS:
- Play alone or together. Playing together should allow for votes to happen in a time frame where the path is chosen. Creation wouldn't be possible when playing together.
- Visualize nodes and edges of potential paths through the story. Ideally as a force directed graph of edges and nodes. Also acceptable is a 2D drawing using underscores ("_"), pipes ("|") to connect nodes, doorways to represent puzzles ("="), and the at ("@") to represent loops. Could use "#" to represent previously visited locations, "*" to show where we are, and "?" to show there is more to explore

# Archetype Beginnings
- You awake in a strange room. 
- A hallway where you are able to browse starting points for various series, and connect to hallways with various categories used to filter the potential outcomes
- Safe mode lever (filtering out NWS options)

# Archetype Endings
- Reach a safe place (save point)
- Reach the outdoors
- Return to a hallway (navigation point)
- Find childhood pet and a perfectly preserved version of favorite home
- Reach an ideal destination (island, vacation, mountain, snowy valley, waterfall)
- Defeat a monster
- Release a long lost friend / love 
- Reunite with that long lost friend / love
- Discover lost treasure
- Uncover a new discovery about the nature of the universe
