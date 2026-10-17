# Kurnia Zulda Matondang

**AI Engineer in Jakarta, building in public.** I build RAG systems, LLM agents, and computer-vision pipelines, and I turn what I learn into small tools I can reuse.

I care about the parts that decide whether an AI feature survives contact with users: measuring retrieval quality, tracking latency and cost, and keeping the code easy to change.

## My public project: Zul

[**Zul**](https://github.com/kazuma313/zul_utilities) (site: [zulkit.my.id](https://zulkit.my.id)) is where I focus. It is an open-source (MIT) toolkit for AI and data applications in Python, and it is also the one place where everything I do in public lives: the code, the documentation, the blog, my experiments, and my practice. The writing is in Indonesian.

### The toolkit

| Part | What it does |
|---|---|
| **Adapter layer** | Wraps LangChain, OpenCV, RF-DETR, Docling, pymilvus, redisvl, and ragas as small composable functions. Each library is imported in exactly one file, and a test enforces it, so swapping or pinning a library is a one-file change. |
| **Retrieval evaluation** | Measures a retriever with ragas: dataset loading, indexing into Milvus, dense and hybrid retrievers, LLM-as-judge scoring, hit rates, latency percentiles, and Excel reports. |
| **MCP server for code assistants** | Gives Claude Code and similar assistants read-only tools (docs search, module guides, source, runnable examples, a style checker) so the code they write for Zul follows its conventions. |
| **Computer-vision boilerplate** | A complete app starter for camera analytics: RF-DETR detection, my own ByteTrack, per-camera YAML config, line counting, zone and dwell timers, Docker, and tests with a fake detector. |
| **Agent skill pool** | Reusable skills and utilities for learning and research workflows, such as syllabus building and reading material with any vision or OCR model. |

The test suite has more than 600 tests, and GitHub Actions builds and deploys the docs on every docs change.

### Where to find the rest

| I want to see... | Go to |
|---|---|
| Tutorials, how-to guides, reference, and concepts | [zulkit.my.id](https://zulkit.my.id) |
| What I write about and learn | [Blog](https://zulkit.my.id/blog/) |
| Side-by-side comparisons I ran (retrieval evaluation, contextual retrieval, file readers, learning skills) | [`framework/studies`](https://github.com/kazuma313/zul_utilities/tree/main/framework/studies) |
| Algorithm and fundamentals practice written by hand (sorting, string algorithms, probability simulation, stress tests, Python object model) | [`research/latihan`](https://github.com/kazuma313/zul_utilities/tree/main/research/latihan) |
| Small standalone projects | [`research/proyek`](https://github.com/kazuma313/zul_utilities/tree/main/research/proyek) |

## What I work with

| Area | Tools |
|---|---|
| LLMs and agents | LangChain, LangGraph, tool calling, LoRA and QLoRA fine-tuning |
| Retrieval | Hybrid search (BM25 plus dense vectors), Milvus, Elasticsearch, Redis semantic cache, multilingual embeddings, reranking |
| Serving and observability | vLLM, SGLang, LiteLLM, Langfuse, FastAPI, Docker, GitHub Actions |
| Evaluation | Ragas, LLM-as-judge, latency tracking (P50, P95, P99) |
| Computer vision | YOLO and RF-DETR, tracking, OCR, edge deployment, OpenCV |
| Backend | Python, FastAPI, PostgreSQL, MongoDB, hexagonal architecture |

## Contact

[Website](https://zulkit.my.id) · [LinkedIn](https://linkedin.com/in/kurnia-zulda) · [Email](mailto:kurniazuldam@gmail.com)
