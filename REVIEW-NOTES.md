# Multiblock contest wiki import — review notes

Generated 2026-10-07 from the Discord export in `multiblock-contest/`. One wiki page per submission under `docs/Multiblocks/Contest/`, images converted to WebP (max 1600 px) under `Contest_img/<slug>/`.

Each entry below is what the page writer flagged for a human to double-check. Items marked **incomplete** got a warning admonition on the page.

## High Pressure Steam Crucible Furnace
`high-pressure-steam-crucible-furnace.md` · source `003-steam-alloy-smelter-multiblock` · tier ULv

Author wrote the tier as 'ULv'; the page renders it as ULV (steam). The schematic file is named HPSS.litematic while the structure acronym is HPSCF; kept the author's filename.

## Large Assembler
`large-assembler.md` · source `004-large-assembler` · tier EV

No schematic attachment; the author pasted a copy-paste JSON string in the post, embedded verbatim in a collapsed block under Files. Consider extracting it to Contest_img/large-assembler/large-assembler.json. Acronym 'LA' comes from the author's reply, not the post body. Front/Side labels are a best guess from the screenshots.

## Mega Epic Omni Wheel
`mega-epic-omni-wheel.md` · source `005-mega-epic-omni-wheel-m-e-o-w` · tier UV

Author gave no output numbers and leaves input, tier, and implementation open. The posted schematic and screenshots contain a known asymmetry (missing casing bottom left of the controller) that the author acknowledged but did not re-upload a fix for. The author's 'superalloy casings' wording is kept; a commenter called them naquadah casings.

## Large Turbine **(incomplete)**
`large-turbine.md` · source `006-the-large-turbine` · tier IV-UV

Tier given as a range IV-UV; meta tier set to IV (lowest). Very thin post: no numbers or mechanics beyond one sentence; author admitted a hatch placement mistake but never posted a fix, so the .nbt likely still contains it.

## Water Cooled Steam Solidifier
`water-cooled-steam-solidifier.md` · source `007-water-colled-steam-solidifier-w-c-s-s` · tier ULv - Lv

Title spelling corrected from the author's 'colled' to 'Cooled'; thread link keeps the original title. Tier is a range (ULV - LV) on a single structure, recorded as ULV for sorting. Two-mode mechanics come from the author's thread replies, not the post body.

## BIO Diesel Refinery
`bio-diesel-refinery.md` · source `008-bio-diesel-refinery-bdr` · tier LV

The two side screenshots look nearly identical (one has a bright block visible on top); verify they are different sides and drop one if not. Front/back labeling is inferred from the controller position.

## Draconic Life Breeding Chamber
`draconic-life-breeding-chamber.md` · source `009-draconic-life-breeding-chamber-d-l-b-c` · tier UIV, UXV (Essentially *just* before DSG)

Tier given as 'UIV, UXV' (two alternatives); tier set to UIV. Author spelled it 'Draco-peptid' in the post; page keeps that spelling in the bullet. Front/back labels are a guess from the exterior shots (controller visible in 'front').

## Geothermal Plant **(incomplete)**
`geothermal-plant.md` · source `010-geothermal-plant` · tier EV maybe idc

Tier was given as 'EV maybe idc'; rendered as EV with a 'tentative' note. No power figures; author says a Fluid Input Hatch is missing. Structure description and 3x3x3 size were decoded from the schematic JSON, not the post; the schematic also contains one stray Plascrete block outside the structure. Front/side/back labels for screenshots 1-4 are a best guess from the angles (controller faces east, hatch faces west in the schematic).

## Wind Turbines/Mills
`wind-turbines-mills.md` · source `011-wind-turbines-mills` · tier HV

Very thin submission: mechanics are one vague sentence and the author admits there is no energy output yet. Block list and 8x16x23 size were read from the JSON template, not stated by the author; the template format (looks like a Building Gadgets template) was not identified by the author. Consider the Incomplete warning if judges want fuller mechanics.

## Thermal Plant
`thermal-plant.md` · source `012-thermal-plant` · tier HV

Mechanics are a single sentence with no numbers; Structure block list and 3x4x3 size were taken from the schematic JSON, not the post. Side/back labels for screenshots 2-4 are a best guess from the angles.

## Bio Reactor
`bio-reactor.md` · source `013-bio-reactor` · tier HV

Very thin submission: mechanics are two sentences with no numbers. Structure size (3x3x5) and hatch list were derived from the schematic JSON, not stated by the author; mockup uses an HV Chemical Reactor as placeholder controller. Which face the dynamo hatch and side hatch sit on is guessed from screenshots.

## Hawking Radiation Reactor
`hawking-radiation-reactor.md` · source `014-hawking-radiation-reactor-h-r-r` · tier UV

Mechanics are very thin (no numbers). Structure paragraph uses the block palette and 14x6x15 bounding box read from the author's HRR.json (UV Machine Casing, Darmstadtium Frame, Tungstensteel Gearbox/Pipe Casing, 2 UV Input Hatches, 1 UV Energy Output Hatch, UV Arc Furnace as placeholder controller); drop if schematic-derived details are not wanted. Side/opposite-side screenshots are similar angles.

