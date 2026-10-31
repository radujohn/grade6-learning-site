# Grade 6 Alberta Study Pages: Tracker

Last updated: October 30, 2026.

## Source of truth

Official Grade 6 Science outcomes: https://curriculum.learnalberta.ca/curriculum/en/c/sci6  
Grade 6 Mathematics: https://curriculum.learnalberta.ca/home/en  
Source PDFs reviewed: Science (K–6), Mathematics (K–6), and Grade 6 Parent Guide supplied in this project.

The supplied Alberta PDFs remain the source of truth. Topic names alone do not establish full outcome coverage; practical skills and procedures must also be practised.

## Current pages

| Page | Subject | Status |
|---|---|---|
| Matter Success Package | Science | Existing page; concept coverage partial against full outcome |
| Forces and Interactions | Science | Existing page; concept coverage partial against full outcome |
| Energy Resources Success Package | Science | Existing page; concept coverage partial against full outcome |
| Climate Success Package | Science | Existing page; concept coverage partial against full outcome |
| Ecosystems Success Package | Science | Existing page; concept coverage partial against full outcome |
| Solar System Success Package | Science | Existing page; concept coverage partial against full outcome |
| Computer Science Success Package | Science | Existing page; concept coverage partial against full outcome |
| Scientific Methods Success Package | Science | Existing page; concept coverage partial against full outcome |
| Math Practice | Mathematics | 11 practice areas; partial coverage across several official outcomes |
| Symmetry and Congruence | Mathematics | NEW standalone page; adds the missing Grade 6 Geometry area |
| Grade 6 Learning Hub | Navigation | NEW local landing page linking all current topic pages |

## New work completed in this build

- Created `Math – Symmetry and Congruence – Grade 6.html` as a standalone, phone-first lesson.
- Covers reflection symmetry, rotation symmetry, congruence in different orientations, combined transformations, tessellations, and respectful context for First Nations and Métis star blanket designs.
- Includes Learn it, Try it, and Your turn sections, hints, retries, shuffled multiple-choice options, progress stars, local browser saving, and reset.
- Created `Grade 6 Learning Hub.html` linking the nine existing subject pages plus the new Geometry page.
- Preserved the original Math Practice file; no original source HTML was overwritten.

## Quality checks completed

- New Geometry page JavaScript syntax checked successfully with Node.js.
- Original Math Practice JavaScript syntax had previously passed Node.js syntax checking.
- The local headless browser could not navigate local file URLs in this environment. Full interactive browser QA and phone testing are therefore still outstanding; do not mark them complete.
- Google Fonts is used for Atkinson Hyperlegible with system fallback. Internet access is needed to fetch the web font; page content itself is local.
- Each page stores progress separately in its own browser storage. Progress does not sync across devices or automatically report to a parent.

## Curriculum audit summary

### Science

All eight current Science pages align with the relevant broad Grade 6 learning areas, but the current packages do not yet provide sufficient practice for all required skills and procedures. Priority additions:

- Matter: controlled experiment on mass across a phase change; liquid thermometer design; compare density of liquid and solid water; safety practices.
- Forces: investigations of internal/external forces; identify forces in interactions; test elasticity/plasticity; demonstrate and represent action–reaction pairs.
- Energy: investigate selection factors and Alberta's principal resources; responsible management; design a device using an energy resource.
- Climate: interpret climate data; compare local/Canadian climates; local agriculture and sustainable harvesting; collaboration with Elders, Knowledge Keepers and scientists.
- Ecosystems: represent biotic/abiotic relationships; investigate and compare local ecosystems; create a model or simulation; connect preservation with climate action.
- Solar System: strengthen comparison and modelling of celestial body characteristics and exploration.
- Computer Science: add practical algorithm/coding structures and create a computational artifact; examine intended and unintended impacts.
- Scientific Methods: develop and test hypotheses; identify variables; evaluate evidence; create correctly labelled graphs/tables; communicate for an audience; demonstrate scientific ethics.

### Mathematics

The supplied Mathematics PDF has 14 Grade 6 learning outcomes. The current practice page touches most areas but does not fully address all skills. The separate Geometry page now addresses the previously missing symmetry/congruence area. Remaining priorities:

- Standard algorithms: addition/subtraction in varied contexts and metric measurement.
- Prime factorization: common factors, divisibility and products with more than two factors.
- Multiplication/division: larger natural and decimal numbers, standard algorithms and estimation.
- Fractions as quotients: equal-sharing models and fraction/division statements.
- Ratios: proportions and percent as proportional relationships.
- Algebra: combine like terms, use algebraic properties, simplify both sides and verify solutions.
- Coordinates: rotations and coordinate relationships after transformations.
- Area: unknown base/height, rearrangement and composite areas.
- Volume: cubic units and three-dimensional arrays/models.
- Functions: independent/dependent variables, tables, graph points and equations.
- Relative frequency: conduct experiments, collect categorized data and compare sample sizes.

