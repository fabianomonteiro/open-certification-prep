# Open Certification Prep

Welcome to **Open Certification Prep**, an open-source repository providing practice prompts for certification exams. This repository aims to help candidates prepare for certification exams by offering interactive and realistic simulations that reflect the style and complexity of official exams.

## Overview

This repository contains prompts designed to simulate certification exam questions for various providers, including AWS, CKAD, and more. Each prompt offers practical questions, real-time feedback, and additional resources to reinforce learning.

### Prompt Features

- **Interactivity:** Prompts guide users through personalized simulations with immediate feedback and explanations.
- **Reinforced Learning:** Flashcards and detailed explanations for questions to strengthen understanding.
- **Question Distribution:** Aligns with the official exam structure, distributing questions based on exam topic percentages.
- **Continuous Updates:** Prompts are regularly updated to match changes in certification requirements.

## Prompt Validation Status

| Certification                          | Level        | [ChatGPT](https://chatgpt.com) | [Claude](https://claude.ai) | [Gemini](https://gemini.google.com) | [Perplexity](https://www.perplexity.ai) | [Meta AI](https://www.meta.ai) | Status                |
|---------------------------------------|--------------|---------------------------------------|-----------------------------------------|---------------------------------------------|-------------------------------------------|--------------------------------|-----------------------|
| AWS Certified Cloud Practitioner       | Foundational | ✅                                     | ✅                                     | ✅                                         | ✅                                        | ✅                             | Active                |
| AWS Certified AI Practitioner          | Foundational | ✅                                     | ✅                                     | ✅                                         | ✅                                        | ✅                             | Active                |
| AWS Certified SysOps Administrator     | Associate    | ✅                                     | ✅                                     | ✅                                         | ✅                                        | ✅                             | Active                |
| AWS Certified Solutions Architect      | Associate    | ✅                                     | ✅                                     | ✅                                         | ✅                                        | ✅                             | Active                |
| AWS Certified Developer                | Associate    | ✅                                     | ✅                                     | ✅                                         | ✅                                        | ✅                             | Active                |
| AWS Certified Machine Learning Engineer| Associate    | ✅                                     | ✅                                     | ✅                                         | ✅                                        | ✅                             | Active                |
| AWS Certified Data Engineer            | Associate    | ✅                                     | ✅                                     | ✅                                         | ✅                                        | ✅                             | Active                |
| AWS Solutions Architect Professional   | Professional | ✅                                     | ✅                                     | ✅                                         | ✅                                        | ✅                             | Active                |
| AWS DevOps Engineer Professional       | Professional | ✅                                     | ✅                                     | ✅                                         | ✅                                        | ✅                             | Active                |
| AWS Machine Learning Specialty         | Specialty    | ✅                                     | ✅                                     | ✅                                         | ✅                                        | ✅                             | Active                |
| AWS Security Specialty                 | Specialty    | ❓                                     | ❓                                     | ❓                                         | ❓                                        | ❓                             | In Development        |
| AWS Advanced Networking Specialty      | Specialty    | ❓                                     | ❓                                     | ❓                                         | ❓                                        | ❓                             | In Development        |
| AWS Database Specialty                 | Specialty    | ❓                                     | ❓                                     | ❓                                         | ❓                                        | ❓                             | In Development        |
| AWS Data Analytics Specialty           | Specialty    | ❓                                     | ❓                                     | ❓                                         | ❓                                        | ❓                             | In Development        |
| AWS SAP on AWS Specialty               | Specialty    | ❓                                     | ❓                                     | ❓                                         | ❓                                        | ❓                             | In Development        |

**Legend:**
- ✅ Tested and fully functional
- ⚠️ Tested, but with inconsistencies
- ❌ Tested and not functional
- ❓ Not tested yet

**Versions Used**:
1. **ChatGPT**: GPT-4, GPT-4o
2. **Claude**: Claude 3.5 Sonnet
3. **Gemini**: Gemini Pro 1.5
4. **Perplexity**: Version not publicly disclosed
5. **Meta AI (Llama)**: Llama 3.2 

## Repository Structure

```
open-certification-prep/
├── pt-br/
│   ├── aws/
│   │   ├── 01-foundational/
│   │   │   ├── ai-practitioner.md
│   │   │   └── cloud-practitioner.md
│   │   ├── 02-associate/
│   │   │   ├── data-engineer.md
│   │   │   ├── developer.md
│   │   │   ├── machine-learning-engineer.md
│   │   │   ├── solutions-architect.md
│   │   │   └── sysops-admin.md
│   │   ├── 03-professional/
│   │   │   ├── devops-engineer.md
│   │   │   └── solutions-architect.md
│   │   └── 04-specialty/
│   │       ├── machine-learning.md
│   │       ├── networking.md
│   │       └── security.md
│   ├── README.md
├── CONTRIBUTING.md
├── LICENSE
├── README.md
└── template.md
```

## How to Use

1. **Choose a Certification Provider:** Navigate to the directory corresponding to the provider (e.g., `aws`, `ckad`).
2. **Select a Certification:** Locate the directory for the desired certification and level.
3. **Copy and Paste the Prompt:** Use the prompt in your chosen AI model (e.g., ChatGPT, Claude).
4. **Interactive Simulation:** Answer questions and receive real-time feedback with detailed explanations.
5. **Review with Flashcards:** Optionally, review key concepts with flashcards based on answered questions.

## Contributing

We welcome contributions! Here's how you can contribute:

1. **Fork the Repository:** Create your own copy of the repository.
2. **Create a Feature Branch:** `git checkout -b feature/new-certification`
3. **Commit Your Changes:** `git commit -m 'Add prompts for new certification'`
4. **Push to Your Branch:** `git push origin feature/new-certification`
5. **Submit a Pull Request:** Propose your changes for review.

### Contribution Guidelines

- Organize prompts by certification provider and level.
- Update the validation status table and document specific requirements.
- Include examples of usage and expected feedback for new prompts.

## License

This project is licensed under the **[GNU General Public License v3.0](LICENSE)**.  
By using or contributing to this project, you agree to comply with the terms of this license.