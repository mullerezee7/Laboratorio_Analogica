# 🛰️ Subsistema Satelital Analógico - Proyecto Integrador

Este repositorio contiene el diseño, simulación e implementación en hardware de los subsistemas electrónicos analógicos para un modelo satelital cúbico, desarrollado como proyecto integrador para la materia Laboratorio de Electrónica Analógica.

**Autores:** Kevin Miranda, Ezequiel Müller

## 📐 Arquitectura de Hardware
El diseño se basa en un enfoque modular jerárquico dividido en cuatro placas físicas independientes, integradas a través de un proyecto maestro en KiCad.

*   **`/hardware/satelite_integrado`**: Proyecto maestro en KiCad con hojas jerárquicas y PCB final.
*   **`/hardware/sistemas_temperatura`**: Monitoreo (LM35), control térmico y redundancia de sensores.
*   **`/hardware/sistemas_solares_1`**: Detección de eclipses y orientación solar mediante cuadrantes de LDRs.
*   **`/hardware/sistemas_solares_2`**: Temporización analógica y control de propulsión.
*   **`/hardware/alimentacion`**: Selección de fuente, supervisión de bus de potencia con comparadores de ventana, filtros activos (Sallen-Key) y protección contra sobrecorriente.

## 🛠️ Herramientas Utilizadas
*   **Diseño de PCB y Esquemáticos:** KiCad
*   **Simulación de Circuitos:** LTspice, Proteus
*   **Componentes Clave:** LM35, LM358, IRF530, LTC7652, CD4066, OPA2186.

## 📄 Documentación
El análisis matemático, cálculos de componentes, capturas de osciloscopio y resultados empíricos de las pruebas en protoboard se encuentran detallados en el informe técnico del proyecto.

