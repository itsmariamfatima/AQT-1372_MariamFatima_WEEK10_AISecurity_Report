# Week 10: AI Security & LLM Application Risks

**AstraQuantum Tech — Summer of Cybersecurity 2026**

## Overview
This repository contains my Week 10 practical assignment on AI Security and Large Language Model (LLM) Application Risks. The work focuses on understanding AI fundamentals, exploring prompt injection in an authorized training environment, and identifying security risks in AI-powered applications.

## Objectives
- Understand basic AI, machine learning, and neural network concepts.
- Explore prompt injection and sensitive information disclosure.
- Apply and verify a defensive control against a prompt injection attack.
- Develop a threat model for a hypothetical university AI assistant.
- Recommend security controls based on the OWASP Top 10 for LLM and GenAI Applications.

## Practical Activities

### 1. AI Fundamentals
Completed the TryHackMe *The Building Blocks of AI* learning room, including the NEURON-1 neural network classification challenge.

### 2. Prompt Injection 101
Used the GenAI Security Lab's simulated LinguaBridge assistant to observe prompt injection and sensitive information disclosure.

Applied the **Keep the Secret Out of the Model** defensive control and verified that the tested exploit was blocked.

### 3. AI Threat Modelling
Developed a threat model for a hypothetical Campus Helper AI application, covering:
- Direct and indirect prompt injection
- Sensitive information disclosure
- Excessive agency
- Improper output handling
- Unbounded consumption

### 4. Security Recommendations
Recommended layered security controls, including least privilege, application-level access control, human approval for sensitive actions, output validation, log protection, and usage limits.

## Key Learning Outcomes
- System prompts alone are not reliable security boundaries.
- Confidential information should be kept outside the model's context and protected by application-level authorization.
- User inputs and uploaded documents must be treated as untrusted.
- AI-generated outputs should be validated before being used by other applications.
- AI security requires multiple layers of defence.

## Tools and Resources
- [TryHackMe](https://tryhackme.com/)
- [GenAI Security Lab — Prompt Injection 101](https://genaisecuritylab.com/learn-ai-security)
- [OWASP Top 10 for LLM and GenAI Applications](https://genai.owasp.org/llm-top-10/)
- [MITRE ATLAS](https://atlas.mitre.org/)

## Scope and Disclaimer
All practical testing was performed in authorized training environments. The Campus Helper AI threat model is hypothetical and was not tested against a real university system.

## Author
**Mariam Fatima**  
BS Cybersecurity Student  
AstraQuantum Tech — Summer of Cybersecurity 2026

**Topic:** AI Security | Prompt Injection | LLM Security | Threat Modelling
