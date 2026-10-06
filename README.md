# Discrete 1D Quantum Walk – interactive applet

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23184139.svg)](https://doi.org/10.5281/zenodo.23184139)

An interactive browser applet for the discrete one-dimensional quantum walk of a qubit,
made for physics and mathematics education (school and teacher training).

**Live version:** https://maxthematics.github.io/dynamicQuantumWalk/quantumwalk.html

## What it shows

- **Amplitudes as arrows:** each site shows the two qubit amplitudes |←⟩ (red) and |→⟩ (blue);
  length = modulus, direction = phase. The walk board shows all time steps at once.
- **Coin and initial state:** coin U(p, φ) with sliders and presets (Hadamard, stay, swap, complex),
  numeric coin matrix, initial qubit state set on a circle or via presets.
- **Probability distribution** after N steps (up to 100), compared with a classical Galton board
  (own parameter q).
- **Measurement:** position and/or qubit measurement in selected rows; single runs with collapse,
  exact average over many runs (density matrix), collected relative frequencies,
  per-row distributions.
- **Animation mode:** shows how one step is computed – coin, addition of the arrows
  (parallelogram) and shift – for up to N = 10.
- German/English, dark mode, responsive layout (desktop, tablet, phone),
  start configuration via URL parameters ("Link" button).

## Usage

Open `quantumwalk.html` in a current web browser – no installation needed.
An internet connection is required (see *Dependencies*).

URL parameters can preset the applet, e.g.
`quantumwalk.html?coin=hadamard&start=left&N=20&ort=alle`.
The "Link" button in the applet shows the link for the current state.

## Dependencies

The applet is written in [CindyJS](https://cindyjs.org) (CindyScript) and loads
CindyJS 0.8 and its KaTeX plugin from `cindyjs.org` at runtime.
These libraries are **not** included in this repository:

- CindyJS – Apache License 2.0
- KaTeX (used by CindyJS for formulas) – MIT License

## Citation

If you use the applet in teaching material or publications, please cite it:

> Hoffmann, M. (2026). *Discrete 1D Quantum Walk – interactive applet*. Zenodo.
> https://doi.org/10.5281/zenodo.23184139

See also `CITATION.cff`.

## Funding

Supported by the Deutsche Forschungsgemeinschaft (DFG, German Research Foundation) –
Project-ID 491392403 – TRR 358.

## License

MIT License, see `LICENSE`.

---

*Deutsch:* Interaktives Applet zum diskreten 1D-Quanten-Walk eines Qubits für den Einsatz in
Schule und Lehrkräftebildung (Pfeildarstellung der Amplituden, Münze und Startzustand, Verteilung,
Vergleich mit dem Galtonbrett, Orts- und Qubit-Messung, Animationsmodus). Sprache im Applet
umschaltbar (DE | EN).
