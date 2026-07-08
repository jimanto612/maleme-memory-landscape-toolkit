# Maleme Memory Landscape Toolkit — Working Notes

> These are rough project notes for the open-source development of the Maleme thesis toolkit.  
> They are not final thesis writing. They are a place to keep research fragments, design decisions, mapping logic, questions, and unresolved problems.

---

## 0. Project frame

**Project title:** Maleme Memory Landscape Toolkit  
**Site:** Old Maleme airfield, Crete  
**Type:** Architecture thesis / open-source design-research toolkit  
**Core sequence:** WAR → SCAR → MEMORY → RECOVERY → PEACE

The project is not only about producing a final architectural proposal. It is about building a repeatable method for reading a wounded landscape and translating that reading into maps, diagrams, spatial interventions, material studies, and architectural drawings.

The site should not be treated as an empty field waiting for design. That would be weak. Maleme already contains memory, violence, absence, military traces, landscape scale, and silence. The architecture has to work with that existing thickness rather than covering it with a clean formal object.

---

## 1. Central thesis idea

The old airfield is approached as a landscape of memory rather than as a neutral plot.

The architectural question:

**How can a spatial intervention make memory legible without turning trauma into spectacle?**

The project should avoid the obvious museum answer. A building that simply “explains history” may become too literal. The stronger direction is a sequence of spatial conditions: exposure, distance, pause, compression, shade, fragment, horizon, and return.

The design should behave like a device for reading the landscape.

---

## 2. Working conceptual sequence

### WAR

War is not represented through theatrical destruction. It is represented through interruption, exposure, hard edges, fragments, and the inability of the landscape to be read as innocent.

Possible spatial translations:
- long axial movement;
- exposed walking lines;
- sharp material transitions;
- fragments that suggest damage without imitating ruins;
- tension between ground and sky.

### SCAR

The scar is not decoration. It is the mark that remains when the violent event has ended but has not disappeared.

Possible spatial translations:
- cut in the ground;
- linear trace following the airfield geometry;
- material weathering;
- discontinuous surfaces;
- visible joints;
- structures that do not fully close.

### MEMORY

Memory is unstable. It is not a clean archive. It appears through fragments, repetition, distance, and atmosphere.

Possible spatial translations:
- partial information;
- framed views;
- suspended shade;
- perforated surfaces;
- moments where the visitor must stop rather than simply pass.

### RECOVERY

Recovery should not mean erasing the scar. That would be sentimental and false. Recovery means learning to inhabit the scar without denying it.

Possible spatial translations:
- softer ground conditions;
- vegetation returning carefully;
- spaces of rest;
- filtered light;
- gradual opening toward the landscape.

### PEACE

Peace is not a decorative ending. It is a fragile condition produced after confrontation with memory.

Possible spatial translations:
- open horizon;
- shade without enclosure;
- quiet viewing point;
- minimal structure;
- low intervention that leaves the site dominant.

---

## 3. Site-reading notes

The old airfield should be studied through layers, not through a single plan.

Important layers:
- runway / airfield geometry;
- military history and Battle of Crete memory;
- surrounding agricultural landscape;
- horizon and sea orientation;
- road access and movement;
- existing vegetation and dry ground;
- ruins, remains, traces, and absences;
- tourist pressure / risk of superficial memorialization.

A strong map set should not just show “data.” It should reveal conflict.

Maps to develop:
- historical trace map;
- scar / absence map;
- movement and access map;
- horizon and view corridor map;
- material ground condition map;
- vegetation and exposure map;
- memory intensity diagram;
- intervention logic diagram.

---

## 4. Design language notes

The architecture must stay restrained. If it becomes too iconic, it betrays the site.

Avoid:
- monumental ego-object;
- fake ruin aesthetic;
- random parametric fragmentation;
- emotional clichés;
- over-designed memorial symbolism;
- museum-like object placed on the site without landscape logic.

Pursue:
- structural clarity;
- controlled fragmentation;
- dry material palette;
- slow movement;
- exposed joints;
- architectural silence;
- atmosphere through shadow and proportion;
- details that feel constructed, not theatrical.

---

## 5. Material notes

Potential materials:
- weathered steel / corten for memory, oxidation, time, exposure;
- concrete for ground contact, weight, and permanence;
- perforated metal or fabric for filtered shade;
- timber only if it has a clear reason and does not soften the project too much;
- gravel / compacted earth for walking surfaces;
- local stone or rough aggregate where the ground needs weight.

Material risk:
Corten can become too fashionable if used lazily. It must be justified by weathering, trace, and time — not because it looks “memorial.”

Fabric can become too resort-like if it is too clean or decorative. If used, it needs tension, shadow, wind, and fragility.

Concrete can become too brutal if not tied carefully to scale and ground.

---

## 6. Structural notes

The structure should express how it stands.

