# 🛡️ Aegis Veil

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Aegis%20Veil-111827?style=for-the-badge&logo=github" alt="Aegis Veil banner" />
</p>

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/README-English-1f6feb?style=for-the-badge" alt="English"></a>
  <a href="./README.es.md"><img src="https://img.shields.io/badge/README-Español-c92a2a?style=for-the-badge" alt="Español"></a>
</p>

<p align="center"><em>🛡️ Escudo anti-prompt-injection y skill poisoning.</em></p>

---

## Overview
Escudo de protección contra prompt injection y skill poisoning. Implementa detección heurística de intentos de manipulación, sandboxing de ejecución y monitoreo en tiempo real de vectores de ataque conocidos.

## Architecture of understanding
```mermaid
flowchart LR
  A[Input goal] --> B[Scope check]
  B --> C[Plan minimal steps]
  C --> D[Execute safely]
  D --> E[Verify outcomes]
  E --> F[Report + next steps]
```

## Installation
```bash
git clone https://github.com/smouj/Aegis-Veil.git
cd Aegis-Veil
# read the contract
cat SKILL.md
```

## Quick usage
```bash
# Example placeholder command
printf "running aegis-veil...\n"
```

## Badges
- Status: Initiating
- Difficulty: Media-Alta

## Roadmap
- [ ] Implement core logic v0
- [ ] Add integration tests
- [ ] Publish stable tag v1.0.0
