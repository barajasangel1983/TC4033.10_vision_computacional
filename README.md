# TC4033.10 — Vision computacional para imágenes y video

**Alumno:** José Ángel Barajas Flores | A01797221
**Profesor titular:** Dr. Gilberto Ochoa Ruiz
**Tutor:** Mtra. Niza Salas Vargas
**Programa:** Maestría en Inteligencia Artificial (Tec Online)
**Período:** Septiembre–diciembre 2026 (12 semanas)

---

## Descripción

Repositorio de código y notebooks para el curso **TC4033.10 — Vision computacional para imágenes y video**. Aquí vivimos los ejercicios, los labs y el desarrollo del proyecto: procesamiento de imágenes/video con OpenCV, detección/segmentación con YOLO (ultralytics), y los pipelines de deep learning con PyTorch. Los notebooks se organizan por semana (`notebooks/semanaN/`).

---

## Estructura

```
TC4033.10_vision_computacional/
├── README.md
├── requirements.txt
├── LICENSE
├── .env.example
├── .gitignore
├── configs/           ← Configuraciones (YAML, JSON)
├── data/              ← Datos de trabajo (imágenes/video, archivos grandes gitignored)
├── docs/              ← Documentación adicional
├── models/            ← Checkpoints / pesos de modelos (gitignored)
├── notebooks/         ← Notebooks de laboratorio por semana
│   ├── semana1/
│   ├── ...
│   └── semana12/
├── scripts/           ← Scripts auxiliares
├── src/               ← Código fuente (módulos reutilizables)
└── tests/             ← Tests (pytest)
```

---

## Setup

```bash
python -m venv .venv
source .venv/bin/activate

# PyTorch con CUDA (instalar PRIMERO, antes de requirements.txt)
# Para laptop RTX 5080 (CUDA 12.4+):
pip install torch torchvision --index-url https://download.pytorch.org/whl/cu124

# Resto de dependencias
pip install -r requirements.txt

cp .env.example .env   # (solo si el curso requiere tokens externos)
```

> **Nota CUDA:** si tu entorno no es compatible con CUDA, usa la build CPU:
> `pip install torch torchvision` (sin `--index-url`).

---

## Proyecto por Etapas

_Pendiente — completar al recibir la forma de trabajo del curso._

| Etapa | Entregable | Semana estimada |
|-------|-----------|-----------------|
| 1 | [Pendiente] | Semana N |
| 2 | [Pendiente] | Semana N |

---

## Política de IA

En cada entrega se declara qué se delegó a la IA, qué se verificó y qué se corrigió.

---

## Referencias

- Scaffolding de investigación: `research/TC4033_VisionComputacional/` (workspace del agente Vision)
