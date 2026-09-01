# The Isles

*A growing archipelago of tiny interactive worlds — feed a polar bear, watch an octopus vanish into the reef, or catch a bear slipping into its den at dusk.*

---

## How this started

We had about a dozen ideas we refused to let die quietly in a notes app: a polar bear that actually gets fed a fish, an octopus that panics and vanishes into a rock, and a bear that goes home to sleep and doesn't want to be bothered until you knock.

**The Isles** is a scattered archipelago of standalone worlds, each one built fast, each one built around a single question: *what's the most satisfying thing a person could click here?*

---

## The worlds

Every isle is small on purpose. One mood, one mechanic, done properly, rather than five ideas done halfway.

| Isle | What you'll find | What you can do |
|---|---|---|
| **Polar Caps** | A bear, penguins, a seal, snow that never stops | Feed the bear — watch it actually walk over |
| **Lake** | Koi, lily pads, dragonflies stitching the air | Drop food, watch the water ripple and the fish arrive |
| **Rainforest** | A sleeping tiger, a gator half in the mud, hidden birds | Discover what's really watching you back |
| **Bird Paradise** | An eagle's nest, a feeder, a whole restless flock | Call the eagle home. Fill the dishes. Watch the sky get busy |
| **Barnyard** | A coop, a mud pen, chickens who know where home is | Feed two species who refuse to share a food bowl |
| **Desert** | Dunes, an oasis, a camel with a saddle blanket | Send the camel walking. Watch the fox come for water |
| **Ocean** | Coral, kelp, an octopus with something to hide | Click too close and watch it disappear in real time |
| **Silvane** | Pines at dusk, fireflies, a deer family, a den | Send a deer to graze or drink. Send the bear to bed — or wake it up |

That's not a feature list. That's a growing collection of small promises, each one kept.

---

## Controls

- **Drag (Left Click)** — Orbit and rotate the camera 360° around the diorama
- **Scroll / Pinch** — Zoom in and out to inspect micro-details
- **Click** — Interact with creatures and environmental elements
- **Sound Toggle** — Click the ambient music button to toggle soundtracks

---

## Built with

- **Three.js**, running raw — no framework between us and the render loop
- **GSAP** for camera moves and interaction timing
- Vanilla **HTML / CSS / JS** — every isle is one self-contained file, because when an idea is good you don't want a build step standing between you and seeing it work

---

## Running it

Open `index.html` to explore the full interactive archipelago hub, or open any diorama file directly (e.g. `silvane-diorama.html`, `polar-caps-diorama.html`).

For the best experience with full ambient audio and music playback, serve locally via any simple HTTP server:

```bash
# Using Python
python -m http.server 8000

# Or using Node
npx serve .
```

Then open `http://localhost:8000` in your browser. No build steps or heavy installs required.

---

## What we actually learned building this

Low-poly doesn't mean simple — it means *disciplined*. Every creature that felt "off" turned out to be a proportions problem or a missing pair of eyes, not a polygon-count problem. And the mechanic that people lingered on longest wasn't the fanciest one — it was watching an octopus notice it had been seen.

---

## What's next

- Expanding the archipelago with new biomes and living creature ecosystems
- Rendering all floating islands together in a single continuous sky realm
- Adding dynamic weather, day/night cycles, and richer interactive mechanics
