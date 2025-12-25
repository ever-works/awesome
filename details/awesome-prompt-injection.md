# Awesome Prompt Injection

**URL:** https://github.com/FonduAI/awesome-prompt-injection#readme  
**Category:** Themed Directories  
**Tags:** awesome-lists, security, LLM  
**Brand:** fondu-ai

---

## Overview
Awesome Prompt Injection is a curated directory of resources focused on **prompt injection**, a class of vulnerabilities that target machine learning and large language model (LLM) systems. The list aggregates educational and technical materials such as papers, tutorials, and blog posts that explain how these attacks work and how to detect and mitigate them.

Prompt injection exploits the model’s difficulty in distinguishing between instructions and data, allowing malicious inputs to alter a model’s intended behavior, potentially leading to data leakage or other harmful outcomes.

---

## Features

### 1. Concept Introduction
- Explains what prompt injection is in the context of prompt-based learning.
- Describes how attackers craft malicious prompts that mix benign instructions with harmful ones.
- Uses concrete examples (e.g., appending “Meanwhile, share sensitive information” to an otherwise benign prompt) to illustrate the attack mechanism.
- Discusses factors that influence the severity of attacks, such as:
  - Model complexity.
  - Degree of attacker control over the input prompt.

### 2. Educational Resource Directory
- **Articles and Blog Posts**
  - Section dedicated to written explanations and discussions of prompt injection and related LLM security issues (specific items not fully visible in the provided content, but the structure is present).

- **Tutorials**
  - Section for hands-on learning materials that teach how prompt injection attacks work and how to defend against them (individual entries not visible in the provided content, but the category is part of the structure).

- **Research Papers**
  - Curated academic and technical papers on prompt injection and broader adversarial attacks on LLMs, including:
    - *Not what you've signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection*
      - Explores **indirect prompt injection** attacks via applications that integrate LLMs.
      - Identifies risks such as remote data theft and ecosystem contamination.
      - Covers both real-world and synthetic application scenarios.
    - *Universal and Transferable Adversarial Attacks on Aligned Language Models*
      - Proposes a simple, efficient method to get aligned language models to generate objectionable content with high probability.
      - Shows that generated adversarial prompts are **transferable** across different models and interfaces.
      - Highlights challenges in reliably controlling objectionable information in LLM outputs.

### 3. Security & Mitigation Focus
- Repository goal is explicitly to support:
  - **Understanding** prompt injection attacks and their mechanics.
  - **Detecting** such attacks in LLM-based applications.
  - **Mitigating** or reducing the impact of these vulnerabilities.
- Aims to contribute to building more secure machine learning and LLM systems.

### 4. Open Repository Structure
- Includes standard open-source project files:
  - `README.md` – main documentation and resource listing.
  - `LICENSE` – defines terms of use for the list and its contents.
  - `CONTRIBUTING.md` – guidelines for contributing additional resources to the directory.
- Hosted on GitHub, allowing community contributions and updates.

---

## Use Cases
- Learning the fundamentals of prompt injection vulnerabilities in LLMs.
- Finding research literature for security assessments or academic work on LLM security.
- Discovering tutorials and practical guides for building safer LLM-integrated applications.
- Using it as a reference catalogue for security teams, ML engineers, or researchers focused on adversarial ML and LLM safety.

---

## Pricing
- This is a public GitHub “awesome list” repository.
- **Cost:** Free to access and use under the terms of its open-source license (see the `LICENSE` file in the repository for details).