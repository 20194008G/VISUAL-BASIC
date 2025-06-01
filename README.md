# Cronograma Semanal de Desarrollo del Proyecto

## Fase Inicial (Semanas 1-5)
| Semana | Actividad | Entregables | Responsable |
|--------|-----------|-------------|-------------|
| 1 | Presentación del proyecto y revisión bibliográfica | Documento de contexto tecnológico | Todo el equipo |
| 2-3 | Definición de solución técnica (autónoma/semi-autónoma) | Propuesta técnica con análisis comparativo | Líder técnico |
| 4 | Formación de equipos y asignación de roles | Acta de constitución con cronograma específico | Coordinador |
| 5 | Especificación de requisitos técnicos | Documento de alcance con métricas de validación | Ingeniero de sistemas |

## Fase de Desarrollo (Semanas 6-12)
| Semana | Actividad | Entregables | Recursos Requeridos |
|--------|-----------|-------------|---------------------|
| 6-7 | Investigación de mercado y estado del arte | Benchmark de competidores + informe CAPECO | Laboratorio GMIDEI |
| 8-9 | Diseño CAD y selección de componentes | Modelos 3D + lista de materiales cotizados | SolidWorks, Inventor |
| 10 | Desarrollo de núcleo SLAM (ROS2) | Repositorio GitHub con paquetes básicos | Jetson Nano, LIDAR |
| 11-12 | Pruebas de simulación en Gazebo | Video demostrativo + reporte de validación | Estación de simulación |

## Fase de Implementación (Semanas 13-16)
| Semana | Hito | Criterios de Éxito | Riesgos |
|--------|------|---------------------|---------|
| 13 | Integración mecánica-electrónica | Prototipo ensamblado al 85% | Retraso en importación |
| 14 | Calibración sensorial y pintura | Manual de procedimientos | Error de precisión >±3mm |
| 15 | Pruebas de campo en obra controlada | Certificado de cumplimiento ODS | Condiciones climáticas |
| 16 | Presentación final y documentación | Informe técnico + pitch ejecutivo | - |

## Diagrama de Dependencias
```mermaid
gantt
    title Cronograma del Proyecto
    dateFormat  YYYY-MM-DD
    section Fase Inicial
    Investigación          :a1, 2024-03-01, 21d
    Definición técnica     :after a1, 14d
    section Fase Desarrollo
    Diseño CAD            :2024-04-01, 21d
    Desarrollo software   :2024-04-15, 28d
    section Fase Final
    Pruebas integradas    :2024-05-10, 21d
    Documentación         :2024-05-25, 14d
