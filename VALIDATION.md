# Validation

- Production build: TypeScript checks and Vite build passed.
- Desktop: rendered in browser; project modal opens with correct problem, features, stack and repository.
- Keyboard: Escape dismisses modal and restores focus to its triggering button.
- Filters: DevOps shows AI DevOps Copilot; search combines with filter; unmatched query shows empty state; reset restores six additional projects.
- Theme: switching to light works and survives reload.
- Navigation: Contact link scrolls to section; active navigation updates to Contact.
- Copy email: status confirmed and browser clipboard matched the supplied address.
- Responsive QA: inspected production build at 390px and 768px iframe widths. No horizontal document overflow at either size; mobile menu opens and closes after selecting About.
- Resume: actual supplied PDF copied to public assets and included in production output; a browser download-event check timed out, so download event completion was not independently confirmed.
- Link checking: SKC website responded via web lookup. GitHub repository fetches were disabled and GHS portal could not be fetched. These links are preserved from the brief, not claimed verified. Fork/upstream status remains unverified.
- Preview markup clearly labels project visuals and example API response as illustrative.
- Browser console inspection showed extension metadata errors; no application error was observed.
- Reduced-motion support is implemented in CSS; OS-level reduced-motion emulation was not available in the browser controls.

## 3D redesign

- TypeScript and production build passed with separately loaded Three.js renderer.
- This cloud browser disables WebGL. Native WebGL visual output could not be verified; interactive CSS 3D fallback was verified instead. No browser graphics restrictions were changed.
- Verified mode switching updates the caption and monitor content, pause updates animation state, rotation updates the 3D transform, and reset returns it to zero.
- Verified dark theme, mobile mode switching and navigation, and mobile project dialog contents.
- Phone (390px) and tablet (768px) iframe QA showed no horizontal document overflow.
- Shared content and previously verified interactions are preserved.

## Playful redesign (current)

- Current active scene is native CSS 3D; no WebGL dependency or graphics fallback is needed. The previous WebGL implementation has been removed.
- Verified Build mode updates speech and laptop content; Happy dance creates 12 confetti elements; pause applies paused animation state.
- Keyboard right arrow updates yaw; reset returns it to zero.
- Random project picker opens a valid project dialog; Escape closes it and restores focus to the picker.
- Phone (390px) and tablet (768px) iframe checks show no document overflow; phone navigation opens and closes correctly after choosing Projects.
- Visually reviewed the warm light theme, robot, layered laptop/platform, navigation, and responsive hero.
