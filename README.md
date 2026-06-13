# Elevatron

**A graduate-level concept study of a magnetically-pinched, laser-coupled beam as a dual-purpose structure and conductor for assisted access to space.**

> **Status:** Speculative concept synthesis + reproducible benchtop demonstrations of the underlying physics.
> This is an *experiment in rigorous concept evaluation*, not an engineering proposal for a buildable launcher. The honest feasibility verdict is in [`docs/06-feasibility-analysis.md`](docs/06-feasibility-analysis.md): the megastructure version is **not viable with foreseeable technology**, but the component physics is real, well-cited, and reproducible at the bench.

---

## The core idea

A high-current charged-particle (or plasma) beam driven along a central axis generates its own azimuthal magnetic field. Above a threshold current the beam **self-pinches** (the Bennett / Z-pinch effect), compressing into a dense, narrow column that resists radial spreading. Surround that column with an external ring/solenoid magnet array, and add lasers to pre-ionize, stabilize, or energize the channel.

The conjecture this repository evaluates — proposed conversationally by the author — is that **the central beam can play two roles at once**:

1. **Conductor.** A fully-ionized plasma or relativistic electron beam is an excellent current carrier; it can deliver power or momentum along its length.
2. **Structure.** Magnetic tension in the pinched column plus interaction with the external field could, in principle, provide rigidity — a *dynamic, self-reforming "pillar"* rather than a material cable.

The repository asks, with citations and bench experiments: **how far does the physics actually carry this idea?**

## What's in here

| Path | Contents |
|------|----------|
| [`docs/00-abstract.md`](docs/00-abstract.md) | One-page abstract |
| [`docs/01-introduction.md`](docs/01-introduction.md) | Framing, scope, and what "Elevatron" is and isn't |
| [`docs/02-physics-magnetic-pinch.md`](docs/02-physics-magnetic-pinch.md) | Bennett relation, Z-pinch, MHD instabilities — derivations |
| [`docs/03-central-beam-structure-conductor.md`](docs/03-central-beam-structure-conductor.md) | The dual-role conjecture, evaluated quantitatively |
| [`docs/04-laser-coupling.md`](docs/04-laser-coupling.md) | Where lasers fit: pre-ionization, guiding, MagLIF analogy, beamed propulsion |
| [`docs/05-system-architecture.md`](docs/05-system-architecture.md) | A reference architecture (ring magnets + axial beam + laser channel) |
| [`docs/06-feasibility-analysis.md`](docs/06-feasibility-analysis.md) | Energy budget, instability growth, atmospheric breakdown — the honest verdict |
| [`docs/07-homemade-experiments.md`](docs/07-homemade-experiments.md) | **Graduate lab chapter:** safe, low-cost demonstrations of the real physics |
| [`docs/08-conclusions.md`](docs/08-conclusions.md) | What survives scrutiny, and the nearer-term cousins |
| [`references/bibliography.bib`](references/bibliography.bib) | BibTeX of the cited literature |
| [`references/citations.md`](references/citations.md) | Annotated reading list |
| [`experiments/`](experiments/) | Build notes & data templates for the benchtop demos |

## The "citation as an experiment" framing

This project treats the whole exercise as an *experiment in honest citation*: every load-bearing claim is tied to a real, locatable source (see [`references/`](references/)), and every place where the popular framing outruns the physics is flagged. The point is to show how a speculative megastructure idea holds up when you actually attach the references and run the numbers.

## Safety note

The homemade chapter ([`docs/07`](docs/07-homemade-experiments.md)) deliberately restricts itself to **low-energy, supervised, educational demonstrations** of the pinch *principle* (parallel-wire forces, a low-current saltwater pinch, plasma-globe and salvaged-CRT observations). It does **not** describe building a high-energy capacitor-bank Z-pinch — those store lethal energy and are strictly facility-grade apparatus. Read the safety preamble before attempting anything.

## License

MIT — see [`LICENSE`](LICENSE). Cite responsibly.
