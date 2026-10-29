# Haunted Hour 🎃

A dependency-free Halloween arcade overlay for websites, with responsive controls on mobile, tablet and desktop.

## Features
- Seven catchable creatures, including a rare golden pumpkin
- Score, combos, levels, rotating missions and locally saved best score
- Original synthesized Halloween music and creature sound effects, independently toggled
- Mouse, touch and keyboard support
- Shadow DOM isolation so the underlying page remains clickable
- Reduced-motion setting respected

## Quick start
Open `index.html` for the demo. To embed the overlay, add:

```html
<script defer src="/path/to/haunted-hour.js"></script>
```

## API
```js
window.__hw.spawn('ghost');
window.__hw.pause(true);
window.__hw.mute(true);
window.__hw.music(true); // Trigger through a user click
window.__hw.wave();
window.__hw.reset();
console.log(window.__hw.state);
```

## Audio and accessibility
Audio is off until the visitor opts in. Mobile browsers require user interaction to activate Web Audio. With reduced motion enabled, gameplay starts paused.

## License

GNU General Public License v3.0 (GPL-3.0-only). See [LICENSE](LICENSE).
