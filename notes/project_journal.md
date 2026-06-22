# Project Journal

## Session 1 - Environment Setup


## Validation Test - Requirement 8.4

### Objective

Test whether a local AI model can accurately explain PCI DSS 4.0.1 Requirement 8.4.

### Model Tested

* Qwen 2.5 3B (Ollama Local Model)

### Prompt

Asked the model to explain PCI DSS 4.0.1 Requirement 8.4 and provide:

* Requirement summary
* Audit objective
* Evidence examples
* Common failures
* Remediation recommendations
* Interview questions

### Result

The model incorrectly stated that Requirement 8.4 pertains to secure application software updates.

### Validation

Reviewed the official PCI DSS 4.0.1 source document and confirmed that Requirement 8.4 pertains to Multi-Factor Authentication (MFA).

### Lessons Learned

* Local AI models can provide inaccurate compliance information.
* Regulatory and audit-related responses must be validated against authoritative source documents.
* Human review remains necessary for compliance work.
* RAG and document retrieval will be necessary to improve answer quality.

### Next Actions

* Test Gemma 4 against the same requirement.
* Begin building document-grounded retrieval using PCI DSS source documents.
* Compare model responses against official documentation.

### Completed

* Installed Ollama
* Downloaded and tested Qwen 2.5 3B
* Installed Visual Studio Code
* Installed Continue Extension
* Installed Git
* Created GitHub repository
* Cloned repository locally
* Created project folder structure
* Created PCI auditor system prompt
* Created first Git commit
* Successfully pushed changes to GitHub

### Lessons Learned

* Local AI models can provide outdated compliance information.
* PCI-DSS version accuracy matters.
* Git commits act as project checkpoints.
* GitHub provides version control and project history.

### Current Goal

Build a PCI-DSS 4.0.1 Compliance Copilot that uses official source documents instead of relying solely on model memory.

### Next Steps

1. Add PCI-DSS 4.0.1 source documents to the docs folder.
2. Create document retrieval capability.
3. Improve prompt engineering.
4. Build a document-grounded compliance assistant.
