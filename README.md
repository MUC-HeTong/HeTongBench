# HeTongBench

**HeTongBench: An Open Benchmark Suite for Multilingual, Multimodal, and Low-Resource Foundation Models**

**和同评测基准体系**

*和而不同，智联万语。 — Harmony in Diversity, Intelligence Across Languages.*

[中文文档](./README_zh.md) · [HeTong Model Family](https://github.com/MUC-HeTong/HeTong) · [HeTongEval](https://github.com/MUC-HeTong/HeTongEval)

> **Project status: Planning / Repository scaffolding.** No benchmark datasets, evaluation code, scores, or official leaderboard results are released in this repository yet.

## Overview

HeTongBench is the planned open benchmark suite within the **HeTong** ecosystem. It will focus on multilingual and multimodal foundation model capabilities, particularly low-resource languages, cultural understanding, and reproducible evaluation.

**HeTongBench defines evaluation benchmarks and their documentation.** **HeTongEval** is the separate evaluation and monitoring platform intended to execute evaluations. **HeTongRank** is the planned public leaderboard.

## Planned Benchmark Areas

| Area | Focus |
| --- | --- |
| Text and multilingual reasoning | Understanding, generation, and cross-lingual reasoning |
| Vision-language | Multimodal perception and reasoning |
| Speech and audio | Speech recognition and audio-language understanding |
| Machine translation | Low-resource and cross-lingual translation |
| Agents | Tool use and multi-step task completion |
| Safety and cultural understanding | Reliability, cultural context, and responsible behavior |

Initial research priorities include Tibetan, Mongolian, Uyghur, and other underrepresented languages. Exact language coverage, language varieties, tasks, and supported modalities will be specified when the benchmark resources are released.

## Repository Structure

| Path | Intended use |
| --- | --- |
| `README.md` | English project overview |
| `README_zh.md` | Chinese project overview |
| `docs/` | Benchmark methodology and governance documentation |
| `benchmarks/` | Future benchmark specifications and resource descriptions |
| `languages/` | Language coverage and writing-system documentation |
| `tasks/` | Future task definitions and evaluation protocols |
| `metadata/` | Dataset metadata and versioning documentation |
| `reports/` | Future benchmark analyses and reports |

At present, the directories above contain placeholder files only. Their presence does not indicate that datasets or evaluation tasks are available.

## Guiding Principles

- **Reproducibility:** Document dataset and metric versions, prompts, and evaluation settings when released.
- **Language coverage:** State language varieties, scripts, and annotation conventions explicitly.
- **Data governance:** Review licensing, privacy, consent, and potential dataset contamination before publication.
- **Responsible comparison:** Avoid unsupported cross-task aggregate rankings or misleading claims.

## Roadmap

- [x] Initialize the public repository and documentation layout
- [ ] Publish benchmark design and language coverage specifications
- [ ] Release reviewed benchmark resources with suitable licenses
- [ ] Integrate supported tasks with HeTongEval
- [ ] Publish verified evaluations and reports

## Related Projects

- [HeTong Model Family](https://github.com/MUC-HeTong/HeTong)
- [HeTongEval — Evaluation and Monitoring](https://github.com/MUC-HeTong/HeTongEval)
- [HeTongRank — Planned Leaderboards](https://github.com/MUC-HeTong/HeTongRank)

---

**HeTongBench — 和而不同，智联万语。**
