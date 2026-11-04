---
layout: default
lang: es
title: Política de privacidad
description: Política de privacidad de Balora. Tus datos financieros se quedan en tu móvil.
permalink: /es/privacidad/
home: /es/
alternates:
  en: /privacy/
  es: /es/privacidad/
  fr: /fr/confidentialite/
---

# Política de privacidad

<p class="updated">Última actualización: {{ site.updated.es }}</p>

<div class="summary" markdown="1">

**En resumen:** tus datos financieros se quedan en tu móvil. Balora no tiene permiso de internet, ni cuentas de
usuario, ni anuncios, ni analítica, ni seguimiento. El desarrollador nunca recibe tus movimientos, saldos ni importes.
Los datos solo salen del móvil cuando tú lo decides: al exportar una copia, al pasar tus datos a un móvil nuevo con
Android, al usar la copia en tu cuenta de Google de Balora Plus o al escribirnos un correo.

</div>

## 1. Responsable

Balora la desarrolla **{{ site.owner }}** ({{ site.country.es }}), responsable del tratamiento descrito en esta política.
Contacto: [{{ site.email }}](mailto:{{ site.email }}).

## 2. Qué guarda Balora en tu móvil

Todo lo que apuntas se guarda solo en el almacenamiento privado de la app, en tu móvil:

- Movimientos (gastos e ingresos), saldos de tus cuentas, categorías, presupuestos, movimientos recurrentes, etiquetas
  (viajes y proyectos) y ajustes.
- **Papelera:** lo que borras de Movimientos se guarda 30 días para que puedas restaurarlo; después se elimina solo, o
  antes si lo borras de la papelera (con la excepción que explica el apartado 12).
- **Perfiles:** si tienes varios (por ejemplo, uno personal y otro de trabajo), cada uno guarda sus datos y sus ajustes
  por separado, también dentro del móvil.
- **Importar extractos del banco:** el fichero que eliges (CSV, Excel, Norma 43, OFX, QIF o CAMT) se lee en el móvil
  y no se guarda. Balora conserva los
  movimientos que importas, el número de cuenta (IBAN) y el concepto original de cada movimiento importado, para no
  importar dos veces el mismo, y las plantillas de importación que guardes.
- **Copia automática interna:** cada día, después de tus cambios (como mucho una vez por hora) y al salir de la app si cambiaste algo, Balora guarda una copia
  de los datos de cada perfil en su almacenamiento privado, para poder recuperarlos si la base de datos se daña. Solo
  sale del móvil con la copia de seguridad de Android (apartado 3).
- **Imagen de «Tu año»:** al compartir tu resumen del año, Balora crea una imagen sin ningún importe en su memoria
  temporal; la sustituye la siguiente vez que compartes y Android puede borrarla cuando necesita espacio.

El desarrollador no tiene acceso a nada de esto. Al desinstalar la app o borrar sus datos, se elimina del móvil (salvo
las copias que hayas exportado tú).

## 3. Qué sale de tu móvil, y solo cuando tú lo decides

