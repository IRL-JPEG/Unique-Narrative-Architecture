# 🌙 UNA: Unique Narrative Architecture

> **Built in 12 Days.** A deterministic, high-performance narrative engine designed to solve the "Brand Safety vs. Generative Scale" paradox.

![Status](https://img.shields.io/badge/Status-Hackathon_MVP-success) ![Architecture](https://img.shields.io/badge/Architecture-Hybrid_Event_Driven-blue) ![Cost](https://img.shields.io/badge/Cost-90%25_Reduction-green) ![Safety](https://img.shields.io/badge/Brand-Safe-secure)

## 🚀 The Pitch

We identified a critical blockage in the advertising indsutry when it comes to AI: **Brands want to personalize storytelling with customers, but they are terrified of Generative AI.**

Legal teams kill projects because of hallucination risks, while when you stack up the numbers, many teams will kill projects because LLM inference at scale for campaigns is are too expensive.

**UNA** is the answer. It is not a wrapper for ChatGPT. It is a **System Design solution** to there problems that allow brands to handcraft content with creative teams, but use genertive AI to create safe, trusted variaions in content. 
By decoupling narrative logic from asset generation, we've created an engine that delivers bespoke, 10-minute audiobooks in under 8 seconds—safely, affordably, and knowing we can trust every word.

---

## 🏗 System Architecture: The "Hybrid" Engine

We didn't just ask an LLM to "write a story." We engineered a pipeline that treats narrative as a graph of logic, not a stream of tokens. 
Inspired by branching interactive storytelling, 'choose your own adventure' books, we saw a new way to weave content geneartion with an existing method of content writing. 

### 1. Deterministic Logic Core
At the heart of UNA is a custom-built logic engine. Instead of rolling the dice on every sentence, UNA assembles stories from a graph of pre-approved, high-quality narrative fragments.
*   **The "Director" Concept:** The engine knows exactly what is happening in every scene before it generates a single asset.
*   **Variable Injection:** It surgically inserts user data (names, pronouns, dynamic traits) into the narrative flow without breaking the story structure.

### 2. The "Two-Lane" Processing Model
To ensure a seamless user experience on mobile, we architected a non-blocking event loop:
*   **🏎️ The Fast Lane (Text):** The logic engine resolves the narrative graph instantly, delivering the text and metadata to the user immediately.
*   **🚛 The Heavy Lane (Audio):** In the background, a distributed worker pool handles synthesis and stitching, pushing the final audio assets to the client asynchronously.

### 3. Intelligent Asset Caching (The Cost Killer)
This is where the system design shines. UNA analyzes the generated story and checks a local library for existing assets.
*   **Deduplication:** If 1,000 users generate a story where the cat is "curious," we only pay to synthesize that narrative block *once*.
*   **Smart Stitching:** The system seamlessly blends cached audio with on-demand synthesized audio (for unique names).
*   **Result:** We drop the cost from **~$0.25 per story** (Pure GenAI) to **~$0.02 per story** (UNA Hybrid).

---

## ✍️ The Narrative Pipeline: Human + AI Symbiosis

This wasn't just a coding challenge; it was a workflow challenge. We built this with a two-person core team: a System Architect and a Narrative Designer.

**The Workflow:**
1.  **Human Architecture:** Our Narrative Designer mapped out complex branching plots and emotional arcs.
2.  **AI Expansion:** We utilized **Claude** to flesh out these arcs into thousands of narrative variations, adhering to a strict JSON schema designed to integrate with UNA.
3.  **Human Polish:** We performed manual continuity edits and quality assurance on the "Packs" (the source data).
4.  **System Integration:** The finalized packs were loaded into UNA, creating a "Sandbox" where the AI can play, but cannot break the rules.

*Note: While the system is robust, the speed of the hackathon means there are still minor continuity quirks—but the architecture allows these to be fixed centrally without code changes.*

---

## 🔮 The Future: Multi-Modal Brand Safety

Because UNA is **deterministic** (it knows *what* the story is), it acts as a perfect prompt engineer for other modalities. It solves the "consistency" problem in generative media.

### 🎨 Image Generation (Flux / Stable Diffusion)
Since the engine knows the scene is "A ginger cat knocking over a vase in a cottage," it can programmatically construct the perfect image prompt. We can inject brand-specific LoRAs to ensure the art style remains 100% on-brand, regardless of the user's input.

### 📹 Video Generation (Luma / Runway)
UNA can act as the Director for video models.
*   **First-Frame Control:** Use the generated images as anchors.
*   **Motion Instructions:** The logic engine passes metadata (e.g., `camera_move: pan_right`, `action: jump`) to the video model, ensuring the video matches the audio narration perfectly.

### 📖 Print & Layout
The engine's output is structured data, not just text. We can pipe this directly into layout engines (HTML/CSS to PDF) to create physical, print-on-demand books where the text layout dynamically adjusts to the length of the personalized story.

---

## 🛡️ The Value Proposition

| Feature | Pure GenAI Approach | The UNA Approach |
| :--- | :--- | :--- |
| **Safety** | High Risk (Hallucinations, IP infringement) | **100% Brand Safe** (Pre-approved logic) |
| **Cost** | High ($$$ Inference per user) | **Low** ($ Caching + Logic) |
| **Quality** | Variable (Tone drift) | **Consistent** (Human-curated arcs) |
| **Speed** | Slow (Streaming tokens) | **Instant** (Logic resolution) |

---

## 🏆 The 12-Day Sprint

We went from a concept to a deployed, scalable API in less than two weeks.

*   **Days 1-5:** Architecture design, Logic Engine coding, and Narrative structuring.
*   **Days 6-9:** Parallel workflows: Narrative Designer generating/polishing content via Claude; Developer building the Audio Stitching and Caching layers.
*   **Days 10-12:** Integration, Load Testing, and Mobile App connection.

UNA is proof that you don't need a massive team or a billion-dollar model to build world-class generative experiences. You just need **better system design.**

---

*Built by JPEG, DMT and Love for lewis Carroll*
