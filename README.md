# Diseño e implementación de una solución personalizada para la automatización de facturación con integración bancaria en una empresa automotriz

Proyecto Final de Ingeniería en Informática — Facultad de Ingeniería,
Universidad del Salvador.

**Autor:** Esteban Nicolas Hernandez
**Decano:** Walter Oscar Rodríguez Esquivel
**Director de carrera:** Germán Buchniv
**Profesor y tutor:** Esteban Tissera

## Resumen

El trabajo aborda la automatización del proceso de facturación de unidades
financiadas en una empresa automotriz con operaciones en Chile y Perú. Se
diseñó una solución que integra los sistemas internos de la empresa con las
APIs REST de las entidades bancarias para consultar y actualizar en forma
automática las líneas de crédito de los concesionarios, informar las
facturas emitidas y registrar la trazabilidad de cada comunicación,
reemplazando la carga manual de saldos y el intercambio de planillas.

## Compilar

Requisitos: TeX Live (incluye `pdflatex`, `biber` y `makeglossaries`).

```bash
git clone https://github.com/hernandez-esteban-usal/tesis-facturacion-automatizada.git
cd tesis-facturacion-automatizada
latexmk main.tex
```

`latexmk` ejecuta pdfLaTeX, biber y makeglossaries en el orden necesario y
genera `main.pdf`.

## Estructura

| Archivo | Contenido |
|---|---|
| `main.tex` | Datos del trabajo y orden de los capítulos |
| `preliminares/` | Agradecimientos, resumen, abstract, declaración sobre el uso de IA, glosario y siglas |
| `capitulos/01` a `08` | Introducción · Metodología de la investigación · Síntesis de la literatura consultada · Justificación técnica y diseño de la solución · Justificación económica · Riesgos · Presentación de resultados · Implicaciones, conclusiones y recomendaciones |
| `apendices/` | Guía y registro de las entrevistas a usuarios referentes |
| `figuras/` | Imágenes del trabajo |
| `refs.bib` | Bibliografía (estilo APA, procesada con biber) |

## Versión entregada

La versión final corresponde al tag `entrega-final`.

---

Basado en el template oficial de la cátedra:
<https://github.com/Noorman999/usal-proyecto-final-template>
