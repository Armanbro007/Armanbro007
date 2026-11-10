<a href="https://github.com/Armanbro007/DeFakeNet-Lite"><img src="assets/header.svg" alt="Arman Rahman: I build AI that's small enough to actually use." width="100%"></a>

### In 20 seconds

| | |
| --- | --- |
| **Looking for** | Werkstudent / working-student roles in AI and automation, alongside my MSc in Germany (2027) |
| **Strongest work** | [DeFakeNet-Lite](https://github.com/Armanbro007/DeFakeNet-Lite): beat a published deepfake detector with a model 13.5× smaller |
| **Good at** | Taking an AI idea from paper to something people can use, then measuring it honestly |
| **Languages** | Bengali (native) · English (professional working) · German (learning) |
| **Reach me** | [LinkedIn](https://www.linkedin.com/in/armanspov) |

<br>

<a href="https://github.com/Armanbro007/DeFakeNet-Lite"><img src="assets/thesis.svg" alt="DeFakeNet-Lite: 98.75% accuracy, 13.5x fewer parameters, 3x faster on CPU, 3.87 MB model" width="100%"></a>

<details>
<summary><b>How DeFakeNet-Lite works</b> (click to open)</summary>
<br>

```mermaid
flowchart LR
    A[Face photo<br/>256 × 256] --> B[MobileNetV3-Large<br/>pre-trained on ImageNet]
    B --> C[Small head<br/>Dense 128 + dropout]
    C --> D{Real or<br/>AI-generated?}
    E[Better training recipe<br/>gentle augmentation · frozen warm-up<br/>EMA weights · label smoothing] -.-> B
```

The published model got 91.95%. I rebuilt it from the paper, found that its heavy image augmentation was the main thing holding it back (−3.85 points, McNemar p < 0.001), fixed the recipe, then swapped in a backbone 13.5× smaller. Every number is the mean of 3 runs, and the notebooks are saved with their outputs so anyone can check them.

It also has a known limit, written up in the repo: it catches StyleGAN faces almost perfectly, but not faces from diffusion models like Stable Diffusion XL.

</details>

### Projects

<p>
<a href="https://github.com/Armanbro007/DeFakeNet-Lite"><img src="assets/card-defakenet.svg" alt="DeFakeNet-Lite" width="32%"></a>
<a href="https://github.com/Armanbro007/DOCTORPR"><img src="assets/card-prescription.svg" alt="Prescription Digitizer" width="32%"></a>
<a href="https://github.com/Armanbro007/khela-calendar"><img src="assets/card-khela.svg" alt="Khela Calendar" width="32%"></a>
</p>

<img src="assets/roadmap.svg" alt="May 2026 Prescription Digitizer, Jul 2026 Khela Calendar, Nov 2026 BSc thesis, now learning AI automation and German, Dec 2026 IELTS, 2027 MSc in Germany" width="100%">

### Tools I use

**AI and data:** Python · TensorFlow / Keras · scikit-learn · Kaggle GPUs · LLM APIs (Gemini, OpenAI)
**Building and shipping:** Streamlit · JavaScript · Vercel · Git
**Learning now:** n8n and workflow automation · German

<sub>Every graphic on this page was designed by hand for this profile and follows your light or dark theme.</sub>
