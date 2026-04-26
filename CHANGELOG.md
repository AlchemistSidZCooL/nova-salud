# Changelog - NOVA Health

Todos los cambios notables en este proyecto serán documentados en este archivo.

## [4.7.3] - 2026-04-26 "Shift-Ready Synchronization"
### Modificado
- **Banner de Acción Crítica:** Actualizada la alerta superior para mostrar la siguiente dosis (23:30 - 8ª Ronda) tras completar la de las 15:30.
- **Sincronización Git:** Optimización del flujo de push manual para actualizaciones en tiempo real durante el trayecto al trabajo.

## [4.7.2] - 2026-04-26 "Real-Time Environment & Weather"
### Añadido
- **Módulo de Clima en Tiempo Real:** Integración de la API de Open-Meteo en el header para monitorizar la temperatura de Madrid (25°C actual) y prevenir golpes de calor post-operatorios.
- **Versionado Interno:** Sincronización de las etiquetas de versión (v4.7.2) en el <title> y el header del Dashboard para auditoría visual rápida.

## [4.7.1] - 2026-04-26 "Dashboard Decluttering"
### Modificado
- **Piloto Automático:** Limpieza de tareas completadas (Ducha, Comida). Enfoque exclusivo en "Mochila Decathlon" y "Salida Metro".
- **Registro de Medicación:** Marcado manual de la 7ª Ronda (Amoxi + Enantyum) como tomada a las 16:06.

## [4.7.0] - 2026-04-26 "Neuro-Pacing (Slow Walk Protocol)"
### Añadido
- **Protocolo de Paso Lento:** Ajuste del cronograma de salida a las 16:17 (en lugar de 16:07) para permitir una caminata sin prisas hacia el metro, reduciendo el riesgo de aumento de tensión arterial.

## [4.6.9] - 2026-04-26 "L4 -> L1 Metro Optimization"
### Modificado
- **Ruta Estratégica de Transporte:** Cálculo y documentación de la ruta óptima (Línea 4 a Línea 1 via Bilbao) para llegada exacta a las 16:44 (Marqués de Viana 15).

## [4.6.7] - 2026-04-26 "Symptom Control: Bleeding Resolved"
### Eliminado
- **Módulo de Control de Sangrado:** Eliminación del bloque de emergencia por hemorragia tras confirmarse la estabilización total de los coágulos.

## [4.6.5] - 2026-04-26 "Active Duty & Crisis Resolution"
### Modificado
- **Estado Laboral:** Transición de estado "Baja Prevista" a "Modo Supervivencia (Turno Activo)".
- **Gestión de Crisis [EXE]:** Resolución exitosa del dilema "Salud vs Trabajo" mediante comunicación asertiva, protegiendo tanto los ingresos como las restricciones físicas.

## [4.6.4] - 2026-04-26 "Hygiene Protocol & Day Shift"
### Añadido
- **Protocolo de Higiene Seguro:** Documentación estricta sobre el orden de limpieza (Cepillado -> Enjuague de agua con sal) y prohibición de escupir para evitar la alveolitis.
- **Sincronización al Domingo:** Actualización del panel de Piloto Automático y Cuadrante en el Dashboard para reflejar el inicio del Domingo 26 (Día Crítico de Reposo).

## [4.6.3] - 2026-04-25 "Labor vs Clinical Risk Alignment"
### Añadido
- **Módulo de Gestión de Crisis Laboral:** Integración de un panel de advertencia sobre el dilema salud vs presión externa (Contexto Oliver).
- **Sincronización Cronológica:** Ajuste global de fechas al Sábado 25, sincronizando el Cuadrante de Vive Madrid y los protocolos de medicación.
- **Análisis de Neurodiversidad [EXE]:** Incorporación de notas sobre Disfunción Ejecutiva y Parálisis por Análisis ante la amenaza de despido.

## [4.6.2] - 2026-04-24 "Night Shift & Dopamine Routing"
### Añadido
- **Alarma Visual Dinámica:** Integración de un banner gigante en la cabecera del dashboard que indica claramente el próximo evento crítico (07:30 AM).
- **Directrices de Reposo y Química:** Documentación de hacks de dopamina seguros para el TDAH (música, frío, hiperfoco) como sustitutos a estímulos nocivos (tabaco/cocaína) prohibidos durante la cicatrización.
- **Protocolo Laboral:** Evaluación médica de riesgo que contraindica el trabajo físico (hostelería) a las 24-48h post-extracción múltiple para evitar hemorragias.

