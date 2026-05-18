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
1. [Descripción del Proyecto](#-descripción-del-proyecto)
2. [Estructura del Repositorio](#-estructura-del-repositorio)
3. [Listado de Ítems de Configuración](#-listado-de-items-de-configuracion)
4. [Convenciones de Commits](#-convenciones-de-commits)
5. [Glosario](#-glosario)

## Estructura del Repositorio
La organización de los Ítems de Configuración sigue la siguiente jerarquía de directorios:

```text
DOCS_CYANEA
│
├── README.md
│
├── 00_Plantillas
│   └── Plantilla_<<Tipo>>_vX.Y.<<docx/pdf>>
│
├── 01_EstudioInicial
│   └── EstudioInicial_vX.Y.pdf
│
├── 02_PlanDeProyecto
│   └── DefinicionAlcance_vX.Y.pdf
│
├── 03_Sprints
│   ├── Sprint_0
│   │   ├── WorkingAgreement_vX.Y.pdf
│   │   ├── GestionDeConfiguracion_vX.Y.pdf
│   │   ├── ArquitecturaYStack_vX.Y.pdf
│   │   ├── PlanDeTesting_vX.Y.pdf
│   │   └── BacklogInicial_vX.Y.pdf
│   └── Sprint_<<NS>>
│       └── InformeSprint_<<NS>>_vX.Y.pdf
│
├── 04_Trazabilidad
│   ├── Historias
│   │   └── US<<NUS>>_<<Nombre>>
│   │       ├── US<<NUS>>_<<Nombre>>_vX.Y.pdf
│   │       ├── Diagrama_<<Nombre>>_vX.Y.png
│   │       └── CasosPrueba_US<<NUS>>_vX.Y.xlsx
│   └── ModeloDatos
│       └── DER_vX.Y.png
│
├── 05_EntregaFinal
│   ├── Paper_vX.Y.pdf
│   ├── Poster_vX.Y.<<pdf/png>>
│   └── Video_vX.Y.mp4
│
└── 06_DocumentacionFinal
    ├── ProcesoPostImplementacion_vX.Y.pdf
    ├── InstructivoDeUso_vX.Y.pdf
    ├── ManualInstalacion_vX.Y.pdf
    ├── ImpactoAmbiental_vX.Y.pdf
    └── RetrospectivaFinal_vX.Y.pdf

```
## Listado de Ítems de Configuración

| Ítem de Configuración | Regla de Nombrado | Ubicación |
| :--- | :--- | :--- |
| **Plantilla** | `Plantilla_<<Tipo>>_<<vX.Y>>.<<docx/pdf>>` | `DOCS_CYANEA/00_Plantillas` |
| **Estudio Inicial** | `EstudioInicial_<<vX.Y>>.pdf` | `DOCS_CYANEA/01_EstudioInicial` |
| **Declaración del Alcance** | `DefinicionAlcance<<vX.Y>>.pdf` | `DOCS_CYANEA/02_PlanDeProyecto` |
| **Documento Sprint 0** | `<<Documento>>_<<vX.Y>>.pdf` | `DOCS_CYANEA/03_Sprints/Sprint_0` |
| **Informe de Sprint** | `InformeSprint_<<NS>>_<<vX.Y>>.pdf` | `DOCS_CYANEA/03_Sprints/Sprint_<<NS>>` |
| **Historia de Usuario** | `US<<NUS>>_<<Nombre>>_<<vX.Y>>.pdf` | `DOCS_CYANEA/04_Trazabilidad/Historias/US<<NUS>>_<<Nombre>>` |
| **Diagrama de Secuencia** | `Diagrama_<<Nombre>>_<<vX.Y>>.<<png/jpg>>` | `DOCS_CYANEA/04_Trazabilidad/Historias/US<<NUS>>_<<Nombre>>` |
| **Casos de Prueba** | `CasosPrueba_US<<NUS>>_<<vX.Y>>.xlsx` | `DOCS_CYANEA/04_Trazabilidad/Historias/US<<NUS>>_<<Nombre>>` |
| **Modelo de Datos** | `DER_<<vX.Y>>.png` | `DOCS_CYANEA/04_Trazabilidad/ModeloDatos` |
| **Paper de Investigación** | `Paper_<<vX.Y>>.pdf` | `DOCS_CYANEA/05_EntregaFinal` |
| **Póster Técnico** | `Poster_<<vX.Y>>.<<pdf/png>>` | `DOCS_CYANEA/05_EntregaFinal` |
| **Video Demostrativo** | `Video_<<vX.Y>>.mp4` | `DOCS_CYANEA/05_EntregaFinal` |
| **Post Implementación** | `ProcesoPostImplementacion_<<vX.Y>>.pdf` | `DOCS_CYANEA/06_DocumentacionFinal` |
| **Instructivo de Uso** | `InstructivoDeUso_<<vX.Y>>.pdf` | `DOCS_CYANEA/06_DocumentacionFinal` |
| **Manual Instalación** | `ManualInstalacion_<<vX.Y>>.pdf` | `DOCS_CYANEA/06_DocumentacionFinal` |
| **Impacto Ambiental** | `ImpactoAmbiental_<<vX.Y>>.pdf` | `DOCS_CYANEA/06_DocumentacionFinal` |
| **Retrospectiva Final** | `RetrospectivaFinal_<<vX.Y>>.pdf` | `DOCS_CYANEA/06_DocumentacionFinal` |

## Glosario
- **vX.Y** → Versión del documento (X: versión mayor, Y: versión menor).
- **NS** → Número de Sprint.
- **NUS** → Número de User Story (Historia de Usuario).
- **US** → User Story.
- **DER** → Diagrama Entidad-Relación.

## Convenciones de Commits
Para mantener un historial de cambios limpio y trazable en la documentación, se debe seguir la siguiente regla:

**Formato:** `docs(<carpeta>): <verbo en presente> <artefacto> v<X.Y>`

### Ejemplos:
* `docs(sprint-01): agrega informe sprint 1 v1.0`
* `docs(trazabilidad): agrega diagramas y casos de prueba HU01 Login v1.0`
* `docs(doc-final): agrega instructivo de uso v1.0`
