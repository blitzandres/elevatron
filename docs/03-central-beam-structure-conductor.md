# 3. The Central Beam as Conductor *and* Structure

This is the chapter the whole repository exists to evaluate. The conjecture has two halves; we grade them separately.

## 3.1 The conductor role — **strong**

A fully-ionized plasma column or a relativistic electron beam is among the best electrical conductors available.

- **Spitzer conductivity** of a hot plasma scales as $\sigma \propto T_e^{3/2}$ and at fusion-relevant temperatures rivals or exceeds copper.
- A relativistic electron beam *is* a current; carrying power along it is automatic.
- Self-focusing (the same Bennett effect, §2.2) lets a beam stay collimated over long ranges — the basis of long-distance power-beaming concepts (Greason's relativistic-beam architecture; the self-pinch extends usable range by large factors compared to an unfocused beam).

**Verdict:** the beam-as-conductor is not just plausible, it is how Z-pinches, lightning return strokes, and electron-beam power-transfer concepts already work. No objection. ✅

## 3.2 The structure role — **weak, and here is precisely why**

The intuition is that the magnetic forces holding the beam together also make it a rigid *pillar* that could help carry a payload upward. Two distinct failures:

### 3.2.1 The confining force points the wrong way

The self-pinch field $B_\theta$ produces a **radial inward** force (§2.1). It holds the column *together* against its own pressure. It does **nothing** to support a load *vertically* against gravity. A rope analogy: the pinch is like the *twist* that keeps the fibres of a rope bundled — it is not the *tension* that lets the rope hold a weight.

To get vertical support from magnetic fields you need one of:

- **Axial field gradients** pushing on a magnetized payload (this is *magnetic levitation / a launch loop / a coilgun* — and the support then comes from the **external structure**, not the beam).
- **Momentum transfer** — the beam continuously delivers upward momentum to the payload (this is *beamed propulsion*, §4 — again, the beam is an energy/momentum conduit, not a static strut).

In neither case is the *beam itself* the load-bearing member. The honest restatement: **the beam can be a power line or a momentum hose; it cannot be a column.**

### 3.2.2 Even as a strut, the numbers and the clock both fail

Suppose, generously, we tried to use magnetic tension as a structural element. Two ceilings:

1. **Stability clock.** The standing column tears itself apart on $\tau_A \sim$ µs (§2.4). A launch corridor must persist for **seconds to minutes**. That is a 10⁶–10⁹× gap, and external-field stabilization (§2.5) buys small factors, not orders of magnitude. A "self-reforming" column that reforms every microsecond is not a structure; it is a continuous, power-hungry discharge.

2. **Power to stand still.** Unlike a steel tower, a plasma pillar dissipates energy *continuously* — ohmic heating along its (small but nonzero) resistance, plus bremsstrahlung and line radiation scaling with $n^2$. A standing kilometre-scale, high-current channel radiates and conducts away power at a rate that has to be replaced every instant just to *exist*, before any payload is moved. A steel beam holds a load for free; a plasma pillar bills you by the microsecond.

**Verdict:** the beam-as-structure fails on direction of force, on stability timescale, and on standing-power cost. ❌

## 3.3 What the conjecture *does* survive as

Strip away the "static pillar" framing and a defensible system remains:

> **An external magnet array provides confinement/guidance; the central beam is a self-focusing conductor that delivers power or momentum to a climbing or beam-riding payload.**

That is no longer an elevator. It is a **beamed-energy launch assist with a plasma channel** — and that *is* a researched, physically-sound class of system (§4–§5). The author's dual-role intuition is right about the conductor and wrong about the structure, and recognizing exactly where the line falls is the contribution of this study.

## 3.4 Scorecard

| Sub-claim | Grade | Why |
|-----------|-------|-----|
| Beam carries power/current along its length | ✅ | Plasma/relativistic-beam conductivity |
| Beam self-focuses over distance | ✅ | Bennett self-pinch (§2.2) |
| Beam holds itself together radially | ✅ | Pinch confinement (§2.3) |
| Beam supports a payload vertically as a strut | ❌ | Force is radial, not axial (§3.2.1) |
| Standing column persists for a launch | ❌ | $\tau_A\sim$µs; continuous radiative/ohmic loss (§3.2.2) |
| System as *beamed-energy + guidance* | ⚠️→✅ | Reframed, it's a real concept (§4–5) |
