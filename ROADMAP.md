# Dance Combat Lab — iPhone Version Roadmap

## Parking Lot

### 🎵 Music Theory Mode (Future Feature)

Idea: Teach rhythm concepts organically through combat. As players progress, the game surfaces and labels real musical concepts that are already embedded in the structure.

**Concepts to teach through gameplay:**

| Concept | How it maps to the game |
|---|---|
| **Beat / Pulse** | The BEAT bar already shows the pulse — label it "beat 1, 2, 3, 4" |
| **BPM (Tempo)** | Already shown in HUD; animate the change between levels |
| **Downbeat (Beat 1)** | Bar 1 flash already exists — label it explicitly |
| **Upbeat / Off-beat** | Half-beat attacks ARE upbeats — label them |
| **Measure / Bar** | 4-beat groupings already drive phrase logic |
| **Subdivision** | 8th note half-beats, 16th note quarter-beats as higher levels |
| **Note values** | Light = 8th note (quick), Heavy = quarter note (strong), FIN = whole note |
| **Syncopation** | Half-beat attacks that land on the upbeat |
| **Groove / Feel** | High-combo "dance" mode IS groove — name it |
| **Dynamic (loud/soft)** | Mic input: loud hit = Heavy, soft tap = Light |
| **Rhythm reading** | Future: show a simple drum grid (kick/snare) matching the beat |

**Implementation ideas:**
- A "Theory Mode" toggle on the title screen that overlays beat numbers (1 2 3 4) on the beat bar
- After each level, a short "What you just did" card naming the concepts used
- Level 6+ unlocks a drum pad view where the player taps kick/snare patterns to "build" the beat, and the enemy reacts to the groove quality
- Strumming detection (via mic) already maps to guitar rhythm — label it: "downstroke = heavy, upstroke = light"

**Audio input already supports:**
- Tapping (finger on table/desk) → Light attack
- Drumming (snare/kick) → Heavy attack  
- Strumming (guitar pick, rubber band) → transient burst = Heavy or Finisher
- Clapping → Parry timing input (loud transient on the beat)

This feature should stay parked until the core combat loop is fully stable across all 5 levels.
