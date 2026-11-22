# Builder o Engineer: prepárate para tu próximo puesto en IA

[![Builder o Engineer: prepárate para tu próximo puesto en IA](guia/assets/banner-es.jpg)](https://inematds.github.io/builder-ou-engineer/guia/es/)

**🇧🇷 [Português](README.md) · 🇺🇸 [English](README.en.md) · 🇪🇸 [Español](README.es.md)**

## Qué es

Las empresas que más usan IA ya distinguen dos perfiles de entrada: el **AI Engineer**, que construye modelos y sistemas, y el **AI Builder**, que viene de cualquier área y usa la IA para resolver problemas del negocio. iFood paga de R$ 5.200 a R$ 7.000 al mes para formar a ambos perfiles en el programa genAI, y las inscripciones para la cohorte de 2027 cerraron el 17/11/2026. El **Plan Builder o Engineer** es un plan gratuito de 12 semanas para que llegues preparado a la próxima cohorte o a cualquier puesto de IA: descubre tu perfil, sigue la ruta con cursos gratuitos de INEMA.CLUB, haz un proyecto con cifras de antes y después y practica con IA cada etapa del proceso de selección.

No tiene relación con iFood ni garantiza un puesto: es preparación.

## 📖 Guía de uso

Guía completa: **https://inematds.github.io/builder-ou-engineer/guia/es/**

🎬 Video: en producción (se agregará a la guía cuando esté publicado).

## Empieza pidiéndole ayuda a tu IA

Pega esto en ChatGPT, Claude o Gemini:

```
Sé mi entrenador para que pueda entrar a un programa de pasantías o residencia en IA (como genAI de iFood), con un lenguaje sencillo.
1. Haz conmigo, de a una pregunta por vez, una prueba para saber si me parezco más a un AI Builder o a un AI Engineer. Pregúntame también qué estudio y cuándo me gradúo.
2. Arma un plan de 12 semanas, de unas 5 horas por semana, siguiendo el "Plan Builder o Engineer" en https://inematds.github.io/builder-ou-engineer/guia/es/ y usando los cursos gratuitos que se mencionan allí.
3. Ayúdame a elegir un proyecto de prueba que resuelva un problema real de alguien y tenga una cifra de antes y después.
4. Cuando diga "práctica", asume el papel del evaluador de cada etapa del proceso de selección. Al final de cada una, dame una calificación y dime qué olvidé.
Sé honesto: si estoy flojo en algo, dímelo.
```

## El programa de referencia (verificado el 22/11/2026)

- 2.ª edición del genAI de iFood: inscripciones del 27/10 al 17/11/2026, inicio en febrero de 2027.
- Pasantía: graduación entre jul/2027 y ene/2029, estipendio de R$ 5.200. Residencia: graduados entre dic/2025 y dic/2026, estipendio de R$ 7.000.
- AI Engineer: computación, ingeniería de software, matemáticas, estadística, física. AI Builder: cualquier formación, sin necesidad de programar a fondo.
- Fuentes: [comunicado oficial](https://institucional.ifood.com.br/releases/programa-gen-ia/) · [página de carreras](https://carreiras.ifood.com.br/gen-ai/).

---

## El proceso, de principio a fin

Quién participa: 🧠 tú (con la IA a tu lado) · 🤖 tu IA (ChatGPT, Claude, Gemini) · ⚙️ ningún script: el plan es solo lectura y práctica.

| # | Paso | Dónde | Quién |
|---|---|---|---|
| 1 | Descubrir el perfil (Builder o Engineer) | pedido anterior o [guía#perfis](https://inematds.github.io/builder-ou-engineer/guia/es/#perfis) | 🤖 + 🧠 |
| 2 | Semanas 1–2: usar IA en 3 tareas y anotar el tiempo antes y después | [PLANO.md](PLANO.md) (en portugués) | 🧠 |
| 3 | Semanas 3–6: ruta del perfil (cursos gratuitos) | [PLANO.md](PLANO.md#semana-a-semana) (en portugués) | 🧠 |
| 4 | Semanas 7–10: proyecto de prueba + 1 página de portafolio | [PLANO.md](PLANO.md#semana-a-semana) (en portugués) | 🧠 |
| 5 | Semanas 11–12: práctica de las 6 etapas de selección | [pedidos de treino](PLANO.md#pedidos-de-treino-cole-na-sua-ia) (en portugués) | 🤖 + 🧠 |
| 6 | Hasta la próxima cohorte: un proyecto por mes | — | 🧠 |

## Instalación técnica

No hay nada que instalar: el proyecto es una guía estática (`guia/index.html`, `guia/en/`, `guia/es/`) y un plan en texto (`PLANO.md`). Para ver la guía localmente:

```bash
git clone https://github.com/inematds/builder-ou-engineer.git
cd builder-ou-engineer && python3 -m http.server 8000   # abrir http://localhost:8000/guia/
```

Publicación: GitHub Pages mediante la Action `.github/workflows/pages.yml` (raíz del repo).

## Licencia

MIT. Gratis en inema.club, directamente en internet.