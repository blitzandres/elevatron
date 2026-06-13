# 2. The Physics of the Magnetic Pinch

## 2.1 Self-generated field

A column of plasma (or a charged-particle beam) carrying an axial current density $J_z(r)$ generates an **azimuthal** magnetic field. Ampère's law on a circle of radius $r$ gives

$$
B_\theta(r) = \frac{\mu_0}{2\pi r}\,I(r), \qquad I(r) = \int_0^r J_z(r')\,2\pi r'\,dr'.
$$

The current and its own field exert a body force $\mathbf{J}\times\mathbf{B}$ that points **inward** (radially toward the axis). This is the pinch: the beam squeezes itself.

## 2.2 The Bennett relation (radial equilibrium)

For a static, cylindrically symmetric column the radial momentum equation balances the kinetic pressure gradient against the magnetic force:

$$
\frac{dp}{dr} = -J_z B_\theta = -J_z \frac{\mu_0}{2\pi r} I(r).
$$

Integrating across the column and using $p = n k_B (T_e + T_i)$ yields **Bennett's relation** (Bennett 1934):

$$
\boxed{\;\frac{\mu_0 I^2}{8\pi} = N\,k_B\,(T_e + T_i)\;}
$$

where

$$
N = \int_0^\infty n(r)\,2\pi r\,dr
$$

is the **line density** (particles per unit length). The result is exact and independent of the radial profile — a remarkable feature that makes it the workhorse of pinch physics.

**Reading it physically:** for a given line density and temperature there is a unique current that holds the column in radial balance. Drive more current and it compresses further; less, and it expands. This is precisely the self-confinement the Elevatron conjecture relies on — and it is real.

## 2.3 Magnetic pressure — how strong is the "wall"?

The confining magnetic pressure is

$$
P_B = \frac{B_\theta^2}{2\mu_0}.
$$

A lab Z-pinch at $I = 1\ \mathrm{MA}$ and radius $a = 1\ \mathrm{mm}$ has

$$
B_\theta = \frac{\mu_0 I}{2\pi a} = \frac{(4\pi\times10^{-7})(10^6)}{2\pi(10^{-3})} \approx 200\ \mathrm{T},
\qquad
P_B = \frac{(200)^2}{2\mu_0} \approx 1.6\times10^{10}\ \mathrm{Pa} \;(\sim160\ \mathrm{kbar}).
$$

So the *radial* confinement is enormous — far beyond any material strength. **This is the seductive part of the concept.** The trap, developed in §3 and §6, is that this pressure points the wrong way for holding a payload *up*.

## 2.4 The instability problem

Bennett equilibrium is a *static* solution, and it is **violently unstable**. The two classical modes:

- **Sausage ($m=0$):** a local narrowing increases $B_\theta \propto 1/r$ there, which squeezes harder, which narrows it further — runaway necking that pinches the column off.
- **Kink ($m=1$):** a transverse bend concentrates field on the inside of the bend, amplifying the bend.

Both grow on the **Alfvén transit time**

$$
\tau_A \sim \frac{a}{v_A}, \qquad v_A = \frac{B}{\sqrt{\mu_0 \rho}}.
$$

For the parameters above, $\tau_A$ is on the order of **nanoseconds to microseconds**. Real pinches (MagLIF, dense plasma focus) survive only because they are *transient* — the interesting physics happens in the tens of nanoseconds before the column tears itself apart. Stabilization requires sheared axial fields, conducting walls, or active feedback, and even then buys you small factors, not the seconds-to-minutes a launch corridor needs.

> **Key takeaway for Elevatron:** the pinch is a brilliant way to *briefly* confine a dense plasma. It is a terrible way to maintain a *standing, kilometre-scale* column. The timescales are off by six to nine orders of magnitude.

## 2.5 Adding an external field

Wrapping the column in an external solenoid (axial $B_z$) is exactly the **screw-pinch / tokamak-like** stabilization route: the combined helical field resists the kink, and the column becomes a *magnetized* Z-pinch. This is the configuration the author's intuition points at — the "circle magnet" around the central beam. It genuinely improves stability (this is the physics behind MagLIF's axial pre-magnetization; Slutz et al. 2010). But:

- It does not change the *direction* of the confining force (still radial).
- It adds its own free energy and its own modes.
- It costs continuous power to maintain over any macroscopic length.

The external field is real and useful — for *confinement quality*, not for *vertical support*. §3 makes that distinction quantitative.

## 2.6 Summary of §2

| Claim | Verdict | Basis |
|-------|---------|-------|
| A current-carrying beam self-confines radially | **True** | Bennett relation, §2.2 |
| Radial confinement pressure can be enormous | **True** | §2.3 |
| The static pinch is stable on launch timescales | **False** | §2.4, $\tau_A\sim$ µs |
| An external solenoid helps stability | **Partly true** | §2.5, screw-pinch / MagLIF |
