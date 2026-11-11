# Poolcito · Seguimiento, prototipo y design system

> Estado: Provisional (decisión D-009, 03/11/2026). Las puertas 4 (alcance) y 5 (diseño) no están aprobadas.
> Datos ficticios · sin backend · sin integraciones.

Prototipo navegable de Poolcito para mostrar a la founder y al equipo de tecnología cómo se construye la app a partir de la investigación con familias.

## Sitio publicado
https://uffdg.github.io/poolcito-prototipo/

| Ruta | Qué es |
|---|---|
| `/` | Seguimiento del proyecto: etapas, puertas, entregables, decisiones y próximos pasos. Para actualizarlo, editá el bloque `DATA` al final de `index.html`. |
| `/prototipo/` | Prototipo de concepto navegable v0. |
| `/design-system/` | Design system v0. |

## Cómo ver el prototipo
Abrí `/prototipo/` en el navegador. No necesita instalar nada.

- **Columna izquierda:** las pantallas agrupadas por flujo del usuario (7 flujos) y los *Casos borde* (5). Arriba, «Ver todos los flujos» abre el mapa completo.
- **Centro:** el teléfono. Se navega tocando los botones de la app o con ← → del teclado.
- **Columna derecha:** arriba, el **flujo del usuario** de la pantalla actual (quién, para qué, pasos y ramas de casos borde; cada paso es clicable). Abajo, las notas de cada pantalla: qué feature es, qué resuelve, de qué evidencia sale, qué cambia respecto del diseño original, notas para tecnología y qué hipótesis testea.
- Los recuadros punteados **«Simular»** y **«Caso borde»** no son parte de la app: sirven para abrir las ramas del prototipo.
- Para ver solo el teléfono (por ejemplo, para capturas), agregá `&phone` al final del enlace: `prototipo/#h5&phone`.

## Recorrido
**Flujos del usuario:**
1. Armar el núcleo familiar: bienvenida → crear la cuenta → mi núcleo familiar (uno solo para los dos chicos) → invitar → invitación recibida.
2. Ver la agenda de todos: inicio (agenda única, filtrable por chico) → semana repartida → mis chicos → agenda de Joaquín → agenda de Emilia.
3. Repartir las tareas en casa: el reparto en casa (traslados y organización) → pasar una tarea → tarea pasada.
4. Pedir a la red: pedir → pedido enviado → acuerdo → recorrido → banner en vivo → seguimiento → traspaso → entregado.
5. Ofrecer un lugar: puedo llevar.
6. Grupos de actividades: crear grupo → grupo → personas.
7. Mi perfil y lo que pasó: mi perfil → actividad.

Navegación inspirada en Splitwise (D-013, D-014, D-015): núcleo familiar único, organización por chico y sin saldos entre familias.

**Casos borde:** nadie responde · cancelación de último momento · nadie confirma la llegada · hueco entre los dos hogares · cambio de horario.

## De dónde sale
- Insight (03/11): no es pedir una mano, es **gestionar en comunidad y distribuir responsabilidades**. Objetivo: **aminorar la carga cognitiva de quienes gestionan**, también con la familia responsable (otro hogar, abuelos, niñeras).
- Investigación: 5 entrevistas y encuesta con 19 respuestas (octubre de 2026). Los participantes se citan con códigos (P01 a P05).
- Diseño base: pantallas de la founder, ajustadas a la evidencia; tokens del design system v0.

Ver `LIMITACIONES.md`.
