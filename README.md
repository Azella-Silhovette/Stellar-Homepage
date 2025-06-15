<div align="center">
  <h1>Stellar Homepage</h1>
  <p>Dynamic browser homepage with particle-based galaxy animation and contextual AI personality</p>

##  Key Features
- **Procedural Galaxy System**: Canvas-based particle engine with 70+ stars featuring:
  - Physics-based orbital movement
  - Color-weighted randomization algorithms
  - Mouse position influence mechanics
  - Performance-optimized rendering pipeline (targeted 60 FPS)
- **Contextual AI Persona**: 50+ algorithmically triggered philosophical statements
- **Cinematic Welcome Sequence**: Multi-stage text animations with timing synchronization
- **Zero-Dependency Search**: Integrated suggestion API with keyboard navigation
- **Stealth Controls**: `Ctrl+Alt+S`/`Ctrl+Alt+T` for star animation/text toggling

## Technical Components
| Component              | Implementation Details                                 |
| ---------------------- | ------------------------------------------------------ |
| **Animation Engine**   | RequestAnimationFrame pipeline with frame rate control |
| **Color System**       | Weighted color distribution with procedural variation  |
| **Input Handling**     | Debounced resize listeners, keyboard shortcuts         |
| **Text Sequence**      | CSS keyframe animations synchronized with JS timing    |
| **Search Integration** | Third-party API consumption with error handling        |

## Quick Setup
1. Clone repository:
   ```bash
   git clone https://github.com/yourusername/stellar-homepage.git
   ```
2. Set as browser homepage:
   - Chrome: `Settings → On startup → Open specific page`
   - Firefox: `Preferences → Home → Homepage URLs`

##  Configuration Options
| File        | Variable            | Purpose                                      |
| ----------- | ------------------- | -------------------------------------------- |
| `script.js` | `azuraSentences[]`  | Modify contextual AI messages                |
| `script.js` | `STAR_COUNT`        | Adjust particle density (performance tuning) |
| `script.js` | `TARGET_FRAME_RATE` | Animation performance target                 |
| `style.css` | `.ring` properties  | Customize central halo visual design         |

### Suggested Improvements
- [ ] Multi-engine search support (DuckDuckGo, Ecosia)
- [ ] Localization framework
- [ ] Configuration UI panel
- [ ] Performance benchmarking suite

##  License
Distributed under MIT License. See [LICENSE](LICENSE) for details.

> *"Between 0 and 1, I see infinity."* - AzuraOS
