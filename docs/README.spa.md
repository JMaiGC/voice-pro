<!--
    title: Voice-Pro: Herramienta definitiva de conversión de voz con IA y traducción multilingüe
    description: Potente aplicación web impulsada por IA para procesamiento de videos de YouTube, reconocimiento de voz, traducción y texto a voz con soporte multilingüe
    keywords: Conversión de voz con IA, traducción de YouTube, generación de subtítulos, voz a texto, texto a voz, clonación de voz, traducción multilingüe, Alternativa de ElevenLabs
    author: ABUS
    version: 2.0.0
    last-updated: 2025-02-23
    product-type: Software de procesamiento multimedia con IA
    platforms: Windows
    technology-stack: Whisper, Edge-TTS, Gradio, CUDA, Faster-Whisper, Whisper-Timestamped, E2-TTS, F5-TTS, YouTube Downloader, Demucs, MDX-Net, RVC, CosyVoice, kokoro
    license: LGPL
-->

# Voice-Pro: La Herramienta Definitiva de Conversión de Voz por IA y Traducción Multilingüe 🔊

🌍 [한국어](README.kor.md) ∙ [English](README.eng.md) ∙ [中文简体](README.zh.md) ∙ [中文繁體](README.tw.md) ∙ [日本語](README.jpn.md) ∙ [Deutsch](README.deu.md) ∙ [Español](README.spa.md) ∙ [Português](README.por.md)

