# Oleg Skydan

Backend-focused software developer with a background in project management — bringing systems thinking and architectural discipline to code.

**Current focus:** Secure backend systems · RESTful APIs · Relational data modeling · Containerized environments

📍 Germany  |  📧 olegskydan@proton.me  |  🔗 [LinkedIn](https://www.linkedin.com/in/oleg-skydan)

-----

## Kurzprofil

Backend-Entwickler mit Hintergrund im Projektmanagement. Schwerpunkt auf robuste, strukturierte und wartbare Softwarearchitektur.

-----

## Tech Stack

|Layer                |Technologies       |

|---------------------|-------------------|

|Languages            |Java · C# · Python |

|Databases            |PostgreSQL         |

|Infrastructure       |Docker · Git       |

|Protocols & Messaging|MQTT · HMAC/SHA-256|

|Web                  |HTML · CSS · PHP   |

-----

## Featured Project

### [CubeSat Security Simulator](https://github.com/Skydan111/CubeSat-Security-Simulator) 

A telemetry security platform simulating authenticated communication between a satellite (Raspberry Pi) and a ground station. Built to explore security-by-design principles in constrained embedded environments.

**Architecture**

- Modular structure: `satellite /` `ground /` `shared /` `tests /` `docs /`

- Clean separation of transport, validation, and application layers

**Security implementation**

- HMAC-SHA256 message signing and verification

- Replay attack protection with structured validation pipeline

- Adaptive security mode: anomaly detection with temporary lockout

- Audit logging across three flows: processed / rejected / quarantine

**Transport:** MQTT  |  **Platform:** Raspberry Pi + desktop ground station  |  **Language:** Python

-----

## Engineering Approach

- Architecture decisions over shortcuts

- Explicit validation — nothing is trusted implicitly

- Reproducible builds via Docker

- Structured, reviewable Git history

-----

 