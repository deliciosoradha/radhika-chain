# Consenso Dharma/PoK

RadhikaChain usa **Proof of Karma (PoK)** — un consenso que combina:

- **SHA256d PoW** (como Bitcoin) para la seguridad base
- **KarmaHash** (BLAKE3 + SHA3) como capa de consenso adicional
- **Dharma nonce** — nonces especiales que eximen ciertas validaciones

## Reglas

- Todos los bloques necesitan karma válido desde el genesis
- El minero es **dharma-gate-core** (no arbitrario)
- La verificación de karma es obligatoria para aceptar bloques

## Licencia

MIT (igual que Bitcoin Core)
