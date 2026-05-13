# Plan Narrativo y Arquitectura del Micrositio SellUp

## 1. Entendimiento ejecutivo del proyecto
**SellUp** (provisionalmente Sales Engine UBITS) no es una simple colección de "bots" o la integración de Gems de Gemini. Es una **capacidad comercial estratégica** diseñada para transformar un proceso de ventas hoy fragmentado y manual en un sistema inteligente, conectado y escalable.

- **Qué busca resolver:** Elimina los cuellos de botella en la prospección, la preparación inconsistente de llamadas, el riesgo operativo y la lentitud en la generación de cotizaciones, y la falta de visibilidad gerencial sobre el pipeline en tiempo real.
- **Por qué no es solo unificar Gems:** Las Gems son "cerebros" aislados sin manos ni memoria. SellUp les da **capacidad de ejecución** (integración con HubSpot y Slack), **persistencia** (base de datos propia) y **gobierno** (reglas de negocio y trazabilidad), convirtiéndolas de curiosidades tecnológicas en herramientas productivas.
- **Oportunidad Estratégica:** Representa el paso de una "artesanía de ventas" a una "ingeniería de ventas", permitiendo que el equipo comercial se enfoque en la relación y el cierre, mientras la IA orquesta la inteligencia, los datos y la documentación necesaria para ganar deals.

## 2. Audiencia principal del micrositio
- **Stakeholders C-Level y Directivos de Ventas/Operaciones:** Personas que deciden sobre presupuesto, estrategia y adopción tecnológica.
- **Qué necesitan entender:** El valor de negocio, el retorno de inversión (ahorro de tiempo y aumento de efectividad), la viabilidad técnica y el nivel de riesgo/control.
- **Decisiones esperadas:** 
    1. Validar la visión de largo plazo (Arquitectura Backend Agentic).
    2. Aprobar el alcance del MVP (Preparación + Cotización).
    3. Definir la ruta de inversión (Piloto vs. Construcción robusta).

## 3. Objetivo narrativo del HTML
El micrositio debe contar una historia de **evolución y control**.
- **La historia:** "Hoy operamos con fricción y datos dispersos. SellUp es el motor que unifica nuestra inteligencia comercial para escalar nuestras ventas de forma predecible."
- **Sentimiento:** El stakeholder debe sentir que la propuesta es sólida, analizada a profundidad (no es "humo" de IA) y que tiene el control sobre cómo se construye y cuánto cuesta.
- **Nivel:** Altamente ejecutivo en la superficie, con "capas de profundidad" técnica accesibles para quienes deseen validar la robustez de la propuesta.

## 4. Arquitectura narrativa recomendada
La estructura sigue un flujo de **Problema -> Solución -> Decisión**:

1.  **Apertura (The Vision):** Impacto inmediato de SellUp.
2.  **Diagnóstico (The Reality):** El flujo actual y sus dolores (empatía con el problema).
3.  **El Motor (The Logic):** Cómo funcionan los agentes y qué capacidades habilitan.
4.  **Evaluación (The Path):** Comparativa de las 4 rutas tecnológicas.
5.  **Recomendación y Economía (The Plan):** Costos, fases y sugerencia técnica.
6.  **Cierre (The Call to Action):** Decisiones requeridas.

## 5. Secciones mínimas y estructura
| Sección | Objetivo de comunicación | Mensaje clave | Contenido | Visual recomendado | Profundidad |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Hero / Apertura** | Impacto y propósito | "Vender más, con más inteligencia y menos fricción." | Título potente, visión 360 y valor agregado. | Video de fondo sutil / Animación de "motor". | Alta |
| **El Reto / Diagnóstico** | Validar los dolores | "Nuestro proceso actual tiene fugas de tiempo y consistencia." | Resumen de los 5 dolores críticos. | Heatmap de dolores en el funnel. | Media |
| **Flujo Comercial** | Entender el contexto | "SellUp se inserta en cada etapa vital del vendedor." | Mapa de etapas desde prospección a cierre. | Timeline interactivo del Journey. | Baja |
| **Capacidades (Agentes)** | Mostrar la "magia" real | "7 Agentes especializados trabajando en sincronía." | Grid de agentes con funciones y outputs. | Cards interactivas / Diagrama de red. | Media |
| **Rutas de Solución** | Transparencia técnica | "Evaluamos 4 caminos según velocidad y robustez." | Resumen de las 4 alternativas (Platform, Slack, Claude, Backend). | Matriz 2x2 (Velocidad vs Robustez). | Alta |
| **Comparativa Visual** | Facilitar la elección | "La mejor opción depende de nuestra ambición." | Tabla comparativa de fortalezas y límites. | Matriz comparativa interactiva. | Alta |
| **Economía de IA** | Realismo financiero | "IA escalable con costos controlados y trazables." | Costos de construcción vs ejecución (tokens). | Gráfico de barras de costos por fase. | Alta |
| **Recomendación** | Dirección estratégica | "Backend propio: La base para un sistema sin límites." | Justificación de la ruta recomendada. | Diagrama de arquitectura simplificado. | Media |
| **Ruta de Despegue** | Plan de acción | "Validar rápido, construir sólido, escalar fuerte." | Roadmap en 3 fases: Piloto, MVP, Escala. | Roadmap horizontal / Gantt ejecutivo. | Media |
| **Decision Hub** | Provocar el cierre | "El futuro de Sales Engine empieza con estas 5 decisiones." | Listado de decisiones estratégicas pendientes. | Checklist interactivo / Formulario. | Alta |

