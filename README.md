# MUSICAL-MOODS: Video Data

This repository contains the video data component of the MUSICAL-MOODS project, a foundational resource for training and validating AI models on complex, subjective, and unstructured human data.

**For a full overview of the project, please see the [central project hub](https://github.com/fabiopaolizzo/musical-moods.main).**

---

### Data Description

The data in this repository consists of complete, continuous video recordings of the full dance improvisation sessions. The video was captured from a fixed, wide-angle perspective to serve two primary purposes:

1.  It provides a rich source for **computer vision analysis** of the dancer's movements and overall performance context.
2.  Critically, it serves as the **qualitative ground truth and validation reference** for the corresponding high-dimensional motion capture (MoCap) data.

### Data Acquisition & Processing

The source footage was captured in a professional, controlled **green screen environment** to ensure clean data for analysis.

*   **Source Capture:** 1080p resolution at 120 frames per second (fps), using an APS-C sensor.
*   **Delivered Files:** The downloadable files in this repository have been rendered from the high-quality source footage into a standard format (640x360 resolution, 30fps, 228kbps) for ease of use and distribution.

This two-step process ensures that the underlying data comes from a high-fidelity, professional source, while the final files are optimized for accessibility in a research context.

### Potential Applications & Research Areas

This dataset is a rich resource for research in computer vision, behavioral analysis, and multimodal AI. It is particularly well-suited for developing and benchmarking models in:

-   **Cross-Modal Validation:** Using visual information to validate and interpret sensor-based (MoCap) time-series data.
-   **Sensor Fusion:** Developing models that learn by combining visual and kinematic data streams.
-   **Human Pose Estimation:** Tracking and analyzing the kinematics of the human form with a corresponding ground-truth reference.
-   **Behavioral Analysis:** Correlating visual cues with other data modalities to build more comprehensive models of human behavior.

---

*This research was supported by the EU's Horizon 2020 programme (MSCA-IF-GF, REA Grant Agreement No. 659434).*
