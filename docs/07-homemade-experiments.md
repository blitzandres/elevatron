# 7. Homemade Demonstrations of the Pinch Principle (Graduate Lab Chapter)

This chapter shows how to demonstrate the **real physics** behind Elevatron — the magnetic force between currents, self-constriction, and beam focusing — with **safe, low-cost, supervised apparatus** suitable for a teaching lab. Each demo maps back to an equation in §2.

> ## ⚠️ Safety preamble — read before anything else
>
> **What this chapter does NOT cover, on purpose:** high-energy capacitor-bank Z-pinches, electromagnetic "can crushers," and pulsed-power discharges. Those store **lethal** energy (kilojoules at kilovolts), can kill instantly through a single contact, and are **facility-grade apparatus requiring trained supervision, interlocks, and dump resistors.** Do not attempt them from a web document. They are out of scope here.
>
> **General rules for everything below:**
> - Work under qualified supervision (this is written at the level of a graduate teaching lab).
> - Stay at **low voltage** (≤ extra-low-voltage SELV, i.e. ≤ ~50 V) for any wet or hand-contact experiment. High *current* at low *voltage* (a bench supply, a battery) is how you safely show magnetic force.
> - **Never open a CRT or any vacuum tube.** Intact only.
> - Eye protection for anything that heats, sparks, or glows.
> - One hand behind your back near any energized circuit; know where the off-switch is.

---

## 7.1 Demo A — The Ampère force between parallel currents

**Maps to §2.1:** the inward $\mathbf{J}\times\mathbf{B}$ force that *is* the pinch, shown in its simplest form.

**Learning objective.** Observe and measure the attraction between two parallel conductors carrying current in the same direction — the elementary force the pinch integrates over a whole column.

**Apparatus (all low-voltage):**
- Two strips of household aluminium foil (~1 cm × 30 cm), hung side by side ~5–10 mm apart from an insulating support.
- A low-voltage **high-current** source: a bench supply in current-limit, or a single lead-acid cell through a current shunt. **Stay ≤ 12 V.**
- Series resistor / shunt to set and read current; clip leads.

**Procedure.**
1. Hang the two foil strips parallel, bottoms free to move, tops connected so current runs *up one and down the other* (anti-parallel → repulsion) or *up both* via a folded loop (parallel → attraction). Try both.
2. Ramp current; watch the strips deflect. Parallel currents pull together; anti-parallel push apart.
3. Estimate the force from the deflection angle and the strip weight.

**Analysis.** The force per length between two wires distance $d$ apart is

$$
\frac{F}{L} = \frac{\mu_0 I_1 I_2}{2\pi d}.
$$

Compare measured deflection to this prediction. This is literally the building block of the Bennett relation (§2.2): a pinch is a continuum of parallel current filaments all attracting.

**What it proves for Elevatron.** The self-confining force is real, mundane, and follows from $\mu_0 I^2$. The *radial* nature of the attraction is also visible — which is exactly the point of §3.2.1: the force pulls things *together sideways*, it does not lift them.

---

## 7.2 Demo B — The electrolytic (liquid) pinch

**Maps to §2.2–2.3:** self-constriction of a current-carrying conductive column.

**Learning objective.** See a conducting *fluid* column narrow when it carries current — the original visible pinch (the effect Bennett formalized).

**Apparatus (low-voltage only):**
- A shallow non-conductive trough of **mildly** conductive liquid (salt solution) — or, for a cleaner effect, a teaching-lab liquid-metal cell if your institution has one (galinstan, non-toxic). **No mercury.**
- Low-voltage bench supply, current-limited, **≤ 24 V**; electrodes at each end.
- Camera for slow-motion.

**Procedure.**
1. Establish a thin liquid bridge/column between electrodes.
2. Pass current and increase it; observe the column constrict (and, with liquid metal, sometimes neck off — the **sausage instability**, §2.4, made visible).
3. Record current at which constriction/necking onsets.

**Analysis.** Relate the observed constriction to the magnetic pressure $P_B = B_\theta^2/2\mu_0$ (§2.3) versus the fluid's hydrostatic/surface forces. The necking you see *is* the $m=0$ mode — a direct, safe view of the instability that dooms the standing-column idea (§6.2).

**Safety.** Keep voltage low; salt solutions and metals can heat. No mains. Ventilation if any electrolysis gas is produced.

---

## 7.3 Demo C — Beam focusing and deflection in a sealed electron tube

**Maps to §3.1 (conductor/beam) and beam steering:** a charged beam responds to magnetic fields and can be focused — the "self-focusing conductor" intuition, shown with an external field.

**Apparatus:**
- A **commercial sealed electron-beam deflection tube** (the Teltron/Leybold-type "fine beam" or "Maltese cross" tube used in university EM teaching). These are *designed* for student use with the proper HV supply and stand.
- The matched HV supply and Helmholtz coils that come with the teaching set.
- **Do not** improvise from a salvaged CRT, and **never open** any tube.

**Procedure.**
1. Energize the tube per the manufacturer/lab manual; observe the visible electron beam.
2. Apply a transverse field with the Helmholtz coils; watch the beam deflect (Lorentz force).
3. With a fine-beam tube, vary the field to focus the beam into a tight circle — a benchtop analogue of magnetic focusing/collimation.

**Analysis.** From the deflection radius $r = mv/(qB)$ you can even extract $e/m$. Conceptually: a charged beam is steered and focused by external $B$ — the kernel of §3.1's conductor role and §3.2.1's point that the field controls the beam's *path*, not a payload's *weight*.

**Safety.** Teaching tubes run at kilovolts internally — use only the matched supply, follow the lab manual, keep the tube in its stand, eye protection, no contact with HV terminals.

---

## 7.4 Demo D — Plasma globe: filamentation and self-organization (zero-build)

**Maps to §2.4–2.5:** filament channels, branching, and how a field organizes a discharge.

**Apparatus:** a commercial plasma globe (sealed, mains-isolated consumer item).

**Procedure & analysis.**
1. Observe the spontaneous filaments — current channels in low-pressure gas.
2. Bring a grounded finger near the glass; watch a single dominant channel form (a guided discharge — the §4.1 idea of *channeling* a current, demonstrated for free).
3. Note how channels wander and reform — qualitative cousin of the instability/reformation discussion in §3.2.2.

**Safety.** Use only an intact commercial globe; don't run for long periods (the glass and base warm). Pacemaker/RF cautions per the product manual.

---

## 7.5 Demo E — Bennett-relation estimation (analysis exercise, no new hardware)

**Maps to §2.2.** Using the current and rough column dimensions from Demo B (or published Z-pinch parameters), have students rearrange Bennett's relation

$$
\frac{\mu_0 I^2}{8\pi} = N k_B (T_e + T_i)
$$

to estimate the line density $N$ implied by their measured current and an assumed temperature, then sanity-check it against the geometry. This is the quantitative through-line that ties every demo to §2 and to the feasibility verdict in §6.

---

## 7.6 Lab report rubric (graduate level)

A complete write-up should, for each demo attempted:

1. State the governing equation from §2 and the prediction.
2. Report apparatus, currents/voltages, and measurement method.
3. Compare measurement to prediction with an error estimate.
4. Connect the result to the Elevatron evaluation — **specifically**, which sub-claim of §3.4 it supports or undermines.
5. Note the safety controls used.

The intended outcome is not a working launcher — it is a student who can show, with their own hands and a clear conscience about the citations, exactly **why the conductor role is real and the structural role is not.**
