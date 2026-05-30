# Hi, I'm Nima Kelidari

Master's student in Computer Science (Artificial Intelligence) at the **University of Southern California**, Viterbi School of Engineering. Previously a CS undergrad at the **Sharif University of Technology**. Based in Los Angeles, CA.

I work on efficient and interpretable methods for **large language models, multimodal learning, and robot learning**, with a particular interest in inference-time interventions and reproducible ML infrastructure.

---

## Current research

I am running three concurrent projects at USC:

### 3D-DELTA — Learned low-rank steering head for Mixture-of-Experts LLMs
*With Profs. Robin Jia and Xuezhe Ma*

A 50-thousand-parameter learned low-rank head that replaces SteerMoE's hand-engineered statistic for routing intervention on OLMoE-1B-7B. Beats SteerMoE (ICML 2026) by **+0.101 mean across six faithfulness benchmarks**, with **+0.288 on FaithEval-Inconsistent**. Manuscript in preparation.

[Repository](https://github.com/Nikelroid/moe-steering-3d-delta)

### Adversarial Co-Evolution of RL and LLM Agents
*With Prof. Yan Liu*

A distributed multi-core PPO training pipeline with a custom three-phase curriculum (Random → Self-Play → Adversarial), reaching a **99.12% win rate** against baseline agents on Gin Rummy. The system includes a Master-Worker inference engine that distills strategic knowledge from Llama-3, Gemma, and GPT-OSS into compact reinforcement-learning policies.

[Repository](https://github.com/nikelroid/adversarial-coevolution)

### Linguistic-Agnostic Speech Emotion Recognition
*With Prof. Mohammad Soleymani, USC SAIL*

An MLOps probing framework in PyTorch and HuggingFace evaluating six pretrained speech encoders (Wav2Vec2, HuBERT, WavLM, XLS-R, and related models) across eight emotion-recognition datasets via SLURM, with a FastAPI / JavaScript dashboard for real-time layer-wise paralinguistic analysis.

[Repository](https://github.com/nikelroid/linguistic-agnostic-ser)

---

## Research interests

- Inference-time methods and parameter-efficient interventions for large language models
- Mixture-of-Experts routing and steering
- Multimodal learning (vision, language, speech)
- Robot learning and manipulation
- MLOps, benchmarking, and reproducible ML infrastructure

---

## Selected other projects

- **[Multi-Modal Sentiment Classification](https://github.com/Nikelroid/Multi-Modal-Sentiment-Classification)** — A multimodal fusion network integrating RoBERTa, ViT, and wav2vec2 for joint text–vision–audio sentiment prediction. Includes a FastAPI deployment.
- **MLOps Pipelines (3 projects)** — Production-style ML pipelines built with Docker, Jenkins, and Weights & Biases.
- **QA-image** — A native iOS app paired with a Dockerized Python backend deployed on Google Cloud.
- **Sharif undergraduate research** — Ten months with Dr. Tefagh on Computer Vision and Generative AI methods using Vision Transformers and 3D Convolutional Neural Networks.

---

## Tools and stack

**Languages:** Python · Java · SQL · C++ · R
**ML / DL:** PyTorch · HuggingFace · TensorFlow · scikit-learn · OpenCV
**LLM / NLP:** Mixture-of-Experts (OLMoE, Mixtral, Qwen3, Phi-3.5-MoE), Llama-3, vLLM, contrastive activation probing
**Reinforcement Learning:** Stable Baselines 3 · PettingZoo · custom curriculum learning
**Infrastructure:** SLURM · Docker · Kubernetes · Jenkins · MLflow · Weights & Biases · FastAPI
**Data:** MySQL · MongoDB · PostgreSQL · Redis · DVC · Apache Airflow
**Cloud:** Google Cloud · AWS

---

## Contact

- Website: [kelidari.com](https://kelidari.com)
- Email: [kelidari@usc.edu](mailto:kelidari@usc.edu)
- LinkedIn: [nima-kelidari](https://linkedin.com/in/nima-kelidari)