## Next steps

- [ ] Browser QA: test every page's navigation, hints, retries, answer feedback, progress save and reset.
- [ ] Test all pages on a phone and at narrow desktop widths.
- [ ] Expand Math Practice: algebra, coordinates, area/volume, functions and relative frequency.
- [ ] Add practical Science activities beginning with Matter, Forces and Scientific Methods.
- [ ] Add more varied practice and challenge questions after checking correctness.
- [ ] Decide whether parent progress reporting is actually needed; keep it out of the MVP until requested.
- [ ] Deploy the hub and topic pages to a static host such as GitHub Pages; update the tracker with live URLs only after deployment is verified.

## Learning design rules

- Grade 6 Alberta curriculum is the source of truth.
- One self-contained HTML page per topic; a simple hub links them together.
- Phone-first, large tap targets, Atkinson Hyperlegible with fallback, light/dark appearance.
- Tap-first; typing may be optional when it genuinely helps. No voice requirement.
- Pattern: Learn it → Try it → Your turn. Add Investigate it where outcomes require practical application.
- No timers or punitive marking. Hints and retries remain available.
- Save progress locally in the browser, with a clear reset. Explain that local progress does not sync.
- Canadian spelling and Alberta-relevant examples.
- Preserve source originals; work in copies and keep a change log.

## Phase 2 — Math expansion (October 30, 2026)

- Added 42 supplemental, curriculum-aligned question cards across Algebra, Coordinates, Area and Volume, Functions, Data, Prime Factors, Money/Metric, Multiplication/Division, Fractions and Ratios.
- New questions are interleaved with the existing randomly generated practice. The original HTML in the parent folder is untouched.
- Geometry Symmetry and Congruence remains a separate page linked from the hub.
- Static JavaScript syntax check performed; full mobile/browser interaction testing remains outstanding.
- Still partial: hands-on models, learner-created tables/graphs, experimental data collection, written explanations, and full standard-algorithm instruction. These cards are supplementary practice, not a claim of full curriculum mastery.
- Student input remains tap-first, with hints and retries. Progress remains per browser.

## Phase 3 — Science Investigation Lab (October 30, 2026)
- Added a standalone Science Investigation Lab linked from the learning hub.
- Matter: simulated sealed-sample mass readings before and after melting; prediction and evidence-based conclusion.
- Forces: simulated elastic/plastic responses for rubber band, clay, spring and paper clip.
- Scientific Methods: identify manipulated, responding and controlled variables in a fair-test scenario.
- Clearly labelled as on-screen models, not home experiment instructions.
- Browser/mobile runtime testing remains outstanding; content is a first practice layer, not complete coverage of all Science skills.


## Phase 4 — Science Studio (October 30, 2026)

- Added `Grade 6 Science Studio.html` and linked it from the learning hub.
- Ecosystems: biotic/abiotic identification, a simplified ecosystem relationship model and change scenario.
- Energy resources: four selection factors, before/after processing example, and a device-design prompt.
- Climate: weather/climate distinction, fictional data comparison (clearly labelled), and curriculum-linked climate/agriculture practice.
- Computer science: tap-to-order algorithm, conditionals, loops and technology-impact reasoning.
- Solar system: compare exploration technologies, natural/artificial satellites and barriers to living/working in space.
- Activities are conceptual on-screen models. They do not replace teacher-guided local investigations, actual coding, or full scientific data collection.
- Progress is saved locally in the browser, separately from other pages.
- JavaScript syntax and ZIP integrity checks are included in the delivery process; full browser interaction and phone testing remain outstanding.

## Current phase status

- Science now has two supplementary practice pages beyond the original topic packages: the Investigation Lab (Matter, Forces, Scientific Methods) and Science Studio (Ecosystems, Energy, Climate, Computer Science, Solar System).
- These additions address selected gaps from the curriculum audit; they do not yet demonstrate complete coverage of every Grade 6 Science knowledge, understanding, and skills/procedures expectation.
- Math Practice still needs a dedicated audit/fix pass for topic navigation and complete coverage. Do not describe the supplemental questions as six new topic tabs.


## Phase 5 — Mathematics navigation and outcome separation (October 30, 2026)

- Corrected the Grade 6 Mathematics outcome count: the supplied Alberta curriculum PDF contains **15 learning outcomes**, not 14. Earlier tracker references to 14 were incorrect.
- Reworked Math Practice navigation into 15 distinct outcome areas:
  1. Positive and negative numbers
  2. Standard algorithms for addition and subtraction
  3. Prime factorization and exponentiation
  4. Standard algorithms for multiplication and division
  5. Fractions as quotients
  6. Addition and subtraction of fractions
  7. Multiplication of a natural number by a fraction
  8. Ratios, rates and percentages
  9. Algebraic expressions and equations
  10. Symmetry and congruence (opens the dedicated visual lesson)
  11. Cartesian plane and transformations
  12. Area of parallelograms and triangles
  13. Volume
  14. Functions and change
  15. Relative frequency using experimental data
