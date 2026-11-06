## Syed Ayaan Ahmed
Software & Machine Learning Engineer | Local-first ML systems, agent memory, and deterministic agent frameworks.

Final-year B.Tech CSE (AI & ML) at Woxsen University, Hyderabad. I build systems end to end: data, training, evaluation, tests, and setup that anyone can run.

Currently building [**atlas**](https://github.com/Ayai1/atlas), a local-first AI companion that diagnoses and explains your machine without sending a byte of it anywhere.

---

### Selected work

| Project | What it does | Where it got to |
|---|---|---|
| [**EngramOS**](https://github.com/Ayai1/EngramOS) | Local-first temporal memory pipeline for LLM agents. Facts are stored as time-valid (entity, attribute, value) slots with provenance, and a deterministic gate quarantines suspicious updates from untrusted sources | **68.4%** vs 57.9% for hybrid RAG on a pre-registered 38-question suite, with 0 quarantine leaks; 361 tests; runs on a local 30B model |
| [**symptoms-disease-reasoning**](https://github.com/Ayai1/symptoms-disease-reasoning) | Hybrid diagnostic reasoning engine: rule-based severity scoring, Random Forest / XGBoost priors, Tree-of-Thoughts follow-up questioning, and RAG explanations grounded in PubMed | Research prototype with an interactive CLI; for research and education only, not medical advice |
| [**autostream-ai-agent**](https://github.com/Ayai1/autostream-ai-agent) | LangGraph agent that turns a conversation into a qualified lead: passive field extraction, confidence-thresholded intent routing, RAG-grounded replies | Working CLI agent; WhatsApp webhook design documented |
| [**Continual learning with DCE-CVAE**](https://github.com/Ayai1/continual-learning-dce-cvae) | Class-incremental learning on Split-MNIST via pure latent replay: four-tier memory hierarchy, per-task orthogonal subspaces, latent merging | **≈0.66** avg accuracy over 5 sequential tasks vs ≈0.20 for naive fine-tuning |
| [**AI-Generated Image Detection**](https://github.com/Ayai1/AI-Generated-Image-Detection-Using-EfficientNet-B0) | EfficientNet-B0 classifier for DALL·E / Midjourney / SDXL output, with Grad-CAM to show what the model keyed on | **98.5%** on a 20,000-image test set, trained on 120k images |

**Patent:** Smart Air Quality Monitoring IoT Device (granted)

---

### Tools

`Python` · `PyTorch` · `TensorFlow` · `scikit-learn` · `Transformers` · `LangChain` · `LangGraph` · `XGBoost` · `OpenCV` · `FastAPI` · `Ollama` · `SQLite`

### Interests

Agent memory and retrieval-augmented systems · healthcare AI · continual learning · computer vision · on-device and privacy-preserving ML

### Reach me

[LinkedIn](https://www.linkedin.com/in/syed-ayaan-ahmed-766a85289) · saayaan1208@gmail.com