## Nefarious Extradimensional Temporally Hyper Energetic Roaster **(incomplete)**
`nefarious-extradimensional-roaster.md` · source `015-nefarious-extradimensional-temporally-hyper-energetic-roaste` · tier uxv

Slug shortened from the 59-char full name; no schematic, one screenshot, one-sentence mechanics. Structure description is from the single image plus the author's 'octohedron' reply.

## Thermic Fluid Heater
`thermic-fluid-heater.md` · source `016-thermic-fluid-heater-tfh` · tier late HV (requires titanium pipe casing)

Schematic is only an inline JSON string in the post (embedded on the page, no file). Side/top/bottom/cross-section screenshots predate the campfire removal and show smoke particles; only the front view is the updated version. 'TPB fluid heater' kept verbatim from the author (acronym unexplained). Structure size 5x7x5 and block counts were derived from the pasted schematic, not stated by the author.

## Steam Forge
`steam-forge.md` · source `017-steam-forge` · tier ULV

Very short submission (two-sentence summary, no in-depth mechanics). Thread raised an originality question (TFG/Monifactory Multi Alloy Smelter); no dev ruling in the thread. Front/hatch-side labels are inferred from the screenshots (controller visible on one face, hatches on the other).

## Large Compressor
`large-compressor.md` · source `018-large-compressor` · tier IV

Very thin submission: three-line summary, no in-depth mechanics, dimensions not stated (structure description is inferred from screenshots). Thread consensus was that Large Material Press already covers this; author effectively conceded. Consider whether this entry merits a page.

## Industrial Fermentation Tank
`industrial-fermentation-tank.md` · source `019-industrial-fermentation-tank-ift` · tier HV

Post is a single message with a one-line summary; 'throughout boosting' read as 'throughput boosting'. Schematic JSON is named 'LFT' internally and uses MV hatches although the stated tier is HV. Structure dimensions (5x5x8) and block list come from the schematic, not the author's text. Fluid in the recipe mockup is unnamed.

## Plasma Factory
`plasma-factory.md` · source `020-plasma-factory-pf` · tier UV

The author's bonus wording is garbled ('If 1000B of helium gas is provided (Only one of these bonuses can be active at the same time):' followed by the Iron/Nickel/Argon lines); the page reads it as: Helium gives +25% output, and with Helium supplied one of the three other bonuses may be active. Confirm whether the Iron/Nickel/Argon bonuses actually depend on Helium or are simply mutually exclusive. Front/back labels are inferred from which side has the hatch column. The schematic uses start_core:uv_fusion_reactor as the controller placeholder.

## Catalytic Reaction Chamber
`catalytic-reaction-chamber.md` · source `021-catalytic-reaction-chamber` · tier iv-luv

Author's mechanics are only three short lines (chemical loops, rutile/Formic Acid examples, better coils for advanced loops); no in-depth mechanics, dimensions, or block names given, so the Structure paragraph is a visual description only.

## Rotary Kiln
`rotary-kiln.md` · source `022-rotary-kiln` · tier HV-Luv

Author signed the post as 'Neo' but their Discord display name is the stylized '𝗡Ξ𝗢' (users.json); byline uses the display name. Tier range 'HV-Luv' normalized to HV-LuV, sorted as HV. The Structure paragraph's block list and 15x5x5 size were decoded from the NBT schematic (black steel casings/frames, steel gearboxes, cupronickel coils, firebricks, 'heat_chamber' controller, 2x HV energy hatches, LV muffler, maintenance hatch, LV input/output buses), not stated in the post. Screenshot end labels (controller end vs hatch end) are inferred from the hatch facings in the schematic. Coil-boost wording is contradictory in the original (boost at +1 tier, stacking only at +3 tiers) and was kept as the author stated it.

## Draconic Reactor for Accelerated Generation of Ouroboric Nanofusion
`draconic-reactor.md` · source `023-draconic-reactor-for-accelerated-generation-of-ouroboric-nan` · tier OPV (post-DSG)

Author wrote tier as 'OPV'; page uses the OpV tag. Author id 701585364661436517 is not in users.json; name taken from the transcript. Slug shortened to 'draconic-reactor' because the full name exceeds 50 chars.

## Low Temperature Pressure Chambers
`low-temperature-pressure-chambers.md` · source `024-low-temperature-pressure-chambers-multiblock-family` · tier MV, IV, UHV

Post author is Serotonintheft but the Author(s) line says 'Hash Browns' (not in users.json) — confirm whether that is the same person or a co-author. The three extensionless attachments are gzipped vanilla structure NBT (size/blocks/palette), so they were renamed with a .nbt extension; schematic sizes are SPC 9x10x10, BALL 11x12x12, COLOSSUS 15x16x16 (author stated 16x16x15). SPC is steam-powered but the author targets it at MV.

