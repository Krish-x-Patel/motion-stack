# Motion Stack Demo

**Live site: https://krish-x-patel.github.io/motion-stack/**

A one-page demo of three animation libraries working together:

- **[Lenis](https://github.com/darkroomengineering/lenis)** smooths the scroll and sets the browser's real scroll position every frame.
- **[GSAP](https://github.com/greensock/GSAP)** runs the shared clock (`gsap.ticker`) and the scroll animations: a pinned horizontal track with ScrollTrigger, scrubbed text, and a page progress bar.
- **[React Bits](https://github.com/DavidHDev/react-bits)** supplies 11 animated components: GradientWaves, SplitText, ShinyText, RotatingText, ScrollVelocity, ScrollReveal, SpotlightCard, CountUp, StarBorder, ClickSpark and TiltedCard.

The corner readout shows Lenis's live numbers (scroll position, target, velocity, progress) and GSAP's frame rate.

## What's in this repo

This repo holds the built site only: `index.html` is a single self-contained file (React, GSAP, Lenis and the components are bundled into it), plus the tab icon and link-preview image. It was built with Vite and `vite-plugin-singlefile`.

## Credits and licenses

- GSAP: GreenSock standard "no-charge" license.
- Lenis: MIT, by darkroom.engineering.
- React Bits: MIT + Commons Clause, by David Haz. The components are used here as part of a website, which the license allows; they are not offered for reuse from this repo.
