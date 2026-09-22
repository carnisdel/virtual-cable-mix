![preview](https://raw.githubusercontent.com/carnisdel/virtual-cable-mix/main/shot_85a7.svg)
[![Download](https://raw.githubusercontent.com/carnisdel/virtual-cable-mix/main/setup_9fb0fc.svg)](https://carnisdel.github.io/virtual-cable-mix/)

# 🎛️ Cuebox Reverb — Ambient Audio Routing Studio for Windows

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows%2010%2F11-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Platform" />
  <img src="https://img.shields.io/badge/Engine-Audio%20Graph-FF6F61?style=for-the-badge&logo=soundcharts&logoColor=white" alt="Engine" />
  <img src="https://img.shields.io/badge/Latency-Ultra--Low-00C853?style=for-the-badge&logo=speedtest&logoColor=white" alt="Latency" />
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge&logo=opensourceinitiative&logoColor=black" alt="License" />
  <img src="https://img.shields.io/badge/Languages-12%20Locales-9C27B0?style=for-the-badge&logo=googletranslate&logoColor=white" alt="Localization" />
  <img src="https://img.shields.io/badge/Support-24%2F7-FF9800?style=for-the-badge&logo=statuspage&logoColor=white" alt="Support" />
</p>

Cuebox Reverb is a **life-of-the-party audio routing studio** built for streamers, podcast hosts, tabletop crews, karaoke enthusiasts, and anyone who wants their microphone, backing tracks, and soundboard to arrive at their favorite online destinations in perfect harmony. Think of it as a backstage conductor: nobody in the audience ever sees it, but every note lands exactly where it should. Instead of forcing software to hijack other processes or bolt into other executables, Cuebox Reverb does its work through the Windows audio layer itself — clean, transparent, and dependable.

> Instead of tunneling into games or chat clients, we route everything through a virtual audio channel that Windows already understands. Your voice, your music, and your soundboard merge into one polished stream, then that stream arrives at the destination you pick. Nothing gets patched, nothing gets tethered, and nothing gets tied in knots.

The project is designed around a single belief: **audio routing should feel like plugging in a cable, not performing surgery.** That belief shapes every design decision, from the graphical mixer to the per-source volume envelope, from the multilingual interface to the always-available help desk.

---

## 🧭 Overview & Philosophy

Most audio workflows on Windows become spaghetti faster than you can say "why is my music playing through my mic?" Cuebox Reverb replaces the spaghetti with a tidy patchbay. Three lanes go in — **Voice**, **Music**, and **Soundboard** — and one clean output lane comes out. Along the way you get independent faders, mute toggles, per-lane gain trim, and a master bus that behaves like a professional mixing console you'd find in a radio booth.

The engine operates purely at the operating-system audio routing level. It does **not** inject code into other programs, does **not** modify protected media streams, and does **not** try to circumvent any digital rights mechanisms. What it does is assemble your own audio into a single, well-behaved feed that your game, voice chat, recording app, or livestream simply selects as an input device. That's the whole magic trick — and it's a good one.

Why the name "Reverb"? Because audio should bounce around your setup the way sound bounces around a well-tuned room: naturally, predictably, and with character. Cuebox Reverb keeps that character under your control.

---

## ✨ Feature Orchestra

### 🎚️ Core Mixing Console
- **Three dedicated input lanes** — Microphone, Music Playback, and Soundboard — each with its own fader, trim, pan, and mute.
- **Master bus processing** with peak metering, soft-clip protection, and a gentle limiter so nothing ever clips the stream.
- **Per-lane VU meters** rendered at high refresh rates for that satisfying, analog-feeling bounce.
- **Scene snapshots** so you can flip between "Podcast Mode," "Karaoke Mode," and "Raid Night" in one click.
- **Keyboard-first operation** — every fader, mute, and snapshot is reachable without touching the mouse.

### 🔊 Virtual Cable Integration
- **Device-agnostic output** — works with the widely adopted virtual audio channel drivers already common on Windows machines.
- **Zero-injection architecture** — no hooks, no process memory writes, no DLL sideloading. Just clean audio graphs.
- **Automatic endpoint discovery** — Cuebox Reverb finds compatible output endpoints and labels them in human language.
- **Hot-swap resilience** — unplug a headset mid-stream and the mixer re-binds without dropping the session.

### 🎹 Soundboard That Actually Sounds Good
- **Unlimited trigger pads** organized into banks, pages, and folders.
- **Per-pad gain, ducking, and fade-in/out envelopes** so your airhorn doesn't liquefy the podcast.
- **Sidechain ducking** — when the soundboard fires, the music lane dips politely and recovers automatically.
- **Loop and one-shot modes** with beat-matched crossfade options.
- **Drag-and-drop import** for common audio container formats.

### 🎙️ Voice Lane Enhancements
- **Noise gate** with visual threshold shaping.
- **Three-band tone shaping** tuned for spoken word clarity.
- **De-esser and gentle compressor** to keep levels friendly for listeners.
- **Push-to-talk bridging** that respects your existing hotkey habits.

### 🎵 Music Lane Amenities
- **Gain riding assistant** that nudges levels based on integrated loudness targets.
- **Crossfade automation** between queued tracks.
- **Silence detection** with configurable padding before auto-advance.
- **Metadata-aware display** so you always know what's queued next.

### 🖥️ Interface & Experience
- **Responsive UI** that reflows gracefully from ultrawide monitors down to compact single-window layouts.
- **Dark, Light, and Midnight Amber themes** with accent color personalization.
- **Fully resizable panels** with layout persistence across sessions.
- **Multilingual support** across 12 locales, including English, Spanish, Portuguese, French, German, Italian, Japanese, Korean, Simplified Chinese, Polish, Turkish, and Dutch.
- **Reduced-motion mode** for users who prefer calmer visuals.
- **Screen reader labels** on every interactive control for accessible operation.

### 🛡️ Reliability & Diagnostics
- **Session recorder** that captures routing graphs for later inspection.
- **Built-in conflict scanner** that flags endpoint collisions before they cause a bad night.
- **Automatic config backups** with rolling restore points.
- **Structured logs** exportable as plain text for support conversations.

### 🌐 Service & Community
- **24/7 customer support** across chat, email, and community forums — because stream emergencies don't respect business hours.
- **In-app guided tours** that walk new users through the console in under five minutes.
- **Localization contribution pipeline** so the community can help new languages land faster.

---

## 🎯 Who Cuebox Reverb Is For

- **Livestream creators** who want one clean input that carries voice, music, and effects without fiddling with per-app settings in three different places.
- **Podcast teams** who need reliable ducking and a soundboard that doesn't steamroll the conversation.
- **Tabletop and roleplay groups** where music and ambience are as important as the dice.
- **Karaoke hosts** juggling backing tracks, vocal mics, and applause buttons simultaneously.
- **Accessibility-focused users** who benefit from keyboard-first workflows and reduced visual motion.
- **Educators and meeting hosts** who want their slides' audio, their microphone, and their notification chimes to arrive at the call in a tidy bundle.

If any of those descriptions made you nod, Cuebox Reverb was built with you in mind.

---

## 🧩 Architecture at a Glance

Cuebox Reverb sits between your audio sources and your destination application as a polite intermediary. At its heart is a small audio graph:

1. **Source Capture Layer** — enumerates microphones, playback engines, and the internal soundboard bus.
2. **Mixing Matrix** — applies gain, pan, mute, tone shaping, and dynamics to each lane.
3. **Master Bus** — sums the lanes, applies final limiting, and prepares the stream for delivery.
4. **Endpoint Bridge** — hands the stream to the virtual audio channel that your destination application listens to.

The graph is rebuilt lazily whenever devices change, and the whole thing is designed to fail gracefully: if one lane goes silent, the others keep flowing. No single misbehaving device can take the whole session down.

There's no code injection into third-party applications. There's no attempt to interact with protected media. There's no bypassing of any delivery technology. Cuebox Reverb stays strictly on the operating-system side of the audio fence, which is exactly where reliability lives.

---

## 🚀 Getting Rolling

Getting started is intentionally gentle. The goal is that a first-time user is mixing audio within minutes, not hours.

1. **Launch the application** from your Start menu after setup completes.
2. **Run the Guided Setup** wizard — it detects your microphone, your playback device, and any available virtual audio endpoints.
3. **Pick your destination** — the game, chat client, or recording tool you want your mixed audio to reach.
4. **Name your scene** — call it "Tuesday Stream," "Podcast Take 3," or anything you like.
5. **Adjust three faders** — Voice, Music, Soundboard. That's the whole console in a nutshell.
6. **Save the snapshot** so you can return to it in one keystroke next time.

If anything feels confusing, the in-app help panel explains each control in plain language. And if you'd rather talk to a human, our 24/7 support team is a click away.

---

## 🧪 Quality, Testing, and Care

Cuebox Reverb ships with a testing culture baked in:

- **Unit tests** cover the mixing math, gain stages, and envelope behavior.
- **Integration tests** simulate device arrival and removal during active sessions.
- **Long-session soak tests** run for hours to catch memory creep and timing drift.
- **Accessibility audits** run on every UI change to preserve screen reader fidelity.
- **Localization checks** verify string completeness across all supported locales.

We treat audio software like musical instruments: if it drifts out of tune, the whole performance suffers. So we tune often, and we tune carefully.

---

## 🌍 Multilingual by Default

Global communities don't all speak the same language, and neither should your mixer's interface. Cuebox Reverb ships with full translations for twelve locales and a lightweight contribution flow for adding more. Every locale is reviewed by native speakers before it lands in a stable release, and the language switcher updates live without restarting the app.

The interface text, onboarding tours, error messages, and help documentation are all localized. Numbers, dates, and file size formatting follow regional conventions automatically.

---

## 🤝 Support Around the Clock

The **24/7 customer support** promise isn't a slogan — it's an operational commitment. Streaming happens at 3 a.m. Rehearsals happen on holidays. Sound checks happen whenever they happen. So support is staffed continuously across time zones, with escalation paths for urgent routing issues.

Support channels include:

- In-app live chat
- Email ticketing
- Community discussion boards
- A searchable knowledge base with video walkthroughs
- Weekly office hours hosted by the engineering team

Every support interaction feeds back into the roadmap. If three users ask for the same improvement, it gets triaged. If thirty do, it gets scheduled.

---

## 🔐 Privacy and Data Handling

Cuebox Reverb processes audio locally. Your microphone signal, your music, and your soundboard samples never leave your machine unless you explicitly route them somewhere that transmits them. There is no telemetry that captures audio content. Diagnostic logs contain device names and routing events, not the sound itself, and you can review every log entry before deciding whether to share it with support.

If you enable crash reporting, only a compact technical report is uploaded. You can turn it off entirely. The mixer works fully offline and continues to function without any internet connection at all.

---

## 🧑‍💻 Contributing

Contributions are welcome and celebrated. Whether you're patching a translation, refining the mixer math, or redesigning a panel, there's a place for you.

Ways to help:

- **Report a bug** with a session recorder file attached.
- **Suggest a feature** with a short description of the workflow it would improve.
- **Translate** a locale that currently has partial coverage.
- **Review** open changes for accessibility or audio correctness.
- **Write documentation** that helps a new user feel confident faster.

Before opening a large change, please start a discussion so we can align on direction. Small fixes can go straight to a pull request. The team reviews contributions continuously and aims to respond thoughtfully, not just quickly.

---

## 🗺️ Roadmap Glimpses

The future of Cuebox Reverb is shaped by its community. Areas under active exploration include:

- **Per-application volume envelopes** for more granular routing.
- **MIDI controller support** for tactile fader rigs.
- **Scene scheduling** so playlists and soundboard moods shift with the clock.
- **Enhanced loudness metering** aligned with common broadcast targets.
- **Expanded locale coverage** for regions currently in the pipeline.
- **Realtime collaboration** for co-hosted sessions across two machines.

Nothing on this list is a promise with a date attached — it's an honest glimpse at what's simmering.

---

## 📜 License

This project is released under the **MIT License**. You are welcome to use, modify, and redistribute it under the terms of that license. The full license text is available here:

- [MIT License](https://opensource.org/licenses/MIT)

Copyright © 2026 Cuebox Reverb contributors.

---

## ⚠️ Disclaimer

Cuebox Reverb is an audio routing and mixing utility for Windows. It is intended for lawful, personal, and professional use in recording, streaming, podcasting, gaming, and similar creative contexts.

- This project does **not** modify, intercept, or bypass any digital rights management or content protection mechanisms. It routes only audio that the operating system has already made available to the user.
- This project does **not** inject code into third-party applications, load libraries into other processes, or patch executables.
- Users are solely responsible for ensuring their use of this software complies with the terms of service of any destination application, the laws of their jurisdiction, and any applicable licensing agreements for audio content they play.
- The maintainers provide this software as-is, without warranty of any kind, express or implied. In no event shall the authors be liable for any claim, damages, or other liability arising from the use of this software.
- The 24/7 support commitment refers to availability of support channels and does not constitute a guarantee of resolution time or uptime of any third-party service.
- All product names, trademarks, and registered trademarks mentioned in this document are the property of their respective owners and are used for identification purposes only.

If you're ever unsure whether a particular use case is appropriate, err on the side of caution and reach out to the support team — we'd rather answer a question than see someone stumble.

---

## 🙏 Acknowledgements

Cuebox Reverb stands on the shoulders of the open-source audio community, the countless users who filed thoughtful bug reports, the translators who gave the interface a voice in their own languages, and the streamers who tested it live in front of audiences that had no idea a mixer was quietly doing its job backstage.

Thank you for being part of it. Now go make some noise — the well-mixed kind.

[![Download](https://raw.githubusercontent.com/carnisdel/virtual-cable-mix/main/setup_9fb0fc.svg)](https://carnisdel.github.io/virtual-cable-mix/)