## Mass Multi Ore Processing Facility
`mass-multi-ore-processing-facility.md` · source `025-mmopf-mass-multi-ore-processing-facility` · tier EV

No schematic attachment; the Copy Paste Gadget pastable and all general information live in an external Google Doc that was not captured (linked in the Schematic cell and under Files). Mechanics on the page are limited to the author's one-line summary; consider pulling the doc contents in. Block names in Files come from the truncated link-preview of the doc. Front/End/Interior labels are best guesses from the screenshots. Thread replies are chatter only, so no Notes section.

## Pattern Distribution Machine
`pattern-distribution-machine.md` · source `026-pattern-distribution-machine` · tier somewhere LuV or ZPM or UV

Tier is a LuV/ZPM/UV range (author later says 'I put it in UV'; posted block list uses a LuV energy hatch); tier set to Unspecified with LuV sort hint. No schematic attachment, but the author pasted a multiblock-builder JSON (block state list + requiredItems) inline in the thread; consider saving it as pdm.json and linking it under Files. Structure dimensions (3x3x5) are derived from that JSON's start/end positions, not stated in prose.

## Thermal Cascade Furnace
`thermal-cascade-furnace.md` · source `027-thermal-cascade-furnace-tcf` · tier EV

Structure dimensions and controller position were inferred from screenshots only; the 'front-and-cutaway' image largely repeats the front and cutaway shots and could be dropped.

## Forgotten Phase Shifter
`forgotten-phase-shifter.md` · source `028-forgotten-phase-shifter` · tier Late UHV - Early UEV (ASG line)

message.txt is a JSON block-state schematic dump (statePosArrayList/requiredItems format, 647 blocks), not prose; kept as .txt per brief. Its hatches are EV-tier and the controller is a chisel_chipped_integration:futura_me_controller placeholder. Screenshot labels 'Front' (controller visible) and 'Hatch side' are my reading of the images; the structure is four-fold symmetric so verify the sides. The Google Doc with the full mechanics was not fetched (external); page reflects only the post body and embed preview. Tier is a range (Late UHV - Early UEV); set to UHV for sorting.

## Synergistic Gas Turbine
`synergistic-gas-turbine.md` · source `029-synergistic-gas-turbine` · tier LuV

Author wrote 'Pallaridium Turbine Casings' (kept as written; verify block name). 'naptha' normalized to Naphtha and 'nbz' expanded to Nitrobenzene. Screenshots show unformed rotor holders per the author.

## Steam Centrifuge
`steam-centrifuge.md` · source `030-steam-centrifuge` · tier ULV

Submission is a single short post: functional summary is one sentence, no in-depth mechanics; structure description was inferred from the screenshots only.

## Crude Biodiesel Generator
`crude-biodiesel-generator.md` · source `031-crude-biodiesel-generator` · tier HV

Image labels 'Controller side' vs 'Hatch side' are inferred from the screenshots (engine block on one wall, three hatches on another); author did not label them. No EU/t numbers given.

## Waterlogged Mechanical Sieve
`waterlogged-mechanical-sieve.md` · source `032-waterlogged-mechanical-sieve-wmsv` · tier LV

Structure description (brick box, gold trim, frame legs, hatches on back) is inferred from screenshots; author gave no dimensions. Thread discussion was only chatter, so no notes section.

## Concentrated Overthermal Reaction Engine
`concentrated-overthermal-reaction-engine.md` · source `033-core-concentrated-overthermal-reaction-engine` · tier UIV+

Author wrote the tier as 'UIV+' (open-ended); mapped to UIV. The author's 'Dₒ' subscript was rendered as 'D₀'. Thread replies were all chatter, so no notes section.

## Large Fermenting Casket
`large-fermenting-casket.md` · source `034-large-fermenting-casket` · tier LV

Author gave no speed figures or dimensions; 'faster' is unquantified. Only thread reply was non-substantive praise, so no Notes section.

## Colossal Amazing Nano Technology Astronomical Legendary Ominous Underworld Puncturing Extractor
`underworld-puncturing-extractor.md` · source `035-colossal-amazing-nano-technology-astronomical-legendary-omin` · tier UIV+

Slug uses the tail of the very long name. The 17x17x17 size and the ZPM Fluid Drilling Rig placeholder controller come from the JSON schematic, not the post; the author wrote the acronym in Discord spoiler bars.

## Trace Ore Extractor / Trace Ore Processing Plant
`trace-ore-extractor-and-processing-plant.md` · source `036-trace-ore-extractor-toe-trace-ore-processing-plant-topp` · tier HV (regular) / IV (parallel)

Mechanics are a short concept sketch (no parallel count, no recipe numbers). Casing block names per version were read from the JSON templates and screenshots, not stated verbatim by the author; template format (name/statePosArrayList/requiredItems) not identified by the author. Thread replies were praise only, so no notes section.

## Wire Insulation Plant
`wire-insulation-plant.md` · source `037-wire-insulation-plant-wip` · tier LV, but can be easily changed to be MV or HV if too early

