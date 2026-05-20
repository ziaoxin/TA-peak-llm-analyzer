# 🚀 Splunk PEAK AI Threat Hunter

![Splunk](https://img.shields.io/badge/Splunk-Enterprise_10.x-black?logo=splunk)
![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![AI](https://img.shields.io/badge/LLM-OpenAI_Compatible-green?logo=openai)
![License](https://img.shields.io/github/license/ziaoxin/TA-peak-llm-analyzer?style=flat-square)

An enterprise-grade Splunk Add-on that transforms your SOC into an autonomous Threat Hunting operation center based on the **PEAK Framework** (Prepare, Execute, Act).

## ✨ Core Features
* 🤖 **Autonomous Reasoning**: Dynamically generates ABLE hypotheses and multi-round drill-down SPL queries.
* 💰 **FinOps Tracking**: Granular tracking of LLM API token consumption and financial costs per hunt cycle.
* 📊 **Executive Dashboard**: A premium dark-themed, pure XML dashboard displaying real-time risk scores and automated hunting trajectories.
* 🛡️ **Bulletproof Architecture**: Built-in context distillation, hallucination safeguards, and robust cross-phase data validation.

## 📦 Installation Guide
1. Navigate to the [Releases](https://github.com/YourGitHubName/TA-peak-llm-analyzer/releases) matrix and download the latest `TA-peak-llm-analyzer-1.0.x.spl` package.
2. In your Splunk Web UI, navigate to **Manage Apps** -> **Install app from file**.
3. Upload the `.spl` file binary and restart the Splunk daemon if prompted.
4. Access the Add-on's **Configuration** portal to securely map your LLM API Credentials and Base URL endpoint.

## 🤝 Contribution Guidelines
Contributions are highly welcome! Please ensure you do not commit any files within the volatile `local/` directory. Submit your Pull Requests utilizing semantic commit messages to the `main` branch.
