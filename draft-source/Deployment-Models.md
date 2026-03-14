# Deployment Models

## Overview

The Carapace platform is designed to support multiple deployment models to accommodate different organizational requirements, security policies, and infrastructure environments.

Organizations may choose between local-only deployments, self-hosted platforms, hybrid trust networks, or managed services depending on their privacy, security, and operational needs.

This flexibility allows Carapace to function both as a **local security platform** and as part of a broader **agent trust network**.

---

# Deployment Model 1 — Local-Only Deployment

## Description

In a local-only deployment, the entire Carapace platform runs within the organization's infrastructure.

All telemetry collection, event processing, detection logic, and risk scoring remain internal.

No behavioral telemetry or derived signals leave the environment.

## Use Cases

* highly regulated environments
* financial institutions
* government systems
* internal enterprise AI infrastructure
* organizations with strict data sovereignty requirements

## Characteristics

* full control over telemetry data
* no external data sharing
* complete privacy preservation
* local trust scoring only
* internal dashboards and APIs

## Architecture Example

Agent / API Client
↓
Telemetry SDK
↓
Event Ingestion
↓
Detection Engine
↓
Risk Scoring Engine
↓
Internal Dashboard / Policy Engine

---

# Deployment Model 2 — Self-Hosted Platform

## Description

Organizations deploy the full Carapace platform within their private cloud or on-premise infrastructure.

The platform operates as a dedicated internal security service protecting APIs, LLM systems, and automation workflows.

Telemetry is analyzed locally but may optionally integrate with external systems.

## Use Cases

* enterprise platform protection
* internal AI infrastructure monitoring
* API abuse prevention
* LLM application security

## Characteristics

* full platform deployment
* scalable infrastructure
* integration with internal security systems
* private dashboards and APIs
* configurable policies and enforcement

## Example Infrastructure

* Kubernetes cluster
* private cloud environments
* internal streaming pipelines
* enterprise security integrations

---

# Deployment Model 3 — Hybrid Trust Network

## Description

In a hybrid deployment, organizations analyze telemetry locally while sharing **derived trust signals** with a federated trust network.

Raw telemetry remains private, while anonymized indicators may be shared to improve detection across organizations.

Examples of shared signals may include:

* agent fingerprints
* infrastructure reputation indicators
* risk flags
* aggregated reputation scores

## Benefits

* improved detection accuracy
* shared threat intelligence
* coordinated attack detection
* ecosystem-wide reputation signals

## Privacy Model

Raw telemetry never leaves the organization.

Only **derived and anonymized indicators** may be shared with the trust network.

This preserves organizational privacy while enabling collaborative defense.

---

# Deployment Model 4 — Managed Platform (SaaS)

## Description

Carapace may also be deployed as a managed platform operated by a trusted provider.

Organizations send telemetry events to the hosted platform and query trust decisions through APIs.

The managed platform performs:

* event ingestion
* detection analysis
* risk scoring
* trust graph intelligence
* dashboard hosting

## Use Cases

* startups and smaller teams
* organizations without internal infrastructure
* rapid integration environments
* multi-tenant SaaS protection

## Characteristics

* minimal operational overhead
* hosted dashboards
* scalable trust intelligence
* simple API integrations

---

# Hybrid Architectures

Many organizations may deploy **hybrid architectures** combining multiple deployment models.

Examples include:

Local telemetry analysis combined with external trust intelligence.

Self-hosted scoring engines with optional federation into the trust network.

Internal enforcement engines integrated with external trust scoring APIs.

This flexibility allows organizations to balance:

* privacy
* operational complexity
* ecosystem intelligence

---

# Deployment Components

A typical Carapace deployment may include the following components.

Telemetry collectors
Event ingestion service
Streaming pipeline
Detection engine
Risk scoring engine
Trust graph service
Policy enforcement engine
Operator dashboard
Trust API

These components may be deployed together or independently depending on organizational requirements.

---

# Infrastructure Considerations

Organizations deploying Carapace should consider the following infrastructure requirements.

High-throughput event ingestion

Behavioral telemetry may generate large volumes of events.

Streaming pipelines

Distributed streaming systems allow scalable event processing.

Stateful detection logic

Detection engines may require rolling state for behavioral analysis.

Graph storage

Trust graph intelligence requires graph-aware storage systems.

Secure telemetry handling

Telemetry pipelines must protect sensitive data and prevent tampering.

---

# Deployment Goals

The Carapace deployment architecture is designed to achieve several goals.

Flexibility

Organizations can choose deployment models that match their infrastructure and compliance requirements.

Privacy preservation

Raw telemetry remains under the control of the organization.

Scalability

Streaming pipelines and distributed processing support large-scale agent telemetry.

Interoperability

Different deployments can participate in shared intelligence networks.

---

# Summary

Carapace supports multiple deployment models to accommodate different operational environments.

These models include:

Local-only deployment
Self-hosted platform deployment
Hybrid trust network participation
Managed platform services

This flexibility allows the platform to operate both as an **internal agent security system** and as part of a broader **agent trust infrastructure for the agentic web**.
