# Awesome-AI-Code-Review-Static-Analysis

## Top AI Code Review & Static Analysis Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on AI Pull Request Reviewers, Static Application Security Testing (SAST), Code Quality Linters & Automated Vulnerability Detection*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Code Review & Static Analysis**. These tools combine deterministic AST/dataflow static analysis (SAST) with LLM-powered pull request reviewers to catch security vulnerabilities, detect code smells, enforce architectural rules, and generate actionable inline fix suggestions.



**Examples** include SonarQube Cloud, Snyk Code, Veracode, Checkmarx, Code Climate, Codacy, Synopsys Coverity, Semgrep, DeepSource, CAST Highlight, and victorkildahl/cra (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for open-source AI PR review bots, multi-language static analysis engines (`Semgrep`, `CodeQL`, `OpenGrep`, `SonarQube Community`), security scanners (`Bandit`, `Gosec`, `Trivy`), and fast linters (`Ruff`, `Biome`, `Oxlint`) — ideal for DevSecOps engineers, open-source maintainers, and software teams building self-hosted code quality pipelines.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global Static Application Security Testing (SAST) and automated code review market is estimated at **$2.5B–$4.2B**, expanding rapidly at a ~18–22% CAGR driven by DevSecOps shift-left adoption and the proliferation of AI-generated code. The sector exhibits a **moderately fragmented and evolving structure**: multi-product enterprise AppSec giants dominate traditional compliance-heavy portfolios, while agile developer-first AI code review and next-gen SAST platforms rapidly capture developer workflows.

## SaaS/Hosted Platforms

| Platform | Company Size (Valuation / Revenue) | Pricing (Starting Paid Tier) | Free Tier / Free Trial Limits | Key Highlights |
| :--- | :--- | :--- | :--- | :--- |
| **[Snyk Code](https://snyk.io)** | **~$7.4B** valuation (~$309M ARR) | $25 / developer / month (Team plan) | **Free Forever**: 100 tests/month for Snyk Code (SAST); unlimited members; 60-day inactivity expiration | Developer-first cloud SAST platform powered by DeepCode AI providing real-time IDE and PR vulnerability detection with automated fix recommendations. |
| **[SonarQube Cloud](https://sonarsource.com)** | **~$4.7B** valuation (~$200M ARR) | $34 / month (100k Lines of Code) | **Free Forever**: Up to 50,000 LOC for private repositories; unlimited LOC for public open-source repositories | Cloud-based continuous code quality and static analysis service supporting 30+ languages with AI CodeFix suggestions, PR decoration, and security hotspots. |
| **[Veracode Static Analysis](https://veracode.com)** | **~$2.5B** valuation (~$280M ARR) | ~$15,000 / year (starts ~$1,250/mo base app tier) | **Free Trial Only**: Custom sales-scoped Proof of Concept (PoC) / 14-day trial for select modules | Enterprise cloud AppSec platform offering binary and source-level SAST, Veracode Fix AI remediation, and compliance reporting across CI/CD pipelines. |
| **[Black Duck Coverity](https://blackduck.com)** | **~$2.1B** acquisition (~$500M ARR) | ~$15,000 / year (~$800–$1,500/dev/yr base tier) | **Free Forever (OSS only)**: Coverity Scan is free for registered open-source projects; commercial SAST is sales-assisted PoC evaluation (14–30 days) | Industrial-grade static analysis engine renowned for deep path-sensitive defect and security vulnerability detection in C/C++, Java, C#, and embedded codebases. |
| **[CodeRabbit](https://coderabbit.ai)** | **~$1.5B** valuation (~$100M ARR) | $24 / developer / month (billed annually) or $30/mo | **Free Tier & 14-Day Trial**: Free plan offers PR summaries; 14-day full free trial of Advanced plan; free Team features for public open-source repos | AI-first pull request review platform delivering line-by-line code walkthroughs, sequence diagrams, AST-verified bug detection, and one-click commit fixes across GitHub and GitLab. |
| **[Checkmarx One](https://checkmarx.com)** | **~$1.15B+** valuation (~$200M ARR) | ~$30,000 / year (~$1,000/dev/yr base SAST tier) | **Free Trial Only**: 14-day sales-guided Proof of Concept (PoC) evaluation; 30-day trial for local developer assist | Cloud-native enterprise application security platform unifying SAST, SCA, IaC security, and AI-guided remediation for complex software portfolios. |
| **[Semgrep Cloud Platform](https://semgrep.dev)** | **~$600M** valuation (~$25M ARR) | $30 / contributor / month (Team plan) | **Free Forever**: Up to 10 contributors, 10 repositories, and 60 AI credits/month; unlimited scans for open source | Managed AppSec platform combining fast syntax-aware static analysis rules with Semgrep Assistant AI for false-positive triage and contextual remediation guidance. |
| **[CAST Highlight](https://castsoftware.com)** | **~$150M** valuation (~$50M ARR) | ~$6,800 / application / year (~$567/mo base tier) | **Free Trial Only**: Guided sandbox workshops & partner assessments; no permanent self-serve free plan | Enterprise software intelligence and maintainability analytics platform measuring technical debt, cloud-readiness, architectural complexity, and engineering velocity. |
| **[Codacy](https://codacy.com)** | **~$70M** valuation (~$8M ARR) | $18 / developer / month (billed annually) or $21/mo | **Free Forever & 14-Day Trial**: Free developer plan for local IDE plugins & unlimited public repos; 14-day free trial of Team tier | Automated cloud code review and quality governance platform aggregating static analysis, security scanning, test coverage, and AI-assisted PR insights. |
| **[DeepSource](https://deepsource.com)** | **~$25M** valuation (~$3M ARR) | $24 / user / month (billed annually) or $30/mo | **Free Forever**: Up to 3 team members, 3 private repositories, and 1,000 PR reviews/month for public open source | Cloud static analysis and code health platform featuring Autofix AI, continuous vulnerability scanning, and automated quality gates for pull requests. |
| **[Code Climate (Qlty Cloud)](https://castsoftware.com)** | **~$20M** valuation (~$5M ARR) | $20 / contributor / month (Qlty Pro plan) | **Free Forever**: 1,000 analysis minutes/month and 100 AI autofixes/month across unlimited public/private repos | Code quality maintainability, duplication checks, automated linting, and AI autofix suggestions (via Qlty Software, spun out from Code Climate). |





## Open-Source GitHub Projects



- **[victorkildahl/cra (Code Review Agent)](https://github.com)**  

  Open-source AI code review CLI and agent workflow built to analyze Git diffs, identify logic flaws and maintainability issues, and deliver structured developer feedback locally or in CI.



- **[Semgrep (`semgrep/semgrep`)](https://github.com)**  

  Lightweight, fast open-source (`LGPL-2.1`) static analysis engine supporting 30+ languages via human-readable YAML patterns that match code structure rather than fragile regex.



- **[Opengrep (`opengrep/opengrep`)](https://github.com)**  

  Community-driven open-source (`LGPL-2.1`) fork of Semgrep committed to keeping full SAST rule capabilities, taint tracking, and cross-file analysis freely available.



- **[PR-Agent / Qodo Merge (`qodo-ai/pr-agent`)](https://github.com)**  

  Leading open-source (`Apache-2.0`) AI-powered pull request reviewer providing automated PR descriptions, code walkthroughs, bug/security detection, and `/improve` suggestions for GitHub, GitLab, and Bitbucket.



- **[SonarQube Community Build (`SonarSource/sonarqube`)](https://github.com)**  

  Widely deployed open-source (`LGPL-3.0`) self-hosted static analysis server for continuous inspection of code quality, bugs, code smells, and security vulnerabilities.



- **[GitHub CodeQL (`github/codeql`)](https://github.com)**  

  Semantic code analysis engine treating code as queryable relational data to uncover complex zero-day vulnerabilities and taint flows (open-source queries and CLI under `MIT` / GitHub CodeQL terms).



- **[CodeAnt AI / Sweep / AI Code Reviewer (`anc95/ChatGPT-CodeReview`)](https://github.com)**  

  Popular open-source (`ISC`) GitHub Action and webhook bot using LLMs to automatically post line-level code review comments and refactoring suggestions on pull requests.



- **[Trivy (`aquasecurity/trivy`)](https://github.com)**  

  Comprehensive open-source (`Apache-2.0`) all-in-one security scanner detecting vulnerabilities, IaC misconfigurations, hardcoded secrets, and SBOM license issues across repositories and containers.



- **[Bearer (`Bearer/bearer`)](https://github.com)**  

  Open-source (`ELv2` / `Apache-2.0`) code security and privacy SAST scanner specialized in dataflow analysis, OWASP Top 10 detection, and sensitive data leak tracking.



- **[Bandit (`PyCQA/bandit`)](https://github.com)**  

  Standard open-source (`Apache-2.0`) AST-based static security linter engineered to find common security issues in Python codebases.



- **[Gosec (`securego/gosec`)](https://github.com)**  

  Open-source (`Apache-2.0`) Go security checker that inspects source code ASTs for SQL injection, weak cryptography, command injection, and unsafe memory patterns.



- **[Brakeman (`presidentbeef/brakeman`)](https://github.com)**  

  Zero-configuration open-source (`MIT`) static analysis security vulnerability scanner built specifically for Ruby on Rails applications.



- **[Ruff (`astral-sh/ruff`)](https://github.com)**  

  Extremely fast open-source (`MIT`) Python linter and code formatter written in Rust consolidating Flake8, Bandit, isort, and pyupgrade static checks at 10–100x speed.



- **[Biome (`biomejs/biome`) & Oxlint (`oxc-project/oxc`)](https://github.com)**  

  Next-generation open-source (`MIT`) Rust-powered linters and static analyzers for JavaScript, TypeScript, JSX, and CSS delivering millisecond CI feedback.



- **[PMD (`pmd/pmd`) & SpotBugs (`spotbugs/spotbugs`)](https://github.com)**  

  Battle-tested open-source (`BSD` / `LGPL`) static code analyzers for Java and JVM languages detecting unused variables, concurrency bugs, null-pointer dereferences, and copy-pasted code (`CPD`).



- **[Cppcheck (`danmar/cppcheck`) & Clang Static Analyzer (`llvm/llvm-project`)](https://github.com)**  

  Essential open-source (`GPL-3.0` / `Apache-2.0`) static analysis tools for C and C++ uncovering memory leaks, out-of-bounds accesses, and undefined behavior without executing code.



- **[Checkov (`bridgecrewio/checkov`) & TFLint (`terraform-linters/tflint`)](https://github.com)**  

  Open-source (`Apache-2.0` / `MPL-2.0`) static analysis tools for Infrastructure-as-Code (`Terraform`, `Kubernetes`, `Dockerfile`, `CloudFormation`) enforcing cloud security policies prior to deployment.



### Additional Strong Open-Source Options



- **[Gitleaks (`gitleaks/gitleaks`)](https://github.com)** and **[TruffleHog (`trufflesecurity/trufflehog`)](https://github.com)** for scanning Git commits and pull requests to prevent leaked API keys, tokens, and credentials.

- **[Qlty CLI (`qltysh/qlty`)](https://github.com)** for a modern, unified open-source multi-language code quality runner and maintainability analyzer replacing legacy Code Climate engines.

- **[Reviewdog (`reviewdog/reviewdog`)](https://github.com)** for bridging any open-source linter or static analyzer output directly into inline GitHub/GitLab pull request review comments.

- **[Joern (`joernio/joern`)](https://github.com)** for an open-source Code Property Graph (CPG) platform enabling deep interprocedural vulnerability discovery across C/C++, Java, Python, and JS.

- **[AI Code Review GitHub Actions (`coderabbitai` / `kody-ai/kodus-ai` / `presubmit/ai-reviewer`)](https://github.com)** for self-hostable open-source AI PR review agents supporting custom team rules and local/BYOK LLMs.
