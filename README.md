# nexusflow-orchestrator
Core orchestration engine for NexusFlow platform. Handles service discovery, dynamic routing, canary deployments, and resilience patterns (circuit breaker, retries) for microservices architectures.
# NexusFlow Orchestrator

[![Go Version](https://img.shields.io/badge/Go-1.21-blue)](https://golang.org/)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

The heart of the NexusFlow platform. This service is responsible for the real-time orchestration of microservices across hybrid-cloud environments.

## Features
- **Dynamic Service Mesh Integration:** Automatically configures service mesh (Istio) based on declarative definitions.
- **Intelligent Canary Releases:** Automated traffic shifting based on metrics (latency, error rate).
- **Resilience Patterns:** Built-in circuit breaker, retry, and timeout mechanisms.
- **Observability:** Native integration with Prometheus and Grafana for monitoring.

## Getting Started
```bash
git clone https://github.com/alexey-kovalev-dev/nexusflow-orchestrator.git
make build
make run
