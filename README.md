# VaaNi — Voice of the Unheard

A two-way multimodal communication bridge for Deaf and Hard-of-Hearing communities in India, using Indian Sign Language (ISL) recognition and speech transcription.

---

## Motivation

India has an estimated 63 million people with hearing impairment — one of the largest such populations in the world. Yet almost no accessible, open-source tooling exists for **Indian Sign Language** specifically. Most gesture recognition systems are built for American Sign Language (ASL), leaving ISL users without digital tools that reflect their language and culture.

VaaNi (वाणी — Sanskrit for *voice* or *speech*) aims to change that. It is a two-way system: a hearing person's speech is transcribed and converted into ISL signs, and a deaf person's ISL gestures are recognized and converted back into text. A real communication bridge, not just a one-way demo.

This project is built progressively alongside Andrew Ng's Machine Learning Specialization, with each module introducing more sophisticated ML as the course advances.

---

## Modules Roadmap

| # | Module | Description | Status |
|---|--------|-------------|--------|
| 1 | ISL Gesture Recognition | MediaPipe hand landmarks → Logistic Regression / SVM classifier for ISL alphabets and common words | 🔴 Not Started |
| 2 | Speech-to-Text | Whisper-based transcription optimized for Indian English and Hindi accents | 🔴 Not Started |
| 3 | Text → ISL Gloss Converter | Rule-based + ML hybrid that converts transcribed text into ISL gloss notation | 🔴 Not Started |
| 4 | Sign Animation Display | Curated ISL sign video clips strung together from gloss output for visual rendering | 🔴 Not Started |
| 5 | Noise Robustness + Evaluation | PCA on landmark features, anomaly detection for model uncertainty, performance under degraded conditions | 🔴 Not Started |

---

## Tech Stack

| Layer | Tools |
|---|---|
| Hand Landmark Extraction | MediaPipe |
| Computer Vision | OpenCV |
| Classical ML | scikit-learn |
| Deep Learning | PyTorch |
| Speech Transcription | OpenAI Whisper |
| Data Processing | NumPy, Pandas |
| Visualization | Matplotlib, Seaborn |
| Backend | FastAPI |
| Frontend / Demo | Gradio / Streamlit |
| Deployment | Hugging Face Spaces |
| Environment | Python 3.10, Conda |

---

## License

VaaNi is licensed under the [AGPL-3.0 License](./LICENSE) for open and academic use.
For commercial use, please contact: samayankwork@email.com
