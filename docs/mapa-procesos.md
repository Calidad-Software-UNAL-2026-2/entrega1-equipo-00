# Mapa de Procesos y Modelo de Ciclo de Vida

> Generado con el workflow de flujo único. La definición formal del
> modelo de ciclo de vida (justificación, orden, relación entre
> procesos) se documenta en la wiki, página `04c-Modelo-Ciclo-Vida`,
> no en este archivo.

## Proceso: Requisitos

- **Entradas:** Modelo verbal extendido, necesidades de negocio e interesados
- **Actividades:** Elicitación, análisis y especificación de requisitos
- **Salidas:** Documento de especificación de requisitos
- **Recursos:** BABOK v3, entrevistas/supuestos del equipo

## Proceso: Diseño

- **Entradas:** Documento de especificación de requisitos
- **Actividades:** Definición de módulos, interfaces y decisiones de diseño
- **Salidas:** Vista arquitectónica del sistema
- **Recursos:** Requisitos funcionales/no funcionales priorizados

## Proceso: Implementación

- **Entradas:** Vista arquitectónica del sistema
- **Actividades:** Construcción de los módulos definidos en el diseño
- **Salidas:** Componentes de software construidos
- **Recursos:** Estándares de codificación, entorno de desarrollo

## Proceso: Testing

- **Entradas:** Componentes de software construidos
- **Actividades:** Diseño y ejecución de pruebas, registro de defectos
- **Salidas:** Reporte de pruebas, defectos identificados
- **Recursos:** Plan de pruebas, casos de prueba

### Proceso: Pruebas de integración del software

- **Entradas:** API de ingesta y dashboard en entorno de pruebas (procesos anteriores); requisitos funcionales y no funcionales (Paso 2)
- **Actividades:** Diseño y ejecución de casos de prueba de integración entre API y dashboard, pruebas de carga sobre la ingesta, verificación de los criterios de aceptación, registro y corrección de defectos
- **Salidas:** Reporte de pruebas de software; lista de defectos y su estado; software validado para la integración final
- **Recursos:** Plan de pruebas, framework de pruebas automatizadas, herramienta de pruebas de carga, entorno de pruebas

