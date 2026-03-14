# Use Cases

## Overview

The Carapace platform provides behavioral trust intelligence for AI agents interacting with APIs, services, and infrastructure.

As autonomous agents become more common across software ecosystems, organizations need tools to determine whether automated actors are trustworthy.

Carapace enables organizations to observe agent behavior, detect suspicious activity, compute risk scores, and enforce automated policies.

The following use cases illustrate how the platform can be applied across different environments.

---

# Use Case 1 — Protecting LLM APIs from Malicious Agents

## Problem

AI-powered APIs are increasingly exposed to autonomous agents capable of generating high volumes of requests.

These agents may attempt to:

* scrape model outputs
* exploit prompts
* perform prompt injection attacks
* extract training data
* bypass usage limits

Traditional API protection tools are not designed to detect AI-driven behavior patterns.

## Carapace Solution

Carapace monitors behavioral signals associated with AI agents interacting with LLM endpoints.

Detection capabilities include:

* prompt injection detection
* model exfiltration attempts
* abnormal request velocity
* automated prompt generation patterns
* infrastructure reputation analysis

Organizations can automatically apply policies such as:

* rate limiting
* challenge workflows
* request blocking

This protects AI model infrastructure from malicious automation.

---

# Use Case 2 — Detecting Agent Farms

## Problem

Attackers may deploy large numbers of automated agents designed to evade detection.

These agent farms may perform activities such as:

* large-scale scraping
* API abuse
* trial exploitation
* automated content generation
* coordinated request flooding

Individual agents may appear benign, but coordinated behavior reveals malicious intent.

## Carapace Solution

The Carapace Trust Graph identifies relationships between agents and shared infrastructure.

Signals analyzed include:

* shared IP infrastructure
* identical behavioral cadence
* shared payment instruments
* synchronized task execution
* common organization identifiers

Graph intelligence allows detection of coordinated automation networks.

Organizations can identify and block entire clusters of malicious agents.

---

# Use Case 3 — API Abuse Detection

## Problem

Public APIs frequently experience abuse from automated agents performing activities such as:

* scraping proprietary data
* bypassing rate limits
* generating excessive requests
* enumerating endpoints
* abusing free tiers

Traditional API rate limiting is often insufficient against sophisticated automation.

## Carapace Solution

Carapace analyzes behavioral telemetry across multiple dimensions including:

* request velocity
* endpoint diversity
* session behavior
* infrastructure origin
* retry patterns

Detection rules identify abnormal behavior patterns associated with automation abuse.

Organizations can enforce policies such as:

* request throttling
* dynamic rate limiting
* temporary quarantine
* blocking malicious agents

---

# Use Case 4 — Preventing Economic Abuse

## Problem

Autonomous agents interacting with online services may exploit economic systems.

Examples include:

* free trial abuse
* compute resource fraud
* payment manipulation
* microtransaction exploitation
* chargeback abuse

Economic abuse can result in significant financial losses.

## Carapace Solution

Carapace incorporates economic telemetry signals into its behavioral analysis.

Signals may include:

* transaction velocity
* payment method reuse
* wallet correlation
* resource consumption spikes
* chargeback indicators

Detection rules identify suspicious economic patterns and raise agent risk scores.

Organizations can enforce additional verification or block transactions.

---

# Use Case 5 — Agent Reputation Network

## Problem

Organizations interacting with external AI agents often lack visibility into the history and reputation of those agents.

Without reputation systems, services cannot easily determine whether an automated actor has previously behaved maliciously.

## Carapace Solution

Carapace enables the creation of a behavioral reputation network for AI agents.

Agents accumulate risk signals over time based on their observed behavior.

Trust scores allow organizations to evaluate the likelihood that an agent is trustworthy.

Services may query the Carapace Trust API to retrieve:

* agent risk score
* triggered risk flags
* behavioral history indicators

These signals allow systems to make automated trust decisions.

---

# Use Case 6 — Securing Autonomous Workflows

## Problem

Modern AI agents increasingly execute complex workflows that interact with multiple external systems.

Examples include:

* data pipelines
* automation workflows
* financial operations
* system orchestration
* autonomous research agents

If compromised or manipulated, these agents may perform unintended or harmful actions.

## Carapace Solution

Carapace monitors behavioral telemetry generated by agent workflows.

Detection capabilities include:

* abnormal task execution patterns
* execution loop detection
* retry anomalies
* tool misuse patterns
* unexpected resource consumption

Organizations can monitor agent behavior and intervene when suspicious activity occurs.

---

# Use Case 7 — Cross-Organization Threat Intelligence

## Problem

Many automation attacks target multiple organizations simultaneously.

Without collaboration, organizations may detect attacks too late.

## Carapace Solution

Carapace supports a privacy-preserving intelligence sharing model.

Organizations may contribute derived signals such as:

* malicious agent fingerprints
* abusive infrastructure indicators
* prompt injection signatures
* automation abuse patterns

These signals help other organizations detect similar threats earlier.

---

# Summary

Carapace enables organizations to manage risk associated with autonomous AI agents across many environments.

Key use cases include:

* protecting LLM APIs
* detecting agent farms
* preventing API abuse
* identifying economic exploitation
* establishing agent reputation systems
* securing autonomous workflows
* enabling collaborative threat intelligence

As the agentic web evolves, behavioral trust infrastructure will become essential for safe interaction with autonomous systems.
