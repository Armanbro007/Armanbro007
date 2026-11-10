<img src="assets/header.svg" alt="Arman Rahman: I turn AI ideas into tools people actually use." width="100%">

### In 20 seconds

| | |
| --- | --- |
| **What I do** | Build practical AI and web tools, from a research model to an app people can use |
| **Built so far** | An AI-generated face detector, a handwritten prescription reader, and a World Cup calendar app |
| **Education** | BSc in Computer Science & Engineering (final year), East Delta University, Chattogram |
| **Languages** | Bengali (native) · English |
| **Reach me** | [LinkedIn](https://www.linkedin.com/in/armanspov) |

### Selected work

<p>
<a href="https://github.com/Armanbro007/DeFakeNet-Lite"><img src="assets/card-defakenet.svg" alt="DeFakeNet-Lite: 98.75% accuracy at spotting AI-generated faces" width="49%"></a>
<a href="https://github.com/Armanbro007/DOCTORPR"><img src="assets/card-prescription.svg" alt="Prescription Digitizer: reads handwritten medicine names" width="49%"></a>
<a href="https://github.com/Armanbro007/khela-calendar"><img src="assets/card-khela.svg" alt="Khela Calendar: 104 World Cup matches synced to any calendar" width="49%"></a>
<img src="assets/card-next.svg" alt="More projects on the way" width="49%">
</p>

<details>
<summary><b>How each project works</b> (click to open)</summary>
<br>

**DeFakeNet-Lite** · my BSc thesis. A published 2025 model reached 91.95% at telling real faces from StyleGAN fakes. I rebuilt it, found that its heavy image augmentation was the main thing holding it back, fixed the training recipe, and swapped in a much lighter backbone. Result: 98.75% with 1.9M parameters instead of 25.7M, averaged over 3 runs. [Read the full write-up](https://github.com/Armanbro007/DeFakeNet-Lite)

**Prescription Digitizer** · turns photos of handwritten Bangladeshi prescriptions into typed medicine names, with a confidence score and a safety warning so a pharmacist confirms instead of guessing. [See the pipeline](https://github.com/Armanbro007/DOCTORPR)

```mermaid
flowchart LR
    A[Prescription photo] --> B[Handwriting model<br/>CRNN + CTC]
    A --> C[Gemini vision]
    B --> D[Match to medicine list]
    C --> E[Names + confidence]
    D --> E
```

**Khela Calendar** · World Cup 2026 is played in North America, so most matches fall at night in Bangladesh. This app shows all 104 matches in Bangladesh time and creates a calendar feed you subscribe to once, in Bangla or English. [See the app](https://github.com/Armanbro007/khela-calendar)

</details>

<img src="assets/roadmap.svg" alt="What I've built so far: May 2026 Prescription Digitizer, Jul 2026 Khela Calendar, Nov 2026 BSc thesis DeFakeNet-Lite, more on the way" width="100%">

### Tools I use

**AI and data:** Python · TensorFlow / Keras · scikit-learn · OpenCV · LLM APIs (Gemini)
**Apps and shipping:** Streamlit · JavaScript · Vercel · Git

<sub>Every graphic on this page is hand-made for this profile and follows your light or dark theme.</sub>
