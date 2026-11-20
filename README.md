# 4DX One · Generador de tableros ejecutivos

**Demo en vivo: [jvazquezh79-svg.github.io](https://jvazquezh79-svg.github.io/)**

## Simulador ABB Flow-to-Value

También disponible en este sitio: **[Abrir ABB Flow-to-Value Simulator v5](https://jvazquezh79-svg.github.io/abb-flow-to-value/)**.

Práctica interactiva de OEE, TPM, RCA, A3 y 8D, con turnos sintéticos, cálculos y construcción del A3 mediante arrastrar y soltar. Consulta sus [instrucciones y autoría](abb-flow-to-value/README.md). La herramienta 4DX continúa disponible en la página principal.

## Modelo de Madurez Lean Tools · ABB MTY 1.0

**[Abrir el Modelo de Madurez Lean Tools](https://jvazquezh79-svg.github.io/abb-madurez-lean-tools/)**.

Autoevaluación del nivel de madurez (0–4) de 14 herramientas Lean, con regla secuencial, demo guiada, versión ES/EN, roadmap de mejora y reporte ejecutivo en PDF. Consulta sus [instrucciones](abb-madurez-lean-tools/README.md).

---

Aplicación web para crear el *One-Page* ejecutivo de un equipo siguiendo **las 4 Disciplinas de la Ejecución (4DX)**, combinado con el formato *4-Blocker*. Genera un tablero semanal listo para presentar a dirección: meta crucial (WIG), medidas predictivas, compromisos semanales y bloqueos con decisión solicitada.

## Características

- **Asistente guiado en 6 pasos** con validación por paso, ejemplos y recomendaciones de llenado en cada campo.
- **Ejemplo guía incluido**: al abrir por primera vez puedes cargar un tablero completo de muestra que sirve como referencia de llenado.
- **Bilingüe**: interfaz completa en español e inglés (botón EN/ES); recuerda tu preferencia.
- **Semáforo automático**: el estado (En ruta / Atención / Bloqueado) se calcula con el avance esperado por fechas, el cumplimiento de las medidas predictivas y la severidad de los bloqueos.
- **Fotografías semanales**: guarda hasta 8 cortes semanales que alimentan la gráfica de tendencia y pueden recargarse.
- **Exportación**: descarga los datos en JSON (respaldo/importación), genera un HTML estático de solo lectura para compartir, o imprime en PDF con formato 16:9.
- **Modo presentación** de pantalla completa para la sesión WIG.
- **Sin dependencias**: un solo archivo HTML con CSS y JavaScript vanilla; funciona sin conexión una vez cargado.

## Uso

1. Abre [la página](https://jvazquezh79-svg.github.io/) o descarga `index.html` y ábrelo en tu navegador.
2. Elige «Ver ejemplo guía» para explorar un tablero completo, o «Comenzar en blanco».
3. Completa los 6 pasos del asistente; la vista previa se actualiza en tiempo real.
4. Al cierre de cada semana, guarda una fotografía y usa «Imprimir / PDF» o «Generar HTML» para distribuir el reporte.

## Privacidad de los datos

Los datos capturados **no se envían a ningún servidor**: se guardan únicamente en el `localStorage` del navegador de quien usa la página. Para respaldar o mover un tablero entre equipos, usa «Guardar JSON» e «Importar».

---

*Basado en la metodología* The 4 Disciplines of Execution *(McChesney, Covey y Huling, FranklinCovey).*