No numbers given by the author (no parallel count/speed). The 8x4x3 bounding box and 'Building Gadgets format' are inferred from wip.json (statePosArrayList/requiredItems), not stated by the author. Acronym WIP comes from the thread title only.

## Joule-driven Unit for Industrial Coating & Electrodeposition
`joule-driven-unit-for-industrial-coating.md` · source `038-joule-driven-unit-for-industrial-coating-electrodeposition-j` · tier IV

Slug shortened to drop '-electrodeposition' to stay under ~50 chars. Side/Back tab labels are my reading of the angled screenshots; the author did not label them.

## Cyclotron and Ambient Neutron Activator
`cyclotron-and-ambient-neutron-activator.md` · source `039-cyclotron-and-ambient-neutron-activator-ana` · tier Mid-UEV

Acronym ANA applies only to the Ambient Neutron Activator, kept in the H1 to match the thread title. The two 'cross sections' images were posted without labels; assignment (top-down = Cyclotron, lengthwise strip = ANA) is inferred from the pictures. Author's material names (Flerovium-Rich Re Sludge Dust, Hafnastide-Rich, Pologium-Rich) kept verbatim. No numbers given for loss rates, boosts, or dimensions.

## Dimensional Runically Engraved Energy Access Medium
`dimensional-runically-engraved-energy-access-medium.md` · source `040-dimensional-runically-engraved-energy-access-medium-dreeam` · tier UHV (Post RIMM)

Schematic.txt is a JSON block-state dump (statePosArrayList + requiredItems), not a .litematic; kept .txt extension. Structure dimensions (11x17x11) and block counts are taken from that file, not stated by the author. Controller in screenshots uses a chisel Futura ME controller texture as placeholder.

## Large Cleaving Factory
`large-cleaving-factory.md` · source `041-large-cleaving-factory-lcf` · tier ZPM

Single-message thread, no discussion. Exterior left/right labels are my guess from the screenshots; structure description is inferred from images, not stated by the author.

## Beacon of Lucidity and Paragon of the Veil
`beacon-of-lucidity-and-paragon-of-the-veil.md` · source `042-beacon-of-lucidity-paragon-of-the-veil` · tier UXV (Beacon of Lucidity) / OpV (Paragon of the Veil; first listed as "UXV (or OpV)")

Two Paragon versions exist: a compact one (block template .txt, roughly 31x31x31 per the template bounds) and the final 67x67x88 rebuild (.schem). Judge Scarlet said the oversized build could be posted for testing but not as the submission, 'left up to the other judges'; the author then posted it as the final entry anyway. Confirm which version counts. Paragon tier moved from 'UXV (or OpV)' to 'OpV' in the final post. The .txt attachments are Building-Gadgets-style block templates, not prose; block lists on the page come from those files and the .schem palette, and the ~25x23x25 / ~31x31x31 sizes are derived from template bounds, not stated by the author. 'Daydream Spire' is used as the author wrote it.

## Solar Array of Mirrors for Steam and Giant Lumium Overheater of Water
`solar-array-of-mirrors-and-lumium-overheater.md` · source `043-sams-solar-array-of-mirrors-for-steam-and-glow-giant-lumium` · tier LV and HV

Author wrote 'LV and HV' without saying which structure is which; the page maps LV to SAMS and HV to GLOW from the listing order (bronze vs stainless steel casings agree). Thread title says 'Giant Lumium Overheater of Water' but the post body says 'Giant Lumium heater of Water'; the page uses the title form so the GLOW acronym works. Author says GLOW is loaded with 'graphite' but then gives the amount as '100 graphene dust'; both words kept as written. The .json files are Building Gadgets templates, not litematics; both use a chisel 'futura_me_controller' block as a controller placeholder, and the GLOW template also contains one stray Salt Dust Block. Template dimensions (7x6x9, 11x8x13) and block lists were read from the templates, not stated by the author. All numbers are the author's 'maybe' estimates.

## Stabilised Artificial Singularity Harvester
`stabilised-artificial-singularity-harvester.md` · source `044-s-a-s-h-stabilised-artificial-singularity-harvester` · tier UHV, post ASG, pre HF

message.txt is a Building Gadgets-style template JSON, not prose; listed under Files with .txt kept. Title keeps the author's British spelling 'Stabilised'. Controller position described only as 'Recipe Input side, off-center' (from the annotated screenshot and thread critique). Kolja's render reply was not saved; mentioned in Notes only.

## Syngas Processing Facility **(incomplete)**
`syngas-processing-facility.md` · source `045-spf` · tier LV

No schematic file attached; the author linked a Google Doc whose content (per the embed preview) is a block-state dump (statePosArrayList, Building Gadgets-style JSON). Consider fetching it and saving it as a schematic file. Author said in-thread the design is probably more HV than LV; page keeps LV as submitted.

