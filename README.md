[README (1).md](https://github.com/user-attachments/files/32756856/README.1.md)
# AxTrade Config - Español

Configuración personalizada en español para **AxTrade**, diseñada para ofrecer un sistema de intercambios claro, organizado y fácil de utilizar dentro de servidores Minecraft.

La configuración modifica tanto la interfaz principal de intercambio como los mensajes enviados por chat. El diseño utiliza un estilo visual limpio con secciones de información, estados de confirmación, ofertas de dinero y experiencia, y mensajes administrativos adaptados al español.

## Vista previa de la configuración

### Ayuda administrativa

Muestra los comandos principales de AxTrade para jugadores y administradores, incluyendo envío, aceptación y rechazo de solicitudes, activación o desactivación de intercambios, recarga del plugin, intercambio forzado y vista previa de la interfaz.

![Ayuda administrativa](screenshots/01-ayuda-administrativa.png)

---

### Recarga de configuración

Mensaje mostrado al ejecutar la recarga de AxTrade correctamente, permitiendo verificar que los cambios de configuración fueron aplicados sin errores.

![Recarga de configuración](screenshots/02-recarga-configuracion.png)

---

### Activar y desactivar solicitudes de intercambio

Ejemplo de los mensajes enviados cuando el jugador utiliza el sistema de toggle para dejar de recibir solicitudes de intercambio o volver a habilitarlas.

![Activar y desactivar solicitudes](screenshots/03-toggle-solicitudes.png)

---

### Interfaz principal de Trade

Vista general de la GUI de intercambio entre dos jugadores. Cada lado dispone de sus propios espacios para objetos y opciones independientes para añadir dinero, experiencia y confirmar la oferta.

![Interfaz principal de Trade](screenshots/04-interfaz-trade.png)

---

### Confirmar oferta

Botón utilizado para confirmar que los objetos y monedas ofrecidos son correctos antes de completar el intercambio.

![Confirmar oferta](screenshots/05-confirmar-oferta.png)

---

### Cancelar confirmación

Una vez confirmada la oferta, el botón cambia de estado y permite cancelar la confirmación para modificar objetos, dinero o experiencia antes de finalizar el intercambio.

![Cancelar confirmación](screenshots/06-cancelar-confirmacion.png)

---

### Oferta de dinero

Opción destinada a añadir dinero al intercambio mediante una economía compatible con Vault. El lore muestra la cantidad ofrecida y permite modificarla directamente desde la interfaz.

![Oferta de dinero](screenshots/07-oferta-dinero.png)

---

### Oferta de experiencia

Permite incluir experiencia como parte del intercambio. La interfaz muestra la cantidad de EXP ofrecida y permite cambiarla desde el mismo menú.

![Oferta de experiencia](screenshots/08-oferta-experiencia.png)

---

### Estado del otro jugador

Indicador visual que informa si el otro jugador todavía no ha confirmado su oferta. Cuando confirma, el estado cambia para mostrar que ambas partes están listas para completar el intercambio.

![Estado del otro jugador](screenshots/09-estado-esperando.png)

---

## Características principales

- Interfaz de intercambio completamente adaptada al español.
- Diseño de lore limpio y organizado.
- Sistema visual de confirmación y cancelación.
- Oferta de objetos mediante espacios separados para cada jugador.
- Integración de dinero mediante Vault.
- Intercambio de experiencia.
- Mensajes de solicitudes, aceptación, rechazo y expiración traducidos.
- Mensajes administrativos y ayuda de comandos en español.
- Avisos de inventario lleno, distancia, mundos bloqueados y modos de juego restringidos.
- Sonidos configurados para diferentes acciones del sistema.
- Resúmenes de objetos y monedas entregados o recibidos después del intercambio.

## Archivos incluidos

- `config.yml` — ajustes generales de AxTrade.
- `guis.yml` — diseño de la interfaz de intercambio.
- `lang.yml` — mensajes y textos del plugin en español.
- `currencies.yml` — configuración de monedas compatibles.
- `toggled.yml` — almacenamiento del estado de solicitudes de intercambio.
- `assets/en_us.yml` — nombres de materiales utilizados por AxTrade.

## Instalación

1. Instala **AxTrade** en tu servidor.
2. Detén el servidor.
3. Sustituye los archivos correspondientes dentro de la carpeta de AxTrade por los incluidos en este repositorio.
4. Inicia nuevamente el servidor.
5. Comprueba la configuración utilizando `/axtrade preview` y `/axtrade reload`.

## Dependencia

Esta configuración **no incluye el plugin AxTrade**. Debes instalarlo por separado.

Documentación oficial: https://docs.artillex-studios.com/axtrade.html

## Créditos

Configuración personalizada por **Marco035xd**.

Créditos a **Artillex Studios** por el plugin AxTrade.
