# Limitaciones del prototipo v0

- **Todo es simulado.** No hay backend, cuentas, base de datos ni envío real de mensajes.
- **Datos ficticios.** Valentina, Diego, la abuela Elsa, Rosa, Joaquín, Emilia, Carla, Ezequiel, Inés, Sofi, Benja y las familias G., L., R. y M. son personajes de ejemplo. No pueden usarse nombres del equipo, de la founder ni de ninguna persona entrevistada o encuestada, ni derivados (D-010).
- **WhatsApp simulado, con reglas reales (D-016).** Las pantallas de chat imitan WhatsApp y solo muestran lo que se puede hacer:
  - **Lo que manda una persona** (invitaciones, ofrecer lugares, sumarse, pasar una tarea, compartir en un grupo): Poolcito abre WhatsApp con el texto y el link listos (wa.me u hoja de compartir) y la persona toca enviar. Poolcito no escribe en nombre de nadie ni publica solo en grupos.
  - **Lo que manda Poolcito** (repaso de la noche anterior, «llegaron», avisos de cambios a quien no tiene la app): mensajes individuales desde un número de empresa con la API de WhatsApp Business, con plantillas aprobadas, consentimiento y costo por mensaje. No puede escribir en grupos.
  - **Tarjetas:** son la vista previa del link (Open Graph). No tienen botones y no se actualizan después de enviadas; los datos al día se ven al abrir el link.
  - Poolcito no puede leer los grupos de WhatsApp ni saber si un mensaje se envió: se entera cuando alguien abre el link.
- **Seguimiento simulado.** El banner en vivo y el mapa del viaje son dibujos fijos. En una web app la ubicación solo se comparte con la página abierta; seguir el viaje en segundo plano y el banner del sistema (Live Activities) requieren app nativa.
- **Recorrido en Google Maps.** El botón arma un link real de Google Maps. Las paradas son lugares públicos de ejemplo, no domicilios.
- **Sin autorización escolar real.** El botón «Enviar» de la autorización no hace nada.
- **Pantallas no cubiertas:** registro completo, edición de familia y actividades, eventos (cumpleaños), administración de grupos (quitar miembros, invitaciones vencidas), ajustes y privacidad, errores de red.
- **Decisiones pendientes** (ver `00-gobierno/preguntas-abiertas.md` en el proyecto): alcance a la familia responsable (Q-030), quitar calificaciones y «Mejor opción» (Q-017, Q-023), tipografías (Q-028), design system (Q-029).
- **Accesibilidad:** se respetan el contraste AA y los tamaños táctiles de 44 px o más. No se probó con lector de pantalla.
