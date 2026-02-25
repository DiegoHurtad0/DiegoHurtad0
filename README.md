<h1 align="center">Hi, I'm Diego O’Hurtado 👋</h1>
<h3 align="center">Senior Data Scientist & Machine Learning Engineer</h3>
<h4 align="center">GenAI | RAG Architectures | MLOps | Cloud Engineering</h4>

<p align="center">
  <a href="https://www.linkedin.com/in/diego-hurtado-olivares/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://medium.com/@diego.hurtado.olivares" target="_blank"><img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white"/></a>
  <a href="https://www.kaggle.com/diegohurtadoo" target="_blank"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white"/></a>
</p>

<br>

<h3>🚀 Professional Summary</h3>
<p>
I am a <strong>Senior Data Scientist and Machine Learning Engineer</strong> with <strong>8+ years of experience</strong> delivering production-grade ML solutions for Fortune 500 companies like <strong>Walmart, DHL, and Huawei</strong>. 
</p>
<p>
My expertise lies in the intersection of <strong>Ads-Tech, Retail, and Supply Chain</strong>, where I focus on delivering scalable ML pipelines, AI recommendation systems, and converting Generative AI (GenAI) into actionable business roadmaps.
</p>

<h3>🏆 Key Impact Highlights</h3>
<ul>
  <li><strong>💰 $40M Revenue Increase:</strong> Spearheaded AI-powered market mix models at Huawei.</li>
  <li><strong>📈 10% CTR Uplift:</strong> Optimized product relevance personalization algorithms at Walmart.</li>
  <li><strong>⚡ 30% Efficiency Gain:</strong> Deployed predictive analytics for logistics optimization at DHL.</li>
  <li><strong>🧠 GenAI & RAG:</strong> Currently engineering Dense Vector Retrieval systems and LLM-based personalization to boost AdSense ROI by 8%.</li>
</ul>

<h3>🛠 Tech Stack & Skills</h3>

<table>
  <tr>
    <td align="center"><strong>GenAI & ML Stack</strong></td>
    <td align="center">LlamaIndex, LangChain, RAG, Hugging Face, OpenAI, SentenceTransformers, BERT, GPT, Prompt Engineering</td>
  </tr>
  <tr>
    <td align="center"><strong>Cloud & Orchestration</strong></td>
    <td align="center">GCP (BigQuery, Vertex AI), AWS, Azure, Docker, Kubernetes, Terraform, Airflow, Databricks, MLflow</td>
  </tr>
  <tr>
    <td align="center"><strong>Languages & Core</strong></td>
    <td align="center">Python, SQL, PySpark, Bash, FastAPI, Pytest, Git</td>
  </tr>
  <tr>
    <td align="center"><strong>Data Viz</strong></td>
    <td align="center">Plotly Dash, Streamlit, Looker, Tableau, PowerBI</td>
  </tr>
</table>

<br>

<!-- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// //-->

<br>
<img src="https://github.com/DiegoHurtad0/Offline-Multimodal-Clinical-Triage-Powered-by-MedGemma/blob/main/assets/divide.png" width="100%" height="5px">
<br>

<br>

<h1 align="center">Gemma 3 1B Reasoning Fine-Tuning with Tunix (LoRA SFT → GRPO)</h1>
<h3 align="center">Strict XML Output Contract • Kaggle TPU–stable • Judge-ready inference wrapper</h3>

<a href="https://github.com/DiegoHurtad0/gemma-tunix-production" target="_blank">
  <img height="460" width="460" align="right" src="https://raw.githubusercontent.com/DiegoHurtad0/gemma-tunix-production/main/assets/training_dashboard_smoothed.png" />
</a>

<h3 align="left">Summary:</h3>

<p align="left">
This project documents a <strong>production-grade reasoning fine-tuning pipeline</strong> for <strong>Gemma 3 1B Instruct</strong> using <strong>Tunix (JAX)</strong> on Kaggle TPUs.  
The core goal is <strong>judge robustness</strong>: ensure the model emits a machine-parseable output schema every time:
</p>

<pre>
&lt;reasoning&gt;...&lt;/reasoning&gt;
&lt;answer&gt;...&lt;/answer&gt;
</pre>

<ul>
  <li><strong>Stage 1 — LoRA SFT:</strong> Seeds strict XML format + instruction-following behavior.</li>
  <li><strong>Stage 2 — GRPO:</strong> Reinforcement learning with composite rewards (format + task quality + stability).</li>
  <li><strong>Judge-safe inference wrapper:</strong> Deterministic repair + escaping guarantees strict XML for evaluation.</li>
  <li><strong>Systems reliability:</strong> OOM-safe GRPO defaults, KV-cache sizing guarantees, and Tunix 0.1.6 concat-safe rollout batching.</li>
  <li><strong>Evaluation harness:</strong> Quant metrics, qualitative before/after, and TensorBoard-derived training curves.</li>
</ul>

<br>

<h3 align="left">Check it here:</h3>

<a href="https://github.com/DiegoHurtad0/gemma-tunix-production" target="_blank">
  <img align="left" src="https://www.vectorlogo.zone/logos/github/github-tile.svg" alt="github" height="30" width="40" />
</a>

