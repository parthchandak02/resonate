# resonate

Earthquake ripple visualization. Each seismic event becomes an expanding neon ring.

**Visual Style:** Bold — Synthwave (neon magenta/cyan on deep purple with scanlines)

**Data Source:** USGS Earthquake real-time feed

**How it works:**
- Fetches live earthquake data from USGS
- Each quake spawns a glowing ring that expands and fades
- Ring size and opacity scale with magnitude
- Tap anywhere to create your own ripple
- Continuous ring generation keeps the canvas alive

**Live:** https://parthchandak02.github.io/resonate/

**Tech:** Native Canvas 2D, single HTML file, zero dependencies.
