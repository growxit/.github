# Growxit

Holding de productos y servicios digitales.

## Proyectos

| Repositorio | Qué es | Estado |
|---|---|---|
| [agents](https://github.com/growxit/agents) | Agente de atención al cliente por WhatsApp para todos los sitios | MVP |

## Convenciones

- Un repositorio por proyecto, privado por defecto, nombrado en minúsculas y con guiones (`agents`, `tienda-deco`).
- Rama principal `main`, protegida. Los cambios entran por pull request con la CI en verde.
- Los secretos nunca se suben: cada proyecto tiene un `.env.example` y el `.env` real vive solo en el servidor.
- Cada repositorio tiene README con cómo correrlo localmente y cómo desplegarlo.