## 6. Visualizaciones recomendadas
- **Funnel de Dolores:** Un embudo comercial donde se resaltan visualmente las "fricciones" (puntos calientes) que SellUp resuelve.
- **Radar de Agentes:** Un gráfico donde se vea qué agentes cubren qué dolores, demostrando cobertura total.
- **Matriz de Alternativas:** Un comparador dinámico donde el usuario pueda filtrar por "Prioridad: Velocidad" o "Prioridad: Escalabilidad" y vea qué opción se ilumina.
- **Calculadora de Impacto (Sugerida):** Un pequeño widget donde se pueda proyectar el ahorro de tiempo (ej: "Ahorro de 4h/semana por BD").
- **Arquitectura "Lego":** Un visual que muestre cómo el Backend Agentic es la base sobre la que se "conectan" Slack o la Plataforma.

## 7. Qué contenido resumir y qué evitar
- **Esencial (Visible):** Dolores de negocio, recomendación final, costos operativos y fases de entrega.
- **Detalle (Expandible):** Lógica técnica de prompts de cada agente, límites exactos de tokens de Claude 3.5, detalles de integración de API de HubSpot.
- **Evitar:** Jerga técnica excesiva (ej: "RAG", "Embeddings", "Chain of Thought") a menos que sea en modales de "Saber más". No saturar con los 22 documentos de una vez; usar la síntesis.

## 8. Recomendación de tono y estilo
- **Tono:** "El Consultor Experto". Seguro, analítico, innovador pero pragmático.
- **Estilo Visual:** Premium Enterprise (Dark mode elegante con acentos en colores UBITS, uso de gradientes sutiles, tipografía moderna como *Outfit* o *Inter*).
- **Copy:** Enfocado en verbos de acción y resultados de negocio (ej: "Acelerar la cotización", "Eliminar la incertidumbre", "Unificar la inteligencia").

## 9. Jerarquía de mensajes
1.  **Principal:** SellUp es el sistema operativo inteligente que Sales necesita para escalar.
2.  **Secundario 1:** No es solo IA, es un sistema conectado a HubSpot y Slack.
3.  **Secundario 2:** La cotización es el corazón operativo que debemos proteger y automatizar.
4.  **Secundario 3:** Tenemos una ruta clara de inversión y construcción por fases.
5.  **Cierre:** La decisión técnica de hoy define nuestra capacidad competitiva de mañana.

## 10. Riesgos narrativos a evitar
- **El "Efecto Magia":** No presentar la IA como algo que lo hace todo solo. Siempre enfatizar el "Human-in-the-loop" (validación humana).
- **Parálisis por Análisis:** Evitar que la comparativa de 4 opciones confunda. El micrositio debe guiar fuertemente hacia la recomendación.
- **Sesgo de Herramienta:** No dejar que parezca que "nos gusta n8n" o "nos gusta Claude", sino que elegimos lo que mejor sirve al negocio.

## 11. Propuesta de experiencia de navegación
- **Navegación Narrativa (Scroll-based):** La página se lee como una presentación fluida hacia abajo.
- **Quick Jump Lateral:** Menú de puntos lateral para saltar a secciones específicas durante una reunión (ej: "Ir directo a costos").
- **Interacción Selectiva:** Tabs para cambiar entre las 4 soluciones y comparar rápidamente.
- **Modales de Profundidad:** Para que un stakeholder técnico pueda dar clic en un agente y ver su "Ficha Técnica" sin ensuciar la vista ejecutiva.

## 12. Estructura final recomendada (Resumen)
| Orden | Sección | Objetivo | Visual principal | Prioridad |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Hero | Enganche y Visión | Video/Hero dinámico | Crítica |
| 2 | Diagnóstico | Validar urgencia | Heatmap de Dolores | Alta |
| 3 | Solución SellUp | Presentar el concepto | Diagrama de Ecosistema | Crítica |
| 4 | Los 7 Agentes | Demostrar valor | Grid de Cards Interactivas | Alta |
| 5 | Comparativa 4 Rutas | Facilitar decisión | Matriz Comparativa | Crítica |
| 6 | Economía y Costos | Viabilidad financiera | Gráfico de Costos/Tokens | Media |
| 7 | Recomendación | Definir rumbo | Arquitectura Estratégica | Crítica |
| 8 | Roadmap | Mostrar el "Cómo" | Línea de tiempo de fases | Alta |
| 9 | Decisiones | Cerrar el acuerdo | Checklist de Stakeholder | Crítica |

## 13. Preguntas o vacíos detectados
1.  **Naming Final:** Aunque SellUp es el nombre provisional, el documento 21 usa intensivamente "Sales Engine". Se requiere confirmar si el micrositio usará la marca **SellUp** como identidad visual o se mantendrá como **Sales Engine** por formalidad institucional.
2.  **Urgencia de Cotización:** En los documentos se menciona como "obligatoria" y "crítica", pero también se sugiere validarla primero. Hay una ligera ambigüedad sobre si el MVP *debe* incluirla funcionalmente desde el día 1 o si el primer MVP es solo "Cognitivo" (Inteligencia + Speech). Mi recomendación en el micrositio será incluirla en el MVP Operativo.
3.  **Presupuesto de Licencias Claude:** Si se elige la Opción 3, ¿existe ya un estimado de cuántos vendedores recibirán licencias? Esto cambia drásticamente la comparación económica vs. el Backend Propio.
4.  **Propiedad del Backend:** ¿Quién mantendrá el Backend Agentic? (¿TI UBITS, un proveedor externo, el equipo de producto?). Esta decisión de "ownership" es vital para la decisión de stakeholders.
