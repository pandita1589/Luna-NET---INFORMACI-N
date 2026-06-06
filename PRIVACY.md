# 🔐 Política de Privacidad — Luna NET

**Luna NET · Moon Studios**
**Última actualización:** 22 de marzo de 2026

> Versión oficial publicada en: https://luna-net.netlify.app/privacy-policy

En Moon Studios nos tomamos en serio la privacidad de los usuarios de Luna NET. Esta política describe con exactitud qué datos recopilamos, por qué y cómo los usamos.

---

## 1. Datos que recopilamos

Al añadir Luna NET a tu servidor o usar sus funciones, recopilamos y almacenamos en **Firebase / Firestore** únicamente lo siguiente:

- **ID de usuario de Discord** — identificador único proporcionado por Discord. Nunca almacenamos tokens ni contraseñas.
- **Nombre de usuario y URL de avatar** — almacenados únicamente cuando el usuario se convierte en *campeón de XP* de un servidor, para mostrar su perfil en el ranking global. Persisten hasta que otro usuario supere su puntuación.
- **XP, nivel y posición en el ranking** — generados automáticamente por actividad en el servidor (mensajes enviados). El contenido de los mensajes no se analiza ni almacena.
- **Fecha de cumpleaños (día y mes únicamente, sin año)** — proporcionada de forma voluntaria mediante el comando `/birthday`. El año nunca se solicita ni se guarda.
- **Razón de estado AFK** — texto opcional proporcionado al activar el modo AFK con `/afk`. Se almacena temporalmente y se elimina automáticamente al desactivar el estado.
- **Perfil de usuario personalizado** — datos opcionales como biografía o campos de perfil configurados voluntariamente.
- **Configuración del servidor** — IDs de canales, roles y ajustes configurados por administradores. No incluye contenido de mensajes.

> ⚠️ **El contenido de los mensajes NO se almacena.** Se procesa en memoria de forma transitoria únicamente para ejecutar comandos, otorgar XP y realizar traducciones automáticas, y se descarta inmediatamente tras el procesamiento.

---

## 2. Cómo usamos tus datos

- Proveer, operar y mantener las funciones del bot en tu servidor.
- Calcular y mostrar el sistema de XP, niveles y rankings por servidor.
- Mostrar el estado AFK de un usuario cuando es mencionado.
- Enviar felicitaciones de cumpleaños automáticas donde el usuario lo haya habilitado explícitamente.
- Traducir mensajes en tiempo real mediante la **API de Groq** (solo si el servidor tiene habilitada la auto-traducción).
- Gestionar la configuración de administración del servidor (bienvenidas, tickets, paneles de roles, etc.).

---

## 3. Almacenamiento y seguridad

Los datos se almacenan en **Firebase / Firestore (Google Cloud)**, que aplica cifrado en reposo (**AES-256**) y en tránsito (**TLS/HTTPS**) de forma nativa. El acceso a la base de datos está restringido mediante reglas de seguridad de Firebase y solo es accesible por personal autorizado de Moon Studios bajo acuerdo de confidencialidad. No realizamos cifrado adicional a nivel de aplicación, confiando en las garantías de seguridad de Google Cloud.

---

## 4. Compartición de datos con terceros

No vendemos, alquilamos ni comercializamos tus datos. Los compartimos únicamente con los proveedores técnicos necesarios para el funcionamiento del servicio:

- **Discord Inc.** — plataforma base a través de la cual opera el bot.
- **Firebase / Google Cloud** — almacenamiento de base de datos (Firestore).
- **Groq Inc. (API LLaMA)** — el contenido de los mensajes se envía exclusivamente para traducción automática en tiempo real. Groq no retiene los datos según su política. Solo se activa si el administrador habilita la auto-traducción.
- **Procesadores de pago (PayPal, MercadoPago)** — exclusivamente para gestionar suscripciones Premium. No tenemos acceso a datos bancarios completos.

---

## 5. Retención y eliminación de datos

Conservamos los datos mientras el usuario o el servidor utilice el servicio:

- **Estado AFK** — se elimina automáticamente al desactivar el modo AFK.
- **Campeón de XP (username y avatar)** — persiste hasta que otro usuario supere la puntuación del campeón actual.
- **XP, nivel y cumpleaños** — persisten mientras el usuario no solicite su eliminación.

Para solicitar la **eliminación completa** de tus datos, abre un ticket de soporte en nuestro servidor de Discord o escríbenos a `studios.soporteplaykia@gmail.com`. Eliminaremos todos los datos asociados en un plazo máximo de **30 días**.

---

## 6. Tus derechos

- **Acceso** — solicitar un listado de los datos personales que almacenamos sobre ti.
- **Rectificación** — pedir que corrijamos datos incorrectos o desactualizados.
- **Eliminación** — solicitar la eliminación total de tu cuenta y datos asociados.
- **Portabilidad** — solicitar tus datos en formato legible por máquina (JSON).
- **Opt-out de cumpleaños** — deshabilitar las felicitaciones en servidores específicos o en todos.

Para ejercer cualquiera de estos derechos, contáctanos por el servidor de soporte o por correo.

---

## 7. Menores de edad

Luna NET no está dirigido a personas menores de **13 años**, conforme a las Condiciones de Servicio de Discord. Si eres padre o tutor y crees que tu hijo ha proporcionado datos personales, contáctanos inmediatamente para proceder a su eliminación.

---

## 8. Cambios en esta política

Nos reservamos el derecho de modificar esta política en cualquier momento. Los cambios significativos serán notificados con al menos **7 días** de antelación a través de nuestro servidor de Discord. El uso continuado del bot tras los cambios implica la aceptación de la nueva política.

---

¿Preguntas? Contáctanos en `studios.soporteplaykia@gmail.com` o en nuestro [servidor de Discord](https://discord.gg/5dR8p733Ac).

© 2026 Moon Studios. Todos los derechos reservados.
