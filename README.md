# The AI Album Creation Guide

### From Concept to Streaming Platforms - An End-to-End Framework

*By [Diana Wolfe, PhD](https://dianawolfephd.com) | Based on the [Southern Oracle](https://dianawolfephd.com/blog/on-building-southern-oracle) project*

> "I brought the words, the narrative, the aesthetic vision, the emotional architecture. The AI brought the sonic realization. Where does one end and the other begin? I am not sure the boundary is findable. I am not sure it needs to be."

---

This guide takes you from a blank page to a finished album on Spotify, Apple Music, and every major streaming platform - using AI tools for music generation, visual identity, and (optionally) multi-agent band member personas. It is designed for creators who bring their own vision and want to direct the process, not outsource it.

Southern Oracle - an AI-generated outlaw country band - was built using this exact workflow. The debut album *Turn the Cards* is streaming now. This guide is how you build yours.

---

## Table of Contents

1. [What You Will Need](#1-what-you-will-need)
2. [Phase 1: Album Concept and Vision](#2-phase-1-album-concept-and-vision)
3. [Phase 2: Songwriting](#3-phase-2-songwriting)
4. [Phase 3: Building Your Artist Identity](#4-phase-3-building-your-artist-identity)
5. [Phase 4: Music Production with Suno](#5-phase-4-music-production-with-suno)
6. [Phase 5: Album Art and Visual Identity](#6-phase-5-album-art-and-visual-identity)
7. [Phase 6: Post-Production](#7-phase-6-post-production)
8. [Phase 7: Distribution](#8-phase-7-distribution)
9. [Phase 8: Release and Promotion](#9-phase-8-release-and-promotion)
10. [Optional: Multi-Agent Band Architecture](#10-optional-multi-agent-band-architecture)
11. [Cost Breakdown](#11-cost-breakdown)
12. [Learning Resources](#12-learning-resources)
13. [FAQ](#13-faq)

---

## 1. What You Will Need

### Tools

| Tool | Purpose | Cost |
|------|---------|------|
| **Suno** (Pro or Premier) | AI music generation | $10–30/month |
| **DistroKid** or similar | Distribution to streaming platforms | ~$22.99/year |
| **Midjourney / DALL-E / Leonardo AI** | Album art and visual identity | $10–30/month |
| **ChatGPT / Claude** | Songwriting partner, persona development, project management | $20/month (optional) |
| **DAW** (optional) | Mixing and mastering (GarageBand is free) | Free–$200 |

### Skills (No Prior Experience Required)

You do not need to know how to play an instrument, read music, or use production software. You need:

- A creative vision (what do you want your album to sound like and say?)
- Written lyrics (or willingness to learn - see [Songwriting](#3-phase-2-songwriting))
- Patience to iterate (the first generation is almost never the final version)
- Taste (knowing when something sounds right is more important than knowing why)

### How Long Does This Take?

Once you know what you want to make, production moves fast. Southern Oracle's debut album *Turn the Cards* was written and produced in 24 hours. The technical execution - prompting Suno, generating tracks, iterating, selecting finals, creating album art - can happen in a single focused session or a long weekend.

The part that takes indeterminate time is figuring out what you want to create. That is not a production problem. It is a creative problem, and no tool solves it for you. Some people walk in with a decade of unrecorded songs. Others start from nothing. Both are valid, but they are different starting points with very different timelines.

**If you already have songs or a clear concept:** You can go from lyrics to a finished, distributed album in a weekend. Production is a day. Distribution processing (Spotify, Apple Music, etc.) takes 2-4 weeks regardless.

**If you are starting from scratch:** Give yourself permission for the concept phase to take as long as it takes. Do not rush into production before you know what the album is about. The sections below are designed to help you get there.

| Phase | Time |
|-------|------|
| Finding your concept | Days to months (see below) |
| Songwriting (if starting fresh) | 1-4 weeks |
| Production, art, and post-production | 1-3 days |
| Distribution processing | 2-4 weeks (platform lead time) |

---

## 2. Phase 1: Album Concept and Vision

This is the phase most people underestimate or try to skip. It is also the phase that determines whether the album feels like a cohesive work or a playlist of unrelated tracks. If you already have a strong concept, skim this section and move on. If you do not, slow down here. This is where the album gets made.

### If You Do Not Know What You Want to Make Yet

That is normal. Most albums do not start with a fully formed concept. They start with a fragment: a phrase, an image, a feeling, a question you cannot stop thinking about.

**Start by collecting, not deciding.** Spend a few days (or weeks) gathering raw material without trying to organize it:

- Write down phrases that stick in your head. Song titles, overheard dialogue, lines from books, things you said in conversation that surprised you.
- Notice what you are drawn to visually. Save images, color palettes, film stills, album covers that resonate. You are building an aesthetic instinct before you can name it.
- Pay attention to what you listen to repeatedly. Not what you think you should listen to. What you actually return to. That is data about your taste.
- Ask yourself what emotional territory you keep circling. Are you processing something? Celebrating something? Angry about something? Nostalgic for something?

**Then look for patterns.** After a week of collecting, spread it all out (literally or figuratively) and look for what clusters together. You are looking for the thread that connects the fragments.

**Useful questions to surface a concept:**
- If this album were a place, where would it be?
- If it were a time of day, when?
- What is the emotional state of the person listening to this alone at night?
- What is the one-sentence version of what this album is about?
- If you could only use five words to describe the sound, what are they?
- What albums do you wish existed but do not?

**Use an LLM as a thought partner.** This is one of the highest-value uses of AI in the whole process. Not to generate the concept, but to help you excavate the one you already have:

```
Here are fragments I have been collecting for a potential album:
[paste your notes, images descriptions, phrases, mood words]

Help me find the threads. What themes keep appearing?
What emotional territory does this seem to occupy?
Do not suggest a concept. Help me see what is already here.
```

**When you know you have found it:** The concept clicks when everything starts filtering through it. You hear a song and think "that belongs" or "that does not." You see a color palette and it feels right without explanation. You can describe the album in one sentence and it does not feel reductive. That is when you move on.

### Define These Four Things

Once you have your concept, make it concrete. These four decisions constrain every prompt, lyric, and production choice that follows.

**1. Emotional territory.** What does this album feel like? Is it a late-night drive? A breakup? A reckoning? A celebration? Southern Oracle's *Turn the Cards* was built around tarot imagery, desert landscapes, and women making hard choices.

**2. Sonic identity.** What genre neighborhood does this live in? Not a single genre - a neighborhood. "Outlaw country meets tarot and alchemy" is more useful than "country." Think in combinations: "lo-fi bedroom pop meets spoken word poetry" or "dark folk meets southern gothic."

**3. Narrative arc.** Does the album tell a story? Trace an emotional journey? Move from one state to another? Even if individual songs are standalone, the sequencing should have intention. Plan your opening, your midpoint, and your closer.

**4. Track list and pacing.** Know your album order, or at least your groupings. Albums have pacing. Alternate tempos and energy levels. Do not put three ballads in a row. Open with something that establishes the sonic identity. Close with something that resolves or recontextualizes.

### Album Concept Template

```
Album Title: [Working title]
Artist/Band Name: [Name]
Genre Neighborhood: [2-3 genre descriptors]
Emotional Territory: [1-2 sentences]
Narrative Arc: [Beginning → Middle → End]
Visual Aesthetic: [Colors, textures, mood]
Influences (describe, don't name): [Sound-alikes described in production language]
Track Count: [8-14 tracks]
```

---

## 3. Phase 2: Songwriting

### How Songwriting Has Always Worked

Before we get into the mechanics, it is worth understanding what songwriting actually is and how people have done it for a long time. This matters because AI changes the tools, not the craft.

**Songwriting is decision-making.** Every song is hundreds of small decisions: what to say, what to leave out, where the energy rises, where it drops, which word sounds better sung than spoken. The songwriter is the person making those decisions. That has not changed.

**Traditional songwriting approaches:**

- **The solo writer.** One person, an instrument (or not), working through lyrics and melody together. This is how most folk, country, and singer-songwriter music gets written. The constraint is that you are limited to your own perspective and your own ear.
- **The co-writing room.** Nashville and pop music run on co-writes. Two to four writers in a room, often with a producer, building a song together in a session. The power here is complementary skill sets: one person is a melody writer, another is a lyricist, another knows how to build a hook.
- **Top-line writing.** A producer creates a beat or instrumental track, and a vocalist writes melody and lyrics over it. Common in pop, R&B, hip-hop. The writer responds to what the music gives them rather than building from scratch.
- **The band writing process.** Members bring fragments, riffs, chord progressions, lyric ideas, and the song emerges through rehearsal and arrangement. The creative tension between members shapes the final product.

**What these all have in common:** Someone brings a vision. Someone else (or the same person in a different mode) refines the execution. The best songs happen when there is productive friction between the idea and the craft.

AI songwriting follows this same pattern. You bring the vision, the emotional intent, the story. The AI can help with execution: rhyme alternatives, syllable smoothing, structural feedback, brainstorming imagery. The division of labor mirrors what has always happened in co-writing rooms. The difference is that your co-writer never gets tired and has no ego about their contributions.

The risk is the same risk that has always existed in collaborative writing: losing your voice. If you let the AI write too much, the song stops being yours. The craft is knowing where to draw the line.

### If You Have Never Written a Song Before

Start here. A song needs three things: something to say, a structure to say it in, and language that sounds good when sung.

**Song structure basics:**
- **Verse:** Tells the story. New information each verse.
- **Chorus:** The emotional thesis. Repeats with the same or similar words.
- **Pre-chorus:** Builds tension between verse and chorus. Optional but effective.
- **Bridge:** A departure. New melody, new perspective, usually appears once.
- **Intro/Outro:** Sets the scene and closes it.

**Common structures:**
- Verse – Chorus – Verse – Chorus – Bridge – Chorus (most popular songs)
- Verse – Verse – Chorus – Verse – Chorus (folk/country)
- Verse – Pre-Chorus – Chorus – Verse – Pre-Chorus – Chorus – Bridge – Chorus (pop)

### Songwriting Tips for AI Music Generation

1. **Keep lines short.** Suno handles shorter lines better than dense paragraphs. Aim for 6–10 syllables per line.
2. **Match syllable counts** roughly across lines within a section for rhythmic consistency.
3. **Write for the ear, not the page.** Read your lyrics aloud. If they feel awkward to say, they will sound awkward sung.
4. **Choruses should be simple and repeatable.** The hook is the thing people remember.
5. **Use concrete imagery** over abstract language. "Dust on the highway, cards on the dash" beats "I was feeling lost."
6. **Write more than you need.** Write 15 songs to get 10 good ones. Cut ruthlessly.

### Using AI as a Songwriting Partner

You can use ChatGPT, Claude, or any LLM as a co-writer. Effective approaches:

- **Brainstorming:** "Give me 10 metaphors for leaving a relationship that use desert imagery"
- **Structure check:** "Here are my lyrics. Does the syllable pattern work for singing?"
- **Revision:** "This verse feels too wordy. Help me cut it to half the words without losing the meaning"
- **Rhyme alternatives:** "I need a near-rhyme for 'reckoning' that fits a line about moving on"

Do not ask the AI to write the whole song. Bring your vision. Use the AI to refine execution.

### Songwriting Learning Resources

**YouTube channels for songwriting craft:**
- **Pat Pattison** (Berklee College of Music) - search "Pat Pattison songwriting" for his lectures on object writing, prosody, and lyric structure
- **Holistic Songwriting** - practical tutorials on melody, harmony, and song structure
- **Andrew Huang** - creative approaches to songwriting and production, genre-spanning

**Books:**
- *Writing Better Lyrics* by Pat Pattison - the standard reference for lyric craft
- *Songwriters on Songwriting* by Paul Zollo - interviews with masters on their process

---

## 4. Phase 3: Building Your Artist Identity

### Define the Sound

Before you open Suno, define your artist's sonic signature. This becomes the consistent core of every style prompt.

**Vocal identity:**
- Gender and register (female alto, male baritone, etc.)
- Texture (raspy, breathy, clear, gravelly, smooth)
- Delivery style (understated, defiant, intimate, full-throated)

**Sonic palette:**
- 4–6 core instruments that appear across most tracks
- 1–2 "guest" instruments per song for variety
- Production aesthetic (lo-fi, polished, raw, atmospheric)

**Example - Southern Oracle:**
```
Voice: Raspy female alto, understated delivery
Core instruments: Acoustic guitar, upright bass, pedal steel, brushed drums
Production: Warm analog, lo-fi, reverb-heavy
Aesthetic: Desert gothic, late-night, outlaw
```

### Your Role: The Band Manager

This is the mental model that makes the whole process work. You are not the performer. You are the manager, producer, and creative director. Your job is to:

- **Set the vision.** Define what the project sounds like, looks like, and means.
- **Direct the performances.** Write the prompts, evaluate the outputs, iterate until it is right.
- **Maintain quality control.** Know when a generation is good enough and when it needs another take.
- **Sequence and curate.** Choose the best versions, order the tracks, build the arc.
- **Handle the business.** Distribution, metadata, release strategy.

This framing matters because it preserves your creative authority. The AI is not the artist. You are. The AI is your session musicians, your recording studio, and your production team - all waiting for your direction.

### Creative Collaborative Intelligence

Making an album with AI is an act of collaborative intelligence. It works best when you think about it as a relationship, not a transaction. Three conditions make that relationship productive:

**1. Co-evolution.** You and the AI get better together over time. Your first style prompt will be rough. Your tenth will be precise. Not because you read a manual, but because you learned from what the AI gave you back. Each generation teaches you something about what you actually want. The AI's output shapes your taste, your taste shapes the next prompt, and the work evolves through that loop. This is co-evolution: neither party stays the same through the process. By the end of an album, you will hear differently than you did at the start.

**2. Boundary setting.** The most important skill in human-AI collaboration is knowing what to delegate and what to protect. In album creation, this means being clear about where your creative authority is non-negotiable and where the AI has room to surprise you. Some boundaries are obvious: you write the lyrics, you decide the album sequence, you own the vision. Other boundaries you discover by crossing them. Maybe you let the AI generate a melody that changes the emotional direction of a song, and it works. Maybe it does not and you learn that melody is something you need to control. The boundaries are not fixed. They shift as trust develops. But they must exist, or the work stops being yours.

**3. Complementarity.** The best collaborations happen when each party brings something the other cannot. You bring meaning, narrative, emotional intent, aesthetic judgment, and the ability to say "this is done." The AI brings tireless generation, zero attachment to any particular output, the ability to produce dozens of variations without fatigue, and access to sonic patterns across every genre. Neither of those skill sets is sufficient alone. The album lives in the overlap. When you find yourself fighting the AI (forcing a vocal style it cannot produce, overriding its arrangement instincts on every track), step back and ask whether you are leveraging complementarity or just using the AI as a worse version of a human musician.

These three conditions - co-evolution, boundary setting, complementarity - are not unique to music. They are the conditions for productive human-AI collaboration in any creative domain. An album is just a particularly good place to learn them because the feedback is immediate: you can hear whether it is working.

---

## 5. Phase 4: Music Production with Suno

### How Suno Works

Suno has two input fields that matter.

**Style Prompt** (the "Style of Music" field): Your sonic blueprint. It defines genre, instrumentation, vocal character, tempo feel, and production aesthetic. Think of it as the brief you would give a producer.

**Custom Lyrics** (the lyrics field): Where your lyrics go, along with structural tags in brackets that tell Suno how to arrange the song.

These two inputs are independent. The style prompt sets the sonic world. The lyrics and tags set the structure and performance arc.

### The Style Prompt: Four Components

Every effective style prompt addresses four things. Use 4–7 descriptors total.

#### 1. Genre Stack (2–3 descriptors)

Layer genre descriptors to create a tonal neighborhood rather than a single target. Lead with the dominant genre.

| Intent | Example Stack |
|--------|--------------|
| Outlaw country with atmosphere | `outlaw country, lo-fi, desert gothic` |
| Dark folk with grit | `southern gothic folk, Americana, raw` |
| Moody alt-country | `alt-country, slowcore, dusty` |
| Uptempo honky tonk | `honky-tonk, rockabilly, energetic` |
| Indie bedroom pop | `indie pop, lo-fi, dreamy` |
| Dark electronic | `darkwave, synthpop, atmospheric` |
| Acoustic soul | `neo-soul, acoustic, intimate` |

Suno does not accept artist names. Describe the sound using genre and production language.

#### 2. Instrumentation

Name the instruments you want. If you leave this out, Suno fills with defaults.

Examples:
- `acoustic guitar, upright bass, pedal steel, brushed drums`
- `electric guitar, Hammond organ, sparse drums`
- `fingerpicked acoustic, no drums, cello`
- `synth pads, drum machine, bass guitar, no acoustic instruments`

You can specify exclusions: `no synths, no electronic elements`

#### 3. Vocal Character

The highest-leverage part of the prompt. Specify gender, register, texture, and delivery.

Examples:
- `raspy female alto, understated delivery`
- `breathy female vocal, intimate, low register`
- `strong male baritone, soulful, warm`
- `duet, female lead with male harmony`
- `spoken word intro, female vocal`

For album consistency, reuse the same vocal descriptors across every track.

#### 4. Production and Mood

Describe the feel, the space, the production aesthetic.

Examples:
- `warm analog production, reverb-heavy, late-night`
- `dry, raw, lo-fi recording, garage feel`
- `polished, radio-ready, bright mix`
- `stripped back, minimal, intimate`
- `building energy, cinematic, wide stereo`

#### Complete Style Prompt Examples

```
outlaw country, desert gothic, acoustic guitar, pedal steel,
raspy female alto, warm lo-fi production, late-night
```

```
indie pop, dreamy, synth pads, acoustic guitar, drum machine,
breathy female vocal, intimate delivery, hazy reverb
```

```
neo-soul, acoustic, upright bass, Rhodes piano, brushed drums,
warm male tenor, smooth delivery, late-night, analog warmth
```

### Structural Tags in Lyrics

Tags go inside square brackets on their own line above the section they apply to.

#### Core Tags

```
[Intro]          [Verse 1]        [Verse 2]
[Pre-Chorus]     [Chorus]         [Bridge]
[Outro]          [Instrumental]   [Break]
[Interlude]
```

#### Tags with Performance Cues

```
[Intro: slow, ambient, no vocals]
[Verse 1: stripped back, acoustic only]
[Chorus: full band, building energy]
[Bridge: half-time, reverb-heavy, restrained]
[Outro: fade, minimal instrumentation]
```

#### Vocal Performance Tags

```
[Spoken Word]    [Whispered]      [Humming]
[Ad-lib]         [Harmonies]      [Call and Response]
```

Tags are strong hints, not guarantees. The model generally respects structural labels reliably. Performance cues inside tags are less consistent but still improve output.

**Always tag your lyrics.** Without tags, Suno imposes its own structure, which may not match your vision.

### Song Creation Workflow

**Step 1: Prepare the lyric document.** Format your lyrics with structural tags. Keep lines short.

Example:
```
[Verse 1: stripped back, acoustic guitar]
Dust on the highway, cards on the dash
She drove til the neon gave way to the black
Every mile put a year on the rearview glass

[Pre-Chorus: building, add bass]
And the radio played what the radio plays
But she was done with the sound of staying

[Chorus: full band, anthemic, raspy vocal]
Turn the cards, lay them down
Every queen has left this town
Burn the map, salt the ground
Turn the cards, lay them down
```

**Step 2: Set the style prompt.** Write or paste your style prompt. For the first generation, use the full prompt.

**Step 3: Generate and listen.** Generate 2–4 versions. Listen for:
- Does the vocal character match?
- Does the arrangement follow the structural arc?
- Does the energy build and release where you intended?
- Are there artifacts (garbled words, unexpected instruments, abrupt cuts)?

**Step 4: Iterate.** The first generation is almost never the final version.
- Vary the style prompt slightly (swap one genre descriptor, adjust production aesthetic)
- Adjust structural tags (if the chorus does not lift enough, add performance cues)
- Regenerate sections (use Suno's editor for individual sections)
- Extend or crop (add a bridge, trim a long outro)

Treat each generation as a draft. The negotiation between your intent and what Suno produces is the creative process.

**Step 5: Finalize.** Export the track. On Pro or Premier plans, you have commercial rights. Tracks on the free plan are non-commercial.

### Building Album Cohesion

- **Consistent vocal identity.** Same core vocal descriptors across every track. Vary delivery, keep the fundamental voice consistent.
- **Sonic palette constraints.** Core instruments plus 1–2 guests per song.
- **Style prompt template.** Create a base and vary it per track.

Example base template:
```
outlaw country, [SUBGENRE], [INSTRUMENTATION],
raspy female alto, [DELIVERY], warm lo-fi production, [MOOD]
```

Per track:
- Track 1: `desert gothic` / `acoustic guitar, pedal steel` / `understated` / `late-night`
- Track 2: `honky-tonk` / `electric guitar, piano, full drums` / `defiant` / `energetic, raw`
- Track 3: `slowcore` / `fingerpicked acoustic, cello, no drums` / `breathy, intimate` / `sparse`

### What Suno Cannot Do

Be honest about the boundaries:
- **No note-level control.** You cannot specify melodies or chord progressions.
- **Vocal timbre is approximate.** Consistency improves with consistent prompts but is never guaranteed.
- **Long-form structure is unreliable.** Songs over 3–4 minutes lose coherence. Build in sections.
- **Genre fusion is unpredictable.** More than 3 genre descriptors may cause the model to default to one.
- **Lyrics can be garbled.** Complex multisyllabic words get swallowed. Simplify choruses and hooks.
- **Mixing is basic.** Export stems and finish in a DAW for release quality.

---

## 6. Phase 5: Album Art and Visual Identity

### Tools

| Tool | Best For | Cost |
|------|----------|------|
| **Midjourney** | Highest quality, strong aesthetic control | $10–30/month |
| **DALL-E 3** (via ChatGPT Plus) | Good quality, easy to use | Included with ChatGPT Plus |
| **Leonardo AI** | Free tier available, good for iteration | Free–$12/month |
| **Stable Diffusion** (local) | Maximum control, no ongoing cost | Free (requires GPU) |
| **Canva** | Adding text, layout, final composition | Free–$13/month |

### What You Need

1. **Album cover** - square format, minimum 3000x3000px for streaming platforms
2. **Artist profile image** - for Spotify, Apple Music artist pages
3. **Single covers** (if releasing singles before the album)
4. **Promotional images** - for social media, press

### Prompting for Album Art

Build your visual prompt the same way you build a style prompt:

```
[SUBJECT], [STYLE/MEDIUM], [COLOR PALETTE], [MOOD], [COMPOSITION]
```

Example for Southern Oracle:
```
Three women standing in a desert at twilight, outlaw country aesthetic,
tarot card composition, warm earth tones and deep shadows,
oil painting style, cinematic lighting, album cover format
```

### Tips for Visual Consistency

- **Save your working prompts.** When you find a visual style that works, document the exact prompt.
- **Use consistent style descriptors** across all images (album art, promo, profile).
- **Maintain a color palette.** Pick 3–4 colors and reference them in every prompt.
- **Iterate like you do with music.** Generate 10+ versions. Choose the one that captures the album's emotional territory.
- **Add text in Canva or Photoshop**, not in the AI tool. AI-generated text is unreliable.

### Album Art Specifications

| Platform | Format | Minimum Size |
|----------|--------|-------------|
| Spotify | JPEG or PNG, square | 3000x3000px |
| Apple Music | JPEG or PNG, square | 3000x3000px |
| YouTube Music | JPEG or PNG, square | 2048x2048px |
| DistroKid upload | JPEG or PNG, square | 3000x3000px recommended |

---

## 7. Phase 6: Post-Production

### Do You Need Post-Production?

If you are releasing music for fun, streaming casually, or sharing with friends - Suno's output is fine as-is.

If you want radio-competitive quality, submit to playlists, or take the project seriously - export stems and finish in a DAW.

### DAW Options

| DAW | Cost | Platform | Best For |
|-----|------|----------|----------|
| **GarageBand** | Free | Mac/iOS | Beginners, basic mixing |
| **Reaper** | $60 (personal) | Mac/Win/Linux | Full-featured, affordable |
| **Logic Pro** | $200 (one-time) | Mac | Professional production |
| **Ableton Live** | $99–749 | Mac/Win | Electronic, creative workflows |
| **BandLab** | Free | Web/Mobile | Collaboration, accessibility |

### Basic Post-Production Workflow

1. **Export stems from Suno** (available on higher tiers)
2. **Import into your DAW**
3. **EQ:** Cut muddiness (200–400Hz), add clarity (2–5kHz), add air (10kHz+)
4. **Compression:** Even out dynamics, especially vocals
5. **Reverb/Delay:** Add space and depth
6. **Mastering:** Final loudness and polish (or use an AI mastering service)

### AI Mastering Services

If you do not want to learn mastering:
- **LANDR** - $4–14/track, AI-powered, good enough for streaming
- **eMastered** - $9/month unlimited, simple interface
- **CloudBounce** - Free tier available, AI mastering

### Music Production Learning Resources

**YouTube channels:**
- **In The Mix** - mixing and mastering tutorials for beginners, clear explanations
- **You Suck at Producing** - irreverent but genuinely educational production tutorials
- **Andrew Huang** - creative production techniques, genre experimentation
- **Rick Beato** - music theory, what makes great songs work
- **12tone** - music theory explained visually and accessibly
- **Adam Neely** - music theory, bass, and the intersection of music and culture

---

## 8. Phase 7: Distribution

### Choosing a Distributor

| Distributor | Annual Cost | Per Release | Revenue Share | Best For |
|-------------|-------------|-------------|---------------|----------|
| **DistroKid** | $22.99/year | Unlimited | 0% (you keep 100%) | Most creators |
| **TuneCore** | $0 | $9.99/single, $29.99/album/year | 0% | Established artists |
| **CD Baby** | $0 | $9.95/single, $29.95/album (one-time) | 9% commission | One-time payment preference |
| **Amuse** | Free–$24.99/year | Included | 0% (Pro) | Free tier available |
| **United Masters** | Free–$5.99/month | Included | 10% (free), 0% (paid) | Hip-hop, R&B focus |

**Recommendation:** DistroKid is the best value for most AI album creators. Unlimited uploads for one annual fee means you can release singles, EPs, and full albums without worrying about per-release costs.

### DistroKid Walkthrough

1. **Create an account** at distrokid.com. Choose the Musician plan ($22.99/year).
2. **Upload your album.** Provide: album title, artist name, track files (WAV preferred, MP3 accepted), album art (3000x3000px JPEG/PNG).
3. **Fill in metadata** for each track: title, track number, genre, year, lyrics (optional), ISRC codes (auto-generated if you do not have them).
4. **Select stores.** Choose all platforms or select specific ones (Spotify, Apple Music, Amazon Music, YouTube Music, Tidal, Deezer, etc.).
5. **Set release date.** Allow 2–4 weeks for platform processing. You can set a future date for coordinated release.
6. **Submit.** DistroKid handles delivery to all selected platforms.

### Important: Verify Commercial Rights

Ensure your tracks were generated on a Suno plan that includes commercial licensing (Pro or Premier). This is not retroactive - upgrading later does not convert earlier free-tier tracks to commercial use.

### Metadata Checklist

For each track, prepare:
- [ ] Track title
- [ ] Artist name (consistent across all tracks)
- [ ] Album title
- [ ] Track number
- [ ] Genre (primary and secondary)
- [ ] Release year
- [ ] Songwriter credits
- [ ] Producer credits
- [ ] Lyrics (for Spotify lyrics feature)
- [ ] ISRC code (auto-generated by most distributors)

---

## 9. Phase 8: Release and Promotion

### Pre-Release (2–4 weeks before)

- **Claim your artist profiles** on Spotify for Artists, Apple Music for Artists, Amazon Music for Artists
- **Submit to Spotify editorial playlists** (via Spotify for Artists, at least 7 days before release)
- **Create a pre-save link** (DistroKid provides these)
- **Prepare social media assets** - teaser clips, behind-the-scenes content, album art reveals

### Release Day

- **Verify the album is live** on all platforms
- **Share across social media** with direct links
- **Post the story** - how you made it, what the album means, the creative process
- **Engage with early listeners**

### Post-Release

- **Monitor streaming data** through Spotify for Artists and your distributor dashboard
- **Submit to user-curated playlists** on Spotify (search for playlist submission sites and communities)
- **Create short-form video content** - 15–30 second clips on TikTok, Instagram Reels, YouTube Shorts
- **Write about the process** - blog posts, threads, tutorials (this is how Southern Oracle grew its audience)

---

## 10. Optional: Multi-Agent Band Architecture

This is the advanced section. If you want your AI band members to be more than names on an album - if you want them to have opinions, preferences, and creative input - you can build them as AI agent personas.

### The Concept

Southern Oracle has three band members: Syd, Blair, and Maria. In the next phase of the project, each operates as a distinct AI agent with a defined musical identity, influences, and opinions, collaborating through structured creative sessions.

This is optional. You can make a great album without it. But if you want the creative process to feel genuinely collaborative - if you want to be surprised by what your band members bring to the table - this is how.

### Agent Profile Template

For each band member, define:

```markdown
## [Name]

**Role:** [Lead vocals, guitar, bass, drums, keys, etc.]
**Musical Identity:** [2-3 sentences describing their sound and aesthetic]
**Vocal Character:** [If vocalist - register, texture, delivery]
**Influences:** [Described in production language, not artist names]
**Personality:** [How they approach creative decisions]
**Strengths:** [What they bring to the band]
**Tensions:** [Where they push back or disagree]
**Signature Moves:** [Specific production/arrangement preferences]
```

### Example: Southern Oracle Agent Profiles

**Syd**
- Role: Lead vocals, rhythm guitar
- Musical Identity: The front woman. Raw, direct, emotionally exposed. Prefers stripped-back arrangements where the vocal carries the weight.
- Vocal Character: Raspy alto, understated delivery, occasionally full-throated on climactic moments
- Influences: Desert rock storytelling, confessional folk, outlaw country grit
- Personality: Decisive, impatient with overproduction, trusts her instincts
- Tensions: Resists polish. Wants things to sound like they were recorded in one take.

**Blair**
- Role: Lead guitar, harmony vocals
- Musical Identity: The architect. Thinks in arrangements and sonic textures. More interested in how the pieces fit together than in any single part.
- Influences: Atmospheric pedal steel, ambient country, cinematic soundscapes
- Personality: Methodical, detail-oriented, will argue for a guitar part no one else can hear yet
- Tensions: Wants more layers when Syd wants fewer. The productive friction drives the sound.

**Maria**
- Role: Bass, backing vocals
- Musical Identity: The groove. Holds the rhythm section together. Her taste runs darker and heavier than the others.
- Influences: Deep pocket bass lines, swampy blues, low-end warmth
- Personality: Steady, opinionated about tempo and feel, the one who says "that's too fast"
- Tensions: Pulls toward slower tempos and heavier grooves when the others want to pick up energy.

### Using Agent Personas in Practice

**In an LLM conversation:**
```
You are Syd, the lead vocalist and rhythm guitarist of Southern Oracle.
You are reviewing the lyrics for a new song called "[Title]."
Based on your musical identity and preferences, give your honest creative
feedback. What works? What would you change? How should this song feel?
```

**For creative sessions:**
Run a structured session where you present a song concept and each agent responds in character. Use the disagreements as creative fuel. The best ideas often come from resolving the tension between agent perspectives.

**For style prompt refinement:**
Ask each agent what they want the production to sound like. Synthesize their (conflicting) preferences into a style prompt that captures the band's collective identity.

### Skills and Role Profiles

| Role | Core Skills | AI Tools | Human Judgment Required |
|------|------------|----------|------------------------|
| **Songwriter** | Lyric craft, structure, emotional arc | LLM for brainstorming, rhyme, revision | Vision, meaning, authenticity |
| **Producer** | Style prompting, arrangement direction | Suno for generation, DAW for post | Taste, iteration, quality control |
| **Visual Director** | Aesthetic vision, brand consistency | Midjourney/DALL-E for art generation | Brand coherence, emotional alignment |
| **Band Manager** (you) | Project management, sequencing, release strategy | All of the above | Creative direction, final decisions |
| **A&R** | Song selection, album pacing | LLM for feedback and analysis | Knowing what to cut |

---

## 11. Cost Breakdown

### Minimum Viable Album (Budget Path)

| Item | Cost |
|------|------|
| Suno Pro (1–2 months) | $10–20 |
| DistroKid (annual) | $22.99 |
| Album art (DALL-E via ChatGPT Plus) | $20 (1 month) |
| Post-production (GarageBand) | Free |
| **Total** | **~$53–63** |

### Recommended Setup

| Item | Cost |
|------|------|
| Suno Premier (2 months) | $60 |
| DistroKid (annual) | $22.99 |
| Midjourney (1 month) | $10–30 |
| ChatGPT Plus or Claude Pro (for songwriting) | $20 |
| AI mastering (LANDR, ~10 tracks) | $40–140 |
| **Total** | **~$153–273** |

### Professional Setup

| Item | Cost |
|------|------|
| Suno Premier (3 months) | $90 |
| DistroKid (annual) | $22.99 |
| Midjourney (2 months) | $20–60 |
| Claude Pro (for songwriting and agents) | $20 |
| Logic Pro or Reaper | $60–200 |
| Professional mastering | $200–500 |
| **Total** | **~$413–893** |

For context: recording a 10-track album in a traditional studio costs $5,000–50,000+.

---

## 12. Learning Resources

### Songwriting

| Resource | Type | What You Will Learn |
|----------|------|-------------------|
| Pat Pattison (YouTube/Coursera) | Video lectures | Lyric craft, prosody, object writing |
| Holistic Songwriting (YouTube) | Tutorials | Song structure, melody, harmony |
| *Writing Better Lyrics* by Pat Pattison | Book | The standard reference for lyric writing |
| *Songwriters on Songwriting* by Paul Zollo | Book | How great songwriters think about craft |

### Music Production

| Resource | Type | What You Will Learn |
|----------|------|-------------------|
| In The Mix (YouTube) | Tutorials | Mixing, mastering, EQ, compression basics |
| You Suck at Producing (YouTube) | Tutorials | Production techniques with personality |
| Andrew Huang (YouTube) | Creative tutorials | Experimental production, genre exploration |
| Rick Beato (YouTube) | Analysis | What makes hit songs work, music theory |
| 12tone (YouTube) | Visual essays | Music theory explained accessibly |

### Album Art and Visual Identity

| Resource | Type | What You Will Learn |
|----------|------|-------------------|
| Midjourney documentation | Reference | Prompting techniques, parameters |
| Tokenized (YouTube) | Tutorials | AI art prompting, style consistency |
| Future Tools newsletter | Curation | Latest AI image generation tools and techniques |

### AI Music Specifically

| Resource | Type | What You Will Learn |
|----------|------|-------------------|
| Suno Discord community | Community | Tips, prompt sharing, feedback |
| r/SunoAI (Reddit) | Community | User techniques, examples, troubleshooting |
| This guide | Guide | End-to-end album creation process |

### Distribution and Music Business

| Resource | Type | What You Will Learn |
|----------|------|-------------------|
| DistroKid Knowledge Base | Reference | Distribution mechanics, platform requirements |
| Spotify for Artists resources | Reference | Playlist submission, artist profile optimization |
| Ari's Take (YouTube/blog) | Industry education | Independent music business, distribution comparison |

---

## 13. FAQ

**Do I need to know music theory?**
No. Music theory helps you understand why things sound good, but taste and iteration are more important for this process. You need to know when something sounds right, not why.

**Can I really release AI-generated music on Spotify?**
Yes. Suno Pro and Premier plans include commercial rights. Major distributors accept AI-generated music. Your responsibilities: accurate metadata, original lyrics (if you wrote them), and honest representation.

**How many Suno credits does an album take?**
Budget 50–100 credits per finished song (including iterations and rejected generations). A 10-track album typically takes 500–1,000 credits. The Premier plan (10,000 credits/month) is comfortable for album production.

**Should I tell people the music is AI-generated?**
That is your call. Southern Oracle is transparent about its process. Transparency tends to generate curiosity rather than backlash, especially when you are clearly bringing creative vision and authorship to the project.

**Can I use this process for genres other than country?**
Absolutely. The framework is genre-agnostic. Substitute your genre neighborhood, instrumentation, and vocal character. The process - concept, songwriting, production, art, distribution - is the same regardless of genre.

**What if Suno keeps generating vocals that do not match my vision?**
Iterate on the vocal character descriptors in your style prompt. Small changes matter: "raspy" vs. "gravelly," "understated" vs. "intimate." If one voice is not working, try different register and texture combinations. Generate 4–6 versions and pick the closest match.

**Can I use my own voice?**
Suno does not currently support custom voice models in the standard product. However, you can record vocals separately and layer them over Suno instrumentals using a DAW. Some creators use Suno for backing tracks and instrumentals only.

**How do I handle copyright and ownership?**
On Suno Pro or Premier, you own commercial rights to generated outputs. Your original lyrics are your copyright. Album art generated by AI tools follows each tool's commercial use policy (check Midjourney, DALL-E, etc.). When in doubt, read the terms of service for each tool.

---

## Templates

### [Style Prompt Template](templates/style-prompt-template.md)
### [Lyrics Template](templates/lyrics-template.md)
### [Agent Profile Template](templates/agent-profile-template.md)

---

## About

This guide was created by [Diana Wolfe, PhD](https://dianawolfephd.com), based on the process used to build [Southern Oracle](https://dianawolfephd.com/blog/on-building-southern-oracle) - an AI-generated outlaw country band streaming on [Spotify](https://open.spotify.com/artist/0cxIngq7CGS54iZSfawv9L), Apple Music, and all major platforms.

Diana is an industrial-organizational psychologist and VP/Head of AI Research & Strategy at Kyndryl. She researches how humans and AI systems develop capabilities together. Southern Oracle is her creative laboratory for ideas about authorship, co-evolution, and human-AI collaboration.

A portion of proceeds from Southern Oracle goes to [Girls Start](https://girlstart.org/). Somewhere out there is the girl who is going to build the first AI popstar that changes everything.

---

*Licensed under [MIT](LICENSE). Use it, remix it, make something.*
