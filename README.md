# Wakhi Keyboard — Latin Script (X̌ik-wor)

> An open-source Android keyboard built to preserve and digitize the Wakhi language.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Platform: Android](https://img.shields.io/badge/Platform-Android-green.svg)](https://www.android.com/)
[![Status: Active](https://img.shields.io/badge/Status-Active-brightgreen.svg)]()
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-orange.svg)](CONTRIBUTING.md)

---

## About the Language

**Wakhi** (X̌ik-wor / Вахи) is a critically endangered Eastern Iranian language spoken by an estimated **50,000–85,000 people** across the high-altitude mountain regions of:

| Country | Region |
|---|---|
| Pakistan | Gilgit-Baltistan (Hunza, Ishkoman, Yarkhun) |
| Afghanistan | Wakhan Corridor |
| Tajikistan | Gorno-Badakhshan |
| China | Xinjiang (Taxkorgan) |

Despite its rich oral tradition and a dedicated global diaspora, Wakhi has had no standardized digital input method — until now.

---

## About This Project

This keyboard brings the **full 43-character Latin/romanized Wakhi script** to Android, enabling native typing across all standard apps including WhatsApp, SMS, email, and social media.

### Why Latin Script?

The Latin-based romanization of Wakhi represents **150+ years of academic consensus**:

- **Robert Shaw (1876)** — first systematic documentation of Wakhi using Latin characters
- **Georg Morgenstierne (1938)** — foundational comparative Iranian linguistics work
- **John Payne (1989)** — detailed phonological analysis in Latin script
- **Lennart Lorimer** — extensive Wakhi lexicographic work
- **Max Planck Institute for Evolutionary Anthropology (2019)** — adopted Latin romanization in the most recent cross-regional Wakhi linguistic studies

The Latin script is the **only writing system** that:
- Works consistently across all four countries where Wakhi is spoken
- Is actively used by the global Wakhi diaspora online
- Has been validated by the international linguistics community
- Supports the full phonological inventory of the language

---

## Features

- **Full 43-character Wakhi Latin script** — every phoneme covered
- **Special characters included:**

  | Character | IPA Equivalent | Description |
  |---|---|---|
  | `ə` | /ə/ | Schwa vowel |
  | `ɣ` | /ɣ/ | Voiced velar fricative |
  | `š` | /ʃ/ | Voiceless postalveolar fricative |
  | `č` | /tʃ/ | Voiceless postalveolar affricate |
  | `x̌` | /χ/ | Voiceless uvular fricative |
  | `ð` | /ð/ | Voiced dental fricative |
  | `θ` | /θ/ | Voiceless dental fricative |
  | `ʉ` | /ʉ/ | Close central rounded vowel |
  | `ǰ` | /dʒ/ | Voiced postalveolar affricate |
  | `ḍ` | /ɖ/ | Retroflex voiced stop |
  | `ṭ` | /ʈ/ | Retroflex voiceless stop |
  | `ʣ` | /dz/ | Voiced alveolar affricate |
  | `ʦ` | /ts/ | Voiceless alveolar affricate |
  | `ы` | /ɨ/ | Close central unrounded vowel |

- **Native Android IME** — works system-wide in all apps
- **Optimized key layout** — designed for Wakhi phonological patterns
- **No internet required** — fully offline
- **No data collection** — zero telemetry or tracking
- **Free and open source** — forever

---

## Installation

### Option 1: Install from Release (Recommended)

1. Download the latest `.apk` from the [Releases](../../releases) page
2. On your Android device, enable **Install from unknown sources** in Settings
3. Open the downloaded `.apk` and install
4. Go to **Settings → General Management → Keyboard → On-screen keyboard**
5. Enable **Wakhi Latin Keyboard**
6. Set it as your default keyboard

### Option 2: Build from Source

```bash
git clone https://github.com/zedaan/WAKHI-LANGUAGE-KEYBOARD-Latin.git
cd WAKHI-LANGUAGE-KEYBOARD-Latin
./gradlew assembleDebug
```

Requirements: Android Studio, JDK 11+, Android SDK 21+

---

## Project Status

This project is under active development. Built on weekends by a volunteer developer — progress may be gradual but the commitment is long-term.

**Roadmap:**
- [x] Latin script character set definition
- [ ] Core IME implementation
- [ ] Key layout design and optimization
- [ ] Long-press special character access
- [ ] APK release (v1.0)
- [ ] Google Play Store submission
- [ ] Community testing with native speakers
- [ ] Autocorrect / word suggestions (future)

---

## Contributing

This is a **community project** — no ads, no monetization, just language preservation.

All contributions are welcome:

- **Native Wakhi speakers** — feedback on key layout, missing characters, or usability
- **Android developers** — code contributions, bug fixes, performance improvements
- **Linguists** — corrections to the character set or transliteration conventions
- **Designers** — keyboard layout UI/UX improvements
- **Translators** — help translating the app interface into Wakhi, Urdu, Dari, or Chinese

### How to Contribute

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m 'Add: description of change'`
4. Push to your branch: `git push origin feature/your-feature-name`
5. Open a Pull Request

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting.

---

## Linguistic References

- Shaw, R. B. (1876). *On the Ghalchah Languages (Wakhi and Sarikoli)*. Journal of the Asiatic Society of Bengal.
- Morgenstierne, G. (1938). *Indo-Iranian Frontier Languages, Vol. II*. Oslo.
- Lorimer, D. L. R. (1958). *The Wakhi Language*. School of Oriental and African Studies, University of London.
- Payne, J. (1989). *Pamir Languages*. In R. Schmitt (ed.), Compendium Linguarum Iranicarum. Wiesbaden: Reichert.
- Edelman, D. I. (1980). *The Pamir Languages*. Moscow: Nauka.

---

## License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

You are free to use, modify, and distribute this software, provided attribution is maintained.

---

## Acknowledgements

This project is dedicated to the Wakhi-speaking communities of Pakistan, Afghanistan, Tajikistan, and China — and to everyone working to ensure that no language is lost to the digital divide.

Special thanks to the linguists and researchers whose decades of fieldwork made the standardization of the Wakhi Latin script possible.

---

*"A language is not just words. It is a culture, a tradition, a unification of a community, a whole history that creates what a community is." — Noam Chomsky*
