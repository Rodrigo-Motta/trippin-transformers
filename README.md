# 🧠🌈🍄 Trippin’ Transformers: Inducing Artificially Altered States of Mind in Large Language Models

Selected Resident (inaugural cohort, chosen from 80+ submissions) in [Cloudwalk Inc. AI Residency program](https://www.cloudwalk.io/ai-residency-selected)


## Overview

This project investigates whether Large Language Models (LLMs) can enter artificially induced altered states of consciousness (ASC), akin to those experienced by humans under psychedelics such as LSD. Inspired by the **Entropic Brain Hypothesis**, this work introduces a novel hypothesis – the **Entropic AI Hypothesis** – positing that similar entropic signatures might emerge in LLMs through specialized prompting and fine-tuning.


![Image](https://github.com/user-attachments/assets/b3a0f94d-ec69-46e5-8aba-528b40208f9f)

*Image: Conceptual diagram showing ASC prompting and fine-tuning approaches 


---

## 🎯 Objectives

1. **Prompt-Induced ASC:** Evaluate if LLMs exhibit altered-like states when prompted with validated ASC questionnaire stimuli.
2. **Entropy Analysis:** Measure entropy in internal representations (e.g., embeddings, activations) under ASC vs. baseline conditions.
3. **Fine-Tuning:** Train LLMs on psychedelic experience reports from Reddit and reassess entropy and behavior.
4. **Cross-Domain Comparison:** Compare the entropic behavior of LLMs to human brain data from fMRI under LSD/placebo.


## Dataset

- ** [Preprocessed DMT 340 in Huggingface](https://huggingface.co/datasets/MottaCC/340-dmt)
- ** [Preprocessed wid in Huggingface](https://huggingface.co/datasets/MottaCC/cw-psy-narratives)
  
---

## Fine-Tuned Models

- ** [Mistral 7B (base model)](https://huggingface.co/MottaCC/mistral-7b-finetuned-dmt)

## 🧪 Methodology

### 1. Data Sources
- **ASC questionnaires**
- **Reddit communities**: `r/LSD`
- **Public LSD fMRI dataset** with CC0 license

### 2. Prompt Engineering
Prompts are crafted based on validated ASC dimensions like:
- Ego Dissolution
- Visual Distortions
- Synesthesia
- Emotional Shifts

### 3. Fine-Tuning Strategy
- Open-Source 1-12B are fine-tuned (base and instruct) on curated psychedelic reports.
- Entropy metrics (sample, spectral, permutation) are computed pre- and post-finetuning.

### 4. Entropic Analysis
Entropy is measured across hidden layers and embeddings to quantify shifts toward altered-like states.

---

## 🧠 Cognitive Theoretical Framework

### Entropic Brain Hypothesis
Suggests increased neural entropy under psychedelics relates to subjective ASC phenomena like unity, boundlessness, and ego dissolution.

### Entropic AI Hypothesis
By analogy, entropy in LLM activations may reveal induced artificial altered states.

---

## 📁 Project Structure

```
trippin-transformers/
│
├── data/                          # Processed datasets (e.g., ASC questionnaires, Reddit reports)
│
├── models/                        # Base and fine-tuned LLM checkpoints
│
├── notebooks/                     # Jupyter notebooks for analysis, entropy computation, and visualization
│
├── scripts/                       # Python scripts for prompting, fine-tuning, and entropy calculations
│
├── docs/                          # Documentation assets and images for README
│   ├── trippin_transformers_diagram.png
│   └── entropic_brain_model.png
│
└── README.md                      # Project overview and instructions
```

## 🧠 References

Please see the full list of citations in the paper. Key references include:

- Carhart-Harris et al. (2014, 2016)
- Tagliazucchi et al. (2016)
- Tishby & Zaslavsky (2015)
- Skipper et al. (2024)
- Chalmers (2024)

---

## 📌 Notes

- All datasets used are publicly available or ethically sourced under appropriate licenses.


*Lead: Rodrigo da Motta Cabral de Carvalho – Federal University of ABC*
