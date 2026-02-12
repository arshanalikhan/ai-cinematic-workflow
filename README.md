# The Multiverse: AI-Powered Cinematic Music Video 🪐

**Timeline: 462** - A technical experiment in consistent character generation and narrative storytelling using Generative AI.

[![Watch the Video](youtube)

## 📺 Project Overview
This project explores the capabilities of **Google Veo** and **Gemini** to create a cohesive music video. The core technical challenge was maintaining **character consistency** (clothing texture, facial features) and **lighting continuity** across multiple AI-generated shots while telling a visual story of shifting timelines (Black & White to Color).

## 🛠 Tech Stack
- **Concept & Scripting:** Google Gemini 1.5 Pro
- **Image Generation:** Google Imagen 3 (via Gemini)
- **Video Generation:** Google Veo (Image-to-Video)
- **Post-Production:** DaVinci Resolve 19
- **Typography:** Fusion "Follower" Modifier for dynamic lyric animation

## 📂 Workflow Structure

### 1. Prompt Engineering (`/prompts`)
I used a "Master Prompt" strategy to lock in character details before generating motion.
- **Girl:** Textured blue sweater, fair skin, long hair.
- **Boy:** Black knit sweater, glasses, curly hair, Indian skin tone.
- *See the full prompt log in the [prompts/](./prompts/) folder.*

### 2. Motion Synthesis
Using **Google Veo**, I animated the static master images with specific motion scales:
- **Scale 1 (Low):** For delicate hand movements (to prevent finger warping).
- **Scale 3 (Medium):** For head turns and looking up.

### 3. Post-Production (DaVinci Resolve)
- **Color Grading:** Custom "Teal & Orange" LUT applied to the second half to signify the "Multiverse" shift.
- **Transitions:** "Dip to Color Dissolve" used to bridge the Black & White memory sequence with the Color reality.

![DaVinci Timeline]
*(My post-production workflow showing the lyric layers and color grading nodes)*

---
*Created by [Arshan Ali Khan]*
