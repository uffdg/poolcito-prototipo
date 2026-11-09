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

- **Columna izquierda:** las pantallas, en dos grupos: *Camino feliz* (16) y *Casos borde* (5).
- **Centro:** el teléfono. Se navega tocando los botones de la app o con ← → del teclado.
- **Columna derecha:** las notas de cada pantalla: qué feature es, qué resuelve, de qué evidencia sale, qué cambia respecto del diseño original, notas para tecnología y qué hipótesis testea.
- Los recuadros punteados **«Simular»** y **«Caso borde»** no son parte de la app: sirven para abrir las ramas del prototipo.
- Para ver solo el teléfono (por ejemplo, para capturas), agregá `&phone` al final del enlace: `prototipo/#h5&phone`.

## Recorrido
**Camino feliz:** bienvenida → crear la cuenta → armar la red de los chicos e invitar (otra casa, abuela, niñera) → invitación recibida → inicio → mis chicos → ficha del chico (su red, su agenda y cómo se reparte) → grupo de la actividad → crear grupo → personas → mi perfil → actividad → semana repartida → pedir a la red → pedido enviado → acuerdo → armar el recorrido → banner en vivo → seguimiento → traspaso → entregado → puedo llevar. Navegación inspirada en Splitwise (D-013, D-014): la unidad es el chico y su red; sin saldos entre familias.

**Casos borde:** nadie responde · cancelación de último momento · nadie confirma la llegada · hueco entre los dos hogares · cambio de horario.

## De dónde sale
- Insight (03/11): no es pedir una mano, es **gestionar en comunidad y distribuir responsabilidades**. Objetivo: **aminorar la carga cognitiva de quienes gestionan**, también con la familia responsable (otro hogar, abuelos, niñeras).
- Investigación: 5 entrevistas y encuesta con 19 respuestas (octubre de 2026). Los participantes se citan con códigos (P01 a P05).
- Diseño base: pantallas de la founder, ajustadas a la evidencia; tokens del design system v0.

Ver `LIMITACIONES.md`.