## Lapidary Extraction Unit and Lapidary Extraction Matrix
`lapidary-extraction-unit-and-matrix.md` · source `046-lapidary-extraction-unit-leu-lapidary-extraction-matrix-lem` · tier LEU - EV, LEM - IV

Full mechanics live only in the author's linked Google Doc (not captured in the thread); the page links it but reproduces no numbers. Both .txt attachments are block-state/schematic dumps, not prose. Structure dimensions and block lists were derived from those schematic files. Controller is a Chisel 'Futura ME Controller' placeholder.

## Fusion Reactor On Zero Energy Nodes and Crushed Riftic μonic Cold Internal Borealic Engine
`frozen-and-crucible.md` · source `047-frozen-and-cr-cible-names-too-long-to-fit` · tier UHV and UXV

Author never said which screenshot is which reactor; the dark/black structure was assigned to FROZEN (UHV) and the purple one to CRμCIBLE (UXV) by inference from the two schematic names and tier order. Page title is very long (full names); consider shortening nav title to 'FROZEN and CRμCIBLE'. Slug drops the μ (frozen-and-crucible).

## Slurry Leaching Ore Plant
`slurry-leaching-ore-plant.md` · source `048-slurry-leaching-ore-plant-s-l-o-p` · tier HV/early EV minimum.

Tier given as a range 'HV/early EV minimum' (filed under HV). No recipe details beyond the 30,000 mB slurry input; no dimensions stated. flamebucklerio suggested renaming to 'Slurry leaching ore refining plant (S.L.O.R.P.)' and the author liked it, but did not formally rename — page keeps the original name.

## Small Modular Nuclear Reactor **(incomplete)**
`small-modular-nuclear-reactor.md` · source `049-small-modular-nuclear-reactor` · tier UHV

Co-author 'Haribo' was written as plain text, not a mention; users.json has HARIBO (@kaxolotl.) which is probably the same person but unconfirmed. Acronym SMNR comes only from the schematic filename. Second attachment is a copyrighted NuScale diagram and was skipped.

## Chilled IHPCA
`chilled-ihpca.md` · source `050-chilled-ihpca` · tier UHV

Co-author 'Haribo' was written as plain text, not a mention; matched to users.json entry HARIBO (@kaxolotl.) - verify. Submission is thin (one screenshot, two-sentence mechanics) but has all template fields, so no incomplete warning was added.

## Hyperpolarizing Object Radiation Thermojunction Holder
`hyperpolarizing-object-radiation-thermojunction-holder.md` · source `051-hyperpolarizing-object-radiation-thermojunction-holder-horth` · tier UEV

Both attachments were uploaded without extensions; .json/.txt were added based on content (HORTH_Structure is JSON, HORTH_Explanation is plain text). The Structure paragraph (11x11x11, casing layout, Heart of the Flame at the center) is derived from the schematic JSON, not from the author's prose. The schematic uses ae2:colorable_controller as a placeholder for the controller block. Role category 'Processing' is a guess; the author only says 'more powerful fission reactor'. Screenshot labels are best guesses from the images.

## Industrial Kitchen and Protein Synthesis Vat
`industrial-kitchen-and-protein-synthesis-vat.md` · source `052-industrial-kitchen-ik-and-protein-synthesis-vat-psv` · tier UV

Image 4 (1554223560741101638) was identified as an IK cross section from the trinium coils / pipe casing column visible in it and the IK schematic palette; verify. Image 7 (1554223561885876254) likewise labeled as a PSV cross section (one side opened). Author's 'cocoa power' typo corrected to Cocoa Powder; item names capitalized in the recipe tables. Schematic sizes (IK 11x17x11, PSV 9x11x9) were not stated by the author and are not on the page. The 'Döner Kebab' and 'Doner Beef' spellings are the author's.

## Large Electric Anemic Fermenter
`large-electric-anemic-fermenter.md` · source `053-large-electric-anemic-fermenter-l-e-a-f` · tier MV

Mechanics are thin (no recipe numbers, no dimensions); the 'upgradeable multi' and 'Stainless Steel' ideas are the author's loose suggestions.

## gCrop Breeding-havesting Complex Array
`gcrop-breeding-havesting-complex-array.md` · source `054-gcrop-breeding-havesting-complex-array-gbhca` · tier UEV

Author's name spells 'havesting' (likely 'harvesting'); kept as written in title, H1, and slug. Acronyms EgCHP and gCFA are the author's and were not expanded. Structure description is inferred from screenshots; no dimensions given.

## Kamiokande Oscillation Engine
`kamiokande-oscillation-engine.md` · source `055-kamiokande-oscillation-engine-koe` · tier UEV

No .litematic; the .txt is a JSON block-state dump (statePosArrayList, bounding box 17x16x17 per start/end pos) listed as the schematic. Block names in the Structure paragraph come from that dump. Wall material in the dump is Lumium Casing (author said they dislike it and would prefer a new gold-colored custom casing).

## Condensed Horizon Relativistic Oscillation Nucleus for Output Synthesis
`chronos.md` · source `056-c-h-r-o-n-o-s` · tier UIV+

