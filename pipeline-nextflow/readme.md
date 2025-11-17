Esta carpeta contiene el workflow general que orquesta todas las etapas anteriores.

✔️ Contenido típico en Nextflow:

main.nf → define procesos (QC, trimming, alignment, etc.)

nextflow.config → parámetros, recursos, rutas, perfiles

Subworkflows para modularizar etapas

Perfiles para local/cluster/Docker/Singularity

Scripts auxiliares
 Objetivo

Automatizar y encadenar todos los pasos de:
QC → Preprocesamiento → Alineamiento → Cuantificación → DE → Visualización → Reporte
Además garantiza:

Reproducibilidad

Escalabilidad

Trazabilidad

Portabilidad (Docker/Singularity)
