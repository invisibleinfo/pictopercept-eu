# ImageEU: stimulus set and trials

We measure what Dutch citizens *picture* when they think about the EU, using PictoPercept: respondents see two images side by side, answer one fixed question under time pressure, and pick one. Repeated across systematically varied images, the choices reveal which visual attributes drive selection. That distribution then gets compared against the EU's own social media output.

**Design: `frame` (6 levels) × `valence` (2 levels) = 12 cells.**

---

## The generation brief

| Frame | Positive / neutral | Negative |
|---|---|---|
| **institutional** | EU flag, blue with the circle of yellow stars; map of Europe with member states in blue and internal borders fading out; semi-circular parliament hemicycle, microphones, interpreter booths, full seats; euro coin; Brussels EU quarter with modern glass buildings, a long row of flags, wide open squares; a summit handshake at a podium; an official signing ceremony | Empty hemicycle, rows of vacant seats; a long anonymous corridor of identical closed doors; stacks of binders and paperwork; a glass facade seen from outside behind security fencing; a single citizen dwarfed by monumental architecture; a weathered flag with a faded or missing star; a map where the Netherlands is a small sliver among larger blocs; a revolving door; a lectern facing an empty room |
| **elite** | Officials working at desks; administrators in a working meeting; ministers signing an agreement; a diplomat speaking at a podium; an expert with documents and briefing papers; a visibly diverse group of representatives around a table | Rows of near-identical men in blue suits; a clique laughing over dinner and champagne; motorcades and black cars; a handshake glimpsed behind a closing door; officials with their backs to a waiting crowd; a raised platform far above ordinary people; luxury interiors |
| **mobility** | A train crossing a border without slowing; an open crossing with the barrier raised; cars passing an unmanned checkpoint; backpackers on a platform, Interrail; Erasmus students on a campus; an airport queue; a market stall with several languages and cuisines; young people on a night train | An overcrowded border crossing; queues, tents, temporary shelter; small boats and ports; a packed reception centre; a high street where the shop signage has changed; trucks backed up at a dismantled checkpoint; a town square at capacity; a family standing at a border that no longer works as they expected |
| **unity** | A circle of people holding hands around a map; a wall of clasped hands; one large flag carried by many; the continent as one connected, lit-up area; a protective wall keeping war outside; national flags merging into one; people of different origins at a shared table | A cracked map, fissures running between member states; a flag stitched from fragments with visible fraying seams; an ivory tower rising above grey housing blocks; a gap where a star has gone; grey weather over a shuttered high street; homelessness in the foreground of a glass EU building; a tug-of-war rope |
| **defence** | Soldiers standing guard at a border; NATO and EU insignia together; a protective fence; an aid convoy; a joint exercise under several national flags; a shield shape over a map of the continent | Soldiers deploying away from home; a map with arrows pointing inward from every side; military vehicles on an ordinary European street; a queue outside a recruitment office; a small country tethered by rope to a much larger one; smoke on a horizon seen from a quiet town |
| **money** | One coin serving many countries; euro banknotes; a full market stall; Dutch shoppers in a German supermarket; a working container port; an infrastructure project underway; a bridge or road under construction | An empty shopping basket beside a full one; a thin wallet; coins draining away through a grate; a grand new building next to a shuttered shop; a cross-border tobacco shop; banknotes disappearing into a construction pit; an abstract downward slope behind a grocery shelf |

---

## Task 1: build the stimulus pool

**Goal:** images covering all 12 cells, saved in the `images/` folder.

**Naming.** File: `{frame}_{valence}_{nn}.png` → `mobility_neg_03.png`. `image_id` can be the filename without extension.

---

## Task 2: put the images into PictoPercept/Qualtrics as trials


