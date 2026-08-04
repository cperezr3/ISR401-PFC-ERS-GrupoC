# ISR401-PFC-ERS-GrupoC

## Sistema

**CarniCore** — Sistema de Trazabilidad, Pesaje Inteligente e Inventario para Distribuidora de Cárnicos Pucayacu, La Maná, Cotopaxi.

Proyecto Fin de Curso – Ingeniería de Requerimientos (ISR-401 / 20303), Universidad Técnica Estatal de Quevedo (UTEQ).

---

## Integrantes – Grupo C

- Calle Delgado Kamila Annabella
- Macías Herrera Josthyn Esteban
- Pérez Ruiz Carlos Andrés

---

## Estructura de carpetas

```text
ISR401-PFC-ERS-GrupoC/
├── README.md
├── CHANGELOG.md
├── 01_ERS/
├── 02_Inspeccion/
├── 03_CCB/
├── 04_Trazabilidad/
├── 05_Informe/
└── 06_Evidencias/
```

La descripción detallada de la estructura del repositorio puede consultarse en el informe de la Práctica Experimental – Unidad IV.

---

## Compilación del informe

**Compilador**

- pdfLaTeX (TeX Live 2023 o superior / MiKTeX equivalente)

**Archivo principal**

```
05_Informe/main.tex
```

**Dependencias**

- referencias.bib (BibTeX)
- longtable
- booktabs
- hyperref
- fancyhdr
- tabularx

(Todos disponibles en una instalación estándar de TeX Live o MiKTeX).

---

## Orden de compilación

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```
