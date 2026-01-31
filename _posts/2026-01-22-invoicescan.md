---
title: "InvoiceScan: AI-Powered Invoice Processing"
date: 2026-01-22 12:00:00 +0100
categories: [Application, Project]
tags: [ocr, invoice-processing, vision-llm, fastapi]
description: "An invoice processing system that uses AI vision models to detect invoices and extract structured data including date, amount, and currency."
author: aaron
image:
  path: /assets/img/invoicescan.jpg
  alt: Placeholder
pin: true
---

### 🎯 Goals

**Build an AI-powered invoice processing system** using vision-based Large Language Models.

Focus:
1. **Invoice Detection** — Classify images as invoices or non-invoices
2. **Data Extraction** — Extract structured fields (date, total, currency)
3. **Multi-Backend Support** — Cloud (OpenRouter) and local inference (Ollama, Llama.cpp)

---

### 🚀 Key Contributions

1. **Vision-Based Invoice Detection** — JSON schema-validated classification using multimodal LLMs
2. **Structured Data Extraction** — Handles German date formats, various currencies, and formatting variations
3. **Unified Backend Architecture** — Single Backend class supporting OpenRouter, Ollama, and Llama.cpp backends
4. **Dual Interfaces** — FastAPI web server with web UI + CLI tool for invoice processing
5. **Comprehensive Testing** — 28 passing unit tests covering backends, API, and CLI

---

### 📊 Results

- **Functional Invoice Pipeline** — Successfully detects invoices and extracts date, amount, and currency in ISO formats
- **Flexible Deployment** — Works with cloud APIs (OpenRouter) or fully local inference (Ollama, Llama.cpp)
- **Production-Ready Web UI** — Browser-based interface for easy invoice processing
- **Verified Quality** — Full test suite with 28 passing tests

---

### 🛠 Tech Stack

| Area              | Tools & Frameworks                                                                 |
| ----------------- | ---------------------------------------------------------------------------------- |
| **Languages**     | Python 3.x                                                                         |
| **Web Framework** | FastAPI, Uvicorn, python-multipart                                                 |
| **ML/AI**         | OpenAI SDK (OpenRouter, Ollama, Llama.cpp compatibility)                           |
| **Testing**       | pytest (28 tests)                                                                  |
| **Models**        | Vision LLMs (model-agnostic via OpenAI-compatible API)                             |
| **Repository**    | [github.com/aaronkossler/invoicescan](https://github.com/aaronkossler/invoicescan) |

---

> **Takeaway:** InvoiceScan demonstrates how vision-based LLMs can automate document processing tasks, offering both cloud and fully local deployment options.
{: .prompt-tip }
