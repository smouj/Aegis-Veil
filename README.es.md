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

## Resumen
Escudo de protección contra prompt injection y skill poisoning. Implementa detección heurística de intentos de manipulación, sandboxing de ejecución y monitoreo en tiempo real de vectores de ataque conocidos.

## Arquitectura de entendimiento
```mermaid
flowchart LR
  A[Objetivo de entrada] --> B[Chequeo de alcance]
  B --> C[Plan mínimo de pasos]
  C --> D[Ejecución segura]
  D --> E[Verificación]
  E --> F[Reporte + siguientes pasos]
```

## Instalación
```bash
git clone https://github.com/smouj/Aegis-Veil.git
cd Aegis-Veil
cat SKILL.es.md
```

## Uso rápido
```bash
printf "ejecutando aegis-veil...\n"
```

## Estado
- Status: Iniciando
- Dificultad: Media-Alta

## Roadmap
- [ ] Implementar lógica core v0
- [ ] Añadir tests de integración
- [ ] Publicar tag estable v1.0.0
