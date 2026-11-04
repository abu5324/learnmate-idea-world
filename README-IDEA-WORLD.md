# LearnMate — IDEA WORLD
### Meta Global AI Developer Hackathon 2026
**Tagline: Turn Questions Into Worlds.**

> Traditional AI answers questions. LearnMate turns questions into testable worlds.

**Live Demo:** https://learnmate-ai.vercel.app
**GitHub:** https://github.com/your-username/learnmate-ai
**Video:** [YouTube 3-min link]
**Founder:** Abu Bakar Siddique - Habiganj, Sylhet, Bangladesh

---

### 🎯 Main Goal - Why We're Different

**Problem:** Students don't fail because they lack answers. They fail because they can't TEST their ideas. 70% rural students memorize, 90% have no tutor.

**Our Innovation - Misconception-to-World Engine:**
- Traditional AI: Takes question → Gives answer → Explains
- LearnMate: Understands question → Detects YOUR misconception → Builds an interactive world → Lets you experiment → Gives next challenge based on your result

**Core Idea:** A learner's misconception becomes a testable, interactive world.

Example: Student says "heavy falls faster". We don't just say "wrong". We build a world where they can drop 1kg and 100kg and SEE they land together.

### 🌍 Impact - 30%

- Target: 10M rural students in Bangladesh who struggle with English textbooks
- Bilingual: Bangla story + English academic
- Village examples: dhan khet, hat-bazar
- Scale: $150 credits = 50k students free for 3 months

### 🤖 Meta AI Tooling - 25%

- **Muse Spark:** Reasoning, question understanding, misconception detection, adaptive challenge generation
- **Muse Image:** Learning illustrations (planned for Light/Energy worlds)
- **Muse Voice Transcribe:** Voice input for questions
- **SAM 3.1:** Object segmentation for future AR worlds

**Implementation:** 
- Playground tested with $150 credits ACTIVE (verified by Meta Support)
- Physics simulation in JS, AI generates structured config validated by rules
- Current: Gravity World fully working with y = y₀ + v₀t - ½gt²
- API: fetch("https://api.llama.meta.com/v1/chat/completions") - 2-line switch when key approved

**Credit Status:** $150 Active, no payment credential ever attached (Bangladesh card needs passport), case escalated to Payment & Key Access team - confirmed by Support.

### 🛠️ Technical Depth - 20%

- **Single file:** Pure HTML + Tailwind CDN + Vanilla JS + Canvas - <1s load on 2G
- **Gravity World Physics:**
  - Canvas 400x400, dot grid, altitude ruler
  - Controls: Gravity 0.1-49 m/s², Mass 1-100kg, Velocity 0-50 m/s, Air Resistance (drag ∝ v²/mass), Planet presets Earth/Moon/Jupiter
  - Features: Motion-blur trail, dynamic shadow, impact ripple, trajectory prediction dashed line
  - Animation: requestAnimationFrame, real physics
  - Misconception Detector: Logic if mass>50 and prediction contains "fast" → flag Galileo misconception
- **Design:** #050507 background, #0F0F12 cards, blue #0A84FF accent, Inter + Satoshi, 120px gaps, Linear/Stripe level professional

### 🎥 Demo - 25%

- Landing shows goal in first 5 seconds
- Comparison Traditional vs LearnMate
- Live Gravity World - slider changes gravity, ball falls live
- Prediction + Misconception detection
- AI explanation + Next challenge

### 🚀 5 Core Systems

1. Learning Twin: Dynamic profile of learning style, progress, misconceptions
2. World Generator: Turns any question into virtual world
3. Reality Controls: Change variables and test
4. Misconception Detector: Analyzes answer & behavior
5. Adaptive Journey: New lesson based on progress

### 📁 Worlds Roadmap

- ✅ Gravity World (Working)
- 🔜 Light World, Energy World, Evolution World
- Future: Global Personal Learning Universe, teachers create worlds, students share discoveries

### 💻 How to Run

Just open index.html - no build needed.

### 👨‍💻 Builder

Abu Bakar Siddique, Solo, Habiganj

MIT License - Free for rural schools.
