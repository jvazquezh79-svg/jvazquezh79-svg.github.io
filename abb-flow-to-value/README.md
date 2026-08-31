# ABB Flow-to-Value Simulator v5

**[Abrir el simulador](https://jvazquezh79-svg.github.io/abb-flow-to-value/)** · [Página principal](https://jvazquezh79-svg.github.io/)

Práctica individual para el programa Flow-to-Value de ABB. Integra simulación de desempeño operativo, cálculo de OEE y decisiones de mejora mediante TPM, RCA, A3 y 8D.

## Contenido

| Módulo | Actividades |
| --- | --- |
| Simulación y OEE | Generar datos sintéticos de un turno y calcular disponibilidad, rendimiento, calidad y OEE. |
| TPM | Seleccionar acciones de mantenimiento autónomo, registrar microparos y definir estándares de inspección y auditoría. |
| RCA | Priorizar pérdidas con Pareto, clasificar hipótesis con Ishikawa, seleccionar evidencias y aplicar los 5 Porqués. |
| A3 / 8D | Construir un A3 mediante arrastrar y soltar; distinguir contención, causa raíz, corrección, prevención y verificación. |
| Decisiones y cierre | Definir responsabilidades y métricas, revisar la puntuación final y discutir los aprendizajes. |

El módulo A3/8D es una práctica de conceptos y decisiones; no es un sistema de gestión de expedientes 8D.

## Cómo utilizarlo

1. Abre el [enlace de acceso](https://jvazquezh79-svg.github.io/abb-flow-to-value/) y pulsa **Iniciar**.
2. Revisa las reglas y las fórmulas de OEE.
3. Pulsa **Simular nuevo turno** y utiliza los datos generados en el cálculo.
4. Introduce los porcentajes sin el símbolo `%`, con punto o coma decimal. La tolerancia de evaluación es de ±0.30 puntos porcentuales.
5. Completa las preguntas y el ejercicio de construcción del A3; revisa la puntuación al final.

Se recomienda utilizar una computadora con ratón o panel táctil para el ejercicio de arrastrar y soltar.

## Uso sin conexión y datos

La aplicación está contenida en `index.html`, con sus estilos y lógica incluidos. Para usarla sin conexión, descarga ese archivo y ábrelo en un navegador moderno. No requiere instalación ni cargar una hoja de cálculo.

Los datos del ejercicio son sintéticos y no representan información operativa real, confidencial o histórica de ABB. El simulador no incorpora cuentas, backend, analítica ni envío de respuestas. El progreso se mantiene en memoria durante la sesión; al recargar se reinicia. GitHub Pages sirve el archivo cuando se utiliza el enlace público; el vínculo de LinkedIn requiere conexión si se abre.

## Publicación

Esta carpeta se publica como `/abb-flow-to-value/` desde el repositorio del sitio personal. La página principal y su README incluyen un enlace al simulador.

La publicación conserva la lógica de la copia `abb_flow_to_value_simulator_v5_dragdrop_a3.html`. Se actualizó el rótulo visible de v3 a v5 y se retiró un script externo de Kaspersky incrustado en el HTML descargado, ajeno al funcionamiento de la aplicación.

## Autoría y alcance

**Dr. Jesús Vázquez Hernández** · [LinkedIn](https://www.linkedin.com/in/jvazquezh/)

Aplicación educativa para ABB, 2026. © Todos los derechos reservados, conforme al aviso del archivo original. La publicación pública no concede una licencia adicional de reutilización. No sustituye procedimientos técnicos, de mantenimiento o de seguridad de la planta.