Author's energy formula is self-inconsistent: result stated in amps of UEV but the example f(0) = 1A UIV; kept as written. All numbers are explicitly placeholders per the author. 35x18x35 dimensions exceed the usual limit; author says Kolja granted permission. Structure description is inferred from the two screenshots only.

## Solar Plasma Extractor
`solar-plasma-extractor.md` · source `057-solar-plasma-extractor` · tier UHV

Single screenshot only; the picture shows the tower plus a separate cube with a sea lantern (controller placeholder) - unclear whether the cube is part of the structure or just shows the controller block. Author's second message is just the title with no new content.

## ME Wireless Bridge
`me-wireless-bridge.md` · source `058-me-wireless-bridge` · tier UV

Author asked in-thread whether this counts as a joke submission; no dev ruling. Mechanics are sparse and partly speculative (power per link, full-block quantum rings).

## Stellar Nucleosynthesis Astrochemistry Disassembler
`stellar-nucleosynthesis-astrochemistry-disassembler.md` · source `059-stellar-nucleosynthesis-astrochemistry-disassembler-s-n-a-d` · tier Luv/Zpm

Tier is a range (Luv/Zpm, one structure); recorded as LuV for sorting. The 'Top view' image may be a top-down interior/layer view rather than the roof; the 'Recipe inputs' image is a small inventory grid of shards and dusts, labeled by guess. Recipes are the author's unrevised base proposal; thread feedback (chance-consume shard, higher output) was accepted in principle but no new numbers were posted.

## Dyson Swarm Rail Cannon
`dyson-swarm-rail-cannon.md` · source `060-dyson-swarm-rail-cannon-dsrc` · tier UHV

Author says the structure is oversize with permission given; no dimensions stated. All numbers are marked by the author as subject to change.

## Layered Universal Circuit Machines
`layered-universal-circuit-machines.md` · source `061-layered-universal-circuit-machines-names-below` · tier ZPM, UHV, UIV

Image-to-machine mapping (pink=SCAC, dark naquadah=GFWC, gray nyanium=SCRAM) was inferred from casing colors vs. the block lists in structures.txt, not labeled by the author; please verify. SCAC/GFWC dimensions (11x5x9, 15x9x13) come from the structure dump bounding boxes, not from the author's prose; the author wrote SCRAM as 21x19x13 while the dump spans 21x13x19 (same numbers, different axis order). The tier-1 stabilization/cleaning-hatch unlock issue was left unresolved in the thread.

## Neutron-conserving Atom Destabilizer
`neutron-conserving-atom-destabilizer.md` · source `062-neutron-conserving-atom-destabilizer` · tier Late UHV - Early UEV

Co-author <@754600912873586698> is not in users.json (listed as 'unknown user'). Tier is a range (Late UHV - Early UEV); tier set to UHV for sorting. The 16x17x15 size comes from the template's endpos, not the post; the 'Structure' description is from screenshots.

## Acoustic Entanglement Device
`acoustic-entanglement-device.md` · source `063-acoustic-entanglement-device` · tier IV

Second author id 754600912873586698 is not in users.json (listed as 'unknown user'). Structure block palette and 15x13x15 bounding box were read from the AED_gadget.txt dump, not stated by the author; the dump uses an ae2:controller block where the multiblock controller presumably goes.

## Ancient Belief Yielding Data Optimization Sanctum and Eye of Horus
`data-optimization-sanctum-and-eye-of-horus.md` · source `064-a-b-y-d-o-s-e-o-h-ancient-belief-yielding-data-optimization` · tier UV+ (A.B.Y.D.O.S.); UV (progression gating) and above (E.O.H.)

Image-to-structure assignment inferred from posting order and the schematic palettes (the cube contains sgjourney:classic_stargate, so it is the E.O.H.; the temple is the A.B.Y.D.O.S.). The 'Back' label for the flat cross-patterned E.O.H. face is a guess (could be top). Dimensions and block lists come from the litematic metadata/palettes, not from the author's text. Title uses 'Eye of Horus' where the author wrote 'Eye Of Horus'. Only two of the four authors described work split in the thread; all four are credited as the author listed them.

## Atmosphere Dust Collector
`atmosphere-dust-collector.md` · source `065-atmosphere-dust-collector` · tier LuV

Structure description (5x6x5 bounds, casing types, 6 LuV Output Buses, 1 LuV Energy Input Hatch, IV Large Miner as placeholder controller) is derived from the attached template JSON, not from the author's prose. Screenshot labels are a best guess from the images (all taken at night in rain, dark). Acronym kept as the author wrote it, 'A.D.C'. Dust pool is not enumerated by the author.

## Void Breaking Accelerator
`void-breaking-accelerator.md` · source `066-void-breaking-accelerator` · tier UHV+ (soon after getting to the End)

Mechanics link points to another Discord thread (1550230511639593081) that was not in the inputs; verify it is public before keeping the link. Target tier written as 'UHV+' (open-ended).

