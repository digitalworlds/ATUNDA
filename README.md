# ATUNDA - Afrogenic dance moves

This dataset contains motion data sequences extracted from the [Atunda videos](https://www.atunda.live/) using the MediaPipe pose, FMPose3D, and SAMbody4D detection libraries. The dataset of Afrogenic dance moves has been systematically collected and curated for training machine learning models for dance move classification. The data collection was performed in 3 phases:

| Phase    | Videos   | Moves |
|----------|----------|----------|
| Phase 1  | 397 | 13  |
| Phase 2  | 567  | 36  |
| Phase 3  | In progress  | In progress  |
| Total    | 964      | 49       |

It currently includes 964 move sequences covering 49 distinct dance moves from African and African Diaspora performative culture.

Dataset visual inspector: https://digitalworlds.github.io/atunda-motion-player/

### Publications:

Phase 1 dataset:

Diego Carrascosa, Tristan Pank, Qudus Onikeku, Mas'ud Onikeku, Jeremy Frusco, Osubi Craig, Angelos Barmpoutis. "Atunda: A Novel Afrogenic Dance Video Database for AI-Driven Movement Classification". Journal on Computing and Cultural Heritage (under review).

Phase 2 dataset:

Tristan Pank, Diego Carrascosa, Qudus Onikeku, Jeremy Frusco, Osubi Craig, Angelos Barmpoutis (2026). "Real-Time Computer-Assisted Afrogenic Dance Move Recognition and Analysis", In ACM International Conference on Interactive Media Experiences (IMX) ’26, Athlone, Ireland
https://doi.org/10.1145/3788851.3805020

Phase 3 dataset:

In progress.

------------------------------------------------------------------------

## Dataset Structure

Each subfolder under `data/` is organized into phases and internally into method-specific directories such as `fmpose3d`, `mediapipe`, and `sam-body4d`, with each containing the corresponding estimated motion sequences.

```text
data/
├── phase1/
│   ├── fmpose3d/
│   ├── mediapipe/
│   ├── sam-body4d/
│   └── ...
├── phase2/
│   ├── fmpose3d/
│   ├── mediapipe/
│   ├── sam-body4d/
│   └── ...
└── ...
```

------------------------------------------------------------------------

## License

The data are provided under the [Atunda license](LICENSE). 
By downloading the data you accept the terms and conditions of the license.

Please note that:
- Commercial use is strictly prohibited.
- The license expires in 1 year from the time you download the data.
- You must delete the dataset when your license expires.
- You can renew the license and re-download the dataset, as some of the data may have changed. (Why? Because performers may request to remove their data, or contribute new data). 
