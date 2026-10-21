# Trevor Gordon

Senior Technical Customer Success Manager for developer and infrastructure tooling. Previously Coder, Grafana Labs, and F5/NGINX. Based in San Diego.
I build and operate Alfred, a self-hosted AI assistant running DeepSeek V4.1 Flash-1017 through oMLX/MLX on a 512 GB M3 Ultra Mac Studio, with multi-token prediction and in-memory prefix caching. Hermes handles agent workflows and messaging, while my Gordon Gateway provides model routing, API compatibility, tool-call translation, and tracing. Voice synthesis runs locally with Fish S2-Pro, and Home Assistant connects Alfred to household devices and automations.

The wider infrastructure includes a multi-node NVIDIA DGX Spark k3s cluster and Synology NAS. I’ve built a custom hybrid retrieval pipeline combining LanceDB dense vectors, Tantivy BM25, reciprocal rank fusion, fine-tuned Qwen3 embeddings, and cross-encoder reranking. I use OpenTelemetry, Prometheus, and Grafana for tracing and monitoring, alongside custom benchmarks for model behavior, tool use, and serving performance.

- [alfred-rag](https://github.com/trevorgordon981/alfred-rag) - hybrid retrieval, cross-encoder reranking, and embedding fine-tuning
- [alfred-infra](https://github.com/trevorgordon981/alfred-infra) - cluster monitoring, encrypted backups, health checks, and network hardening
- [context-bench](https://github.com/trevorgordon981/context-bench) - context-window benchmarks for latency, decode throughput, reasoning output, and memory pressure
- [gordon-gateway](https://github.com/trevorgordon981/gordon-gateway) - LLM routing, API and tool-call translation, and OpenTelemetry tracing
- [Local AI Stack Saga](https://alooftwaffle.substack.com) - writing about building and operating the stack
