# 5. A Reference Architecture

To be criticized fairly, a concept must be concrete. Here is the most defensible Elevatron configuration — the version that keeps the conductor role and drops the disproven structural role.

## 5.1 Block diagram

```
                         ┌─────────────────────────────┐
                         │      PAYLOAD / CLIMBER        │
                         │  (beam-rider or magnetized    │
                         │   sled; receives energy &     │
                         │   momentum, not weight-bearing│
                         │   contact)                    │
                         └──────────────▲────────────────┘
                                        │  energy / momentum
        external ring / solenoid        │  delivered up the channel
        magnet array (B_z)        ╔══════╪══════╗
        guidance + screw-pinch    ║      ║      ║   ← axial field B_z
        stabilization             ║   ███████   ║      (confinement quality)
                                  ║   ███████   ║
                                  ║   ███████   ║   ← central self-pinched
        laser pre-ionizer  ─────▶ ║   ███████   ║      conducting beam (B_θ)
        & propulsion driver       ║      ║      ║
                                  ╚══════╪══════╝
                                        │
                         ┌──────────────┴────────────────┐
                         │   GROUND PLANT                 │
                         │   pulsed power (MA-class)      │
                         │   + laser farm (MW–GW)         │
                         │   + cooling / heat rejection   │
                         └────────────────────────────────┘
```

## 5.2 Subsystems

| Subsystem | Function | Maturity |
|-----------|----------|----------|
| Pulsed power supply | Drives MA-class current to form/maintain the pinch | High (Z-machine class exists) |
| External solenoid/ring array | Axial $B_z$ for screw-pinch stabilization + payload guidance | High (superconducting magnets exist) |
| Laser pre-ionizer | Cuts a conducting channel through atmosphere | Demonstrated (laser filaments) |
| Laser propulsion driver | Delivers thrust energy to the climber | Demonstrated small-scale |
| Central beam | Self-focusing **conductor** for power/momentum | Sound physics |
| Heat rejection | Removes continuous ohmic + radiative load | **The silent budget-killer (§6)** |

## 5.3 Operating concept (honest version)

1. Laser filament ionizes a vertical channel through the lower atmosphere.
2. Pulsed power drives the central beam; it self-pinches (radial confinement) and the external $B_z$ stabilizes it against kink.
3. The beam acts as a **conductor / momentum hose**: energy is delivered up the channel to a beam-riding or magnetically-guided climber.
4. The external magnet array provides **guidance and any vertical force**, maglev/launch-loop style — *not* the beam.

This is internally consistent and violates no physics. It is also, candidly, just **"beamed-energy launch assist with a laser-guided plasma channel and magnetic guideway"** wearing the Elevatron name. The grand "magnetic pillar to orbit" is gone, because §3 deleted it.

## 5.4 What changed from the original intuition

| Original framing | Survives? | Replacement |
|------------------|-----------|-------------|
| Beam = standing structural pillar | ❌ | Beam = conductor / momentum conduit |
| Magnetic pinch holds payload up | ❌ | External field guides; momentum/EM lift does the work |
| Lasers stabilize the pillar | partial | Lasers ionize the channel + drive propulsion |
| Conducts power along its length | ✅ | unchanged |
| "Circle magnet" around the beam | ✅ | screw-pinch stabilization + guideway |
