# 🎙️ Narrador con tu propia voz (español)

Notebook de Google Colab para narrar videos cortos (YouTube Shorts, TikTok, Reels) con **tu propia voz**, frase por frase, usando [Chatterbox Multilingual](https://github.com/resemble-ai/chatterbox) (licencia MIT). Gratis, con la GPU de Colab.

**Creado por Eduardo Rincón.**

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/neoworld09/Voz-IA/blob/main/narrador_tu_voz.ipynb)

## Cómo se usa
1. Abre el notebook en Colab y activa **GPU T4** (Entorno de ejecución → Cambiar tipo de entorno).
2. **Ejecutar todo**. La primera vez la sesión se reinicia sola tras instalar: vuelve a darle **Ejecutar todo**.
3. Sube un audio tuyo de 10–30 segundos (sin música ni ruido de fondo).
4. Escribe tu guion en la celda 3, una frase por línea.
5. Ajusta **EMOCION** y **RITMO** con la celda de prueba y genera todo: se descarga un `.zip` con un `.wav` por frase.

## Uso responsable
- Usa solo tu voz o la de alguien que te dio permiso explícito.
- No lo uses para suplantar, engañar o hacer fraudes.
- Los audios generados llevan una marca de agua inaudible (Perth) que permite detectar que son sintéticos.

## Licencia y créditos
- Este notebook: **[CC BY-NC 4.0](LICENSE)** © 2026 Eduardo Rincón. Puedes usarlo, modificarlo y compartirlo **dando crédito** al autor. **No se permite venderlo** ni usarlo como parte de un producto pagado sin permiso.
- Los audios que generes con tu propia voz son tuyos y puedes usarlos en tus videos, incluidos los monetizados.
- Modelo: Chatterbox de [Resemble AI](https://github.com/resemble-ai/chatterbox), licencia MIT (se instala desde su paquete oficial; no se redistribuye aquí).
