# 🛡️ Aegis Veil

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Aegis%20Veil-111827?style=for-the-badge&logo=github" alt="Aegis Veil banner" />
</p>

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/README-English-1f6feb?style=for-the-badge" alt="English"></a>
  <a href="./README.es.md"><img src="https://img.shields.io/badge/README-Español-c92a2a?style=for-the-badge" alt="Español"></a>
</p>

## Overview
Prompt-injection and skill-poisoning defense with pre-execution sandbox checks.

## Purpose
Escudo anti-prompt-injection y skill poisoning: analiza cada skill nueva instalada (incluidas las auto-generadas), detecta payloads ocultos, backdoors o instrucciones maliciosas antes de ejecutar. Sandboxea y reporta riesgos.

## Installation
```bash
git clone https://github.com/smouj/Aegis-Veil.git
cd Aegis-Veil
cat SKILL.md
```

## Architecture (understanding)
```mermaid
flowchart LR
  A[Input] --> B[Validate scope]
  B --> C[Plan safe steps]
  C --> D[Execute]
  D --> E[Verify]
  E --> F[Report]
```

## Status
Initiating

## Difficulty
Media-Alta
