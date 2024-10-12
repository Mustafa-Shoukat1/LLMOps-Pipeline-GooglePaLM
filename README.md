This repository contains resources and code for adapting an open-source pipeline for **supervised fine-tuning** of a **Large Language Model (LLM)**, focusing on improving model performance in specific domains like answering Python coding questions. This project explores end-to-end **LLMOps** principles for training and deploying custom LLMs.


## 📚 What I id
- Retrieve and transform training data for LLM fine-tuning. - Pre-processing training data for **supervised instruction tuning**.
- Version control for data and model tracking. - Versioning datasets and models to manage tuning experiments.
- Supervised tuning pipeline setup and deployment. - Configuring and executing a **supervised tuning pipeline**.
- Responsible AI practices by outputting safety scores. - Deploying a tuned LLM and evaluating **safety scores** for responsible AI use.

## ⚙️ Tools & Technologies
- **BigQuery** (for data pre-processing and storage)
- **Kubeflow Pipelines** (for orchestrating machine learning workflows)
- **Google Cloud** (for cloud-based model training and deployment)

## 💻 Project Structure
- `/data`: Dataset and pre-processing scripts.
- `/models`: Trained and fine-tuned models.
- `/pipeline`: Kubeflow pipeline configurations for LLMOps.
- `/deployment`: Deployment scripts for the custom LLM.

