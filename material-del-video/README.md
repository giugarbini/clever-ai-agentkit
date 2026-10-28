# Material del video · Cómo crear un asistente de IA para WhatsApp (paso a paso)

Esta carpeta acompaña el video del canal de [Giuliana Garbini (@giuliana.garbini)](https://www.youtube.com/@giuliana.garbini).

Este repositorio es una **copia (fork)** del **Agent Kit de Basdonax AI**:
[github.com/fcori47/basdonax-ai-agentkit](https://github.com/fcori47/basdonax-ai-agentkit).
Todo el código es del proyecto original, que está bajo licencia **MIT** (© Basdonax AI). Se conserva su archivo `LICENSE`.
Esta carpeta suma material propio para seguir el tutorial.

El tutorial en el que me basé: [ver el video en YouTube](https://www.youtube.com/watch?v=jwk0jV00KmQ).

## Qué hay en esta carpeta

| Archivo | Para qué sirve |
|---|---|
| `prompt-asistente.md` | Una plantilla de instrucciones para un asistente que atiende pedidos por WhatsApp. Reemplazás los datos entre `[corchetes]` por los de tu negocio. |
| `env-ejemplo.txt` | Una lista corta de los datos que hay que completar para que ande (claves, IDs, direcciones). Es solo un ejemplo con valores falsos. El archivo completo del proyecto es el `.env.example` de la raíz. |

## Qué se usa en el video y qué no

| Pieza | En el video |
|---|---|
| Meta (WhatsApp oficial), Chatwoot, Postgres, un modelo de IA (OpenAI), Hostinger + Coolify, Claude Code | **Sí** |
| `n8n/` | No se usa en este video |
| El resto de las carpetas y archivos del kit (Telegram, Gmail, pruebas, etc.) | Opcionales: están en el proyecto original y no hacen falta para seguir el video |

## Qué NO hay acá (a propósito)

- **No hay claves, tokens ni datos de clientes.** Las claves van en tu archivo `.env`, que **nunca** se sube a GitHub.
- **No hay datos reales de ningún negocio.** Todo lo que figura en la plantilla es inventado.

## Aviso
Armar un asistente que atiende clientes implica manejar claves y datos de personas.
Cuidá tus claves, usá repositorios **privados** para tu configuración real y revisá lo que publicás antes de subirlo.
