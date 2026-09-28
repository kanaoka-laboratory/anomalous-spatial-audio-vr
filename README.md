# "Was That Real?" Understanding How Users Interpret Anomalous Spatial Audio in Virtual Reality

## Repository Overview

This repository provides the supplementary materials for the following paper:

- **"Was That Real?" Understanding How Users Interpret Anomalous Spatial Audio in Virtual Reality**
  Authors: Kousei Otsuka, Shodai Kurasaki, Mayu Fujita, Akira Kanaoka (Toho University)
  In *IEEE International Conference on Metaverse Computing, Networking and Applications (MetaCom 2026)*, 2026.
  <!-- TODO: add DOI / official proceedings link once available -->

The study investigates how users in Virtual Reality (VR) recognize, attribute, and experience anomalous spatial audio, and whether they interpret it as an attack. To support transparency and reproducibility, this repository releases the auditory stimuli, the VR task demo, the questionnaire and interview materials, the interview codebook, and the head-orientation telemetry results used in the user study.

> **Note on language.** The user study was conducted in Japanese. The questionnaire and the interview guide were originally written in Japanese (the files suffixed `_ja`), and the English versions (suffixed `_en`) are machine translations produced with DeepL. In case of any discrepancy, the Japanese versions are authoritative.

---

## Contents

```
.
├── stimuli/                                        # Auditory stimuli used in the study
│   └── HV_human-voice.WAV                          #   HV: Human Voice (recorded by the authors)
│                                                   #   PV, GB, BC, DC: links only (see below)
│
├── questionnaire/                                  # Post-study questionnaire
│   ├── questionnaire_ja.pdf                        #   Japanese (original, authors' language)
│   └── questionnaire_en.pdf                        #   English (translation)
│
├── interview/                                      # Semi-structured interview guide
│   ├── interview-guide_ja.pdf                      #   Japanese (original, authors' language)
│   └── interview-guide_en.pdf                      #   English (translation)
│
├── blockvrise-task-demo.mp4                        # Demo gameplay video of the VR task (BlockVRise)
├── codebook.md                                     # Codebook for the semi-structured interviews (19 codes)
├── head-yaw-telemetry.xlsx                         # Head-orientation telemetry: peak yaw deviation per presentation
└── README.md
```

### Notes on each item

- **stimuli/** — The five auditory stimuli presented during the task (PV, GB, HV, BC are independent of the game context; DC is a legitimate in-game sound presented at an inconsistent timing). Only **HV**, which we recorded ourselves, is included as an audio file. The other four are free-to-use sounds obtained from external sites; to respect their redistribution terms, we do **not** redistribute them here and instead list their sources below so that users can obtain them directly. Please follow the terms of use of each source site.
  - **PV — Phone Vibration** / 携帯電話　バイブレーション01: https://otologic.jp/free/se/cell_phone02.html
  - **GB — Glass Breaking** / グラスが砕ける (glass_break): https://taira-komori.jpn.org/daily01.html
  - **HV — Human Voice** / 人の声（「お疲れ様です」）: included in this repository (`stimuli/HV_human-voice.WAV`), recorded by the authors.
  - **BC — Baby Crying** / 赤ちゃん　泣き声　2: https://vsq.co.jp/plus/sound/category_sub/baby/
  - **DC — Dependent Context** / 決定音「エコー」: https://musmus.main.jp/se.html
- **questionnaire/** — The post-study questionnaire (prior VR/Tetris experience, System Usability Scale, and social acceptability), in Japanese and English.
- **interview/** — The semi-structured interview guide used after the task, in Japanese and English.
- **blockvrise-task-demo.mp4** — A demo playthrough of *BlockVRise*, the Tetris-like VR task developed for the study.
- **codebook.md** — The codebook (19 codes) used to analyze the semi-structured interviews, with definitions and example quotes.
- **AllParticipants_PeakYaw_ByStimulus_ByReport.xlsx** — Per-presentation head-orientation telemetry (peak yaw deviation toward the sound direction). The first sheet (`README`) documents the measurement method and every column.

---

## Usage

These materials may be used, for example, to:

- inform the design of user studies on VR/AR security;
- compare with other perceptual-manipulation or cognitive-attack studies;
- reproduce or extend the experimental setup used in this study.

---

## Citation

If you use these materials, please cite the paper:

```bibtex
@inproceedings{otsuka2026wasthatreal,
  title     = {``Was That Real?'' Understanding How Users Interpret Anomalous Spatial Audio in Virtual Reality},
  author    = {Kousei Otsuka, Shodai Kurasaki, Mayu Fujita, Akira Kanaoka},
  booktitle = {IEEE International Conference on Metaverse Computing, Networking and Applications (MetaCom)},
  year      = {2026}
}
```

<!-- TODO: if this repository is archived on Zenodo, add the dataset DOI and its citation here as well. -->

---

## License

<!-- TODO: confirm the license. CC BY 4.0 is recommended for the research data
     (questionnaire, interview guide, codebook, telemetry, and the HV recording). -->
The research materials in this repository (questionnaire, interview guide, codebook, telemetry results, and the HV audio recording) are released under CC BY 4.0, unless otherwise noted. The other four stimuli (PV, GB, BC, DC) are not redistributed here; each is governed by the terms of use of its original source, listed above.

---

## Contact

- Kousei Otsuka (Toho University): 7526001o@st.toho-u.ac.jp<!-- TODO: update to a currently valid e-mail address -->
- Akira Kanaoka (Toho University): akira.kanaoka@is.sci.toho-u.ac.jp