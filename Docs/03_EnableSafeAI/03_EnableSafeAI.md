---
title: 'Exercise 03: Enable safe AI access'
layout: default
nav_order: 5
has_children: true
---

# Exercise 03: Enable safe AI access

## Scenario
AI access is the latest attack surface and the one that bypasses traditional controls most easily. Browser-based LLM sessions exfiltrate data through file uploads, MCP-speaking clients reach external servers without IT visibility, and prompt injection defeats application-layer guardrails. 
In this exercise, you'll bring all three under GSA using TLS inspection, data loss prevention (DLP), and prompt injection protection for users, while using the Secure Web and AI Gateway integration for Copilot Studio agents.

## Objectives- Route user internet traffic through GSA and apply TLS inspection so the inline proxy can scan encrypted web payloads.
- Block sensitive file uploads from unsanctioned destinations using network DLP content policies.
- Learn about Model Context Protocol (MCP) traffic flowing to remote AI servers using Gen AI Insights logs.
- Bring Copilot Studio agent traffic under network-layer security controls.
- Block adversarial prompts to enterprise LLMs using prompt injection protection before the prompts reach the model.

## Duration
Estimated time: **40 minutes**