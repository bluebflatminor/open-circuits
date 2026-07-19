# Open Circuits

**A field guide to what flows through us — and why the wiring matters more than the current.**

Live: `https://bluebflatminor.github.io/open-circuits/`

## What this is

A single-page essay distilling one long dialogue into twelve connected sections ("nodes"). It starts with a question about machine awareness — could an AI with unlimited surveillance feeds, persistent memory, and an adaptive algorithm become more aware than an ordinary model? — and follows that question wherever it leads: China's surveillance state, values encoded in AI training, American polarization, in-group psychology, leadership, Gandhi and Hitler as a controlled experiment, Viking law and the Nordic welfare state, the ethical program of Christianity, revenge and forgiveness as opposite loop dynamics, and martyrdom as the dual-use hinge between them.

The synthesis, stated plainly at Node 11:

> Humans are the species whose members are open circuits to each other — permeable to one another's desires, fears, and permissions. Everything else is the engineering question of what flows through the connections.

The thread running through human affairs is not a value. It is *conductivity* — a valence-free amplification machinery. Culture is downstream of it; every fracture, sect, and polarization is the machinery running normally. The practical conclusion is therefore not "fix human nature" but "maintain the wiring": the institutions, norms, and algorithms that determine whether the current feeds a self-sustaining chain reaction (othering, revenge, polarization) or a self-terminating control rod (forgiveness, law, circle expansion).

Written to be accessible to a general reader in their twenties. No prior background assumed; ~17 minute read.

A closing appendix, **Test bench**, states the framework's predictions explicitly and runs them against cases the essay wasn't built from — Buddhism (independent replication of the doctrine-plus-power pattern), the Sunni–Shia split (focal-point succession plus grievance-charter martyrdom), Confucianism (a wiring manual rather than a competitor), the China–Dalai Lama standoff (dominance attempting to capture prestige machinery), a pacifist control group whose lack of state power keeps the central prediction honestly untested, Ashoka as the nearest recorded falsifier, and Marxism-Leninism as demonstration that the operative variable is power access, not theism.

## Structure

Twelve nodes on a signal path, each answering a question raised by the one before:

| Node | Section |
|------|---------|
| 01 · Input | It started with a machine that watches everything |
| 02 · Deployed | Someone already built the watching machine |
| 03 · Values | Every AI already has ethics baked in — the question is whose |
| 04 · Noise | American politics: divided by design |
| 05 · Substrate | The "other" is cheap to build |
| 06 · Focal point | Why leaders carry so much weight |
| 07 · Controlled experiment | Gandhi and Hitler: same tools, opposite settings |
| 08 · Boundary | From Viking raids to the welfare state |
| 09 · Exploit | The philosophy that attacked the boundary itself |
| 10 · Loop dynamics | Revenge, forgiveness, and the martyr problem |
| 11 · The thread | Is there a name for all this? (with synthesis schematic) |
| 12 · Output | You don't choose the current. You build the wiring. |
| Appendix · Test bench | Does the framework survive contact? (stated predictions, independent replications, control group, nearest falsifier) |

## Design

Single self-contained HTML file, no build step, no dependencies beyond Google Fonts.

- The visual conceit is a circuit schematic: a copper/live-wire rail runs the left margin, and each node lights as the reader passes it (IntersectionObserver).
- Dark and light themes; defaults to system preference with a manual toggle. Theme choice is session-only by design (no cookies, no storage).
- Node 11 contains an SVG synthesis schematic rendering the entire argument as one signal path: current → substrate → amplifiers → a switch (the wiring) → two output loops.
- The Test bench appendix is interactive: readers name a case, decompose it (boundary stance, power access, martyr caption), receive the framework's prediction *before* being allowed to check the historical record — the ordering is enforced deliberately — and get a scored "bench card" (Replication / Out of scope / Untestable / Falsifier candidate / Partial) they can copy. All in-memory; nothing is stored or transmitted. Selecting the "Defend" martyr caption is flagged as a known gap in the framework's bins.
- Type: Unbounded (display), Instrument Sans (body), IBM Plex Mono (schematic annotation).
- Responsive to mobile; respects `prefers-reduced-motion`; visible keyboard focus.

## Deploying

Rename `open-circuits.html` to `index.html`, push to `main`, and enable GitHub Pages (Settings → Pages → Deploy from branch → `main` / root).

## Method and disclosure

This essay was produced in collaboration with AI systems and distilled from a single extended dialogue (July 2026) between the author and Claude (Anthropic). The distillation, prose, and page design were drafted by Claude under the author's direction. An editorial review pass by GPT (OpenAI) contributed one adopted structural suggestion (the Node 11 synthesis diagram, redrawn to correct a topology error in the reviewer's version) and several sentence-level trims; other suggestions were declined and the declinations documented. Consistent with the correlated-instrument discipline used across this account's projects, agreement between AI reviewers was treated as roughly one opinion, not independent confirmation.

Historical and scientific claims are presented at field-guide resolution: they summarize established research (minimal group experiments, negativity bias, moral elevation, the perception gap, the romance of leadership, Norse legal history, the Xinjiang IJOP reporting) without inline citation. Readers should treat specific figures as pointers to the underlying literature, not as verified primary claims.

## License

CC0 1.0 Universal. No rights reserved. Copy, remix, republish, translate — attribution appreciated, never required.
