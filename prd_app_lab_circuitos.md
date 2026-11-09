# PRD: Asistente Rápido de Laboratorio de Circuitos (ProtoPin / LabCircuit)

## Problema
Estudiantes de primeros semestres de ingeniería mecatrónica o electrónica pierden tiempo buscando conexiones y descifrando hojas de datos (datasheets) de 40 páginas solo para saber el orden de los pines, voltaje de trabajo o valor de resistencia. Queman componentes por error o no terminan montajes en clase.

## Usuario Objetivo
Estudiantes en laboratorio armando prototipos en protoboard que necesitan consultar datos puntuales en segundos desde el celular sin manuales técnicos densos.

## Funcionalidades Principales
1. **Circuitos Básicos y Lista de Materiales**: Selección de circuito (LED con resistor, Op-Amp LM741 no inversor, Timer 555 monoestable/astable, divisor de tensión), lista de componentes requeridos.
2. **Calculadoras Rápidas de Resistencias**: Resistencia para LED (Vs, Vled, Iled), divisor de voltaje (Vin, Vout deseado -> R1, R2 comercial), amplificador no inversor (ganancia -> Rf, R1).
3. **Esquema Rápido y Guía de Conexión en Protoboard**: Numeración de pines, diagrama visual claro de cableado y pines.
4. **Buscador de Pinout Express**: Búsqueda rápida por código ("LM741", "NE555", "2N2222", "7805") mostrando diagrama de pines y voltaje de operación (Vcc min/max).
5. **Checklist de Seguridad y Checklist Pre-Energizado**: Recomendaciones rápidas (polaridad, desacoplo, no cablear con fuente encendida, límites de voltaje).

## Fuera de Alcance (Out of Scope)
- No simula circuitos ni detecta errores automáticos.
- No genera circuitos con IA.
- No analiza fotos con visión artificial.
- No muestra datasheets completos de 40 páginas.
- No calcula potencias complejas o leyes generales extensas.
