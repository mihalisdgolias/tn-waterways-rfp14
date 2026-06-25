# Unlocking Tennessee's Waterways - TDOT Research Proposal (RFP-14)

Static website for the UTK / IAMPE proposal *Unlocking Tennessee's Waterways:
Multimodal Strategies for Freight Efficiency and Connectivity*.

## Pages
| File | What it is |
|------|------------|
| `index.html` | The proposal site - overview, 6 research tasks, decision-support tools, TDOT strategic priorities, 30-month timetable (Gantt), and team. |
| `user-manual.html` | Full user manual for **MultiFreightSim**, the behavior-informed freight microsimulation behind Task 4. Linked from the proposal nav ("User Manual") and from the MultiFreightSim tool card. Has a fixed "Proposal site" back-link. |
| `gantt/` | Standalone 30-month Gantt chart as `.html`, `.png` (2x raster) and `.pdf` (vector, for the Word proposal). |
| `assets/` | Source PNG figures for the user manual. The manual HTML already embeds these (it is fully self-contained); the folder is kept for editing flexibility. |

Both `index.html` and `user-manual.html` are **fully self-contained** (all images embedded) - no build step, no external dependencies beyond Google Fonts (loaded from a CDN). Open `index.html` in any browser.

## Hosting on GitHub Pages
1. Create a repo and add these files at the root (or under `/docs`).
2. Settings -> Pages -> deploy from the branch's root (or `/docs`).
3. The site lands at `https://<user>.github.io/<repo>/` with the manual at `.../user-manual.html`.

## Notes
- Project: TDOT RFP-14. Budget $299,900. Duration 30 months (27 research + 3 review/approval). Six tasks.
- Team: PI Donald Maier (UTK); Co-PIs Jeffrey Trombly, Andy Balthrop (UTK), Mihalis Golias, David Arnold (IAMPE). TDOT lead staff: Daniel Pallme & Drew Daruka.