### Modificado
- **Registro de Medicación:** Bloques de las 15:30 y 23:30 marcados como completados (`done`) con estampas de tiempo exactas.

## [4.6.1] - 2026-04-24 "Crisis Management & Time Tracking"
### Añadido
- **Cronómetro de Intervención:** Implementación de un contador en tiempo real (`time-since-surgery`) para medir el tiempo exacto transcurrido desde la cirugía.
- **Pauta de Medicación Detallada:** Bloque visual específico con los horarios y dosis exactas de Amoxicilina (750mg) y Enantyum (25mg) sincronizados a las 07:30, 15:30 y 23:30.

### Modificado
- **Expediente Clínico:** Actualización del historial y Dashboard reflejando **3 extracciones** en lugar de 1, ajustando el Plan Maestro a la realidad clínica.
- **Protocolos de Asistencia:** Corrección semántica crítica sobre el manejo de gasas (instrucción de extraer con dedos en lugar de "escupir" para evitar riesgo de Alveolitis Seca).

## [4.6.0] - 2026-04-24 "Semantic Digitalization (TDAH/TEA Accessibility)"
### Cambiado
- **Expediente de Alta Legibilidad:** Eliminación total de enlaces a imágenes JPG. Reemplazo por componentes `<details>` nativos en HTML con el contenido de las recetas y pautas de Sanitas estructurado en listas claras.
- **Accesibilidad Cognitiva:** Textos adaptados para lectura rápida bajo fatiga extrema (colores semánticos, negritas estratégicas, cero fricción de clics extra).
- **Reintegración de Contexto:** Restauración de tutoriales de pomada oftálmica y diccionario de fases que se habían omitido, asegurando contexto total en una sola pantalla.

## [4.5.0] - 2026-04-24 "Priority-Driven Architecture"
### Añadido
- **Jerarquía de Supervivencia:** Reestructuración visual del dashboard (`Gestion_Salud_Daniel.html`) priorizando los módulos de urgencia vital (Hemorragia) en la parte superior.
- **Piloto Automático:** Guía de supervivencia hora por hora adaptada a turnos laborales rotativos (Hoy libre / Mañana turno 17h-05h).

## [4.4.0] - 2026-04-24 "Hemostasis & Dual Sync"
### Añadido
- **Módulo de Hemostasia:** Panel de control para el manejo de gasas, con reglas de oro ("NO escupir", "NO pajitas").
- **Meds Sync v2.0:** Sincronización dual de tratamientos (Oftalmológico + Dental) en franjas de 8 horas.

## [4.3.0] - 2026-04-24 "Nexus Protocol"
### Añadido
- **Arquitectura de Portabilidad:** Creación de `NOVA_Health_Schema.json` para migración de datos y protocolos a otros sistemas de gestión.
- **Módulo de Salud Mental (Neuro-Nexus):** Implementación del sistema **N-Log** para el registro estratégico de síntomas TDAH/TEA.
- **Relojes Mundiales Sincronizados:** Integración de Madrid y Colombia en tiempo real con lógica de estado social.
- **Traductor de Fases:** Sección pedagógica en el dashboard para simplificar términos médicos complejos.

## [4.3.1] - 2026-04-24
### Rectificación
- **Datos Reales:** Se procesó el zip `Photos-3-002.zip` con las evidencias de la cita de hoy (24/04).
- **Evidencias Actualizadas:**
  - Receta de Amoxicilina y Enantyum.
  - Pautas postoperatorias oficiales de Sanitas (Págs 1 y 2).
  - Presupuesto de Periodoncia/Curetaje.
- **Limpieza:** Eliminación de archivos obsoletos procesados por error del zip anterior.

## [4.3.0] - 2026-04-24
### Añadido
- **Módulo de Evidencias Clínicas:** Integración de galería digitalizada en el dashboard principal.
- **Nexus Protocol v4.3:** Refinamiento de la arquitectura de datos para soportar evidencias visuales.

## [4.2.0] - 2026-04-24
### Añadido
- **Nexus Protocol:** Evolución de la identidad del sistema hacia un protocolo de gestión clínica integral.
- **Módulo Neuro-Nexus:** Sistema N-Log para documentación estratégica de síntomas TDAH/TEA.
- **Dashboard v4.2:** Integración de relojes mundiales (Madrid/Colombia) y lógica de sincronización horaria.
- **Diccionario Médico:** Traducción de terminología técnica dental a lenguaje humano.
- **Portabilidad:** Generación de `NOVA_Health_Schema.json` para interoperabilidad de datos.

---
*Formato basado en [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).*
