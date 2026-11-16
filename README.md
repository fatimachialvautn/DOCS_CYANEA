# Cyanea - Gestión Integral de Viajes Grupales

## Descripción del Proyecto
**Cyanea** es una plataforma unificada (móvil y web) diseñada para optimizar la organización de viajes en grupo. El sistema permite centralizar en un solo lugar la gestión de itinerarios, el registro y división de gastos y la toma de decisiones colaborativas mediante un sistema de votaciones.

El objetivo principal es reducir la desorganización, los errores organizativos y la falta de claridad financiera que suele ocurrir al utilizar múltiples herramientas no integradas como WhatsApp o planillas de cálculo.

## Integrantes del Grupo
* **Chialva, Fátima**: 95147
* **Correa, Luciano**: 69323
* **Gatica, Andrea Ticiana**: 94371
* **Giampieri, Lucia**: 96505
* **Paez, Maria Candela**: 95256

## Índice
1. [Descripción del Proyecto](#descripción-del-proyecto)
2. [Estructura del Repositorio](#estructura-del-repositorio)
3. [Listado de Ítems de Configuración](#listado-de-ítems-de-configuración)
4. [Política de Versionado de Documentos](#política-de-versionado-de-documentos)
5. [Convenciones de Commits](#convenciones-de-commits)
6. [Glosario](#glosario)

## Estructura del Repositorio
La organización de los Ítems de Configuración sigue la siguiente jerarquía de directorios:

```text
DOCS_CYANEA
│
├── README.md
├── SeguimientoDocumentacion
├── RegistroErroresModificaciones
│
├── 00_Plantillas
│   └── Plantilla_<<Tipo>>_vX.Y
│
├── 01_EstudioInicial
│   └── EstudioInicial_vX.Y
│
├── 02_Sprint0_InicioYPlanificacion
│   ├── ProjectCharter_vX.Y
│   ├── PlanDeProyecto
│   │   ├── DeclaracionAlcance_vX.Y
│   │   ├── WBS_vX.Y
│   │   ├── Cronograma_vX.Y
│   │   ├── PlanDeRiesgos_vX.Y
│   │   └── Presupuesto_vX.Y
│   ├── WorkingAgreement_vX.Y
│   ├── ProductBacklog_vX.Y
│   ├── StoryMapping_vX.Y
│   ├── GestionDeConfiguracion_vX.Y
│   ├── ArquitecturaYStack_vX.Y
│   └── PlanDeTesting_vX.Y
│
├── 03_Sprints
│   ├── GraficosMetricas
│   └── Sprint_<<NS>>
│       └── InformeSprint_<<NS>>_vX.Y
│
├── 04_Trazabilidad
│   ├── Trazabilidad_vX.Y
│   ├── ModeloDeDatos_vX.Y
│   ├── DiagramasDeSecuencia_vX.Y
│   ├── DiagramasDeDespliegue_vX.Y
│   └── EspecificacionAPIs_vX.Y
│
├── 05_EntregaFinal
│   ├── 5K4G14_CYANEA_<<N>>.<<pdf/jpg/mp4>>
│   ├── Paper_vX.Y
│   ├── Poster_vX.Y
│   ├── Video_vX.Y
│   ├── Caratula
│   └── PlanillaDeCatalogacion
│
├── 06_DocumentacionFinal
│   ├── ManualDeUsuario_vX.Y
│   ├── ManualInstalacion_vX.Y
│   ├── ProcesoPostImplementacion_vX.Y
│   ├── ImpactoAmbiental_vX.Y
│   └── RetrospectivaFinal_vX.Y
│
├── 07_IdentidadDeMarca
│   └── <<Recurso>>.<<svg/png/pdf>>
│
└── 08_IdeaProyecto
    └── <<Documento>>
```

> **Formato de los archivos.** En el Google Drive compartido se mantiene la versión editable de cada documento (Google Docs / Sheets). En este repositorio se versiona la exportación a `.pdf` (documentos) o `.xlsx` (planillas) de cada versión aprobada. El nombre del archivo es el mismo en ambos lugares; solo cambia la extensión.

> **Sprint 0 vs. seguimiento de sprints.** `02_Sprint0_InicioYPlanificacion` reúne los documentos de la etapa de inicio y planificación: todo lo que define el proyecto y arma el ambiente antes de comenzar a desarrollar. Estos documentos pueden actualizarse durante el proyecto (registrándolo en su Historial de Revisión), pero se originan en el Sprint 0. `03_Sprints` contiene únicamente el seguimiento de las iteraciones de desarrollo (Sprint 1 en adelante), cada una con su Informe de Sprint.

## Listado de Ítems de Configuración

| Ítem de Configuración | Regla de Nombrado | Ubicación |
| :--- | :--- | :--- |
| **Plantilla** | `Plantilla_<<Tipo>>_vX.Y` | `DOCS_CYANEA/00_Plantillas` |
| **Estudio Inicial** | `EstudioInicial_vX.Y` | `DOCS_CYANEA/01_EstudioInicial` |
| **Declaración del Alcance** | `DeclaracionAlcance_vX.Y` | `DOCS_CYANEA/02_Sprint0_InicioYPlanificacion/PlanDeProyecto` |
| **WBS** | `WBS_vX.Y` | `DOCS_CYANEA/02_Sprint0_InicioYPlanificacion/PlanDeProyecto` |
| **Cronograma** | `Cronograma_vX.Y` | `DOCS_CYANEA/02_Sprint0_InicioYPlanificacion/PlanDeProyecto` |
| **Plan de Gestión de Riesgos** | `PlanDeRiesgos_vX.Y` | `DOCS_CYANEA/02_Sprint0_InicioYPlanificacion/PlanDeProyecto` |
| **Presupuesto** | `Presupuesto_vX.Y` | `DOCS_CYANEA/02_Sprint0_InicioYPlanificacion/PlanDeProyecto` |
| **Project Charter** | `ProjectCharter_vX.Y` | `DOCS_CYANEA/02_Sprint0_InicioYPlanificacion` |
| **Working Agreement** | `WorkingAgreement_vX.Y` | `DOCS_CYANEA/02_Sprint0_InicioYPlanificacion` |
| **Product Backlog** | `ProductBacklog_vX.Y` | `DOCS_CYANEA/02_Sprint0_InicioYPlanificacion` |
| **Story Mapping** | `StoryMapping_vX.Y` | `DOCS_CYANEA/02_Sprint0_InicioYPlanificacion` |
| **Plan de Gestión de la Configuración** | `GestionDeConfiguracion_vX.Y` | `DOCS_CYANEA/02_Sprint0_InicioYPlanificacion` |
| **Arquitectura y Stack Tecnológico** | `ArquitecturaYStack_vX.Y` | `DOCS_CYANEA/02_Sprint0_InicioYPlanificacion` |
| **Plan de Testing** | `PlanDeTesting_vX.Y` | `DOCS_CYANEA/02_Sprint0_InicioYPlanificacion` |
| **Informe de Sprint** | `InformeSprint_<<NS>>_vX.Y` | `DOCS_CYANEA/03_Sprints/Sprint_<<NS>>` |
| **Gráficos de Métricas** | `GraficosMetricas` | `DOCS_CYANEA/03_Sprints` |
| **Trazabilidad (especificación de US, criterios y casos de prueba)** | `Trazabilidad_vX.Y` | `DOCS_CYANEA/04_Trazabilidad` |
| **Modelo de Datos (DER)** | `ModeloDeDatos_vX.Y` | `DOCS_CYANEA/04_Trazabilidad` |
| **Diagramas de Secuencia** | `DiagramasDeSecuencia_vX.Y` | `DOCS_CYANEA/04_Trazabilidad` |
| **Diagramas de Despliegue** | `DiagramasDeDespliegue_vX.Y` | `DOCS_CYANEA/04_Trazabilidad` |
| **Especificación de APIs** | `EspecificacionAPIs_vX.Y` | `DOCS_CYANEA/04_Trazabilidad` |
| **Entregable de Cátedra** | `5K4G14_CYANEA_<<N>>.<<pdf/jpg/mp4>>` | `DOCS_CYANEA/05_EntregaFinal` |
| **Paper de Investigación** | `Paper_vX.Y` | `DOCS_CYANEA/05_EntregaFinal` |
| **Póster Técnico** | `Poster_vX.Y` | `DOCS_CYANEA/05_EntregaFinal` |
| **Video Demostrativo** | `Video_vX.Y` | `DOCS_CYANEA/05_EntregaFinal` |
| **Carátula** | `Caratula` | `DOCS_CYANEA/05_EntregaFinal` |
| **Planilla de Catalogación** | `PlanillaDeCatalogacion` | `DOCS_CYANEA/05_EntregaFinal` |
| **Manual de Usuario** | `ManualDeUsuario_vX.Y` | `DOCS_CYANEA/06_DocumentacionFinal` |
| **Manual de Instalación** | `ManualInstalacion_vX.Y` | `DOCS_CYANEA/06_DocumentacionFinal` |
| **Proceso Post Implementación** | `ProcesoPostImplementacion_vX.Y` | `DOCS_CYANEA/06_DocumentacionFinal` |
| **Impacto Ambiental** | `ImpactoAmbiental_vX.Y` | `DOCS_CYANEA/06_DocumentacionFinal` |
| **Retrospectiva Final** | `RetrospectivaFinal_vX.Y` | `DOCS_CYANEA/06_DocumentacionFinal` |
| **Identidad de Marca** | `<<Recurso>>.<<svg/png/pdf>>` | `DOCS_CYANEA/07_IdentidadDeMarca` |
| **Idea de Proyecto** | `<<Documento>>` | `DOCS_CYANEA/08_IdeaProyecto` |
| **Seguimiento de Documentación** | `SeguimientoDocumentacion` | `DOCS_CYANEA` |
| **Registro de Errores y Modificaciones** | `RegistroErroresModificaciones` | `DOCS_CYANEA` |

**Reglas generales de nombrado**
- Nombres en *PascalCase*, sin espacios, tildes, eñes ni caracteres especiales (`/`, `\`, `:`).
- La versión se separa del nombre con guion bajo: `<<Nombre>>_vX.Y`.
- Al publicar una nueva versión se reemplaza el archivo anterior con el nuevo número de versión; el historial queda en el repositorio y en la sección *Historial de Revisión* del documento.

## Política de Versionado de Documentos
- Cada documento incluye una sección **Historial de Revisión** con versión, fecha, autores y descripción del cambio. Toda modificación debe registrarse allí antes de exportar y versionar el archivo.
- **X** (versión mayor) se incrementa ante cambios de estructura o de contenido sustancial (por ejemplo, correcciones integrales de la tutora); **Y** (versión menor) ante ajustes puntuales.
- **Product Backlog y Story Mapping:** son documentos vivos. Sus versiones posteriores **no se crean como archivos nuevos**: se registran en el mismo documento, en la sección *Evolución del Backlog*, indicando el sprint en que se produjo el cambio, las historias agregadas, modificadas, reestimadas o eliminadas y la justificación de cada cambio.
- Los documentos que se especifican de forma consolidada (Trazabilidad, Diagramas de Secuencia) se organizan internamente en una sección por historia de usuario, identificada por su ID.

## Convenciones de Commits
Para mantener un historial de cambios limpio y trazable en la documentación, se debe seguir la siguiente regla, basada en *Conventional Commits* (ver Working Agreement):

**Formato:** `docs(<carpeta>): <verbo en presente> <artefacto> v<X.Y>`

### Ejemplos:
* `docs(sprint0): agrega project charter v1.0`
* `docs(sprint0): actualiza product backlog v2.0 con cambios del sprint 5`
* `docs(sprint-01): agrega informe sprint 1 v1.0`
* `docs(sprint0): actualiza cronograma v2.1`
* `docs(trazabilidad): agrega especificación US13 Crear viaje a trazabilidad v1.1`
* `docs(doc-final): agrega manual de usuario v1.0`

## Glosario
- **vX.Y** → Versión del documento (X: versión mayor, Y: versión menor).
- **NS** → Número de Sprint.
- **N** → Número de entregable según la nomenclatura de la cátedra.
- **US** → User Story (Historia de Usuario).
- **IC** → Ítem de Configuración.
- **DER** → Diagrama Entidad-Relación.
- **WBS** → Work Breakdown Structure (Estructura de Desglose del Trabajo).
- **API** → Application Programming Interface.
