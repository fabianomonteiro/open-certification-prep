# Contribution Guide

Thank you for considering contributing to the **Open Certification Prep** project! This document provides guidelines and best practices for contributing to the repository.

## Table of Contents

1. [Code of Conduct](#code-of-conduct)  
2. [How to Contribute](#how-to-contribute)  
3. [Prompt Structure](#prompt-structure)  
4. [Validation Process](#validation-process)  
5. [Style Guidelines](#style-guidelines)  
6. [Reporting Issues](#reporting-issues)  

---

## Code of Conduct

This project adheres to a **Code of Conduct** that we expect all contributors to follow. Please read [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) before contributing.

Key points:
- Be respectful and inclusive.
- Avoid offensive or discriminatory content.
- Maintain professionalism.
- Accept constructive feedback.

---

## How to Contribute

### 1. Setting Up Your Environment

```bash
# Fork the repository
# Clone your fork
git clone https://github.com/fabianomonteiro/open-certification-prep.git
cd open-certification-prep

# Create a branch for your contribution
git checkout -b feature/new-contribution
```

### 2. Types of Contributions

- **New Prompts**: Add prompts for certifications not yet covered.
- **Improvements**: Refine existing prompts.
- **Fixes**: Correct errors or inaccuracies.
- **Documentation**: Improve or add documentation.
- **Validation**: Test prompts with different AI models.

### 3. Submission Process

1. Ensure your contribution adheres to the guidelines.
2. Test your changes thoroughly.
3. Update relevant documentation.
4. Commit your changes.
5. Submit a Pull Request (PR).

---

## Prompt Structure

Each prompt must follow the standardized structure defined in the `template.md` file located at the root of this repository.

- **Location**: [template.md](template.md)  
- **Contents**:
  - Context
  - Instructions for the AI Model
  - Control Commands
  - Response Format
  - Covered Topics
  - Usage Examples

### Using the Template
Copy the `template.md` file to your working directory and adapt it for your specific contribution. For example:

```bash
cp template.md prompts/new-certification.md
```

Fill in the relevant sections with details for the certification you’re contributing.

---

## Validation Process

### 1. Local Testing
- Test the prompt with at least one AI model.
- Ensure all necessary sections are present.
- Verify that the commands work as expected.

### 2. Documenting Tests
Update the status table in the main README:

```markdown
| Certification | ChatGPT | Claude | Gemini | Status |
|---------------|---------|--------|--------|--------|
| New Cert      | ✅/⚠️/❓   | ...    | ...    | ...    |
```

### 3. Validation Criteria
- Accuracy of responses.
- Consistency with real exam scenarios.
- Clarity of explanations.
- Functionality of commands.
- Appropriateness of difficulty level.

---

## Style Guidelines

### Markdown
- Use appropriate headings (#, ##, ###).
- Keep one blank line between sections.
- Use lists when applicable.
- Include examples in code blocks.
- Maintain consistent formatting.

### Content
- Be clear and concise.
- Use professional language.
- Avoid unnecessary jargon.
- Focus on educational objectives.
- Provide practical examples.

---

## Reporting Issues

### Submitting Issues
Use the appropriate issue templates to:
- Report bugs.
- Suggest improvements.
- Propose new features.
- Request clarifications.

### Required Information
- Clear description of the issue.
- Steps to reproduce (if applicable).
- Expected vs. observed behavior.
- AI model used.
- Screenshots or examples (if relevant).

---

## Additional Tips

1. **Before Contributing**
   - Check if a similar issue already exists.
   - Discuss major changes in an issue first.
   - Review existing documentation.

2. **During Development**
   - Keep changes focused and specific.
   - Comment your code when necessary.
   - Follow existing conventions.

3. **When Submitting**
   - Write clear commit messages.
   - Provide a detailed description in the PR.
   - Respond to feedback promptly.

---

## Acknowledgments

Your contributions are invaluable to the community! We appreciate your time and effort in improving this project.

---

## Questions?

If you have any questions about contributing, feel free to:  
- Open an issue.  
- Reach out via LinkedIn.  
- Review the existing documentation.

---

By contributing to this project, you agree to adhere to these guidelines and the Code of Conduct.