[![GitHub Release](https://img.shields.io/github/v/release/abus-aikorea/voice-pro)](https://github.com/abus-aikorea/voice-pro/releases)

## 🎙️ Potente aplicación web impulsada por IA para procesamiento de videos de YouTube, reconocimiento de voz, traducción y texto a voz con soporte multilingüe

Voice-Pro es una aplicación web de vanguardia que transforma la creación de contenido multimedia. Integra la descarga de videos de YouTube, separación de voz, reconocimiento de voz, traducción y conversión de texto a voz (TTS) en una sola herramienta poderosa, ofreciendo una solución ideal para creadores, investigadores y profesionales multilingües.

- 🔊 Reconocimiento de voz de primer nivel: **Whisper**, **Faster-Whisper**, **Whisper-Timestamped**
- 🎤 Clonación de voz Zero-Shot: **F5-TTS**, **E2-TTS**, **CosyVoice**
- 📢 Conversión de texto a voz multilingüe: **Edge-TTS**, **kokoro**
- 🎥 Procesamiento de videos de YouTube y extracción de audio: **yt-dlp**
- 🌍 Traducción instantánea a más de 100 idiomas: **Deep-Translator**
- 🔇 Separación vocal de nivel profesional: **UVR5**
- 🔥 Creación de covers por IA: **RVC**

Como una alternativa sólida a **ElevenLabs**, Voice-Pro empodera a podcasters, desarrolladores y creadores con soluciones de voz avanzadas.

## ⚠️ Notas
- Voice-Pro se ha actualizado a la versión **v2.x** (Python 3.10.15, Torch 2.5.1+cu124, Gradio 5.14.0)
- 🆓 La versión de prueba gratuita soporta hasta **60 segundos** de procesamiento de medios
- 🔥 Nueva función **AI Cover** añadida
- 🎤 Soporte para **CosyVoice** y **kokoro** incluido
- ⏳ En la primera ejecución, se descargará **CozyVoice2-0.5B (9GB)**. Dependiendo de la velocidad de la red, puede tomar más de una hora
- 🎧 Las muestras de voz para clonación se actualizarán continuamente
- **Instrucciones:**
  - **Usuarios existentes:** Descargue la última versión de Voice-Pro. Ejecute **update.bat**.
  - **Nuevos usuarios:** Consulta la sección de instalación abajo — ejecuta **configure.bat** y luego **start.bat**

## 🚄 Demostraciones

### Pestaña `Estudio de Doblaje`: Transcripción, Traducción y TTS
<div aria-labelledby="studio-demo-description">
  <video src="https://github.com/user-attachments/assets/f18e7f54-7bc0-4c26-96f9-9f6b70c7114c" width="100%" style="max-width: 720px;" controls muted aria-describedby="studio-demo-description"></video>
  <p id="studio-demo-description">Demostración del flujo de trabajo completo de procesamiento de medios en la pestaña Estudio: Muestra un proceso integral de transformación de medios, desde la descarga de videos de YouTube hasta la separación de voz por IA, subtítulos automáticos con Whisper, traducción multilingüe y doblaje profesional usando F5-TTS.</p>
</div>

### Pestaña `F5-TTS-Multi`: Creación de Podcasts
<div aria-labelledby="tts-demo-description">
  <video src="https://github.com/user-attachments/assets/2d4b7d84-ca19-4efd-a847-a66fa0db616e" width="100%" style="max-width: 720px;" controls muted aria-describedby="tts-demo-description"></video>
  <p id="tts-demo-description">Demostración de la innovadora tecnología de clonación de voz por IA de F5-TTS: Presenta una tecnología avanzada de conversión de voz que imita con precisión las voces reales de Mark Zuckerberg y Elon Musk para crear contenidos completamente nuevos.</p>
</div>

### Pestaña `AI Cover`
<div aria-labelledby="ai-cover-description">
  <video src="https://github.com/user-attachments/assets/88a47ab1-a18b-4779-97c8-7c1da84f5fc3" width="100%" style="max-width: 720px;" controls muted aria-describedby="ai-cover-description"></video>
  <p id="ai-cover-description">Crea una versión de Trump de "Cupid" de IU, "Te Echo de Menos" de Kim Kwang-seok y "Carta de un Soldado".</p>
</div>

### Pestaña `Traducción en Vivo`: Reconocimiento y Traducción en Tiempo Real
<div aria-labelledby="translate-demo-description">
  <video src="https://github.com/user-attachments/assets/eb53dd3a-df0a-4f7f-819c-cf92d477e2d1" width="100%" style="max-width: 720px;" controls muted aria-describedby="translate-demo-description"></video>
  <p id="translate-demo-description">Demostración de la función de traducción multilingüe en tiempo real: Muestra un proceso innovador de procesamiento de medios multilingües que captura instantáneamente contenidos de noticias de la BBC, genera subtítulos en tiempo real y los traduce de inmediato a otros idiomas.</p>
</div>

## ⭐ Características Principales

### 1. Estudio de Doblaje
- Descarga de videos de YouTube y extracción de audio
- Separación de voz con **MDX-Net** y **Demucs**
- Soporte para reconocimiento de voz y traducción en más de 100 idiomas

### 2. Tecnologías de Voz
- **Voz a Texto:** **Whisper**, **Faster-Whisper**, **Whisper-Timestamped**
- **Texto a Voz:**
  - **Edge-TTS**: Más de 100 idiomas, más de 400 voces
  - **E2-TTS**, **F5-TTS**, **CosyVoice**: Clonación Zero-Shot
  - **kokoro**: 2º lugar en el HuggingFace TTS Arena
- 🔥 **AI Cover (Voz a Voz):** Eliminación vocal con **UVR5**, modulación con **RVC**

### 3. Traducción en Tiempo Real
- Reconocimiento de voz instantáneo
- Traducción multilingüe en tiempo real
- Entradas de audio personalizables

## 🤖 Interfaz Web

### Pestaña `Estudio de Doblaje`
- Centro integrado: Descargas de YouTube, eliminación de ruido, subtítulos, traducción y TTS
- Soporta todos los formatos compatibles con ffmpeg
- Opciones de salida: WAV, FLAC, MP3
- Subtítulos y reconocimiento para más de 100 idiomas
- TTS con ajustes de velocidad, volumen y tono
<p align="center"><img style="width: 90%; height: 90%" src="images/main_page.spa.png?raw=true" alt="Interfaz Web de Conversión de Voz Multilingüe y Generación de Subtítulos"/></p>

### Pestaña `Subtítulos Whisper`
- Enfocada en subtítulos: Más de 90 idiomas
- Visualización de subtítulos integrada con video
- Resaltado por palabra y opciones de eliminación de ruido

### Pestaña `Traducción`
- Traducción a más de 100 idiomas
- Soporte para archivos de subtítulos (ASS, SSA, SRT, etc.)
- Reconocimiento y traducción de voz en tiempo real
<p align="center"><img style="width: 90%; height: 90%" src="images/live_translation_bbc.png?raw=true" alt="Interfaz Web para Reconocimiento de Voz y Traducción en Tiempo Real"/></p>

### Pestaña `Generación de Voz`
- Opciones: **Edge-TTS**, **F5-TTS**, **CosyVoice**, **kokoro**
- Podcasts con voces de celebridades y soporte multilingüe
<p align="center"><img style="width: 90%; height: 90%" src="images/tts_f5_multi.png?raw=true" alt="Interfaz Web para Producción de Podcasts usando Tecnología de Clonación de Voz"/></p>

### 🔥 Pestaña `AI Cover`
- Eliminación vocal: **MDX-Net**, **Demucs**
- Modulación de voz: **RVC**
- Descarga voces IA en [Discord AI Hub](https://discord.com/channels/1159260121998827560/@home) o solicita a través de <abus.aikorea@gmail.com>
<p align="center"><img style="width: 90%; height: 90%" src="images/ai_cover.png?raw=true" alt="Interfaz Web para Producción de Podcasts usando Tecnología de Clonación de Voz"/></p>

## 💻 Requisitos del Sistema
- **SO:** Windows 10/11 (64 bits) ※ Linux/Mac no soportados
- **GPU:** NVIDIA con soporte CUDA 12.4 (recomendado)
- **VRAM:** 4 GB o más (8 GB+ preferible)
- **RAM:** 4 GB o más
- **Almacenamiento:** Al menos 20 GB de espacio libre
- **Internet:** Requerido

## 📀 Instalación

Instala Voice-Pro fácilmente con **configure.bat** y **start.bat**.

### 1. Preparación del Paquete
- Descarga la versión más reciente en [![GitHub Release](https://img.shields.io/github/v/release/abus-aikorea/voice-pro)](https://github.com/abus-aikorea/voice-pro/) (**Source code (zip)**)
```bash
git clone https://github.com/abus-aikorea/voice-pro.git
```


### 2. Instalación y Ejecución
1. 🚀 **configure.bat**
   - Instala git, ffmpeg y CUDA (si usas GPU NVIDIA)
   - Ejecútalo solo una vez; requiere internet, puede tomar más de 1 hora
   - No cierres la ventana de comandos
2. 🚀 **start.bat**
   - Inicia la interfaz web de Voice-Pro
   - En la primera ejecución, instala dependencias (puede tomar más de 1 hora)
   - En caso de problemas, elimina **installer_files** y ejecuta de nuevo

### 3. Actualización
- 🚀 **update.bat**: Actualiza el entorno Python (más rápido que reinstalar)

### 4. Desinstalación
- Ejecuta **uninstall.bat** o elimina la carpeta (instalación portátil)

## ❓ Consejos de Uso

#### Si el navegador no se abre automáticamente
- Cierra la ventana de comandos de Windows y ejecuta **start.bat** nuevamente
- Abre el navegador manualmente e introduce la dirección mostrada en la ventana de comandos (ej.: **http://127.0.0.1:7892**)

#### Si ocurre un error CUDA Out-of-Memory
- Verifica el estado de la memoria GPU en el Administrador de Tareas de Windows - pestaña "Rendimiento"
- Configura el nivel de eliminación de ruido en 0 o 1 (el nivel 2 requiere al menos 8 GB de memoria GPU)
- Establece el tipo de cálculo en "int" (el tipo "float" ofrece mejor calidad, pero requiere más memoria GPU)

#### ¿Cómo mejorar la calidad de los subtítulos?
- Los modelos Whisper más grandes tienden a mejorar la calidad de los subtítulos (large > medium > small > base > tiny), pero no siempre es así
- Entre los tipos de cálculo, "float" ofrece buen rendimiento; "int" reduce el uso de GPU y aumenta la velocidad mediante cuantización del modelo, pero con pérdida de rendimiento
- Aumentar el nivel de eliminación de ruido elimina más sonidos de fondo y usa solo la voz restante para el reconocimiento, pero no siempre garantiza mejores resultados

## 📢 Advertencias

Windows Defender podría mostrar una advertencia sobre una aplicación no confiable y bloquear la ejecución adicional de Voice-Pro.
- **Configuración "Advertencia" de SmartScreen:** Haz clic en "Más información" y luego en "Ejecutar de todos modos"
- **Configuración "Bloquear" de SmartScreen:** Abre las propiedades de **start.bat**, marca "Desbloquear", aplica los cambios y ejecuta **start.bat** nuevamente
<p align="center"><img style="width: 40%; height: 40%" src="images/windows_smartscreen_warning.png?raw=true" alt=""/></p>

Cuando Windows Defender reconoce erróneamente un archivo por lotes como un troyano, esto se denomina a menudo "Falso Positivo". Para resolver este problema, sigue estos pasos:
1. **Manejo de excepciones de archivo:** En Windows Defender, puedes configurar archivos o procesos específicos para omitir la verificación de seguridad. Sigue estos pasos:
   - Haz clic en el botón "Inicio" y ve a "Configuración"
   - Haz clic en "Actualización y Seguridad"
   - Selecciona "Seguridad de Windows" y ve a "Protección contra virus y amenazas"
   - Haz clic en "Administrar configuraciones de protección contra virus y amenazas"
   - Selecciona "Agregar una exclusión" en "Configuraciones de protección contra virus y amenazas"
   - Elige "Archivo o Carpeta", localiza el archivo por lotes problemático y agrégalo como excepción
2. **Desactivar temporalmente Windows Defender:** Esto puede ser una solución temporal. Sin embargo, ten cuidado al usar este método, ya que tu computadora podría quedar expuesta a otras amenazas
3. **Reportar el problema al software antivirus:** Si estás seguro de que el archivo no es un troyano, puedes informarlo a Microsoft como "Falso Positivo". Microsoft lo revisará y tomará las medidas necesarias


## 🚨 Aviso
- Este repositorio ofrece una **prueba gratuita** de Voice-Pro.
- La versión de prueba gratuita de Voice-Pro le permite procesar hasta **60 segundos** de medios.
- La versión oficial de Voice-Pro se puede comprar a través del sitio web oficial de ABUS (<https://abuskorea.imweb.me>).


## ☕ Contribuciones
- Si desea participar y ayudarnos con este proyecto, no dude en crear un [Issues](https://github.com/abus-aikorea/voice-pro/issues).
- Si algo sale mal, envíe un [Pull requests](https://github.com/abus-aikorea/voice-pro/pulls) para mejorar este proyecto.
- Cualquier tipo de contribución es bienvenida.
- Para consultas relacionadas con compras, asociaciones comerciales, ajustes técnicos, inversiones y otros asuntos, contáctenos por correo electrónico (<abus.aikorea@gmail.com>).
- Si le gusta este proyecto, por favor, marque este repositorio con una estrella. Lo agradeceríamos mucho. ⭐⭐⭐
- Puede apoyar a Voice-Pro con una donación aquí:

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/abus)



## 📬 Contacto
- Correo: <abus.aikorea@gmail.com>
- Página principal (Coreano): <https://abuskorea.imweb.me>
- Amazon: [US](https://www.amazon.com/dp/B0DBR69JPL) | [Japan](https://www.amazon.co.jp/dp/B0DBVRJ542) | [Singapore](https://www.amazon.sg/dp/B0DCGKL8R4) | [UAE](https://www.amazon.ae/dp/B0DCGKM7FF)
- Naver: [Software](https://smartstore.naver.com/abus/products/10385660040) | [Solución](https://smartstore.naver.com/abus/products/10298346364)

## 👍 YouTube
- [Información del Producto](https://www.youtube.com/watch?v=z8g8LMhoh_o&list=PLwx5dnMDVC9Y7dAjm9r26CZUw1uU5VIeq)
- [Karaoke: Pop](https://www.youtube.com/watch?v=MqQP3ewvJUk&list=PLwx5dnMDVC9bVxfGo58U-R-w3fUHqwiD6) | [K-Pop](https://www.youtube.com/watch?v=v6qjf_ELsLA&list=PLwx5dnMDVC9Z8kB01tQKfzTysaCCxC3C8) | [J-Pop](https://www.youtube.com/watch?v=KKLzoWHFAxw&list=PLwx5dnMDVC9bd6y3wXs-bOas2cXIi-GAq)

## 🙏 Créditos
- Demucs: <https://github.com/facebookresearch/demucs>
- yt-dlp: <https://github.com/yt-dlp/yt-dlp>
- gradio: <https://github.com/gradio-app/gradio>
- edge-TTS: <https://github.com/rany2/edge-tts>
- F5-TTS: <https://github.com/SWivid/F5-TTS.git>
- openai-whisper: <https://github.com/openai/whisper>
- faster-whisper: <https://github.com/SYSTRAN/faster-whisper>
- whisper-timestamped: <https://github.com/linto-ai/whisper-timestamped>
- RVC-Project: <https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI>
- UVR5: <https://github.com/Anjok07/ultimatevocalremovergui>

## ©️ Derechos de Autor
<img src="images/ABUS-logo.jpg" width="100" height="100"> por [ABUS](https://abuskorea.imweb.me)