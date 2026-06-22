# Requirement 8.4 Analysis

## Objective

Evaluate whether a local AI model can accurately explain PCI DSS 4.0.1 Requirement 8.4.

## Model Tested

* Qwen 2.5 3B
* Running locally with Ollama

## Prompt Used

Explain PCI DSS Requirement 8.4.

Provide:

1. Requirement summary
2. Audit objective
3. Evidence examples
4. Common failures
5. Remediation recommendations
6. Interview questions for the control owner

## Model Response

The model incorrectly stated that PCI DSS Requirement 8.4 pertains to secure application software updates.

## Validation Result

Incorrect.

PCI DSS 4.0.1 Requirement 8.4 pertains to Multi-Factor Authentication (MFA), not software updates.

## Risk

Relying solely on model memory can produce inaccurate compliance guidance.

## Lessons Learned

* AI-generated compliance answers must be validated.
* Official PCI DSS documentation should be considered the authoritative source.
* Small local models can hallucinate framework requirements.
* Retrieval-Augmented Generation (RAG) will be needed to improve accuracy.

## Next Steps

* Test Gemma 4 against the same requirement.
* Compare model responses.
* Build document-grounded retrieval using PCI DSS source documents.
