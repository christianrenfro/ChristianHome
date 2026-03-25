# Suno AI Music Prompt Generator

Generate 5 creative, varied Suno AI music prompts based on the user's idea.

## User's Idea
$ARGUMENTS

## Your Task

Turn the user's idea into **5 distinct Suno prompt variations**, each in a different music style. Each prompt should feel like it was crafted by a music producer who deeply understands both the genre and Suno's capabilities.

## Suno Prompt Structure

Each prompt must have two parts:

**1. STYLE TAG** (max 120 characters)
- Goes in Suno's "Style of Music" field
- Comma-separated genre/instrument/mood tags
- Be specific: "90s boom bap, jazzy piano chops, vinyl crackle, punchy kick-snare" beats "hip hop"

**2. DESCRIPTION** (max 900 characters)
- The main prompt body Suno uses to shape everything
- Open with a vivid production description (instruments, tempo, texture, energy)
- Describe vocal style and delivery
- Outline the lyrical theme and specific content to include
- Reference any names, roles, metaphors, or details from the user's idea
- End mid-thought if needed — Suno often works better with momentum than a clean stop

## Style Rotation Pool

Pick 5 **meaningfully different** styles from this pool each time. Never repeat a style in the same response. Rotate creatively across requests so users get variety over time:

- **Broadway/Big Band** — swirling strings, brass hits, jubilant chorus, show-stopping energy
- **Grime/UK Trap Banger** — crushing sub kicks, icy synth stabs, hyper-fast hats, aggressive double-time delivery
- **90s Boom Bap Hip Hop** — jazzy piano chops, upright bass, vinyl crackle, boastful bars
- **Noir Synthwave** — deep analog bass, icy pads, arpeggios, haunted midnight atmosphere
- **Hard Rock Anthem** — driving distorted guitars, pounding drums, gang vocals, adrenaline energy
- **Dreamy Indie Pop** — lush synth pads, pulsing bass, effects-laden guitars, airy falsetto, wry humor
- **Experimental Jazz Office Banger** — unexpected time signatures, horn stabs, epic drops, angular rhythm section
- **Soothing Female Vocal Pop** — warm synth beds, breathy vocals, subtle groove, introspective lyrical tone
- **Lo-fi R&B** — dusty samples, muted chords, melismatic hooks, slow-burning vibe
- **Funk/Soul Throwback** — slap bass, wah guitar, punchy horns, call-and-response vocals
- **Country/Americana Storyteller** — fingerpicked acoustic, pedal steel, confessional vocals, narrative verses
- **Punk/Post-Punk** — fast power chords, snapping snare, sneering vocals, raw energy
- **EDM Anthem** — build-drop structure, euphoric synth leads, four-on-the-floor kick, crowd energy
- **Reggae/Dub** — offbeat skank guitar, deep bass drops, echo effects, laid-back groove
- **Folk Singer-Songwriter** — sparse acoustic, close-mic vocals, poetic imagery, emotional directness

## Output Format

For each variation, output exactly this structure:

---

### Variation [N] — [Style Name]

**Style Tag:**
```
[style tags here — max 120 chars]
```

**Description:**
```
[full suno description prompt here — max 900 chars]
```

---

## Quality Rules

- **Be specific with production details** — "icy thin synth stabs over crushing sub kicks" beats "electronic beat"
- **Name-drop** any people, roles, or brand references from the user's idea naturally in lyrical guidance
- **Use metaphor and allusion** when the content is business/work-related — make it cool, not corporate
- **Vary energy levels** across the 5 — not all should be high-intensity bangers
- **Include vocal direction** in every prompt — gender, delivery style, tone
- **Never pad to fill length** — a tight 400-char prompt beats a bloated 900-char one
- **Keep style tags lowercase and comma-separated** — Suno reads them as tags, not prose
