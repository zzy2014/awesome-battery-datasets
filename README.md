# public-datasets-in-battery

Curated datasets for **XXX领域** (e.g., NLP / Medical / Finance / Robotics).

This repository collects and organizes high-quality datasets for research, benchmarking, and applied development.

---

# 📌 Dataset Categories

## 1. Foundation Datasets

Large-scale datasets used for pretraining and representation learning.

| Dataset | Description | Size | License | Link |
|--------|-------------|------|---------|------|
| Dataset A | General corpus for pretraining | 10M samples | MIT | [Link](#) |
| Dataset B | Web-scale text dataset | 2TB | Apache-2.0 | [Link](#) |

---

## 2. Benchmark Datasets

Standard datasets used for evaluation and comparison of models.

| Dataset | Task | Metric | Size | Link |
|--------|------|--------|------|------|
| Benchmark A | Classification | Accuracy | 50K | [Link](#) |
| Benchmark B | Question Answering | F1 Score | 100K | [Link](#) |

---

## 3. Instruction / Alignment Datasets

Datasets designed for instruction tuning, RLHF, or human preference learning.

| Dataset | Type | Language | Size | Link |
|--------|------|----------|------|------|
| Dataset A | Human preference | EN | 100K | [Link](#) |
| Dataset B | Instruction tuning | Multilingual | 1M | [Link](#) |

---

## 4. Multimodal Datasets

Datasets involving multiple modalities (text, image, audio, video).

| Dataset | Modalities | Task | Size | Link |
|--------|------------|------|------|------|
| Dataset A | Image + Text | Captioning | 5M pairs | [Link](#) |
| Dataset B | Video + Audio | Video QA | 100K | [Link](#) |

---

## 5. Synthetic Datasets

AI-generated or simulation-based datasets.

| Dataset | Generation Method | Use Case | Link |
|--------|------------------|----------|------|
| Dataset A | LLM-generated | Instruction tuning | [Link](#) |
| Dataset B | Simulation | Robotics training | [Link](#) |

---

## 6. Evaluation & Safety Datasets

Datasets used for robustness, bias, safety, and hallucination evaluation.

| Dataset | Focus | Description | Link |
|--------|------|-------------|------|
| Dataset A | Hallucination | Test factual consistency | [Link](#) |
| Dataset B | Bias | Evaluate fairness | [Link](#) |

---

## 7. Domain-Specific Datasets

Specialized datasets for specific industries or applications.

| Domain | Example Datasets |
|--------|----------------|
| Medical | MedQA, PubMedQA |
| Finance | FinQA, Bloomberg datasets |
| Legal | LegalBench |
| Robotics | RoboNet |
| Education | EduQA |
| Security | Cybersecurity datasets |

---

# 📊 Dataset Entry Standard

Each dataset should follow this format:

```yaml
name: Dataset Name
task: Task type (QA / classification / generation)
modality: Text / Image / Audio / Multimodal
language: English / Multilingual
size: Dataset size
license: License type
paper: Paper link (if any)
homepage: Official page
download: Download link
benchmark: Related benchmark (if any)
year: Release year