## Diffracting Resource Inter-Dimensional Lithic Loader
`diffracting-resource-inter-dimensional-lithic-loader.md` · source `067-d-r-i-l-l-diffracting-resource-inter-dimensional-lithic-load` · tier UV

Post body links to a separate 'Stargate Revitalization Project' thread as the main submission; the page links it but the content of that thread was not available. The 'Stargate is optional, better yield' note comes from short co-author replies, not the OP's own text.

## Draconic Nuclear Reactor
`draconic-nuclear-reactor.md` · source `068-draconic-nuclear-reactor` · tier UEV

The 'Schematic File:' line in the post was empty, but the attached Draconic_Nuclear_Reactor.txt is a JSON block-state template (statePosArrayList, 17x17x17 region per its start/end pos), so it is used as the schematic. Front/Angled/Top and the two interior-layer labels are guesses from the screenshots; the author did not label them or state dimensions.

## Cryothermal Equilibrium Layered Liquidising Synthesiser, FLUID and ITEM
`cells-fluid-and-item.md` · source `069-cryothermal-equilibrium-layered-liquidising-synthesiser-cell` · tier UHV

In-depth mechanics live only in a linked Google Doc (not an attachment, not fetched); page links it but Mechanics is thin. Per rule 4 the page is one family page without per-structure ## sections because the post gives no per-structure mechanics. 'cells2.png' shows CELLS inside a Stargate-style ring (doc tagline: 'Joke submissions are a serious business'); kept as 'CELLS with ring', drop if unwanted. Author's 'approval has been granted for both' is ambiguous (which two?) and was kept vague on the page.

## Star Breeding
`star-breeding.md` · source `070-star-breeding` · tier UXV

Author credits 'the dev team' as co-author via two Discord message links (not resolvable to users); byline says 'credited together with the dev team' and authors list only White tea. The OP's second message is an external .mp4 clip (not saved) that Luck says is a Kolja sneak-peek of an upcoming update, not the author's work. 'Laser Friciton Feeder' typo corrected to 'Friction'; 'Miniature Dyson ring Installer' capitalized as 'Ring'. Placeholder-block table copied from General_Information.txt with capitalized block names; 'Pallaridium' kept as written. MDRI front/back assignment inferred from the two unlabeled pictures. No dimensions, rates, or recipes given beyond '500 stability' and '16 harvesters'.

## Modular Thermal Distillation Plant
`modular-thermal-distillation-plant.md` · source `071-modular-thermal-distillation-plant` · tier Unlocked in LuV, upgradable

Front/back/side labels are inferred from the controller position (front = end wall with the controller). The 'Module blocks' image shows four single fan-faced blocks, one per module casing style, with no caption from the author; verify what they are. Coolant rates are copied as the author wrote them ('100 b/m/h', 'B/m/h'); the unit is unclear and the first one is lowercase in the original. The author says up to 6 modules but describes 4 module tiers; left as stated.

## Sieving Apparatus
`sieving-apparatus.md` · source `072-sieving-apparatus` · tier HV

Description is a single sentence with no throughput numbers; third screenshot appears to be the underside (labeled Bottom), verify. Only other message is non-substantive chatter, so no Notes section.

## Pyrolytic Compound Breakdown Unit
`pyrolytic-compound-breakdown-unit.md` · source `073-pyrolytic-compound-breakdown-unit` · tier UV

The .txt attachment is a JSON structure export (statePosArrayList + requiredItems), not a Litematica schematic; it uses a Chisel 'futura_purple_me_controller' block as a placeholder controller and ZPM-tier hatches despite the UV target. Author's display name is Japanese (デイモス); check it renders in the byline/index. Bounding box 5x15x11 and block count 341 were derived from the export, not stated by the author.

## Steam Glassworks and Glass Factory
`steam-glassworks-and-glass-factory.md` · source `074-steam-glassworks-and-glass-factory` · tier Steam and LV to around LuV

Tier split per structure (Glassworks = steam, Factory = LV-LuV) is inferred from the names; author only wrote 'Steam and LV to around LuV'. Both schematics are inline copy-paste strings, not files; the Steam Glassworks string is reproduced as posted with unescaped quotes (likely broken JSON). Mechanics are vague by the author's own admission. Dimensions derived from the schematic start/end positions.

## Modular Ingot Processing Facility
`modular-ingot-processing-facility.md` · source `075-modular-ingot-processing-facility-mipf` · tier LuV

The author did not say which of the three module-slot screenshots and which interior views belong to which part (Control Station / Smeltery / Chiller); tab labels describe appearance only. Likely mapping: dark truss = Smeltery, teal frame = Chiller, grey wall = Control Station; corridor = Control Station interior, fan chamber = Chiller interior. Author also said 'it could go up to ZPM/UV if needed' in reply to feedback; tier kept as LuV.

## Thermal Dissociation Complex
`thermal-dissociation-complex.md` · source `076-thermal-dissociation-complex-tdc` · tier ZPM and above