<!-- Optional: add Kaggle notebook + YouTube once you publish them -->
<!--
<a href="YOUR_KAGGLE_NOTEBOOK_URL" target="_blank">
  <img align="left" src="https://www.vectorlogo.zone/logos/kaggle/kaggle-icon.svg" alt="kaggle" height="30" width="40" />
</a>

<a href="YOUR_YOUTUBE_VIDEO_URL" target="_blank">
  <img align="left" src="https://www.vectorlogo.zone/logos/youtube/youtube-icon.svg" alt="youtube" height="30" width="40" />
</a>
-->

<br>
<br>

<h3 align="left">Languages:</h3>
<a href="" target="_blank">
  <img align="left" src="https://www.vectorlogo.zone/logos/python/python-icon.svg" alt="python" height="30" width="40" />
</a>
<br>
<br>

<h3 align="left">GenAI / ML Stack:</h3>
<img src="https://img.shields.io/badge/Gemma%203-4285F4?style=for-the-badge&logo=google&logoColor=white"/>
<img src="https://img.shields.io/badge/Tunix-JAX%20Native-111111?style=for-the-badge"/>
<img src="https://img.shields.io/badge/JAX-000000?style=for-the-badge&logo=google&logoColor=white"/>
<img src="https://img.shields.io/badge/LoRA-SFT-6E56CF?style=for-the-badge"/>
<img src="https://img.shields.io/badge/GRPO-Reinforcement%20Learning-FF6F00?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Kaggle%20TPU-Stability%20Engineering-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white"/>

<br>
<br>

<h3 align="left">Key Visual Evidence (from the final run):</h3>

<p align="center">
  <img src="https://raw.githubusercontent.com/DiegoHurtad0/gemma-tunix-production/main/assets/token_length_engineering.png" width="32%"/>
  <img src="https://raw.githubusercontent.com/DiegoHurtad0/gemma-tunix-production/main/assets/before_after_xml_validity.png" width="32%"/>
  <img src="https://raw.githubusercontent.com/DiegoHurtad0/gemma-tunix-production/main/assets/before_after_reasoning_depth.png" width="32%"/>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/DiegoHurtad0/gemma-tunix-production/main/assets/dataset_mixture_vibe_check.png" width="49%"/>
  <img src="https://raw.githubusercontent.com/DiegoHurtad0/gemma-tunix-production/main/assets/sequence_length_analysis.png" width="49%"/>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/DiegoHurtad0/gemma-tunix-production/main/assets/vibe_shift_density.png" width="70%"/>
</p>

<br>

<h3 align="left">Results Snapshot (Smoke Test):</h3>
<p align="left">
These are small-N smoke tests designed to catch regressions early (format breaks, empty outputs, instability).
The key win is eliminating judge-visible format failures via deterministic strict-XML repair.
</p>

<ul>
  <li><strong>Strict XML validity (raw generation):</strong> 40.00% (8/20)</li>
  <li><strong>Strict XML validity (after deterministic repair):</strong> 100.00% (20/20)</li>
  <li><strong>Math exact match (normalized, repaired):</strong> 15.00% (3/20)</li>
</ul>

<br>

<h3 align="left">Production-Grade</h3>

<ul>
  <li><strong>Contract-first design:</strong> strict output schema enforced in prompt, rewards, and inference wrapper.</li>
  <li><strong>Tunix 0.1.6 stability engineering:</strong> concat-safe rollout batching + KV-cache correctness guarantees.</li>
  <li><strong>OOM-safe GRPO defaults:</strong> conservative microbatch/generations/kv-extra to finish reliably on Kaggle TPUs.</li>
  <li><strong>Judge-friendly evaluation:</strong> before/after tables + training curves + token budget proof.</li>
  <li><strong>Reproducibility:</strong> config-driven pipeline + deterministic inference settings (INF_TOP_P=None for greedy).</li>
</ul>

<br>

<h3 align="left">Extra Evaluation Artifacts (selected)</h3>

<p align="center">
  <img src="https://raw.githubusercontent.com/DiegoHurtad0/gemma-tunix-production/main/assets/cell66_19-1-visualization-training-curves-from-tensorboard-event-fi_1.png" width="49%"/>
  <img src="https://raw.githubusercontent.com/DiegoHurtad0/gemma-tunix-production/main/assets/cell66_19-1-visualization-training-curves-from-tensorboard-event-fi_4.png" width="49%"/>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/DiegoHurtad0/gemma-tunix-production/main/assets/cell67_19-1-visualization-winning-training-dashboard-smoothed-trend_1.png" width="70%"/>
</p>

<br>

| Challenge / Track | Base Model | Training Strategy | Output Contract | Key Proof |
|------------------|-----------:|------------------|----------------|----------|
| Google Tunix Hackathon (Reasoning Traces) | Gemma 3 1B IT | LoRA SFT → GRPO (reward shaping) | Strict XML: `<reasoning>` + `<answer>` | 100% strict XML post-repair + full eval artifacts |

<br>



<!-- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// //-->


<br>

<h1 align="center">Offline Multimodal Clinical Triage Copilot (MedGemma 1.5)</h1>
<h3 align="center">Evidence‑first • Offline‑first • Auditable PDF • Single T4‑class GPU</h3>

<a href="https://www.kaggle.com/code/diegohurtadoo/multimodal-clinical-reasoning-agent" target="_blank">
  <img width="460" align="right" src="https://raw.githubusercontent.com/DiegoHurtad0/Offline-Multimodal-Clinical-Triage-Powered-by-MedGemma/main/assets/Multimodal_Triage_Dashboard.png" alt="FieldScribe UI dashboard" />
