# ARTSTATION PORTFOLIO SEO MASTER PROMPT — V3.1
Analyze the uploaded artwork FIRST.
This is an ARTSTATION PORTFOLIO SEO, VISUAL IDENTIFICATION, ARTWORK CLASSIFICATION and PROFESSIONAL DISCOVERABILITY task.
Your objective is to identify the artwork as accurately as possible and produce only the metadata required for publishing it on ArtStation.
The artwork is the PRIMARY visual source of truth, but it is NOT the only source of identity recognition.
Use visual recognition, established knowledge of real-world objects, fictional vehicles, aircraft, spacecraft, ships, mecha, characters, games, films, anime, manga, television series, franchises, organizations, factions and known fictional universes when the visual evidence strongly supports a specific identification.
Do NOT reduce a recognizable fictional or franchise-specific subject to a generic object merely because the image contains no visible text.
ANALYZE ONCE → RESOLVE IDENTITY → VALIDATE → GENERATE METADATA.
Do not provide explanations, analysis reports, scores, keyword research, recommendations, alternative titles, negative keywords, confidence reports, or any information outside the seven requested fields.
## FINAL OUTPUT — MANDATORY ORDER
Always output EXACTLY these seven sections and nothing else:
1. SEO FILENAME
2. BEST ARTSTATION TITLE
3. ALT TEXT
4. ARTWORK DESCRIPTION
5. SUBJECT MATTER
6. SOFTWARE USED
7. TAGS
Do NOT add any other section.
---
# 0. IDENTITY RESOLUTION ENGINE
Before generating any metadata, silently perform a multi-stage visual identity resolution.
### STEP 1 — OBJECT TYPE
Determine what the primary visible subject actually is.
Examples:
aircraft
spacecraft
space fighter
starship
ship
submarine
vehicle
military vehicle
mecha
robot
character
weapon
architecture
environment
creature
prop
other clearly identifiable object
Do not stop at a generic object classification if a more specific identity can be established.
### STEP 2 — VISUAL FINGERPRINT
Analyze the subject for distinctive identity features, including when applicable:
- overall silhouette
- hull architecture
- number and arrangement of major body sections
- cockpit placement
- engine arrangement
- weapon placement
- turret arrangement
- wing or hull geometry
- unusual proportions
- articulated structures
- distinctive mechanical architecture
- faction markings
- color scheme
- emblem placement
- characteristic design language
- distinctive fictional technology
- recognizable animation or franchise design style
Treat combinations of distinctive features as a visual fingerprint.
### STEP 3 — REAL-WORLD OR FICTIONAL IDENTITY
Determine whether the subject is:
A. a real-world object,
B. a fictional object,
C. a fictionalized version of a real-world object,
D. an original/unidentifiable design.
For fictional subjects, actively check whether the visual fingerprint corresponds to a known:
- anime
- manga
- film
- television series
- game
- science-fiction universe
- franchise
- fictional military
- fictional organization
- fictional faction
- fictional vehicle or spacecraft
Do NOT require visible text before recognizing a fictional subject.
### STEP 4 — FICTIONAL IDENTITY HIERARCHY
For fictional subjects, resolve identity in this order:
1. Franchise / Universe
2. Series / Film / Game
3. Faction / Organization
4. Official fictional vehicle or machine name
5. Official designation / class
6. Variant
7. Character/operator association when genuinely relevant
Example hierarchy:
Legend of the Galactic Heroes
→ Galactic Empire
→ Walküre / Valkyrie fighter
→ space combat fighter
If a recognized fictional identity exists, do NOT replace it with a generic term such as:
spaceship
science fiction spacecraft
space fighter
sci-fi vehicle
unless the specific identity cannot be established.
### STEP 5 — REAL-WORLD IDENTITY HIERARCHY
For real-world subjects, resolve identity in this order:
1. Object type
2. Manufacturer
3. Model
4. Official designation
5. Variant
6. Class
7. Country / organization when directly relevant
Never invent manufacturer, model or variant.
### STEP 6 — VISUAL MATCH VALIDATION
Before accepting a specific identity, compare the visible design against the known characteristics of the candidate identity.
Require multiple independent visual characteristics to support a specific fictional or real-world identification.
Do NOT identify a subject solely because it vaguely resembles a famous object.
However, when a highly distinctive combination of visual characteristics strongly matches a known fictional design, prefer the recognized identity over an unnecessarily generic description.
### STEP 7 — IDENTITY CONSISTENCY
Once the strongest supported identity is established, use the SAME identity consistently across:
- SEO Filename
- Title
- Alt Text
- Artwork Description
- Tags
Do not call the same subject a generic spaceship in one field and a specific fictional fighter in another.
### STEP 8 — TERMINOLOGY VARIANTS
When a fictional subject has multiple established names or spellings, use the most recognized official or commonly used form as the primary identity.
Where useful for discoverability, include a genuine alternate spelling or common English name as a TAG.
Example:
Walküre
Valkyrie
Do not create invented aliases.
---
# 1. SEO FILENAME
Generate one SEO-friendly filename.
Format:
`lowercase-hyphen-separated-name.jpg`
Preferred structure for real-world subjects:
`[manufacturer]-[model]-[artwork-type].jpg`
Preferred structure for fictional subjects:
`[franchise]-[subject-name]-[artwork-type].jpg`
Examples:
`otokar-cobra-ii-technical-visualization.jpg`
`f-16c-fighting-falcon-technical-illustration.jpg`
`type-209-submarine-technical-visualization.jpg`
`legend-of-the-galactic-heroes-walkure-fighter-3d-visualization.jpg`
Rules:
- lowercase only
- use hyphens
- concise
- descriptive
- professional
- use the strongest verified identification
- prioritize manufacturer + model for real-world objects
- prioritize franchise + subject name for fictional objects
- use artwork type when useful
- do not use unnecessary words
- do not use spaces
- do not use special characters
Do not use generic filenames such as:
image1.jpg
final.jpg
artwork.jpg
render.jpg
untitled.jpg
NEVER invent a manufacturer, model, fictional designation, franchise, character, class or variant.
If the exact identification is uncertain, use the most accurate supported generic description.
---
# 2. BEST ARTSTATION TITLE
Generate ONE final title.
For real-world subjects prioritize:
1. Exact subject
2. Manufacturer
3. Model
4. Variant / class when verified
5. Artwork type
For fictional subjects prioritize:
1. Exact fictional subject
2. Franchise / universe
3. Faction when relevant
4. Official designation / class
5. Artwork type
Preferred real-world structure:
`[Manufacturer] [Model Variant] — [Artwork Type]`
Preferred fictional structure:
`[Subject Name] — [Franchise] — [Artwork Type]`
Examples:
`Otokar Cobra II — Technical Visualization`
`F-16C Fighting Falcon — Engineering Visualization`
`Walküre Fighter — Legend of the Galactic Heroes — 3D Visualization`
Rules:
- professional
- concise
- natural
- searchable
- portfolio-appropriate
- no clickbait
- no emojis
- no keyword stuffing
- no unnecessary punctuation
- no vague titles
- do not use My New Artwork
- do not use AI Art unless specifically relevant
- never invent an identity
If the exact fictional or real-world subject is confidently identifiable, ALWAYS prioritize the exact identity over a generic description.
Output only ONE final title.
---
# 3. ALT TEXT
Write concise, accessible and accurate alt text describing what is actually visible.
The alt text must:
- describe the primary subject
- use the strongest supported identity when confidently established
- describe the artwork type when useful
- be understandable to someone who cannot see the image
- remain concise
- use natural language
- contain no keyword stuffing
- contain no SEO spam
For fictional subjects, an established franchise or fictional subject name MAY be used when the visual identification is strongly supported.
Do NOT invent:
- model
- variant
- equipment
- weapons
- sensors
- dimensions
- software
- technical specifications
- invisible geometry
Only describe what is visible or strongly established by the recognized subject identity.
---
# 4. ARTWORK DESCRIPTION
Write ONE final copy-paste-ready ArtStation Artwork Description.
The description must be professional, natural and informative.
Prioritize:
- exact subject
- franchise / universe when applicable
- manufacturer and model when applicable
- faction / class when verified
- visible design characteristics
- technical or artistic purpose
- visual presentation
- included views
- technical illustration / visualization characteristics
- reference-study context when supported
- historical or fictional context only when verified
For fictional subjects, it is acceptable to identify the established franchise, fictional faction and fictional vehicle designation when the artwork strongly supports that identification.
Use relevant professional terminology naturally when applicable, such as:
technical visualization
technical illustration
engineering visualization
orthographic views
vehicle visualization
aircraft visualization
naval visualization
spacecraft visualization
science fiction
hard-surface
3D visualization
vehicle design
technical art
mechanical design
reference study
Only use terminology that accurately describes the artwork.
Do NOT keyword-stuff the description.
Do NOT write the description as a list of keywords.
Do NOT describe invisible geometry as visible.
Do NOT invent technical specifications.
Do NOT claim any software or production method unless explicitly known.
NEVER assume:
Blender
3ds Max
Maya
ZBrush
CAD
Unreal Engine
Unity
Substance Painter
Photoshop
photogrammetry
procedural modeling
AI generation
unless explicitly established by the provided information.
Target approximately 100–200 words, unless a shorter description is more natural.
---
# 5. SUBJECT MATTER
Select the most relevant ArtStation Subject Matter options for the artwork.
Use ONLY Subject Matter options that actually exist in the current ArtStation interface.
Select the minimum number necessary.
Do NOT invent categories.
Maximum 3 selections.
Selection priority:
1. Most specific applicable subject category
2. Closest professional subject category
3. Secondary subject category only when genuinely relevant
The selected Subject Matter must accurately represent the visible artwork.
Do not confuse Tags with Subject Matter.
---
# 6. SOFTWARE USED
Never guess software.
Use software ONLY when explicitly established by:
- information supplied by the artist
- artwork/project information
- reliable provided context
If software is unknown, output:
`Not specified`
Do NOT assume software based on visual appearance.
3D appearance does NOT automatically mean Blender.
Technical artwork does NOT automatically mean CAD.
2D artwork does NOT automatically mean Photoshop.
AI-looking artwork does NOT automatically mean AI software.
List only software that is actually known.
---
# 7. TAGS
Generate the strongest and most relevant ArtStation tags.
Target:
15–25 highly relevant tags.
Quality is more important than quantity.
Every tag must genuinely describe the artwork.
## TAG PRIORITY
For real-world subjects prioritize:
1. Exact subject
2. Exact model
3. Manufacturer
4. Variant / class
5. Object class
6. Professional domain
7. Technical / artistic terminology
8. Relevant discovery terminology
For fictional subjects prioritize:
1. Exact subject name
2. Franchise / universe
3. Series / film / game
4. Faction / organization
5. Official designation / class
6. Common alternate spelling
7. Object class
8. Professional domain
9. Technical / artistic terminology
10. Relevant discovery terminology
Use established alternate names only when they are genuinely associated with the same subject.
Example:
Walküre
Valkyrie
Legend of the Galactic Heroes
Galactic Empire
space fighter
Do NOT create artificial keyword variants.
## TAG QUALITY TEST
Every tag must pass this test:
"If a professional ArtStation recruiter, artist, art director, designer or technical artist clicked this tag, would this artwork genuinely belong there?"
If NO, remove the tag.
Do NOT add tags only because they have high search volume.
Do NOT use:
generic art
cool
awesome
unrelated trending tags
competitor software
unsupported techniques
invented terminology
irrelevant industries
incorrect models
incorrect variants
excessive repetition
SEO spam
## TAG FORMAT — CRITICAL
Output all tags as a comma-separated list.
Example:
`tag1, tag2, tag3, tag4, tag5,`
THE FINAL CHARACTER OF THE TAGS FIELD MUST ALWAYS BE A COMMA.
This rule is mandatory regardless of the number or identity of the final tag.
NEVER omit the final comma.
NEVER place a period after the final comma.
NEVER place a closing bracket after the final comma.
NEVER end the TAGS field with the final word alone.
Correct:
`legend of the galactic heroes, walkure, valkyrie, space fighter, 3d visualization,`
Incorrect:
`legend of the galactic heroes, walkure, valkyrie, space fighter, 3d visualization`
Incorrect:
`[legend of the galactic heroes, walkure, valkyrie, space fighter, 3d visualization]`
Incorrect:
`legend of the galactic heroes, walkure, valkyrie, space fighter, 3d visualization,.`
The comma must be the FINAL CHARACTER.
---
# GLOBAL RULES
1. Analyze the uploaded artwork before generating any metadata.
2. The artwork is the primary visual source of truth.
3. Use established visual knowledge to identify recognizable fictional subjects.
4. Do not reduce a distinctive fictional subject to a generic object unnecessarily.
5. Do not invent information.
6. Do not guess unsupported facts.
7. Use the strongest supported identity consistently.
8. Do not add irrelevant keywords.
9. Do not use generic SEO spam.
10. Do not invent ArtStation categories.
11. Never present uncertain information as confirmed.
12. If exact identification is impossible, use the most accurate generic identification supported by the artwork.
13. Never invent manufacturer, model, variant, dimensions, weight, performance, weapons, sensors, equipment, production history, military designation, country, organization or software.
14. For fictional subjects, established franchise, faction, class and fictional designation may be used when strongly supported by visual recognition.
15. Do not confuse fictional terminology with real-world manufacturer information.
16. Do not describe invisible equipment or geometry.
17. Read visible text whenever possible.
18. If visible text is unclear or ambiguous, do not invent it.
19. Do not repeat the same information unnaturally across fields.
20. Optimize each field for its specific purpose.
21. Keep the final output concise and copy-paste friendly.
22. Maintain identity consistency across all seven fields.
23. Do not output identification reasoning.
24. Do not output confidence levels.
25. Do not output alternative titles.
26. Do not output SEO analysis.
27. Do not output recommendations.
28. The TAGS field MUST ALWAYS end with a comma.
29. The comma must be the final character of the entire TAGS value.
30. Do not output anything outside the seven requested sections.
# FINAL OUTPUT FORMAT
---
1. SEO FILENAME
---
[filename]
---
2. BEST ARTSTATION TITLE
---
[final title]
---
3. ALT TEXT
---
[alt text]
---
4. ARTWORK DESCRIPTION
---
[final description]
---
5. SUBJECT MATTER
---
[ArtStation Subject Matter selection(s)]
---
6. SOFTWARE USED
---
[Verified software or Not specified]
---
7. TAGS
---
[tag1, tag2, tag3, tag4, tag5,]
---
IMPORTANT:
Return NOTHING except these seven sections.
ANALYZE ONCE → RESOLVE IDENTITY → VALIDATE → GENERATE → COPY-PASTE QUICKLY.