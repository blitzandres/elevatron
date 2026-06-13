# 6. Feasibility Analysis — The Honest Verdict

Three independent budgets decide the concept: **energy**, **stability**, and **atmosphere**. Any one of them is close to fatal for the megastructure; together they are decisive. We then state what *does* survive.

## 6.1 Energy budget

**Minimum energy to orbit.** Low-Earth-orbit insertion needs roughly

$$
e_{\min} \approx \tfrac12 v_{\rm orb}^2 + g h \approx \tfrac12 (7.8\times10^3)^2 + (9.81)(4\times10^5) \approx 3.0\times10^7 + 3.9\times10^6 \approx 3.4\times10^7\ \mathrm{J/kg}
$$

so **≈ 34 MJ/kg** delivered to the payload, *before* any inefficiency. Beamed systems coupling at, optimistically, 10–30 % put the wall-plug figure at **100–340 MJ/kg**.

**Power.** Deliver that over a 100 s ascent: $\approx 0.34$ MW/kg delivered, ~1–3 MW/kg at the plug. A modest **1 t** payload ⇒ **0.3 GW delivered / 1–3 GW plug**. This is large but, notably, *not* the part that kills the concept — directed-energy launch studies (Lubin) live in this regime deliberately.

**The killer is standing power.** A material tower holds load for *zero* continuous power. A plasma channel does not: it bleeds energy every instant it exists via

- **Ohmic dissipation** $P_\Omega = I^2 R_{\rm channel}$ along a kilometre-scale conductor, and
- **Radiation** (bremsstrahlung + line) scaling as $n^2$ over the channel volume.

For an MA-class current in a long, hot, dense channel these run to **gigawatts merely to keep the channel lit** — paid continuously, delivering *no* payload work. You are renting the structure by the microsecond (§3.2.2). This is the budget line that has no analogue in conventional structures and no path to closure.

## 6.2 Stability budget

From §2.4, the column is unstable on the **Alfvén transit time**

$$
\tau_A \sim \frac{a}{v_A}, \qquad v_A = \frac{B}{\sqrt{\mu_0\rho}} \;\Rightarrow\; \tau_A \sim \mathrm{ns\text{–}\mu s}.
$$

A launch corridor must persist **seconds to minutes**. The gap is **10⁶–10⁹×**. Screw-pinch stabilization (external $B_z$, §2.5), conducting walls, and active feedback are real and help — but they buy factors of a few to tens in growth-rate reduction, not nine orders of magnitude. **No known stabilization closes this gap.**

## 6.3 Atmospheric budget

At sea level, dry air breaks down at $E \approx 3\ \mathrm{MV/m}$. A high-power beam or laser through the lower atmosphere causes:

- **Cascade ionization / breakdown** along the path (this is exploitable for *channel formation*, §4.1, but uncontrolled it dumps energy into air, not payload).
- **Thermal blooming**: heated air defocuses an optical beam, degrading aim over the very distances the concept needs.
- **Drag and convective loss** on any physical climber traversing dense atmosphere.

Mitigations (high-altitude or mountaintop start, vacuum tubes for the lower leg) help and are exactly what serious beamed-launch studies assume — but they are engineering taxes layered on top of §6.1 and §6.2.

## 6.4 Verdict table

| Budget | Requirement | Reality | Gap | Fatal? |
|--------|-------------|---------|-----|--------|
| Delivered energy | ~34 MJ/kg | achievable in principle | — | No |
| Plug power | 1–3 GW for 1 t | within directed-energy studies | — | No |
| **Standing channel power** | ideally ~0 | **GW-class, continuous** | structural-class | **Yes** |
| Stability lifetime | seconds–minutes | µs ($\tau_A$) | 10⁶–10⁹× | **Yes** |
| Atmospheric integrity | clean beam path | breakdown + blooming | severe | Major |

## 6.5 The honest conclusion

> **The Elevatron megastructure — a magnetic pinch acting as a standing, load-bearing pillar to space — is not viable with foreseeable technology.** It fails on the direction of the confining force (§3.2.1), on a stability timescale short by six-to-nine orders of magnitude (§6.2), and on a continuous standing-power cost with no structural analogue (§6.1). The atmosphere makes all of this worse.

> **What survives is real and worth pursuing:** the beam as a **self-focusing conductor / momentum conduit**, laser **channel-guiding** and **beamed propulsion**, and **magnetic launch assist**. These are active research areas (Lubin directed energy; Myrabo lightcraft; MagLIF; launch-loop / mass-driver studies), and the author's core intuition — *the central beam carries power beautifully* — is correct. The intuition that it also holds weight up is where the physics says stop.

This is the result a graduate committee would accept: a clear conjecture, tested against first-principles budgets, with a sharp boundary drawn between the part that works and the part that doesn't.