</a>

<h3 align="left">Summary</h3>

<p align="left">
<strong>FieldScribe</strong> is an <strong>offline‑first, evidence‑anchored triage copilot</strong> that:
(1) localizes chest X‑ray findings, (2) detects interval change (Δ heatmap), (3) compresses FHIR‑shaped EHR context into auditable facts, and (4) exports a clinician‑readable <strong>triage report + tamper‑evident PDF</strong>.
</p>

<ul>
  <li><strong>Offline-first:</strong> Runs on-prem / edge once weights & assets are present (no cloud dependency at inference time).</li>
  <li><strong>Evidence-first UX:</strong> Always renders images + Δ heatmap + extracted facts alongside the narrative output.</li>
  <li><strong>MedGemma-powered:</strong> Uses <strong>MedGemma 1.5 4B IT</strong> for multimodal synthesis (CXR + EHR).</li>
  <li><strong>Safety guardrails:</strong> DICOM routing interlock prevents patient mismatches from entering synthesis.</li>
  <li><strong>Auditability:</strong> Structured JSON audit packet + <strong>Unicode-safe</strong> PDF export (ReportLab).</li>
  <li><strong>Feasibility instrumentation:</strong> Logs latency, peak VRAM, and token counts (ablation table in notebook).</li>
</ul>

<br>

<h3 align="left">Check it here</h3>

<a href="https://github.com/DiegoHurtad0" target="_blank">
  <img align="left" src="https://www.vectorlogo.zone/logos/github/github-tile.svg" alt="github" height="30" width="40" />
</a>

<a href="https://www.kaggle.com/code/diegohurtadoo/multimodal-clinical-reasoning-agent" target="_blank">
  <img align="left" src="https://www.vectorlogo.zone/logos/kaggle/kaggle-icon.svg" alt="kaggle" height="30" width="40" />
</a>

<a href="https://youtu.be/dl6Aq4TugQk" target="_blank">
  <img align="left" src="https://www.vectorlogo.zone/logos/youtube/youtube-icon.svg" alt="youtube" height="30" width="40" />
</a>

<br>
<br>

<h3 align="left">Languages</h3>
<img align="left" src="https://www.vectorlogo.zone/logos/python/python-icon.svg" alt="python" height="30" width="40" />
<br>
<br>

<h3 align="left">GenAI / ML Stack</h3>
<img src="https://img.shields.io/badge/MedGemma%201.5-4285F4?style=for-the-badge&logo=google&logoColor=white"/>
<img src="https://img.shields.io/badge/Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/Gradio-FF4B4B?style=for-the-badge&logo=gradio&logoColor=white"/>
<img src="https://img.shields.io/badge/FHIR-0B5FFF?style=for-the-badge"/>
<img src="https://img.shields.io/badge/DICOM-0F172A?style=for-the-badge"/>
<img src="https://img.shields.io/badge/ReportLab-PDF%20Export-111111?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Kaggle%20GPU-T4%20Edge%20Target-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white"/>

<br>
<br>

<h3 align="left">Key Visual Evidence (from the final run)</h3>

<p align="center">
  <img src="https://raw.githubusercontent.com/DiegoHurtad0/Offline-Multimodal-Clinical-Triage-Powered-by-MedGemma/main/assets/Clinical_Pipeline_Architecture.png" width="32%" alt="Clinical pipeline architecture"/>
  <img src="https://raw.githubusercontent.com/DiegoHurtad0/Offline-Multimodal-Clinical-Triage-Powered-by-MedGemma/main/assets/Agent_Demo.png" width="32%" alt="Fact filter context compression"/>
  <img src="https://raw.githubusercontent.com/DiegoHurtad0/Offline-Multimodal-Clinical-Triage-Powered-by-MedGemma/main/assets/Longitudinal_CXR_Delta_Heatmap.png" width="32%" alt="CXR baseline/localization/delta heatmap"/>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/DiegoHurtad0/Offline-Multimodal-Clinical-Triage-Powered-by-MedGemma/main/assets/Safety_Guardrails_and_Audit_Trace.png" width="49%" alt="DICOM routing decision tree"/>
  <img src="https://raw.githubusercontent.com/DiegoHurtad0/Offline-Multimodal-Clinical-Triage-Powered-by-MedGemma/main/assets/Multimodal_Triage.png" width="49%" alt="Edge vs cloud triage architecture"/>
</p>

<br>

<h3 align="left">Impact Snapshot</h3>

<ul>
  <li><strong>Time saved per complex triage case:</strong> ~10–14 minutes (manual EHR review + prior comparison + note drafting → evidence-first workflow).</li>
  <li><strong>Capacity reclaimed (example):</strong> 40 cases/day × 10 min/case ≈ <strong>6.7 clinician hours/day</strong> returned to care.</li>
  <li><strong>Access + privacy:</strong> Enables multimodal assistance in bandwidth-limited or sovereignty-restricted settings.</li>
</ul>

<br>

