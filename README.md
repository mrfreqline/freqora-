# Freora AI Studio — Master Project Guide & Reference Hub

**Product:** Freora (Freora AI Studio)  
**Publisher / Brand:** MRFREQLINE  
**Author:** Nabin  
**Windows Installer:** `Freora-Setup.exe`  
**Brand Identity:** Professional Monochrome (Strict Neutral Grayscale, Zero Prohibited Accents)  
**Palette:** Dark Theme (`#111111` App, `#151515` Workspace, `#101010` Sidebar, `#303030` Borders, `#F5F5F5` Text)

---

## Brand Identity & Official Logos

The official branding assets are stored in `C:\freora-ai\assets\`:

* **App Icon / Symbol (`assets/logo_icon.png`):** The stylized 'F' incorporating an audio waveform frequency on the vertical stem, horizontal editing timeline/filmstrip ruler marks, and a centered playback playhead.
* **Full Brand Lockup (`assets/logo_full.png`):** The complete emblem centered above the bold wordmark **FREORA** and subtitle **AI STUDIO** on a matte dark canvas.

---

## Master File Directory in `C:\freora-ai`

| File Name | Purpose |
| :--- | :--- |
| **`brand.config.json`** | **Master Brand Configuration:** Product name, publisher info, installer executable name, color codes, and paths to `logo_icon.png` and `logo_full.png`. |
| **`UI_UX_DESIGN_SPEC.md`** | **Master UI/UX & Product Design Prompt:** The definitive design system specification detailing the strict professional monochrome palette, desktop-first Windows shell, dual-mode timeline, workspaces, and accessibility standards. |
| **`ARCHITECTURE_MVP.md`** | **System Architecture & MVP:** The dual-mode hybrid video editor (Manual Timeline + AI Assistant), Guest-First zero-registration flow, and the 7.4B Token Tauri Sidecar architecture. |
| **`AUTONOMOUS_VIDEO_ENGINEERING_REMOTION.md`** | **Remotion & Autonomous Pipeline:** Complete technical analysis of video-as-code, Claude Code agent skills, EBU R128 loudness normalization, Auto-Editor silence cutting, and Faster-Whisper. |
| **`MASTER_AI_CATALOG.md`** | **Exhaustive AI & Tool Catalog:** 100+ tools and repositories indexed (FreeLLMAPI, LiteLLM, Wan 2.2, Kokoro-82M, YuE, Demucs, FFmpeg, faster-whisper, DeepFilterNet, etc.). |
| **`HARDWARE_OPTIMIZATION.md`** | **Hardware Calibration for Lenovo LOQ:** Exact memory allocation matrix, Q4 GGUF/INT8 quantization rules, and model limits tailored specifically for your **NVIDIA RTX 4060 Laptop GPU (8GB VRAM) and 16GB RAM**. |

---

## Summary of Core Principles for Future Development

1. **Strict Professional Monochrome Design:** Zero decorative purples, glowing cyans, or landing-page gradients. Grayscale surface elevation hierarchy designed for long, fatigue-free creative sessions.
2. **Configurable Brand:** Freora is 100% brand-agnostic; changing colors, titles, logos, or publisher details requires only editing `brand.config.json`.
3. **Dual-Mode Video Editing:** Users can edit manually with multi-track drag-and-drop or prompt the AI editor with plain text. All AI edits are non-destructive and feature full Undo/Redo (`Ctrl+Z` / `Ctrl+Y`).
4. **The 7.4 Billion Token Pool:** Bundles `FreeLLMAPI` as a hidden local sidecar binary (`localhost:8000`) with AES-256 encrypted local key storage, auto-cascading across 34 free cloud providers, and seamless offline failover to local Ollama.
5. **Multi-Language Nepali/Indic Studio:** Native Devanagari, Nepglish (Romanized), Hindi, and English transcription with 200+ fonts and frame-perfect karaoke tracking.
6. **Lightweight Core Installer:** Keep `Freora-Setup.exe` under 50 MB; stream heavy AI models on demand through the Plugin Manager.