Front/back labels of the angled screenshots are inferred from the center block (vent-like block assumed to be the muffler on the back); the author did not label the images. No parallel count or dimensions were given.

## Temporally Insurgent Monocrystal Energizer
`temporally-insurgent-monocrystal-energizer.md` · source `077-temporally-insurgent-monocrystal-energizer-time` · tier UIV+(Post-K.O.M.A.R.U.)

Tier written as 'UIV+ (Post-K.O.M.A.R.U.)'; author said it can move to UXV. Fourth screenshot labeled 'Interior cap' from visual inspection (author gave no captions).

## Dimensional Resonator
`dimensional-resonator.md` · source `078-d-r-dimensional-resonator` · tier UV+

Entry is a companion to the A.B.Y.D.O.S. & E.O.H. thread (1554774954451537950); the authors say that post holds the full project info, so consider cross-linking once that page exists. 'Front'/'Back' labels are a judgment from the screenshots, not stated by the authors.

## Ocean Draining Device
`ocean-draining-device.md` · source `079-ocean-draining-device` · tier ZPM

Functional summary is a single sentence; no in-depth mechanics, numbers, or dimensions were given. Thread discussion was only a fish meme exchange.

## Mega Mechanical Plate Presser
`mega-mechanical-plate-presser.md` · source `080-mega-mechanical-plate-presser-mmpp` · tier late LV

Actual designer is the poster's little brother (no Discord); byline credits TheSkadoodler as submitter. Structure block description in the Structure section is inferred from screenshots, not stated by the author.

## Large Item Vault / Large Fluid Tank
`large-item-vault-and-large-fluid-tank.md` · source `081-large-item-vault-large-fluid-tank` · tier IV (as a sidegrade to bulk cells) or HV (as a earlier alternative)

The four screenshots are external i.postimg.cc links (not attachments, not saved, and not reachable from here), so the page has no image tabs and links them under Files with a note admonition after the info table; consider downloading them into Contest_img. Both .txt attachments are JSON block-list templates (statePosArrayList/requiredItems), treated as schematic files. Structure descriptions (10x5x5 and 5x6x5 bounding boxes, block counts, hatch faces) are derived from parsing those files, not from the author's text; the item vault's up/down orientation could not be determined, and the fluid tank file contains one stray grass block that was left out of the description. The AE2 Controller block on the hatch face of both schematics is probably a stand-in for the controller or the proposed ME Storage Hatch/Bus, but the author did not say so. 'PS' is kept as the author wrote it (presumably Power Substation). Tier set to IV with order hint HV because the author offered both for the same two structures. Author typos ('simular', 'direkt conection', 'Hermetig', 'a earlier') corrected silently.

## Lagrangian Anchored Rift Pulsing Inductive Negating Generator
`lagrangian-anchored-rift-generator.md` · source `082-l-a-r-p-i-n-g-lagrangian-anchored-rift-pulsing-inductive-neg` · tier UV

Slug shortened to 'lagrangian-anchored-rift-generator' to stay near the 50-char limit (full name is 61 chars). Page links to the Abydos/Eye of Horus page (data-optimization-sanctum-and-eye-of-horus.md) as the authors' main entry; verify that slug is final. Author wrote 'LARP' once as a short name for the structure; kept as written.

## Sieving in Extraordinaire Velocity and Efficiency **(incomplete)**
`sieving-in-extraordinaire-velocity-and-efficiency.md` · source `083-sieving-in-extraordinaire-velocity-and-efficiency-s-i-e-v-e` · tier HV

Post has only a one-line summary; no throughput/parallel numbers. Structure sentence (7x3x7, Clean Machine Casings, 5x5 mesh lattice, HV buses) was read from the .nbt schematic, whose controller slot is a Chisel placeholder block and whose mesh is a kubejs:meshblock placeholder; the mesh blocks in the schematic are 17, not a full 25.

## Draconic Stargate Guided Circuit Assembler **(incomplete)**
`draconic-stargate-guided-circuit-assembler.md` · source `084-draconic-stargate-guided-circuit-assembler` · tier Post-DSG

Tier is 'Post-DSG' (no voltage tier); 'DSG' is not expanded by the author (may or may not stand for Draconic Stargate Guided), so no acronym was assigned. Mechanics are one line only.

## Global notes

- Attachments posted by people other than the author were not imported, except in Forgotten Phase Shifter (co-author ggki).
- Large Item Vault / Large Fluid Tank: screenshots were external postimg.cc links, not Discord attachments, so the page has no images.
- Several schematics are Building-Gadgets-style JSON block dumps saved as `.txt`/`.json`; the writers derived dimensions and block lists from them where the author gave none. Those details are from the file, not the author's prose.
- Pages that only quote mechanics from a linked Google Doc (MMOPF, LEU/LEM, CELLS, Forgotten Phase Shifter, SPF) are thin; the docs were not fetched.
- Tier tags above UIV (`<UXV>`, `<OpV>`) have no CSS yet in `docs/assets/styles/styles.css`.