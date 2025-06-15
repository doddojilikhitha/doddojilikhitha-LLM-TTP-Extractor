# Generative AI-based Extraction of MITRE ATT\&CK Tactics and Techniques from CTI Reports

This project uses Generative AI (LLMs) to extract MITRE ATT\&CK Tactics and Techniques from unstructured Cyber Threat Intelligence (CTI) reports.

# 📌 Problem Statement

CTI reports are often long, unstructured, and rich with subtle attack descriptions. This project aims to automate the extraction of MITRE ATT\&CK TTPs using GPT-4-style language models for threat intelligence enrichment.

# How It Works

1. Raw CTI data was sourced from the **CrowdStrike 2024 Global Threat Report (Executive Summary)**.
2. Relevant paragraphs describing attacker behavior were processed using prompt-based LLM analysis.
3. Extracted TTPs were formatted into a structured CSV and JSON dataset.

# Tools Used

1. GPT-4 / ChatGPT (prompt engineering)
2. Python (for formatting and exporting results)
3. MITRE ATT\&CK Framework ([https://attack.mitre.org/](https://attack.mitre.org/))

# Credits

Report: [CrowdStrike 2024 Global Threat Report](https://www.crowdstrike.com/global-threat-report/)