Important questions:
- What touches the ground?
- What hovers?
- Where is weight visible?
- Where is tension visible?
- Are the supports aligned with the conceptual sequence?
- Does the structural rhythm help the visitor understand time and movement?
- Do the joints show assembly, or is everything hidden behind image-making?

Possible structural language:
- repeated steel frames;
- light canopy on heavier supports;
- half-bridge / viewing ramp condition;
- fragment plates held by a clear secondary structure;
- visible bolts, plates, welded joints;
- supports that create rhythm without becoming decorative.

The project should not hide behind atmosphere. Atmosphere without structure is weak.

---

## 7. Drawing system notes

The open-source toolkit should include drawing logic, not only final images.

Useful drawing categories:
- analytical maps;
- concept sequence diagrams;
- plan at landscape scale;
- intervention plan;
- longitudinal section;
- cross sections;
- structural axonometric;
- material collage;
- detail fragments;
- final board layout logic.

Graphic language:
- off-white / muted background;
- black CAD linework;
- restrained greys;
- limited corten accent;
- no cheap dramatic render language;
- negative space;
- drawings should feel measured and severe.

Greek labels should be simple and controlled. No poetic overloading on every drawing.

---

## 8. AI research workflow notes

Claude / AI should not replace architectural judgment. It should help organize, critique, translate, and test the argument.

Useful AI tasks:
- summarizing sources;
- extracting themes from historical texts;
- structuring thesis chapters;
- stress-testing the design concept;
- producing alternative board descriptions;
- comparing precedents;
- rewriting Greek academic text;
- creating prompt templates for visual studies;
- checking if the argument has become sentimental or generic.

Danger:
AI can make everything sound important. That is dangerous. The project needs specificity: Maleme, the airfield, memory, landscape, material, movement, structure.

A good AI-assisted architecture workflow should include:
1. source input;
2. extraction of key claims;
3. design implications;
4. contradiction check;
5. drawing task;
6. critique;
7. revision.

---

## 9. Repository structure notes

Suggested GitHub structure:

```text
maleme-memory-landscape-toolkit/
├── README.md
├── LICENSE
├── NOTES.md
├── docs/
│   ├── project-frame.md
│   ├── site-reading.md
│   ├── memory-landscape-method.md
│   └── bibliography.md
├── templates/
│   ├── thesis-research-template.md
│   ├── precedent-analysis-template.md
│   └── board-critique-template.md
├── qgis-workflow/
│   ├── layer-structure.md
│   ├── map-export-settings.md
│   └── symbology-notes.md
├── cad-board-methodology/
│   ├── lineweights.md
│   ├── section-logic.md
│   └── board-layout.md
├── ai-research-prompts/
│   ├── source-extraction.md
│   ├── architecture-critique.md
│   └── greek-academic-writing.md
└── maleme-case-study/
    ├── site-notes.md
    ├── concept-sequence.md
    └── materiality.md
```

Need to avoid uploading an empty repo. Even short placeholder files are better than nothing if they explain the intention clearly.

---

## 10. Open questions

These are unresolved and should stay visible during the project:

- Is the intervention too symbolic?
- Is the runway treated as a real spatial trace or only as a diagram?
- Does the visitor experience the sequence physically, or only understand it from the board?
- Does the project respect the silence of the site?
- Is the structure honest, or is it just a graphic image?
- Are the materials chosen for meaning, performance, and aging — or only for aesthetic mood?
- What exactly is open-source here: the thesis, the method, the templates, the prompts, or all of them?
- Who is the toolkit for: architecture students, researchers, educators, or designers working on memory landscapes?
- How can the repo stay useful after the thesis submission?

---

## 11. Immediate tasks

- [ ] Create public GitHub repository.
- [ ] Upload README.md.
- [ ] Upload NOTES.md.
- [ ] Add LICENSE.
- [ ] Create folder structure.
- [ ] Add short documentation files to each folder.
- [ ] Add first version of AI research prompts.
- [ ] Add first QGIS workflow notes.
- [ ] Add CAD board methodology notes.
- [ ] Add Maleme case-study notes.
- [ ] Add bibliography file.
- [ ] Keep private material private if it includes unpublished university work or copyrighted sources.

---

## 12. Rough bibliography direction

Need to collect sources around:
- memory and place;
- architecture and phenomenology;
- landscape as archive;
- war landscapes and memorials;
- ruins and traces;
- military landscapes;
- Battle of Crete / Maleme;
- GIS and architectural site analysis;
- architectural representation methods.

Possible theoretical directions:
- atmosphere;
- memory and place;
- body and perception;
- material aging;
- landscape urbanism;
- critical heritage;
- memorial architecture.

Do not overquote theory. Use theory only when it sharpens the design decision.

---

## 13. Working rule

Every drawing, material, and structural decision must answer this:

**What does this reveal about the site that was already there but not yet visible?**

If the answer is “it looks nice,” delete it.

