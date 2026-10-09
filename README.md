# MOTION: the 3 free tools + my exact prompt

**The tools (all free):**
1. **GSAP**: animation engine pro designers use. https://gsap.com · https://github.com/greensock/GSAP
2. **Lenis**: smooth, buttery scroll. https://lenis.darkroom.engineering · https://github.com/darkroomengineering/lenis
3. **React Bits**: copy-paste animated text, backgrounds and buttons. https://reactbits.dev · https://github.com/DavidHDev/react-bits

**How to use:** open your website project in Claude Code and paste the prompt below. Works on any React / Vite / Next.js site.

---

```
Add these three tools to this website and make it feel premium:

1. GSAP: https://gsap.com (npm: gsap @gsap/react)
2. Lenis: https://lenis.darkroom.engineering (npm: lenis)
3. React Bits: https://reactbits.dev (components are copy-paste, e.g. https://reactbits.dev/r/SplitText-JS-CSS.json)

Do this:
- Install gsap, @gsap/react and lenis with npm.
- Add Lenis smooth scroll for the whole page and drive it from gsap.ticker, synced with ScrollTrigger.
- From React Bits, add: SplitText on the main heading, Aurora as the hero background, ShinyText on the small tagline, Magnet around the main button. Put the component files in src/components/reactbits/.
- Use GSAP + ScrollTrigger to reveal sections and cards as they scroll in (ease "expo.out", 0.8-1.2s, small stagger).
- Keep all my text, images and layout. Only improve typography, spacing and motion.
- Respect prefers-reduced-motion.
- When done, run the build and fix any errors.
```
