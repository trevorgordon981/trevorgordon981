# Trevor Gordon

Senior Technical Customer Success Manager for developer and infrastructure tooling. Previously Coder, Grafana Labs, and F5/NGINX. Based in San Diego.

I run a self-hosted AI assistant called Alfred in production at home. It serves Qwen3.5-397B (MoE) through MLX on a Mac Studio, with prefix caching that cut time-to-first-token by 8.8x. Retrieval and voice run on a multi-node NVIDIA DGX Spark k3s cluster. The RAG pipeline is built from scratch: LanceDB dense vectors and Tantivy BM25 fused with reciprocal rank fusion, a fine-tuned Qwen3-Embedding-8B, and a Qwen3-Reranker-8B cross-encoder. The stack is instrumented end to end with OpenTelemetry, Prometheus, and Grafana.

- [alfred-rag](https://github.com/trevorgordon981/alfred-rag) - hybrid retrieval server and embedding fine-tuning recipe
- [alfred-infra](https://github.com/trevorgordon981/alfred-infra) - monitoring, backup, and network hardening for the cluster
- [context-bench](https://github.com/trevorgordon981/context-bench) - context-window throughput benchmark for local serving endpoints
- [gordon-gateway](https://github.com/trevorgordon981/gordon-gateway) - LLM gateway with routing, tool-call translation, and OTLP tracing
- [Local AI Stack Saga](https://alooftwaffle.substack.com) - writing about building and running all of it
