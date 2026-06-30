# Enverge.ai Labs

**Greener, cheaper AI infrastructure — built for researchers, not datacenter overhead.**

We run GPU workloads on renewable, excess, wasted and stranded energy; ship devtools that feel like a local workstation; and publish open playgrounds for LLMs, RAG, and context research.

> [!TIP]
> **DGX Spark Cloud**
>
> Your own GB10 rig in the cluster — SSH, Docker, full CUDA stack; not a time-shared notebook sandbox.
>
> Dedicated **NVIDIA DGX Spark** (GB10, 128 GB unified memory). Bare-metal **SSH**, **Docker**, **CUDA 12.8**
>
> **[Reserve your instance now → spark.enverge.ai](https://spark.enverge.ai/)**

---

### Experiments

| | What it is | Link |
|---|------------|------|
| **Enverge Lab** | Git-native Python notebooks → production apps in one click. Pay only for training time. | [enverge.ai](https://enverge.ai/) |
| **Enverge CLI** | Self-serve GPU access from your terminal. | [`enverge-cli`](https://github.com/Enverge-Labs/enverge-cli) |

---

### Open source

Research tools, starters, and demos we use in the wild:

- [**evergreen-context-rot**](https://github.com/Enverge-Labs/evergreen-context-rot) — Interactive extension of [Chroma’s Context Rot](https://research.trychroma.com/context-rot) report; run on Ollama models locally.
- [**LLM-Playground**](https://github.com/Enverge-Labs/LLM-Playground) — Experiments and notebooks for LLM workflows.
- [**Memory-Context-and-RAG-Comparison-Tool**](https://github.com/Enverge-Labs/Memory-Context-and-RAG-Comparison-Tool) — Compare memory, context, and RAG setups side by side.
- [**starter**](https://github.com/Enverge-Labs/starter) / [**starter-with-ollama**](https://github.com/Enverge-Labs/starter-with-ollama) — Quickstarts for Enverge Lab and local Ollama.

---

### Why Enverge?

- **100% green energy** — workloads powered by renewables, often surplus capacity.
- **Research-first pricing** — DGX Spark from ~$0.48/hr vs typical H100/H200 hourly rates.
- **SSH-native** — `ssh` into real GPU hardware; no opaque notebook sandboxes required.
- **Blackwell-ready** — develop on GB10 (SM 10.0) before you commit to enterprise clusters.

---

### Writing

Field notes on green GPU infra, LLMs, RAG & context research.

[![Substack](https://img.shields.io/badge/substack-subscribe-ff6719?style=for-the-badge)](https://enverge.substack.com)
[![Blog](https://img.shields.io/badge/blog-enverge.ai-10b981?style=for-the-badge)](https://spark.enverge.ai/blog)

From [spark.enverge.ai/blog](https://spark.enverge.ai/blog):

- **[How fast is the DGX Spark, really? Prefill vs. decode, and the 273 GB/s wall](https://spark.enverge.ai/blog/dgx-spark-prefill-vs-decode)** — Why DGX Spark decode tops out around 3 tok/s on dense 70B models — and why prefill, MoE models, and batched serving tell a very different story.
- **[The Cheapest Way to Run a 70B Model Locally in 2026](https://spark.enverge.ai/blog/cheapest-way-to-run-a-70b-model-locally)** — The cheapest way to run a 70B model locally, compared: DGX Spark, GB10 clones, Mac Studio, RTX 5090, and cloud rental — with specs, prices, and break-even math.
- **[How (and Why) to Quantize LLMs on NVIDIA DGX Spark](https://spark.enverge.ai/blog/quantize-llms-on-dgx-spark)** — Quantize LLMs on NVIDIA DGX Spark using NVFP4, FP8, and GGUF. Step-by-step calibration, evaluation, and tradeoffs for Llama 3.1 70B — under $2 of compute.
- **[Running Research Experiments on DGX Spark: Why Smaller VRAM Can Be Cheaper for Iterative AI](https://spark.enverge.ai/blog/running-research-experiments-dgx-spark-vram-vs-cost)** — Why H100s are overkill for iterative research — and how DGX Spark at $0.65/hr lets you run 5–8x more experiment variants for the same budget.
- **[Run AI Agents Locally: OpenClaw, Local LLMs, and Why the Cloud Should Be Yours](https://spark.enverge.ai/blog/run-ai-agents-locally-openclaw-local-llm)** — Why building AI agents on API calls is expensive and insecure — and how running OpenClaw with local LLMs on Spark Cloud keeps your data private while cutting costs by half.

---

### Links

[![DGX Spark Cloud](https://img.shields.io/badge/DGX%20Spark%20Cloud-spark.enverge.ai-0a0c10?style=for-the-badge)](https://spark.enverge.ai/)
[![Website](https://img.shields.io/badge/website-enverge.ai-10b981?style=for-the-badge)](https://enverge.ai/)
[![CLI](https://img.shields.io/badge/cli-enverge--cli-10b981?style=for-the-badge)](https://github.com/Enverge-Labs/enverge-cli)

---

<sub>© Enverge Labs · Questions: open an issue or reach us via [enverge.ai](https://enverge.ai/).</sub>