| Challenge / Track | Base Model | Deployment Target | Evidence / Audit Artifacts | Key Proof |
|------------------|-----------:|------------------|----------------------------|----------|
| Kaggle MedGemma Impact Challenge | MedGemma 1.5 4B IT | Single T4‑class GPU (edge) | Δ heatmap + fact bullets + JSON audit + PDF | Offline-first, evidence-anchored triage workflow |

<br>

<!-- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// //-->

---

# Why this project matters (Problem : Product)

In many clinical environments, the bottleneck isn’t “can AI answer medical questions?” — it’s **last‑mile triage under severe operational constraints**:

- **Intermittent connectivity:** rural clinics, mobile units, disaster response, overcrowded EDs can’t rely on cloud uptime.
- **Strict data sovereignty:** PHI often cannot leave the site or cross borders.
- **Fragmented evidence:** images, EHR facts, and priors exist — but clinicians must fuse them under intense time pressure.

FieldScribe targets a concrete workflow: **longitudinal chest X‑ray (CXR) interval change triage** where a clinician must:
1) detect what changed,  
2) localize it,  
3) reconcile with EHR context, and  
4) write an auditable note.

> **Status:** Research / demo prototype.  
> **Safety:** Not a medical device. Outputs require clinician verification.

---

## Demo visuals (place these under `assets/`)

This README expects the following files under `assets/`:

- `Multimodal_Triage.jpeg`
- `Clinical_Pipeline_Architecture.png`
- `Multimodal_Triage_Dashboard.png`
- `Agent_Demo.jpeg`
- `Longitudinal_CXR_Delta_Heatmap.png`
- `Safety_Guardrails_and_Audit_Trace.jpeg`
- `Auditable_Clinical_Summary_Report.pdf`

### Edge vs Cloud (why offline-first)

