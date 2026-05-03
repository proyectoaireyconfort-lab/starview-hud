# STARVIEW-HUD-OMNI-OS · E.V.A. v8.0

Single-file HTML/CSS/JS astronomical telemetry system.

## Features

- Dual-State Machine:
  - STATE_A CIVIL_EXPLORER
  - STATE_B ENGINEERING_TACTICAL
- ASCII BIOS pre-loader simulation.
- Complementary sensor fusion core using:
  - deviceorientationabsolute / deviceorientation
  - devicemotion accelerometer and rotationRate
- Formula:
  `filteredAngle = α * (filteredAngle + gyroData * dt) + (1 - α) * accelData`
- Native astronomy kernel:
  - Julian Date
  - J2000 epoch days
  - Local Sidereal Time
  - Equatorial to Alt-Azimuth projection
  - Basic atmospheric refraction
  - Ecliptic plot with 23.44° obliquity
- HVAC field instrumentation:
  - Digital level Pitch/Roll/Yaw
  - Solar incidence / heat-load approximation
- 100+ star catalog with magnitude and spectral color coding.
- Zero-library dependency.
- Single file for GitHub Pages.

## Deploy

Upload only:

`index.html`

Then open:

`https://proyectoaireyconfort-lab.github.io/starview-hud/?v=omni-os`
