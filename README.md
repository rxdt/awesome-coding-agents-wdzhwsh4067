# Awesome Coding Agents

> A curated list of resources on LLM-based coding agents, software engineering benchmarks, harness design, workflow integration, and open-source systems.

This repository is a lightweight, public-facing resource hub inspired by "awesome list" style repositories. It focuses on the ecosystem around coding agents rather than on any single paper draft or unpublished manuscript.

## What This List Covers

- Repository-level coding agents
- Software engineering benchmarks and evaluation realism
- Harness and scaffold design
- Workflow-native development surfaces such as issues, pull requests, reviews, and CI
- Open-source tools, official engineering write-ups, and representative academic papers

## Why This Repo Exists

The coding-agent landscape is changing quickly. Progress now depends not only on raw model quality, but also on repository context, tool access, verification loops, and workflow integration. This list organizes resources around that systems view.

## Contents

- [Surveys and Roadmaps](#surveys-and-roadmaps)
- [Benchmarks and Evaluation](#benchmarks-and-evaluation)
- [Harness and Repository-Aware Design](#harness-and-repository-aware-design)
- [Workflow-Native Products and Systems](#workflow-native-products-and-systems)
- [Open-Source Projects](#open-source-projects)
- [Selected Software Engineering Papers](#selected-software-engineering-papers)
- [Contributing](#contributing)

## Surveys and Roadmaps

- [AI Agentic Programming: A Survey of Techniques, Challenges, and Opportunities](https://arxiv.org/abs/2508.11126)
- [A Comprehensive Survey on Benchmarks and Solutions in Software Engineering of LLM-Empowered Agentic System](https://arxiv.org/abs/2510.09721)
- [Agentic Software Engineering: Foundational Pillars and a Research Roadmap](https://arxiv.org/abs/2509.06216)

## Benchmarks and Evaluation

### Coding-agent benchmarks

- [SWE-bench: Can Language Models Resolve Real-World GitHub Issues?](https://openreview.net/forum?id=VTF8yNQM66)
- [SWE-agent: Agent-Computer Interfaces Enable Automated Software Engineering](https://proceedings.neurips.cc/paper_files/paper/2024/hash/5a7c947568c1b1328ccc5230172e1e7c-Abstract-Conference.html)
- [Introducing SWE-bench Verified](https://openai.com/index/introducing-swe-bench-verified/)
- [Why SWE-bench Verified No Longer Measures Frontier Coding Capabilities](https://openai.com/index/why-we-no-longer-evaluate-swe-bench-verified/)
- [SWE-rebench: An Automated Pipeline for Task Collection and Decontaminated Evaluation of Software Engineering Agents](https://openreview.net/forum?id=nMpJoVmRy1)
- [BigCodeBench: Benchmarking Code Generation with Diverse Function Calls and Complex Instructions](https://openreview.net/forum?id=YrycTjllL0)
- [MLE-bench: Evaluating Machine Learning Agents on Machine Learning Engineering](https://openai.com/index/mle-bench/)

### Practical evaluation questions

- Task realism and underspecification
- Environment setup and dependency reproducibility
- Harness sensitivity and scaffold variance
- Test quality, leakage, and contamination
- Workflow realism beyond isolated patch generation

## Harness and Repository-Aware Design

- [RepoCoder: Repository-Level Code Completion Through Iterative Retrieval and Generation](https://aclanthology.org/2023.emnlp-main.151/)
- [Repoformer: Selective Retrieval for Repository-Level Code Completion](https://proceedings.mlr.press/v235/wu24a.html)
- [Repo2Run: Automated Building Executable Environment for Code Repository at Scale](https://openreview.net/forum?id=fZsd3KLMje)
- [Monitor-Guided Decoding of Code LMs with Static Analysis of Repository Context](https://proceedings.neurips.cc/paper_files/paper/2023/hash/662b1774ba8845fc1fa3d1fc0177ceeb-Abstract-Conference.html)
- [Harness Engineering: Leveraging Codex in an Agent-First World](https://openai.com/index/harness-engineering/)
- [Harness Design for Long-Running Application Development](https://www.anthropic.com/engineering/harness-design-long-running-apps)

## Workflow-Native Products and Systems

### Official docs and product notes

- [About GitHub Copilot Coding Agent](https://docs.github.com/en/copilot/concepts/coding-agent/about-copilot-coding-agent)
- [Pick Your Agent: Use Claude and Codex on Agent HQ](https://github.blog/news-insights/company-news/pick-your-agent-use-claude-and-codex-on-agent-hq/)
- [Claude Code](https://www.anthropic.com/product/claude-code)
- [Jules: Build with Your Asynchronous Coding Agent](https://blog.google/innovation-and-ai/models-and-research/google-labs/jules/)
- [Jules Documentation](https://jules.google/docs/)
- [Jules Environment Setup](https://jules.google/docs/environment)
- [Cognition Devin](https://cognition.ai/)
- [Cursor Changelog](https://www.cursor.com/changelog)
- [Windsurf Cascade Overview](https://docs.windsurf.com/windsurf/cascade/cascade)
- [Windsurf Editor Changelog](https://windsurf.com/changelog)
- [Introducing GPT-5.2-Codex](https://openai.com/index/introducing-gpt-5-2-codex/)
- [Introducing GPT-5.3-Codex](https://openai.com/index/introducing-gpt-5-3-codex/)

### Workflow surfaces worth tracking

- Issue intake and triage
- Repository navigation and retrieval
- Local shell and tool execution
- Pull request generation
- Code review follow-up
- CI-aware iteration
- Human approval and governed deployment

## Open-Source Projects

- [OpenHands](https://github.com/OpenHands/OpenHands)
- [Aider](https://github.com/Aider-AI/aider)
- [SWE-bench](https://github.com/SWE-bench/SWE-bench)

## Selected Software Engineering Papers

### Repository-scale and autonomous repair

- [AutoCodeRover: Autonomous Program Improvement](https://2024.issta.org/details/issta-2024-papers/127/AutoCodeRover-Autonomous-Program-Improvement)
- [RepoAudit: An Autonomous LLM-Agent for Repository-Level Code Auditing](https://openreview.net/forum?id=TXcifVbFpG)
- [A Deep Dive into Large Language Models for Automated Bug Localization and Repair](https://2024.esec-fse.org/details/fse-2024-research-papers/17/A-Deep-Dive-into-Large-Language-Models-for-Automated-Bug-Localization-and-Repair)
- [ConDefects: A Complementary Dataset to Address the Data Leakage Concern for LLM-based Fault Localization and Program Repair](https://2024.esec-fse.org/details/fse-2024-demonstrations/20/ConDefects-A-Complementary-Dataset-to-Address-the-Data-Leakage-Concern-for-LLM-based)

### Testing, verification, and reliability

- [Oracle-Guided Program Selection from Large Language Models](https://2024.issta.org/details/issta-2024-papers/51/Oracle-Guided-Program-Selection-from-Large-Language-Models)
- [UniTSyn: A Large-Scale Dataset Capable of Enhancing the Prowess of Large Language Models for Program Testing](https://2024.issta.org/details/issta-2024-papers/85/UniTSyn-A-Large-Scale-Dataset-Capable-of-Enhancing-the-Prowess-of-Large-Language-Mod)
- [Large Language Models for Equivalent Mutant Detection: How Far Are We?](https://2024.issta.org/details/issta-2024-papers/138/Large-Language-Models-for-Equivalent-Mutant-Detection-How-Far-Are-We-)
- [Towards AI-Assisted Synthesis of Verified Dafny Methods](https://2024.esec-fse.org/details/fse-2024-research-papers/75/Towards-AI-Assisted-Synthesis-of-Verified-Dafny-Methods)
- [Can Large Language Models Transform Natural Language Intent into Formal Method Postconditions?](https://2024.esec-fse.org/details/fse-2024-research-papers/51/Can-Large-Language-Models-Transform-Natural-Language-Intent-into-Formal-Method-Postco)

### Broader SE tasks

- [CoderUJB: An Executable and Unified Java Benchmark for Practical Programming Scenarios](https://2024.issta.org/details/issta-2024-papers/11/CoderUJB-An-Executable-and-Unified-Java-Benchmark-for-Practical-Programming-Scenario)
- [LPR: Large Language Models-Aided Program Reduction](https://2024.issta.org/details/issta-2024-papers/22/LPR-Large-Language-Models-Aided-Program-Reduction)
- [Software Model Evolution with Large Language Models](https://arxiv.org/abs/2406.17651)
- [Leveraging Large Language Models for the Auto-remediation of Microservice Applications](https://2024.esec-fse.org/details/fse-2024-industry/34/Leveraging-Large-Language-Models-for-the-Auto-remediation-of-Microservice-Application)

## Suggested Reading Paths

- If you care about benchmarks: start with SWE-bench, SWE-agent, SWE-bench Verified, and SWE-rebench.
- If you care about system design: read RepoCoder, Repoformer, Repo2Run, and the harness engineering write-ups.
- If you care about product direction: compare GitHub Agent HQ, Claude Code, Jules, Codex, Cursor, Windsurf, OpenHands, and Aider.
- If you care about software engineering impact: focus on evaluation realism, repository legibility, review loops, and CI integration.

## Contribution Principles

- Prefer primary sources over summaries.
- Distinguish benchmark evidence from product claims.
- Add links that are likely to remain stable.
- Keep descriptions short and neutral.
- Avoid vendor marketing language when a paper or doc can say it more precisely.

## Contributing

Suggestions and pull requests are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

[MIT](LICENSE)
