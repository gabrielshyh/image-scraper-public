<!-- image-scraper Public README -->
<!-- Formatted following marklovestech GitHub repository layout -->

<div align="center">

# image-scraper

**A high-efficiency OCR and text formatting pipeline that converts images into structured Markdown for OpenRouter LLMs.**

![platform](https://img.shields.io/badge/platform-Node.js-lightgrey)
![language](https://img.shields.io/badge/JavaScript-ES6%2B-yellow)
![api](https://img.shields.io/badge/API-Google%20Cloud%20Vision-blue)
![status](https://img.shields.io/badge/status-active%20development-yellow)

</div>

---

## What it does

Passing raw image files directly to multimodal vision LLMs is inefficient, consuming massive token counts and API credits on repetitive visual processing. 

`image-scraper` is a specialized pre-processing pipeline that combines **Google Cloud Vision OCR** with advanced text formatters (**Docling** / **MarkItDown**). It ingests document, receipt, and menu images, extracts raw text with computer vision, and transforms messy layout blocks into clean, structured Markdown feeds. By replacing expensive vision tokens with compact Markdown, `image-scraper` enables OpenRouter LLMs to reason and make decisions with maximum accuracy and cost efficiency.

## Highlights

- **Google Cloud Vision OCR.** High-accuracy text detection across complex visual documents, receipts, and multi-column menus.
- **Structured Markdown Formatting.** Converts raw computer vision OCR outputs into clean, semantically structured Markdown using Docling / MarkItDown.
- **Token & Credit Optimization.** Strips visual bloat to minimize token consumption and reduce API credit usage for OpenRouter LLMs.
- **LLM & Agent Ready.** Produces optimized Markdown context feeds designed for seamless ingestion by AI agents and LLM decision engines.

## Tech Stack

| Layer | Technology |
|---|---|
| **Runtime** | Node.js (ES Modules) |
| **Vision OCR** | Google Cloud Vision API |
| **Text Formatter** | Docling / MarkItDown |
| **Target LLM Platform** | OpenRouter LLMs & AI Agents |

## Status

**In active development now, beta version coming soon!**

## Why the source is private

This repo is a public-facing description of a working application. The full implementation lives in a private repository. If you are a collaborator, recruiter, or fellow builder who would like a deeper look into the codebase—please reach out below.

## Contact

**Gabriel Shyh** — [@gabrielshyh](https://github.com/gabrielshyh) · [gabrielsshyh2006@gmail.com](mailto:gabrielsshyh2006@gmail.com)