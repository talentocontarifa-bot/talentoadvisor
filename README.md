# Talento Advisor - Auditoría Digital

Este proyecto es una herramienta de diagnóstico interactiva para **Talento con Tarifa**.
Ayuda a calificar prospectos automáticamente y recomendar el servicio ideal basado en su etapa de negocio, presupuesto e identidad visual.

## Estructura del Proyecto
- `index.html`: Lógica principal y estructura del formulario.
- `style.css`: Estilos visuales con diseño "Pop Art / Vibrant".
- `assets/`: Imágenes y recursos gráficos.

## Lógica de Diagnóstico
El sistema evalúa 3 factores clave:
1. **Etapa del Negocio** (Semilla, Validación, Tracción)
2. **Identidad Visual** (Amateur vs Profesional)
3. **Presupuesto** (Bajo, Medio, Alto, Top)

Dependiendo de la combinación, el algoritmo deriva al usuario a una de las 4 soluciones:
- **Paquete Génesis**: Si la identidad es Amateur.
- **Opción DIY**: Presupuesto bajo/medio.
- **Opción DFY**: Presupuesto alto/top + Identidad Pro.
- **No Califica**: Etapa semilla sin presupuesto.

## Despliegue
Este proyecto es estático y está listo para desplegarse en **GitHub Pages**.

---
*Desarrollado para Talento con Tarifa*
