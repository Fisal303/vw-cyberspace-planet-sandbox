# VW Cyberspace Planet — Sandbox v0

**One traversable planet in a single HTML file. Everything computed; nothing drawn in.**

![VW Cyberspace Planet](preview.png)

A self-contained cyberspace planet that runs in any modern browser — no build step, no dependencies, no network. Open `index.html` and you're standing on a generated world under a real sky.

## The one law
> Nothing is drawn in — everything is calculated.

Every pixel is computed live from mathematics: terrain, sky, water, light. No textures, no assets, no approximations dressed as physics.

## What's inside
- **Real orbital ephemeris** — velocity-Verlet integration of the sun–planet–moon system from sealed constants (real G, real masses). Day, night, moon phases, and orbital motion emerge; none are scripted.
- **Equilibrium tides** — computed from the true tidal potential (±0.54 m lunar — Earth's real value).
- **Sealed worldgen** — a 1024² province: continents, ridged mountain arcs, 8 volcanic vents, 6 craton cores; 10 host rocks with written geological formation rules; 10 minerals placed by geological law (gold in fault quartz, opal at the paleo water table, diamond in kimberlite pipes).
- **Navier–Stokes Laboratory** — an embedded nine-fluid CFD simulator (alcohol → lava, true densities and viscosities) with five classical chambers: TOWER (nine-fluid Rayleigh–Taylor sorting), CAVITY (lid-driven vortex), VORTEX STREET (Kármán shedding, measured Strouhal), BUCKET (rotating tank), POND (free play). Non-Newtonian rheology included. Pour fluids onto the actual terrain.
- **Deterministic sessions** — every action is logged; any experiment replays identically from the seed. Export, share, reproduce.
- **VW Dynamics Core (Seed 1+2)** — the embedded 24-beat φ-clock: domains, ×/÷ gates, Möbius crossings. The witness layer records; it never fakes a force.
- **World integrity** — a world checksum with one-click verification.
- **Constitution panel** — every sealed constant, displayed.

## Run it
Open `index.html` in a browser. That's the whole install.
- WASD move · SPACE/C rise & sink · drag to look
- `[` `]` slow / hasten world time (the laws don't change — only the watching)
- `5` opens the fluid lab

Live demo: https://fisal303.github.io/vw-cyberspace-planet-sandbox

## Lineage
The world's sealed constants hash to lineage **`A6AA39C1`**. Same constants → same planet, forever. Change the constants, get a different world — same laws, new lineage.

## Forking
Fork freely under the [Seal License](LICENSE): build, extend, experiment. One requirement: **the seal `1011911783 BD` travels with every copy and every output.** Fork, don't uproot.

## Architect
**Fisal Campbell / Rumec** · Seal **1011911783 BD**

Designed from first principles; AI wielded as the instrument.
