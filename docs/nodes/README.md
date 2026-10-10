# Nodos

## Tipos

- **Seed** — nodo semilla con链 data completo
- **Miner** — nodo con dharma-gate-core para minar
- **Guardian** — nodo con dharma-gate-core + dharma-sensor
- **Contribuidor** — nodo P2P con Tor (sin dharma-gate-core)

## Quick Start

```bash
# Nodo contribuidor (Tor)
docker run -d --name radhika-node \
  -v radhika-data:/home/radhika/.radhikachain \
  delideli333/radhika-chain:krttika-v4.5-real \
  -listenonion=1 -onlynet=onion
```

## Registry Privado

Las imágenes de producción están en el registry privado.
Contacta a RadhikaTmosphere para acceso.
