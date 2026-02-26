# 🛡️ Aegis Veil

<p align="center">
  <img src="https://img.shields.io/badge/Skill-Aegis%20Veil-111827?style=for-the-badge&logo=github" alt="Aegis Veil banner" />
</p>

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/README-English-1f6feb?style=for-the-badge" alt="English"></a>
  <a href="./README.es.md"><img src="https://img.shields.io/badge/README-Español-c92a2a?style=for-the-badge" alt="Español"></a>
</p>

## Resumen
Escudo anti-prompt-injection y skill poisoning: analiza cada skill nueva instalada (incluidas las auto-generadas), detecta payloads ocultos, backdoors o instrucciones maliciosas antes de ejecutar. Sandboxea y reporta riesgos.

## Instalación
```bash
git clone https://github.com/smouj/Aegis-Veil.git
cd Aegis-Veil
cat SKILL.es.md
```

## Arquitectura de entendimiento
```mermaid
flowchart LR
  A[Entrada] --> B[Validar alcance]
  B --> C[Plan seguro]
  C --> D[Ejecutar]
  D --> E[Verificar]
  E --> F[Reportar]
```

## Estado
Iniciando

## Dificultad
Media-Alta