- Split previously combined practice areas so the navigation mirrors the curriculum outcome structure.
- Added separate generators for standard addition/subtraction, fractions as quotients, multiplication of a natural number by a fraction, and volume navigation.
- The existing Symmetry and Congruence standalone lesson is now directly reachable from its own topic tab.
- This is a navigation and practice-coverage improvement, not a claim that every knowledge, understanding, and skills/procedures statement has been fully taught or assessed.
- Browser interaction and phone testing remain outstanding.


## Phase 6 — Mathematics Mastery Path (October 30, 2026)

- Added `Grade 6 Mathematics Mastery Path.html`, linked from the central learning hub.
- Built a three-stage pathway for all 15 Grade 6 Mathematics outcomes: Learn it, Try it together, Your turn.
- Each topic includes an outcome statement, a short explanation, a worked idea, a guided question and an independent challenge.
- Mastery is recorded per topic only after both the guided and independent questions are answered correctly. Incorrect attempts can be retried without a timer or penalty.
- Progress is saved locally in the browser and can be reset by the learner.
- The page uses Canadian English and Atkinson Hyperlegible, responsive layout, large controls and light/dark system theme support.
- Questions and explanations are a practice layer based on the official Alberta Mathematics (K–6) Grade 6 curriculum PDF; they are not a complete substitute for teacher instruction or every possible application of each outcome.
- Automated JavaScript syntax checks and ZIP integrity checks passed. Full browser interaction and phone testing remain outstanding.


## Phase 7 — Student Dashboard (30 October 2026)

**Delivered**
- Added `Grade 6 Student Dashboard.html` as a central student-facing home screen.
- Linked Mathematics Mastery Path, Math Practice, Symmetry & Congruence, Science Studio, Science Investigation Lab, and all eight original Science topic pages.
- Added on-device progress summaries for Math Mastery (15 topics), Math Practice stars, Science Studio recorded activities, and Science Lab recorded steps.
- Added a refresh control and a clear explanation that progress is local to the current browser/device.
- Updated `Grade 6 Learning Hub.html` with a prominent dashboard entry point.

**Progress interpretation and limitations**
- The dashboard reads existing localStorage records; it does not create cloud accounts or cross-device sync.
- Math Practice stars are activity indicators, not proof of mastery. Math Mastery counts a topic only when both guided and independent answers are recorded correct.
- Science Studio and Science Lab counts reflect the existing saved activity flags, not full curriculum mastery. Original Science topic pages without progress tracking are linked but not scored.
- The pages retain their separate progress stores; the dashboard aggregates their summaries without changing those formats.

**QA**
- Static HTML and JavaScript syntax checks and ZIP integrity checks are run for this phase.
- Actual browser interaction, cross-browser behaviour and phone testing remain outstanding; do not treat the package as deployed or fully user-tested.


## Phase 8 — Consistent navigation and student-first entry (30 October 2026)

**Delivered**
- Made the Student Dashboard the consistent home destination across all 19 HTML pages.
- Added a persistent navigation bar linking to the Student Dashboard and the full Learning Hub.
- Added a keyboard-accessible skip-to-content link and clear focus styling for navigation.
- Kept all original topic pages and the existing separate progress stores intact; this phase changes navigation, not assessment logic or mastery definitions.
- Preserved the existing dashboard's local progress summaries and the explanation of their limitations.

**Learner experience**
- Richard can return to the dashboard from any topic without using browser back repeatedly.
- The Learning Hub remains available as a full directory of every page.
- The dashboard remains the recommended starting point; no account or cloud sync is introduced.

**QA**
- Added shared navigation to 19 HTML pages.
- Static checks confirm each page has one shared navigation block and a valid local dashboard/hub link target.
- ZIP archive integrity checked.
- Automated checks do not replace actual browser, keyboard, screen-reader, cross-browser or phone testing. This package has not been deployed.


## Phase 9 — QA, cleanup and acceptance testing (30 October 2026)

**Delivered**
- Audited all canonical HTML pages for viewport metadata, document language, a main landmark, an H1 and the shared navigation.
- Checked local page links against the package contents.
- Rechecked inline JavaScript syntax.
- Removed six byte-identical percent-encoded duplicate HTML files from the distributable folder.
- Added `PHASE9-QA-REPORT.md` with automated results and a practical manual acceptance-test checklist.

**Results**
- Structural checks passed for all canonical HTML pages.
- No broken local HTML links found.
- All inline JavaScript blocks passed Node syntax validation.
- ZIP integrity passed.

**Important browser-testing limitation**
- A headless Chromium attempt was blocked by the execution environment's browser navigation policy, including local-file and localhost navigation. Live interaction, visual rendering, keyboard, screen-reader and phone testing are therefore still unverified. The QA report gives the exact family acceptance-test steps to complete on the target devices.
