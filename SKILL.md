---
name: aegis-veil
description: "🛡️ Escudo anti-prompt-injection y skill poisoning."
metadata:
  {
    "openclaw": {
      "emoji": "🛡️",
      "version": "0.2.0",
      "author": "smouj",
      "lang_default": "en"
    }
  }
---

# 🛡️ Aegis Veil

## Purpose
Escudo de protección contra prompt injection y skill poisoning. Implementa detección heurística de intentos de manipulación, sandboxing de ejecución y monitoreo en tiempo real de vectores de ataque conocidos.

## Tags
- security
- reliability
- automation
- openclaw-skill

## Execution contract
1. Validate request and constraints.
2. Generate minimal safe plan.
3. Execute in reversible steps.
4. Verify with explicit checks.
5. Return concise summary + next actions.

## Inputs expected
- Goal
- Constraints (time/cost/privacy)
- Optional files/URLs

## Outputs
- Plan
- Actions executed
- Verification results
- Rollback notes

## Guardrails
- Never expose secrets.
- No destructive operation without explicit confirmation.
- Fail safe with actionable diagnostics.

## Commands
```bash
# Placeholder entrypoint
printf "aegis-veil: validate -> execute -> verify\n"
```

## Test checklist
- [ ] Happy path
- [ ] Error handling
- [ ] Idempotency
- [ ] Guardrails respected