| Cuándo | Qué | Quién lo recibe |
|---|---|---|
| **Exportas una copia** | Todos tus datos de Balora, de todos tus perfiles, en un fichero cifrado con tu contraseña o en ficheros CSV (tú eliges) | Solo el sitio que elijas (el almacenamiento del móvil, un USB, un servicio en la nube que uses…) |
| Usas la **copia en tu cuenta de Google** (Balora Plus, desactivada hasta que la actives) | La copia automática de cada perfil y la lista de tus perfiles, mediante el servicio de copias de seguridad de Android | Tu cuenta de Google. Solo se envía con Android 9 o posterior y con el bloqueo de pantalla activado, cifrada de extremo a extremo con él, así que ni Google ni el desarrollador pueden leerla; en Android 8 no se envía. Si la desactivas o termina la suscripción, Balora deja de enviar copias nuevas (como mucho al día siguiente), y la última que ya estaba la conserva Google según su servicio de copias de seguridad. Google la trata según su [Política de privacidad](https://policies.google.com/privacy?hl=es) |
| **Cambias de móvil** con la transferencia de datos de Android | La copia automática de cada perfil y la lista de tus perfiles, copiadas directamente desde el móvil antiguo | Solo tu móvil nuevo |
| **Guardas el informe anual en PDF** (Balora Plus) | Las cifras del año que eliges: ingresos, gastos, balance y gasto por categoría y mes. Se genera en el móvil | Solo el sitio que elijas con el selector de archivos de Android |
| **Compartes «Tu año»** | Una imagen con tus logros del año (días con apuntes, rachas, mejor mes, categoría estrella, nivel de la mascota), sin ningún importe | La app o la persona que elijas en el menú de compartir de Android |
| **Nos escribes un correo** (también con «Enviar una sugerencia», que solo abre tu app de correo con nuestra dirección y un asunto) | Lo que escribas y tu dirección de correo. Balora no añade ningún texto ni dato al correo | El desarrollador, por correo desde tu propia app de correo |

«Recomendar la aplicación» abre el menú de compartir de Android con un mensaje y el enlace a la ficha de Google Play.
El enlace solo indica que la instalación viene de una recomendación (Google Play Console cuenta cuántas) y no lleva
ningún dato tuyo ni de tu móvil; lo envías tú a quien elijas.

## 4. Compras: Balora Plus y apoyo al desarrollo

Las suscripciones y los pagos de apoyo los gestiona **Google Play**. El desarrollador no recibe los datos de tu tarjeta
ni de tu pago. Google le facilita la información del pedido (número de pedido, producto, precio, país o región, fecha y
estado), que se usa solo para gestionar la compra y cumplir las obligaciones contables y fiscales. Google trata tu pago
según sus propias condiciones y política de privacidad. Para saber si tienes Balora Plus, Balora pregunta a la app de
Google Play de tu móvil al abrirse y una vez al día en segundo plano; esa consulta no envía ningún dato de Balora.

## 5. Informes de fallos

Si lo tienes permitido en los ajustes de Android (*Uso y diagnóstico*), Android puede enviar a Google informes de
cierres y bloqueos de la app, que el desarrollador ve de forma agregada en Google Play Console (Android vitals). Balora
no añade código propio para esto y los informes no contienen datos financieros. Puedes desactivarlo en los ajustes de
Android.

## 6. Valoraciones

Si Balora muestra la ventana de valoración de Google Play, la muestra y la gestiona Google. Balora no sabe si has
valorado ni qué has escrito.

## 7. Bloqueo de la app

Si activas el bloqueo de la app, Android comprueba tu huella, cara, PIN, patrón o contraseña. Balora solo recibe si el
desbloqueo ha sido correcto: tus datos biométricos nunca llegan a la app.

## 8. Permisos

- **Notificaciones:** para el recordatorio mensual de saldos, los recurrentes por confirmar, los avisos de
  presupuesto, el aviso de que tu resumen del mes o del año está listo y, solo en los 14 días siguientes a instalar la
  app, como mucho tres recordatorios para empezar a apuntar. Ninguna lleva importes. Puedes desactivarlas cuando
  quieras, todas o cada tipo, en los ajustes de Android.
- **Biometría:** solo para el bloqueo opcional de la app.
- **Compras de Google Play:** para Balora Plus y los pagos de apoyo.
- **Permisos técnicos** que añaden las librerías de Android: ver el estado de la red (lo pide la librería de tareas
  programadas; Balora no se conecta a internet), ponerse en marcha al encender el móvil (para volver a programar los
  recordatorios), mantener el móvil activo un momento mientras termina una tarea y, si una tarea larga lo necesitara,
  seguir con ella en primer plano.

Balora **no** pide acceso a internet, ubicación, contactos, cámara, micrófono ni el identificador de publicidad.

## 9. Sin anuncios, sin analítica, sin venta de datos

Balora no contiene publicidad ni herramientas de analítica o seguimiento, no envía tus datos a servicios de
inteligencia artificial, y el desarrollador no vende, alquila ni comparte ningún dato personal.

## 10. Base legal y conservación

- **Sugerencias y consultas por correo:** tu consentimiento al escribir y el interés legítimo en responderte. Se
  conservan el tiempo necesario para atenderlas y como mucho dos años, salvo que pidas que se borren antes.
- **Información de las compras:** la ejecución del contrato y las obligaciones legales; se conserva el plazo que exigen
  las normas contables y fiscales.

## 11. Tus derechos

Según el RGPD puedes pedir el acceso, la rectificación o la supresión de tus datos personales, limitar u oponerte a su
tratamiento y pedir su portabilidad, escribiendo a [{{ site.email }}](mailto:{{ site.email }}). También puedes
reclamar ante una autoridad de protección de datos; en España, la
[Agencia Española de Protección de Datos](https://www.aepd.es).

Tus datos financieros están solo en tu móvil: puedes exportarlos, cambiarlos o borrarlos tú mismo en la app cuando
quieras (el apartado 12 explica cómo).

## 12. Cómo borrar tus datos

Balora no tiene cuentas de usuario ni servidores: no hay ninguna cuenta que eliminar y el desarrollador no guarda tus
movimientos ni tus saldos, así que los borras tú, sin pedírselo a nadie y gratis.

- **Un movimiento:** en Movimientos, deslízalo a la izquierda. Pasa a la papelera (botón 🗑 de esa pantalla), donde
  puedes restaurarlo o borrarlo definitivamente, uno a uno o con «Vaciar».
- **Un saldo:** bórralo desde Patrimonio.
- **Lo que ya estaba en una copia:** si un movimiento o un saldo borrado ya estaba en una copia exportada o llegó de otro
  móvil, deja de verse, pero la app guarda sus datos con una marca de borrado, también en las copias que exportes
  después, para que importar la copia anterior no lo recupere. Para quitar también esa marca, borra los datos del perfil.
- **Todos los datos de un perfil:** *Ajustes › Perfil › Borrar los datos de este perfil*. Borra movimientos, saldos,
  recurrentes, presupuestos, etiquetas, importaciones del banco y su copia automática. Las categorías y los ajustes
  (también las plantillas de importación) se quedan. Si no es el perfil principal, *Eliminar este perfil* lo quita entero.
- **Todo lo que hay en el móvil:** desinstala la app o borra sus datos en los ajustes de Android. Se eliminan todos los
  perfiles.
- **Copias exportadas, informes en PDF e imágenes compartidas:** Balora no puede llegar a ellos. Bórralos allí donde los
  guardaste o enviaste. Si importas una copia anterior, sus datos vuelven.
- **Copia en tu cuenta de Google:** al desactivarla, Balora deja de enviar copias nuevas, pero la última sigue en Google.
  Después de borrar los datos de un perfil, la siguiente copia que haga Android ya no los lleva. Si reinstalas la app y
  te ofrece recuperar una copia, elige «No, borrarla». Para borrar la copia que tiene Google, entra en el
  [panel de Android de tu cuenta de Google](https://myaccount.google.com/dashboard/android). Lo gestiona Google: esa
  opción puede borrar la copia de todo el dispositivo, no solo la de Balora, así que lee bien lo que indica antes de
  confirmar.
- **Tus correos con el desarrollador:** pide que se borren escribiendo a
  [{{ site.email }}](mailto:{{ site.email }}).
- **Datos de compras:** la información de los pedidos se conserva el plazo que exigen las normas contables y fiscales
  (apartado 10), así que no se puede borrar antes. Tus datos de pago los gestiona Google en tu cuenta de Google.

## 13. Seguridad

Las copias cifradas usan AES-256-GCM con una clave derivada de tu contraseña (PBKDF2, 600.000 iteraciones). Si olvidas
la contraseña, nadie puede recuperar la copia. La app se puede proteger con el bloqueo de pantalla del móvil.

## 14. Menores

Balora está pensada para adultos y no se dirige a menores.

## 15. Cambios en esta política

Si esta política cambia, la nueva versión se publicará en esta página con su fecha. Los cambios importantes se avisarán
también en la app.

## 16. Contacto

[{{ site.email }}](mailto:{{ site.email }})
