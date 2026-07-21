# George Jieh

**AI/ML Engineer & LLM Evaluation Specialist**, Bay Area

Nine years in FINRA/SEC-regulated financial services before pivoting into machine learning. The finance work built systems thinking under regulatory pressure; the AI work is where that thinking goes now that the constraints are open-ended rather than compliance-mandated.

Oracle Tier at Scale AI / Outlier (Aug 2024 - Apr 2025): reviewed and corrected peer annotations as Quality Analyst across twelve RLHF training projects, covering process-supervised code reasoning, multi-turn instruction following, multimodal visual grounding, tool-use accuracy, and adversarial prompt design targeting hallucination and reward hacking. That training data fed pipelines for OpenAI, Anthropic, Google DeepMind, Meta, and Microsoft. Which specific model each project shaped isn't something Scale AI discloses, so I won't claim more precision there than I actually have.

Data science background: BrainStation Data Science Diploma (2023-2024), Google Data Analytics Professional Certificate, and Microsoft Azure AI Engineer / Azure Data Scientist Associate certifications. First place in a Google-sponsored capstone hackathon for a pedestrian-safety scoring model built on 1.9M+ Chicago crime records.

---

## What I'm Building

Everything else on this profile is coursework, a work-in-progress, or something I haven't circled back to yet. These three repos are the ones that actually run, in order of how finished they are.

### 🟢 [MachineRead](https://github.com/georgejieh/MachineRead-Preview) - shipped
Audits any public website for **LLM discoverability** and **agent readiness**: whether AI crawlers can get in, whether the page exposes `llms.txt`, JSON-LD, and MCP/A2A discovery surfaces, and how much of the site a model or an autonomous agent could actually read versus just a human with a browser. FastAPI backend with a 301-test suite, a Next.js/TypeScript dashboard, an OpenAPI 3.1 schema, and a portable Agent Skill package. Runs locally, no API keys, no telemetry. This is the free Essentials tier; a hosted version is planned at [machineread.ai](https://machineread.ai).

`Python` `FastAPI` `Next.js` `TypeScript` `Pydantic` `MCP`

### 🟡 [FreshRSS AI Summarizer](https://github.com/georgejieh/freshrss-ai-summarizer) - works, due for an update
A production-style LLM inference pipeline that pulls financial news out of a FreshRSS feed and summarizes it (sentiment, tickers, market implications), routing through the OpenAI API or a local Ollama model depending on what's available. Cut my own daily news-reading from about an hour to five minutes when I was running it regularly. The prompt schemas it depends on have shifted since I wrote it, so it needs a pass before it's back to fully working order. Flagging that here rather than letting the repo imply otherwise.

`Python` `OpenAI API` `Ollama` `NLP` `Financial Analysis`

### 🟡 [Wine Grape Climate Suitability Model](https://github.com/georgejieh/predicting_grape_suitability_based_on_climate_and_precipitation) - functional, not polished
An end-to-end ML pipeline predicting which grape varietals suit a region's climate, built on 143,000+ wine records and 60+ years of weather data (1961-2016). Scraped Wine Enthusiast ratings myself with a custom Selenium tool to supplement the Kaggle dataset, engineered features around the actual vine growth cycle (budburst, flowering, veraison, harvest), and landed on 56% accuracy with H2O AutoML across a 19-class imbalanced problem: a real result, not a great one. The repo is messier than the other two and the model's accuracy has room to grow, but it's the one I'd point to for seeing a full pipeline, scraping through EDA through a deployed Flask app, in one place.

`Python` `H2O AutoML` `scikit-learn` `Flask` `Selenium` `SMOTE`

More context on all of these, plus the projects that are further from done, is at [georgejieh.dev](https://georgejieh.dev).

---

## Background

- **AI/ML:** LLM evaluation and RLHF, rubric-based grading, chain-of-thought and process supervision, adversarial prompt design, multi-agent orchestration, production inference pipelines
- **Core stack:** Python, SQL, scikit-learn, PyTorch, TensorFlow, H2O AutoML, Flask, FastAPI, Next.js/TypeScript
- **Finance:** Series 7, Series 66, SIE licensed. Nine years at Merrill Lynch and Bank of America in wealth management and branch operations, also where the finance-domain grounding for AI evaluation work comes from
- **Education:** UC Berkeley (BA, American Studies), BrainStation (Data Science Diploma), Google Data Analytics Professional Certificate

## Looking For

Open to AI/ML developer and research roles. Also available for freelance AI training, evaluation, and annotation work on weekends.

## Elsewhere

[Portfolio](https://georgejieh.dev) · [LinkedIn](https://www.linkedin.com/in/george-jieh/) · [Hugging Face](https://huggingface.co/ColdAshSage) · [Email](mailto:contact@georgejieh.dev)