![Edge vs Cloud](https://raw.githubusercontent.com/DiegoHurtad0/Offline-Multimodal-Clinical-Triage-Powered-by-MedGemma/main/assets/Multimodal_Triage.png)

### 4‑step pipeline overview

![Pipeline](https://raw.githubusercontent.com/DiegoHurtad0/Offline-Multimodal-Clinical-Triage-Powered-by-MedGemma/main/assets/Clinical_Pipeline_Architecture.png)

### Offline dashboard UI (Gradio)

![Dashboard](https://raw.githubusercontent.com/DiegoHurtad0/Offline-Multimodal-Clinical-Triage-Powered-by-MedGemma/main/assets/Multimodal_Triage_Dashboard.png)

### Evidence panel (baseline → localization → delta heatmap)

![CXR evidence panel](https://raw.githubusercontent.com/DiegoHurtad0/Offline-Multimodal-Clinical-Triage-Powered-by-MedGemma/main/assets/Longitudinal_CXR_Delta_Heatmap.png)

### Fact filtering (EHR context compression)

![Fact filter](https://raw.githubusercontent.com/DiegoHurtad0/Offline-Multimodal-Clinical-Triage-Powered-by-MedGemma/main/assets/Agent_Demo.png)

### Safety routing + audit posture (DICOM interlock)

![Fact filter](https://github.com/DiegoHurtad0/Offline-Multimodal-Clinical-Triage-Powered-by-MedGemma/blob/main/assets/Safety_Guardrails_and_Audit_Trace.png)

### Sample output artifact (PDF)

➡️ **Download the example PDF:** [Auditable_Clinical_Summary_Report.pdf](https://github.com/DiegoHurtad0/Offline-Multimodal-Clinical-Triage-Powered-by-MedGemma/blob/main/assets/Auditable_Clinical_Summary_Report.pdf)

---

## What I built (Recruiter‑focused)

### 1) Data ingestion + Fact Filtering (EHR)
- Accepts an **offline FHIR‑shaped EHR bundle** (JSON).
- Runs a **Fact Filter** stage that compresses dense EHR into **query‑relevant bullet facts** (non‑inventive, audit‑friendly).
- Goal: keep the LLM context window **clean**, reduce hallucinations, preserve traceability.

### 2) Visual comparison + Δ heatmap (CXR)
- Computes an **interval change heatmap** (current vs prior CXR).
- Produces a visual evidence panel clinicians can inspect immediately (value even before text generation).

### 3) MedGemma multimodal synthesis (AI reasoning engine)
- Uses **MedGemma 1.5 4B IT** as the multimodal model for:
  - longitudinal imaging review
  - anatomical localization / grounding
  - EHR‑informed synthesis
- Runs **deterministic inference** (`do_sample=False`) for reproducibility; optionally exposes a “glass‑box” trace in the UI.

### 4) Triage report + PDF export (paper trail)
- Generates an executive triage summary and a **FHIR‑shaped audit packet**.
- Exports a **Unicode‑safe PDF** (ReportLab) with evidence images, trace metadata, and disclaimers.

---

## Engineering highlights

- **Offline‑first design:** works without external service calls once weights/assets are present.
- **Run‑all notebook reproducibility:** deterministic settings + auto‑reset YAML config pattern.
- **Safety interlock:** DICOM header routing prevents mismatched patient context from entering synthesis.
- **Performance instrumentation:** captures latency, output tokens, and peak VRAM across ablations.
- **Clinician-style UX:** evidence surfaced alongside narrative output.

---

## Performance & feasibility

- Target: **single Tesla T4‑class GPU** (edge deployable).
- Includes:
  - **Warmup** after model load to reduce first‑click latency spikes.
  - **Fast Mode** to cap tokens / reduce context while preserving evidence‑first outputs.
  - **Ablation table** logging: latency (s), output tokens, peak VRAM (MB)

> Example observed in demo screenshot: **Peak VRAM during visualization ≈ 3092 MB** (heatmap + panel rendering).  
> Exact measurements depend on runtime + model caching; see the notebook’s feasibility section.


---

## Disclaimer

FieldScribe is a demonstration prototype. It is **not** a regulated medical device and **must not** be used for definitive diagnosis or treatment decisions. Always defer to qualified clinical judgment and local protocols.




<!-- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// //-->

<br>
<img src="https://github.com/DiegoHurtad0/Offline-Multimodal-Clinical-Triage-Powered-by-MedGemma/blob/main/assets/divide.png" width="100%" height="5px">
<br>


<br>
<h1 align="center" href="https://medium.com/@diego.hurtado.olivares/linear-regression-from-scratch-15bfd15dc2e" > Linear Regression Model Representation & Implementation From Scratch in Python </h1>

<a href="https://www.kaggle.com/code/diegohurtadoo/house-price-prediction-top-12-leaderboard" target="blank"><img height="460" width="460" align="right" src="https://github.com/DiegoHurtad0/Linear-Regression-Model-Representation-Implementation-From-Scratch-using-Python/blob/main/Figures/regression_result1.png?raw=true" /></a>

<h3 align="left">Summary:</h3>
Linear Regression Model Representation & Implementation From Scratch using Python
<h3 align="left">Check it here:</h3>
<a href="https://www.kaggle.com/code/diegohurtadoo/house-price-prediction-top-12-leaderboard" target="blank"><img align="left" src="https://www.vectorlogo.zone/logos/kaggle/kaggle-icon.svg" alt="diegohurtadoo" height="30" width="40" /></a>
<a href="https://medium.com/@diego.hurtado.olivares/linear-regression-from-scratch-15bfd15dc2e" target="blank"><img align="left" src="https://www.vectorlogo.zone/logos/medium/medium-tile.svg" alt="diegohurtadoo" height="30" width="40" /></a>
<br>
</p>
 
<h3 align="left">Languages:</h3>
<a href="" target="blank"><img align="left" src="https://www.vectorlogo.zone/logos/python/python-icon.svg" alt="diegohurtadoo" height="30" width="40" /></a>
<br>
</p>
<h3 align="left">Data Science Tools:</h3>
<img src="https://www.vectorlogo.zone/logos/usepanda/usepanda-icon.svg" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="seaborn" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer"> 
<img src="https://matplotlib.org/3.1.1/_static/logo2_compressed.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<img src="https://geopandas.org/en/stable/_images/geopandas_icon_green.png" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">

<h3 align="left">Data Visualization Tools: </h3>
<img src="https://www.vectorlogo.zone/logos/plot_ly/plot_ly-official.svg" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer"> 
<img src="https://www.vectorlogo.zone/logos/w3_html5/w3_html5-icon.svg" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer"> 

<br>
<br>
 
 
| Challenge           | Models                | Ranking        | People Ranking   |
|---------------------|-----------------------|----------------|---------|
| House Price Prediction | Stacking Models   | Top 3%        |   Top 97 /  4651 |
| House Price Prediction | XGBoost, LightGBM    | Top 12%        |     |
 
 
 
 <br>

<!-- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// //-->


<br>
<img src="https://github.com/DiegoHurtad0/Offline-Multimodal-Clinical-Triage-Powered-by-MedGemma/blob/main/assets/divide.png" width="100%" height="5px">
<br>
 
 <h1 align="center" href="https://medium.com/p/b088390ce0f0" > Customer Churn Prediction Using Machine Learning Models: </h1>

<p>
  <a href="[https://medium.com/p/b088390ce0f0](https://github.com/DiegoHurtad0/DataSciencePortfolio/tree/main/Churn_Prediction)"><img width="500" height="500" align='right' src="https://miro.medium.com/v2/resize:fit:4800/format:webp/1*iX7VFtO1XmKuNhzk4ddg7A.png"></a>
</p>

<h3 align="left">Summary:</h3>
 
▪️ Predict whether a customer will churn using machine learning models

<h3 align="left">Check it here:</h3>
<a href="https://www.kaggle.com/code/diegohurtadoo/telco-churn-prediction-using-lstm-96-accuracy" target="blank"><img align="left" src="https://www.vectorlogo.zone/logos/kaggle/kaggle-icon.svg" alt="diegohurtadoo" height="30" width="40" /></a>
<a href="https://medium.com/p/b088390ce0f0" target="blank"><img align="left" src="https://www.vectorlogo.zone/logos/medium/medium-tile.svg" alt="diegohurtadoo" height="30" width="40" /></a>
<br>
<h3 align="left">Languages:</h3>
<a href="" target="blank"><img align="left" src="https://www.vectorlogo.zone/logos/python/python-icon.svg" alt="diegohurtadoo" height="30" width="40" /></a>
<br>
<h3 align="left">Data Science Tools:</h3>
<img src="https://www.vectorlogo.zone/logos/usepanda/usepanda-icon.svg" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="seaborn" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer"> 
<img src="https://geopandas.org/en/stable/_images/geopandas_icon_green.png" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<h3 align="left">Data Visualization Tools: </h3>
<img src="https://www.vectorlogo.zone/logos/plot_ly/plot_ly-official.svg" alt="plotly2" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<img src="https://www.vectorlogo.zone/logos/w3_html5/w3_html5-icon.svg" alt="html" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap2" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer"> 
<br>
<br>
<br>
 
| Challenge                | Models       | Score | Link                                              |
|--------------------------|--------------|-------|---------------------------------------------------|
| Custumer Churn Prediction   | LSTM         | 96%   | [Repository]([https://github.com/username/repo1](https://www.kaggle.com/code/diegohurtadoo/telco-churn-prediction-using-lstm-96-accuracy))   |
| Telco Customer Churn     | LSTM         | 81%   | [Repository]([https://github.com/username/repo2](https://www.kaggle.com/code/diegohurtadoo/custumer-churn-prediction-lstm-81-accuracy))   |
 
 
 
 <!-- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// //-->

<br>
<h1 align="center" href="https://medium.com/@diego.hurtado.olivares/predicting-taxi-fare-in-new-york-city-c5dd4aef55f4" > Predict Taxi Fare in NY using Machine Learning Techniques </h1>

<a href="https://medium.com/@diego.hurtado.olivares/predicting-taxi-fare-in-new-york-city-c5dd4aef55f4" target="blank"><img height="460" width="460" align="right" src="https://miro.medium.com/v2/resize:fit:4800/format:webp/1*6xnHYe__u8xiJWm_KsWgMw.png" /></a>

<h3 align="left">Summary:</h3>
Linear Regression Model Representation & Implementation From Scratch using Python
<h3 align="left">Check it here:</h3>
<a href="https://medium.com/@diego.hurtado.olivares/predicting-taxi-fare-in-new-york-city-c5dd4aef55f4" target="blank"><img align="left" src="https://www.vectorlogo.zone/logos/medium/medium-tile.svg" alt="diegohurtadoo" height="30" width="40" /></a>
<br>
</p>
 
<h3 align="left">Languages:</h3>
<a href="" target="blank"><img align="left" src="https://www.vectorlogo.zone/logos/python/python-icon.svg" alt="diegohurtadoo" height="30" width="40" /></a>
<br>
</p>
<h3 align="left">Data Science Tools:</h3>
<img src="https://www.vectorlogo.zone/logos/usepanda/usepanda-icon.svg" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="seaborn" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer"> 
<img src="https://matplotlib.org/3.1.1/_static/logo2_compressed.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<img src="https://geopandas.org/en/stable/_images/geopandas_icon_green.png" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">

<h3 align="left">Data Visualization Tools: </h3>
<img src="https://www.vectorlogo.zone/logos/plot_ly/plot_ly-official.svg" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer"> 
<img src="https://www.vectorlogo.zone/logos/w3_html5/w3_html5-icon.svg" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer"> 
<br>

<!-- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// //-->

<h1 align="center" href="https://medium.com/towards-data-science/covid-19-an-overview-of-mexico-ccf702ec80d9/" > Data analysis of covid in Mexico: </h1>

<p>
  <a href="https://medium.com/towards-data-science/covid-19-an-overview-of-mexico-ccf702ec80d9"><img width="500" height="500" align='right' src="https://miro.medium.com/max/720/1*m7P_xKqcyFdEptF77Kqt6w.png?raw=true"></a>
</p>

<h3 align="left">Summary:</h3>
 
▪️ Covid 19 — Data Analyst Mexico Overview
 
▪️ Explanation model of death cases in Mexico
 
▪️ Mexico Counties Covid Cases Correlation
 
▪️ Mexico`s Mobility pattern behaviour
 
▪️ Mexico Counties Clustering
<h3 align="left">Check it here:</h3>
<a href="https://medium.com/towards-data-science/covid-19-an-overview-of-mexico-ccf702ec80d9" target="blank"><img align="left" src="https://www.vectorlogo.zone/logos/medium/medium-tile.svg" alt="diegohurtadoo" height="30" width="40" /></a>
<br>
<h3 align="left">Languages:</h3>
<a href="" target="blank"><img align="left" src="https://www.vectorlogo.zone/logos/python/python-icon.svg" alt="diegohurtadoo" height="30" width="40" /></a>
<br>
<h3 align="left">Data Science Tools:</h3>
<img src="https://www.vectorlogo.zone/logos/usepanda/usepanda-icon.svg" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="seaborn" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer"> 
<img src="https://geopandas.org/en/stable/_images/geopandas_icon_green.png" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<h3 align="left">Data Visualization Tools: </h3>
<img src="https://www.vectorlogo.zone/logos/plot_ly/plot_ly-official.svg" alt="plotly2" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<img src="https://www.vectorlogo.zone/logos/w3_html5/w3_html5-icon.svg" alt="html" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap2" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer"> 
<br>

<!-- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// //-->
 

<h1 align="center" href="https://medium.com/towards-data-science/covid-19-coronavirus-top-ten-most-affected-countries-c165171c50d7" > Data Analysis of the COVID-19 pandemic in North America </h1>


<a href="https://medium.com/towards-data-science/covid-19-coronavirus-top-ten-most-affected-countries-c165171c50d7" target="blank"><img height="460" width="460" align="right" src="https://miro.medium.com/max/720/1*y6hjg5o-HRnvJX3peoJR3w.webp" /></a>

<h3 align="left">Summary:</h3>
An in-depth look at the spread of covid-19 in North America

<h3 align="left">Check it here:</h3>
<a href="https://medium.com/towards-data-science/covid-19-coronavirus-top-ten-most-affected-countries-c165171c50d7" target="blank"><img align="left" src="https://www.vectorlogo.zone/logos/medium/medium-tile.svg" alt="diegohurtadoo" height="30" width="40" /></a>
<br>
<h3 align="left">Languages:</h3>
<a href="" target="blank"><img align="left" src="https://www.vectorlogo.zone/logos/python/python-icon.svg" alt="diegohurtadoo" height="30" width="40" /></a>
<a href="" target="blank"><img align="center" src="https://www.vectorlogo.zone/logos/mysql/mysql-icon.svg" alt="diego o'hurtado" height="30" width="40" /></a>
</p>

  
<h3 align="left">Data Science Tools:</h3>

<img src="https://www.vectorlogo.zone/logos/usepanda/usepanda-icon.svg" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="seaborn" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer"> 
<img src="https://matplotlib.org/3.1.1/_static/logo2_compressed.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<img src="https://geopandas.org/en/stable/_images/geopandas_icon_green.png" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">


<h3 align="left">Data Visualization Tools: </h3>

<img src="https://www.vectorlogo.zone/logos/plot_ly/plot_ly-official.svg" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer"> 
<img src="https://www.vectorlogo.zone/logos/w3_html5/w3_html5-icon.svg" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer"> 
 
 <!-- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// //-->
 
<h1 align="center" href="https://github.com/DiegoHurtad0/Data-Exploration-on-Amsterdam-Airbnb" > Data Exploration on Amsterdam Airbnb </h1>


<a href="https://medium.com/towards-data-science/covid-19-coronavirus-top-ten-most-affected-countries-c165171c50d7" target="blank"><img height="460" width="460" align="right" src="https://github.com/DiegoHurtad0/Data-Exploration-on-Amsterdam-Airbnb/blob/main/figures/app.png?raw=true" /></a>

<h3 align="left">Summary:</h3>
Data Exploration on Amsterdam Airbnb

<h3 align="left">Check it here:</h3>
<a href="https://github.com/DiegoHurtad0/Data-Exploration-on-Amsterdam-Airbnb" target="blank"><img align="left" src="https://www.vectorlogo.zone/logos/medium/medium-tile.svg" alt="diegohurtadoo" height="30" width="40" /></a>
<br>
<h3 align="left">Languages:</h3>
<a href="" target="blank"><img align="left" src="https://www.vectorlogo.zone/logos/python/python-icon.svg" alt="diegohurtadoo" height="30" width="40" /></a>
<a href="" target="blank"><img align="center" src="https://www.vectorlogo.zone/logos/mysql/mysql-icon.svg" alt="diego o'hurtado" height="30" width="40" /></a>
</p>

  
<h3 align="left">Data Science Tools:</h3>

<img src="https://www.vectorlogo.zone/logos/usepanda/usepanda-icon.svg" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="seaborn" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer"> 
<img src="https://matplotlib.org/3.1.1/_static/logo2_compressed.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<img src="https://geopandas.org/en/stable/_images/geopandas_icon_green.png" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">


<h3 align="left">Data Visualization Tools: </h3>

<img src="https://www.vectorlogo.zone/logos/plot_ly/plot_ly-official.svg" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer"> 
<img src="https://www.vectorlogo.zone/logos/w3_html5/w3_html5-icon.svg" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer"> 
 
 <!-- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// //-->

<h1 align="center" href="https://github.com/DiegoHurtad0/USA-Traveling-Salesman-Tour" > Traveling Salesperson Problem </h1>


<a href="https://medium.com/towards-data-science/covid-19-coronavirus-top-ten-most-affected-countries-c165171c50d7" target="blank"><img height="460" width="460" align="right" src="https://github.com/DiegoHurtad0/USA-Traveling-Salesman-Tour/raw/main/output/USATravelingSalesmanProblem.png?raw=true?raw=true" /></a>

<h3 align="left">Summary:</h3>
Efficient route planning for travelling salesman problem for 48 USA States

<h3 align="left">Check it here:</h3>
<a href="https://medium.com/towards-data-science/covid-19-coronavirus-top-ten-most-affected-countries-c165171c50d7" target="blank"><img align="left" src="https://www.vectorlogo.zone/logos/medium/medium-tile.svg" alt="diegohurtadoo" height="30" width="40" /></a>
<br>
<h3 align="left">Languages:</h3>
<a href="" target="blank"><img align="left" src="https://www.vectorlogo.zone/logos/python/python-icon.svg" alt="diegohurtadoo" height="30" width="40" /></a>
<a href="" target="blank"><img align="center" src="https://www.vectorlogo.zone/logos/mysql/mysql-icon.svg" alt="diego o'hurtado" height="30" width="40" /></a>
</p>

  
<h3 align="left">Data Science Tools:</h3>

<img src="https://www.vectorlogo.zone/logos/usepanda/usepanda-icon.svg" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="seaborn" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer"> 
<img src="https://matplotlib.org/3.1.1/_static/logo2_compressed.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<img src="https://geopandas.org/en/stable/_images/geopandas_icon_green.png" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">


<h3 align="left">Data Visualization Tools: </h3>

<img src="https://www.vectorlogo.zone/logos/plot_ly/plot_ly-official.svg" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer"> 
<img src="https://www.vectorlogo.zone/logos/w3_html5/w3_html5-icon.svg" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer"> 
 
 <!-- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// //-->
 
 
 
 <h1 align="left"> Machine Learning Regression Models From Scratch in Python </h1>
 

<a href="https://github.com/DiegoHurtad0/Linear-Regression-Model-Representation-Implementation-From-Scratch-using-Python" target="blank"><img height="460" width="460" align="right" src="https://miro.medium.com/v2/resize:fit:4800/format:webp/1*JvGyX0soGjUNgUPZfoU6eQ.png" /></a>

<h3 align="left">Summary:</h3>

▪️ XGBoostRegressor
 
▪️ RandomForestRegressor
 
▪️ DecisionTreeRegressor
 
<h3 align="left">Check it here:</h3>
<a href="https://github.com/DiegoHurtad0/Linear-Regression-Model-Representation-Implementation-From-Scratch-using-Python" target="blank"><img align="left" src="https://www.vectorlogo.zone/logos/github/github-tile.svg" alt="diegohurtadoo" height="30" width="40" /></a>
<a href="https://medium.com/@diego.hurtado.olivares/linear-regression-from-scratch-15bfd15dc2e" target="blank"><img align="left" src="https://www.vectorlogo.zone/logos/medium/medium-tile.svg" alt="diegohurtadoo" height="30" width="40" /></a>
<br>
</p>
 
<h3 align="left">Languages:</h3>
<a href="" target="blank"><img align="left" src="https://www.vectorlogo.zone/logos/python/python-icon.svg" alt="diegohurtadoo" height="30" width="40" /></a>
<br>
</p>
<h3 align="left">Data Science Tools:</h3>
Numpy
<img src="https://www.vectorlogo.zone/logos/usepanda/usepanda-icon.svg" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">

<br>
<br>
<!-- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// //-->

 <h1 align="left"> Machine Learning Classifiers Models From Scratch in Python </h1>
 

<a href="https://github.com/DiegoHurtad0/Linear-Regression-Model-Representation-Implementation-From-Scratch-using-Python" target="blank"><img height="460" width="460" align="right" src="https://raw.githubusercontent.com/DiegoHurtad0/Machine-Learning-Classifiers-From-Scratch/main/LSTMClassifier/figures/LSTMClassifier.png" /></a>

<h3 align="left">Summary:</h3>
▪️ Long Short-Term Memory (LSTM) Classifier
 
<h3 align="left">Check it here:</h3>
<a href="https://github.com/DiegoHurtad0/Linear-Regression-Model-Representation-Implementation-From-Scratch-using-Python" target="blank"><img align="left" src="https://www.vectorlogo.zone/logos/github/github-tile.svg" alt="diegohurtadoo" height="30" width="40" /></a>
<br>
</p>
 
<h3 align="left">Languages:</h3>
<a href="" target="blank"><img align="left" src="https://www.vectorlogo.zone/logos/python/python-icon.svg" alt="diegohurtadoo" height="30" width="40" /></a>
<br>
</p>
<h3 align="left">Data Science Tools:</h3>
Numpy
<img src="https://www.vectorlogo.zone/logos/usepanda/usepanda-icon.svg" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">

<br>
<br>
<!-- //////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////// //-->

<br>
<h1 align="center" href="https://medium.com/towards-data-science/make-a-covid-19-choropleth-map-in-mapbox-5c93ac86e907"> Covid 19 Choropleth Map </h1>
<p>
  <a href="https://github.com/DiegoHurtad0/Covid-19-Choropleth-Map"><img width="500" height="450" align='right' src="https://miro.medium.com/max/4800/1*UIL5MxvErJUOm35MwAL4Fw.webp?raw=true"></a>
</p>
▪️ How to Make a Covid-19 Choropleth Map in Mapbox
<h3 align="left">Check it here:</h3>
<a href="https://github.com/DiegoHurtad0/Covid-19-Choropleth-Map" target="blank"><img align="left" src="https://www.vectorlogo.zone/logos/github/github-tile.svg" alt="diegohurtadoo" height="30" width="40" /></a>
<a href="https://medium.com/towards-data-science/make-a-covid-19-choropleth-map-in-mapbox-5c93ac86e907" target="blank"><img align="left" src="https://www.vectorlogo.zone/logos/medium/medium-tile.svg" alt="diegohurtadoo" height="30" width="40" /></a>
<br>
<h3 align="left">Languages:</h3>
<a href="" target="blank"><img align="left" src="https://www.vectorlogo.zone/logos/w3_html5/w3_html5-icon.svg" alt="diegohurtadoo" height="30" width="40" /></a>
<br>
<h3 align="left">Data Visualization Tool:</h3>
<img src="https://www.vectorlogo.zone/logos/mapbox/mapbox-icon.svg" alt="plotly" width="40" height="40"/> </a> <a href="" target="_blank" rel="noreferrer">

<!-- //////////////////////////////////////////////////////////////////////////////////// //-->

<br>
<br>
<br>
<br>
<br>
<br>

<img align="center" src="https://raw.githubusercontent.com/DiegoHurtad0/Covid-19-Dataset-Mexico/master/wave.svg" />

