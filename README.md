# Local AI Benchmarks

## Purpose

This repository documents performance benchmarks for running large language models (LLMs) and other AI models locally. It provides structured comparisons across different hardware platforms, runtimes, and configuration settings to help identify optimal setups for local AI inference.

## Benchmark Scope

Benchmarks cover the following dimensions:

- **Model**: Architecture, size, and capability of the AI models tested.
- **Runtime / Backend**: The inference engine (e.g., llama.cpp, vLLM, Ollama, MLX, TensorRT-LLM) and its configuration.
- **Device**: The hardware platform used for inference (CPU, GPU, NPU, or combination).
- **Accelerator**: Any dedicated inference hardware or acceleration library.

## Fair Comparison Rules

To ensure results are meaningful and comparable:

1. Use consistent model versions and quantizations across all hardware.
2. Report full system configuration (OS, kernel, drivers, power settings).
3. Run each benchmark multiple times and report averages and variance.
4. Control for thermal throttling and power limits.
5. Use identical prompts and batch sizes where applicable.
6. Publish raw data and methodology alongside summaries.

## Current Status

**No inference benchmarks have been run yet.** This repository is being set up with structure, templates, and guidelines for future work.
