# Evaluación comparativa de Whisper y Vosk

Proyecto de investigación cuyo objetivo es comparar el desempeño de los modelos Whisper y Vosk para la clasificación de la fluidez lectora utilizando un corpus de voz en español.

## Objetivos

- Adaptar un dataset de voz.
- Evaluar Whisper.
- Evaluar Vosk.
- Comparar WER.
- Comparar latencia.
- Comparar WCPM.

## Estructura

data/

notebooks/

results/

reports/

models/

src/

## Dataset
Este proyecto utiliza el dataset:

Mozilla Common Voice Spontaneous Speech 4.0 - Spanish

Descargar desde:
https://mozilladatacollective.com/datasets/cmqi28y2v004imf076oh7e5zs

# Configuración del entorno

## Crear el entorno virtual

```bash
python -m venv .venv
```

Activar:

```bash
.\.venv\Scripts\activate
```

## Instalar dependencias

```bash
pip install -r requirements.txt
```

## Instalar FFmpeg

Descargar desde:

https://ffmpeg.org/download.html

Agregar la carpeta `bin` al PATH del sistema.

Verificar:

```bash
ffmpeg -version
```