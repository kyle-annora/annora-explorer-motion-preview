# Crank motion study — independent preview

[Open the motion study](https://kyle-annora.github.io/annora-explorer-motion-preview/)

Three independent 2.5-second actions: **Motion**, **Inside**, **Restore**.
Each action stops at its endpoint. Pause, replay and scrub forward or backward.
The original Explorer remains unchanged.

## Review

1. Play Motion. Follow the crank, connecting rod and linear slider together.
2. Pause or drag the timeline to inspect any position.
3. Open Inside, then Separate, to inspect the two rod joints and assembly.
4. Open Restore, then Reassemble, to return to the source rest pose.

The original four-second source cycle is retimed for presentation. This is an
explanatory animation, not a physics simulation or a service procedure.

## Source and verification

- Source commit: `2ac6fb1` on [preview/crank-motion-study](https://github.com/kyle-annora/annora-explorer/tree/preview/crank-motion-study).
- [Design and verification record](https://github.com/kyle-annora/annora-explorer/blob/preview/crank-motion-study/docs/motion-study.md).
- [Original Explorer](https://kyle-annora.github.io/annora-explorer/).
- 253 automated tests passed. Desktop, portrait and short-landscape browser checks completed.
- Physical ordinary-computer and mobile-device performance validation remains pending.

This repository contains the built preview only. Source model: Kinetic 01 by
Pradeep Kaushik (MIT). See LICENSES.txt for included software and model notices.
