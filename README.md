# BUSSIM — City Transit Simulator

A browser-based 3D city bus-driving prototype built with Three.js.

## Features

- Detailed procedural low-poly city bus with side windows, mirrors, wheels, passenger seating, dashboard, and driver cockpit view
- Three camera modes, including a driver-view camera
- Mobile touch controls for steering, accelerator, brake, doors, camera, hazards, and horn
- Keyboard controls for desktop
- Moving traffic in both directions, with simplified collision and service-score penalties
- City buildings, trees, streetlights, sidewalks, bus shelters, waiting passengers, and a repeating route
- Animated passenger doors; doors only operate when nearly stopped
- Bus-stop service and route progress display

## Controls

- **W / Up arrow:** accelerate
- **S / Down arrow:** brake
- **A / Left arrow:** steer left
- **D / Right arrow:** steer right
- **E:** open/close passenger doors (only when nearly stopped)
- **C:** change camera (chase, wide, driver cockpit)
- **H:** horn
- **Space:** pause
- On mobile, hold the on-screen pedals and steering buttons; tap the function buttons.

## Run and deploy

This is a static website. It does not need npm, a package.json, or a build command. For Cloudflare Pages, set Framework preset to **None**, leave the build command empty, use the repository root as the root directory, and publish the root directory. The game loads Three.js from jsDelivr, so an internet connection is needed.

## Important limitation

This is an expanded playable prototype, not a professional-grade simulator. Traffic AI, collision handling, passenger boarding, road rules, vehicle physics, and the city are simplified; the bus and scenery are procedurally modeled rather than high-detail imported assets.
