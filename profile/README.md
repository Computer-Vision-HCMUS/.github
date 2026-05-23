# Computer Vision

**Computer Vision research & development group — University of Science, VNU-HCM**

---

## About

**Computer-Vision-HCMUS** is the GitHub Organization for our **computer vision** work at the **University of Science (HCMUS)**, Vietnam National University Ho Chi Minh City.

We focus on:

- **Video analysis & multimodal summarization** — supervised learning on SumMe / TVSum, combining vision + speech.
- **Multivariate analysis & CCA** — theoretical foundations of Canonical Correlation Analysis for MSA problems.
- **Open-source delivery** — notebooks, reports, Streamlit demos, and reproducible pipelines.

---

## Featured projects

| Repository | Description | Stack |
|------------|-------------|-------|
| [**video-summarize**](https://github.com/Computer-Vision-HCMUS/video-summarize) | Importance-based video summarization; ResNet-50 + Whisper + SBERT, BiLSTM + temporal attention | PyTorch, FFmpeg, Streamlit |
| [**MSA-CCA**](https://github.com/Computer-Vision-HCMUS/MSA-CCA) | CCA research for MSA: geometric reasoning, LaTeX reports, theory demos | Python, Streamlit, LaTeX |

---

## Research areas

```text
┌─────────────────────────────────────────────────────────────────┐
│  Video understanding          Multimodal learning               │
│  · Frame importance           · Vision + speech alignment       │
│  · Dynamic summarization      · Temporal modeling (BiLSTM)      │
├─────────────────────────────────────────────────────────────────┤
│  Multivariate statistics      Reproducible research             │
│  · Canonical Correlation      · Reports, notebooks, ablations   │
│  · Geometry & interpretation  · Open datasets & configs         │
└─────────────────────────────────────────────────────────────────┘
```

---

## Quick start

Clone a repository and follow its README:

```bash
# Video summarization
git clone https://github.com/Computer-Vision-HCMUS/video-summarize.git
cd video-summarize
python -m venv .venv && .venv\Scripts\activate   # Windows
pip install -r requirements.txt

# MSA / CCA theory
git clone https://github.com/Computer-Vision-HCMUS/MSA-CCA.git
cd MSA-CCA
pip install -r requirements.txt
```

---

## Contributing

We welcome issues and pull requests from students, collaborators, and researchers.

1. Open an **Issue** describing a bug, idea, or theory question.
2. Fork the repo → create a branch → submit a small, well-described PR.
3. For algorithm changes: include metrics / ablations or link to a report notebook.

See each repository’s README for detailed workflow.
