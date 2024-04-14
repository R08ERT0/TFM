Los archivos TFM-x son los subprogramas de cada fase del TFM.
Fase 1 - generación de segmentaciones base.
Fase 2 - generación de los bordes.
Fase 3 - unión de superpíxeles considerados no pertenecientes a bordes.
Fase 4 - unión de superpíxeles considerados pertenecientes a bordes.
Fase 5 - unión final de los superpíxeles para generar la segmentación final.

El resto de programas son operaciones auxiliares que se van necesitando en cada fase del estudio.
Tests - contiene el calculo de los test que se usan para tomar las decisiones.
Megapixels - contiene operaciones que se realizan con los superpíxeles.
Bordes - genera los bordes de una segmentación dada de varias maneras.
Preprocesado - contiene herramientas de preprocesado usadas.
Carga fotos - contiene los comandos para extraer la información de los archivos de la BSDS500.
Caracteristicas - contiene las distintas caracerizaciones usadas en las fases 3 y 4.
Caracteristicas_med - contiene las caracterizaciones usadas en la fase final.
