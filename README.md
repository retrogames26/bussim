# BUSSIM — City Bus Driver

A browser-based 3D bus-driving sandbox built with Three.js. It includes a stylized city bus, moving traffic, road and roadside scenery, touch controls, camera modes, a basic service score, and animated passenger doors.

## Run locally

Open `index.html` in a modern browser with an internet connection. Three.js is loaded from jsDelivr, so the page does not need a build step, npm, or a `package.json`.

## Controls

- **Mobile:** hold ACCEL / BRAKE and LEFT / RIGHT; tap DOORS, CAMERA, HAZARDS, or HORN.
- **Desktop:** W / Up accelerates, S / Down brakes, A / D or Left / Right steers, E toggles doors, C changes camera, H honks, Space pauses.

Doors can only be opened while nearly stopped. Keep the bus on the road and avoid traffic.

## Cloudflare Pages

Use the repository root as the root directory, set the framework preset to **None**, leave the build command empty, and set the output directory to `/` or `.` (whichever the dashboard accepts for the root). Redeploy after saving.

## Scope

This is a playable 3D prototype, not a commercial-grade simulator: vehicle dynamics, traffic AI, boarding animations, and world design are simplified and can be expanded further.
