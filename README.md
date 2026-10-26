# Amiga Hydraulic Arm (private)

PRIVATE REPOSITORY. Do not make this repository public. Do not turn on GitHub Pages for it.

This repository contains the complete work:

- **Amiga Hydraulic Arm twin** (`twins/pick-place-twin-amiga.html`): the hydraulic arm on a farm-ng Amiga rover.
- **Lab and tractor twin** (`twins/pick-place-twin.html`): the course twin. The public copy is in the repository `pick-place-twin`.
- **Help pages** (`help/`) for the two twins, and the landing page (`index.html`).

## Changes

- 2026-10-26: Amiga Hydraulic Arm twin: the conveyor rests on a roller at the bin edge; a horizontal cylinder under the rover pushes its low end out under the gripper and pulls it back in.

## Use the files

Open `index.html` or a file in `twins/` directly in a browser. Each twin is one self-contained HTML file and operates offline. No server is necessary.

## Share with a collaborator

On GitHub, open Settings, Collaborators, and add the person by GitHub user name. Remove access when the work is complete. Before you share new results outside Clemson, ask CURF for a nondisclosure agreement.

## Update

```
git add .
git commit -m "Describe the change"
git push
```

## Copyright

Copyright 2026 Clemson University. All rights reserved. Confidential. The embedded libraries keep their own licenses: Three.js and OrbitControls (MIT License), lil-gui (MIT License).
