# AxTrade Config - Español

Configuración personalizada en español para **AxTrade**, diseñada para ofrecer un sistema de intercambios claro, organizado y visualmente intuitivo para servidores de Minecraft.

La configuración adapta tanto la **interfaz principal de Trade** como los mensajes enviados por chat, manteniendo un diseño uniforme para objetos, dinero, experiencia, confirmaciones y estados del intercambio.

El objetivo es facilitar el uso del sistema para los jugadores, permitiendo identificar rápidamente qué están ofreciendo, modificar su propuesta y comprobar cuándo ambas partes están preparadas para completar el intercambio.

---

## Intercambio de experiencia

<img width="469" height="319" alt="Oferta de experiencia" src="https://github.com/user-attachments/assets/b53584fa-dab0-4494-9a17-7f3f8cb221c6" />

Sistema utilizado para añadir **experiencia (EXP)** como parte del intercambio.

La interfaz muestra la cantidad de experiencia que el jugador está ofreciendo y permite modificarla directamente antes de confirmar el Trade.

Esto permite combinar objetos, dinero y experiencia dentro de una misma negociación.

---

## Intercambio de dinero

<img width="412" height="307" alt="Oferta de dinero" src="https://github.com/user-attachments/assets/67492085-c387-48ee-95e3-14079166999f" />

Opción destinada a añadir **dinero** dentro del intercambio.

El jugador puede visualizar la cantidad económica incluida en su oferta y modificarla desde la propia interfaz antes de confirmar.

Esta función permite complementar los objetos ofrecidos utilizando la economía del servidor.

---

## Cancelación de confirmación

<img width="559" height="356" alt="Cancelar confirmación" src="https://github.com/user-attachments/assets/80d12c38-9e4f-4930-9b6e-8accc513d1f9" />

Una vez que el jugador confirma su oferta, el botón cambia de estado para indicar que se encuentra preparado.

Si necesita modificar algún objeto, dinero o experiencia, puede **cancelar la confirmación** antes de que el intercambio finalice.

---

## Confirmación de oferta

<img width="458" height="339" alt="Confirmar intercambio" src="https://github.com/user-attachments/assets/5d5b26d3-8045-47a6-b405-6cb454358fcf" />

Botón utilizado para **confirmar la oferta actual**.

Cuando el jugador considera que todos los objetos y valores introducidos son correctos, puede confirmar su parte del Trade y esperar a que el otro jugador haga lo mismo.

El intercambio solamente podrá completarse cuando ambas partes hayan confirmado.

---

## Interfaz principal de Trade

<img width="526" height="408" alt="Interfaz principal de AxTrade" src="https://github.com/user-attachments/assets/2501e69a-cbac-4c46-be2f-1861c9479ee8" />

Vista general de la **interfaz principal de intercambio de AxTrade**.

El menú separa claramente las zonas correspondientes a cada jugador y permite visualizar los objetos ofrecidos por ambas partes.

También incorpora controles independientes para:

- Añadir dinero.
- Añadir experiencia.
- Confirmar la oferta.
- Consultar el estado del otro jugador.

Todo el diseño utiliza textos y lores personalizados en español para facilitar su comprensión.

---

## Activar y desactivar solicitudes de Trade

<img width="925" height="72" alt="Activar y desactivar solicitudes de intercambio" src="https://github.com/user-attachments/assets/d3690287-7719-414d-8fdc-86fb669c85dd" />

Ejemplo del sistema utilizado para **activar o desactivar las solicitudes de intercambio**.

El jugador puede decidir si desea recibir nuevas invitaciones de Trade de otros usuarios.

El chat muestra un mensaje diferente cuando las solicitudes son desactivadas y cuando vuelven a habilitarse.

---

## Recarga de la configuración

<img width="814" height="94" alt="Recarga de configuración de AxTrade" src="https://github.com/user-attachments/assets/9690a529-2db4-46a6-a645-5e0bf2495676" />

Mensaje mostrado al realizar correctamente una **recarga de la configuración de AxTrade**.

Permite comprobar que los cambios realizados en los archivos fueron cargados nuevamente por el plugin y están disponibles dentro del servidor.

---

## Ayuda administrativa de AxTrade

<img width="789" height="373" alt="Comandos administrativos de AxTrade" src="https://github.com/user-attachments/assets/6abec5f3-a7ce-4354-a5c5-56a450876dcb" />

Vista del sistema de **ayuda de comandos de AxTrade**.

Desde este apartado pueden consultarse diferentes comandos relacionados con el funcionamiento y administración del sistema de intercambios, incluyendo opciones para enviar solicitudes, aceptar o rechazar intercambios, administrar jugadores y recargar la configuración.

La presentación ha sido adaptada al español para facilitar su utilización por parte de jugadores y administradores.

---

## Estado del otro jugador

<img width="483" height="317" alt="Estado esperando confirmación" src="https://github.com/user-attachments/assets/ee119b11-2113-44f7-9e94-1a56dd2ae414" />

Indicador visual encargado de mostrar el **estado de confirmación del otro jugador**.

Mientras la otra persona todavía no haya confirmado su oferta, la interfaz mostrará el estado **Esperando...**.

Cuando ambos jugadores hayan revisado y confirmado sus respectivas ofertas, el intercambio podrá finalizar.

Este sistema permite saber rápidamente cuál de las dos partes todavía necesita confirmar.

---

## Características principales

- Interfaz de intercambio completamente personalizada.
- Configuración adaptada al español.
- Diseño de lores limpio y organizado.
- Zona independiente para los objetos de cada jugador.
- Sistema de confirmación de ofertas.
- Posibilidad de cancelar una confirmación.
- Intercambio de dinero.
- Intercambio de experiencia.
- Estado visual del otro jugador.
- Sistema para activar o desactivar solicitudes de Trade.
- Mensajes de chat personalizados.
- Comandos administrativos traducidos.
- Mensaje personalizado de recarga.
- Diseño pensado para servidores Survival y modalidades con economía.
- Interfaz sencilla para facilitar los intercambios entre jugadores.

---

## Archivos incluidos

La configuración contiene los principales archivos utilizados por **AxTrade**:

- `config.yml`
- `currencies.yml`
- `guis.yml`
- `lang.yml`
- `toggled.yml`
- `assets/en_us.yml`

Los archivos mantienen la estructura necesaria para el funcionamiento del plugin mientras modifican su presentación, idioma y experiencia visual.

---

## Instalación

1. Instala **AxTrade** en tu servidor.
2. Inicia el servidor una vez para generar la carpeta del plugin.
3. Detén el servidor.
4. Sustituye los archivos correspondientes por los incluidos en esta configuración.
5. Inicia nuevamente el servidor.
6. Comprueba la interfaz y los mensajes dentro del juego.

---

## Dependencia

Esta configuración **no incluye el plugin AxTrade**.

Es necesario instalar previamente el plugin original.

Documentación oficial:

https://docs.artillex-studios.com/axtrade.html

---

## Créditos

Configuración creada y personalizada por **Marco035xd**.

Créditos a **Artillex Studios** por el desarrollo del plugin **AxTrade**.
