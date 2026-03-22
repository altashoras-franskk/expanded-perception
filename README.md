# Expanded Perception

**Interactive research dashboard for recursive applied research on perception, complexity, and epistemic tools.**

This repository hosts a live, browser-based research instrument built to support the development of a thesis on recursive self-observation and its epistemic consequences. The dashboard is itself an instance of the argument it tracks: a tool that reconfigures as the research evolves.

---

## The Research

Contemporary epistemological tools overwhelmingly privilege linearity — sequential processing, unidimensional metrics, static representations. W. Ross Ashby's Law of Requisite Variety (1958) formalizes what this implies: instruments with insufficient variety cannot absorb the variety of the systems they attempt to observe. Complexity escapes linear instruments by structural necessity.

**Tools for Perception (T4P)** is an experimental platform — built in TypeScript/React with artificial life techniques — designed as a response to this deficit. It operationalizes Edgar Morin's three complexity operators (dialogic, recursive, hologrammatic) as real-time measurable indices, running within a recursive loop where the observation field modulates the entities that write back into the field.

The candidate thesis: **systems that observe themselves while operating produce forms of knowledge inaccessible to linear analysis.** The candidate contribution: an **Extended Perception Thesis** — extending Andy Clark's Extended Mind via the parity principle (Clark & Chalmers, 1998) into the perceptual domain, with empirical grounding from Edwin Hutchins' distributed cognition framework and theoretical support from 4E Cognition (Gallagher, 2017).

Methodological position: **Research-through-Design** (Frayling, 1993). The artifact is the vehicle of investigation, tested and demonstrated through its own operation. Published under Open Science principles — open code, transparent methodology, open access.

## The Dashboard

Three integrated layers:

**Rizoma** — A force-directed conceptual graph with 38 nodes and 89 connections, organized into five functional groups: Axis (the argument's spine), Operations (what T4P does epistemically), Foundations (direct theoretical sources), Lineage (the Intelligence Amplification tradition), and Concepts (bridges across traditions). Nodes are draggable, fully editable, and include real-time emergence detection. Each node carries its theoretical text, epistemic status (thesis / hypothesis / evidence), key works, and weighted connections.

**Paper** — A structured editor for a 10-section paper with three writing layers per section: narrative (the linear argument), mobilized rhizome nodes (non-linear connections made visible), and recursive notes (self-observation on what writing each section revealed about the argument itself).

**Memory** — A map of 29 research decisions, hypotheses, calibrations, and productive tensions accumulated across sessions, linked to their corresponding concepts in the rhizome.

## Intellectual Lineage

The research positions itself within the **Intelligence Amplification** tradition — the lineage that chose to amplify human cognition rather than replace it:

Douglas Engelbart (1962) → W. Ross Ashby (1956) → J.C.R. Licklider (1960) → Andy Clark (2003) → Edwin Hutchins (1995) → Gregory Bateson (1972) → Stafford Beer (1972) → Bret Victor (2014)

Theoretical foundations: Edgar Morin, Deleuze & Guattari, Maturana & Varela, Heinz von Foerster, Douglas Hofstadter, Donella Meadows, James Gibson.

Contemporary framework: 4E Cognition (Embodied, Embedded, Enacted, Extended) as formulated by Shaun Gallagher, with productive tensions between enactivism and extended mind left deliberately unresolved.

## Technical

Single HTML file. Zero build step. Dependencies loaded via CDN:

- React 18
- D3.js 7 (force simulation, zoom, drag)
- Tailwind CSS
- Babel Standalone (JSX transpilation in-browser)

All edits (nodes, connections, paper text, statuses) persist automatically via `localStorage`. A reset button in the header restores the original research state.

## Usage

Open `index.html` in any modern browser. To deploy as a public page, host via GitHub Pages or any static file server.

## Active Tensions

These are questions the research inhabits rather than resolves:

- **Variety vs. Legibility** — If the instrument needs as much variety as its object (Ashby), how does the human read it? Translation is always partial.
- **Extension vs. Dependence** — If T4P is extended perception (Clark), what persists when the tool is removed?
- **Enactivism vs. Extension** — Knowledge emerges from interaction (enacted) AND is extended by the tool (extended). The T4P operates in both simultaneously.
- **Amplification vs. Substitution** — The IA vs. AI positioning carries political and epistemological weight.
- **Analogy vs. Formalism** — Ashby's law applies to control systems; the bridge to perception requires explicit argumentation.

## Related

- [Tools for Perception (T4P)](https://github.com/altashoras-franskk/Tabom-T4P) — The experimental platform / artifact-thesis

---

*Research in progress. Open Science.*
