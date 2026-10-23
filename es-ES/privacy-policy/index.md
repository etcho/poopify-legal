---
layout: default
title: "Política de Privacidad"
permalink: /es-ES/privacy-policy/
lang: es-ES
---

*Esta es una traducción. En caso de discrepancia, prevalece la [versión en inglés](https://etcho.github.io/poopify-legal/privacy-policy/).*

# Poopify - Política de Privacidad

**Fecha de entrada en vigor:** 21 de octubre de 2026
**Versión:** 1.0

Esta Política de Privacidad explica qué datos personales trata la app Poopify (la "App"), por qué y qué derechos tienes. Se aplica a la App en todos los dispositivos y al servicio opcional de Sincronización en la nube.

## Resumen

- **Por defecto, tus registros de salud nunca salen de tu dispositivo.** En el Modo local, todo lo que registras (deposiciones, ciclo menstrual, síntomas, notas, perfiles) se guarda solo en tu móvil. Nosotros no lo recibimos.
- **La Sincronización en la nube es opcional.** Si la activas y das tu consentimiento explícito, se guarda una copia de tus registros en la nube (Google Firebase, en la Unión Europea) para sincronizarlos entre tus dispositivos. La Sincronización en la nube se está habilitando de forma gradual y **puede no estar disponible en todas las regiones**.
- **Nunca vendemos tus datos, nunca usamos tus registros de salud para publicidad y nunca los compartimos con nadie para sus propios fines.**
- La App muestra anuncios y usa herramientas de Google de análisis y de informes de fallos. Estos servicios reciben identificadores del dispositivo e información de uso de la App, **pero no el contenido de tus registros de salud.**
- Puedes desactivar la Sincronización en la nube, exportar tus datos o eliminar tu cuenta en la nube en cualquier momento, directamente en la App (Menú > Privacidad).

---

## 1. Quién es el responsable de tus datos

El responsable del tratamiento de tus datos personales es:

Everton Carvalho Leite, desarrollador independiente, Río de Janeiro, Brasil
Correo electrónico: **poopify.dev@gmail.com**

- **Contacto de protección de datos / Encarregado (LGPD):** Everton Carvalho Leite, poopify.dev@gmail.com

## 2. Datos guardados solo en tu dispositivo (Modo local)

Cuando usas la App sin la Sincronización en la nube, los siguientes datos se guardan **solo en tu dispositivo**, en el almacenamiento privado de la App:
- los registros que introduces: fecha y hora, características de las heces, síntomas, dolor, notas sobre medicamentos y alimentos, método de higiene, información del ciclo menstrual, notas de texto libre;
- los perfiles que creas (nombre, icono, fecha de nacimiento opcional) y la configuración de la App.

No tenemos acceso a estos datos. No se nos envían a nosotros ni a terceros, salvo en los siguientes casos, que tú controlas:
- **Exportaciones y compartir:** cuando exportas una copia de seguridad, un CSV, un JSON o un PDF, el archivo se crea en tu dispositivo y se envía solo a donde tú decidas compartirlo.
- **Copia de seguridad del dispositivo Android:** según la configuración de tu dispositivo, Android puede incluir los datos de la App en la copia de seguridad del propio dispositivo en tu cuenta de Google. Esa copia la gestionan Google y la configuración de tu dispositivo, no nosotros.

## 3. Sincronización en la nube (opcional)

La Sincronización en la nube es una función opcional que se está habilitando de forma gradual. **Puede no estar disponible en todos los países o regiones** y, donde no está disponible, la App no la muestra.

### 3.1 Qué tratamos
Si activas la Sincronización en la nube, tratamos:
- **Datos de la cuenta:** un identificador único de la cuenta y la dirección de correo electrónico de la cuenta con la que inicias sesión (por ejemplo, tu cuenta de Google), gestionados por Firebase Authentication.
- **Tus registros de salud:** una copia de los registros y perfiles descritos en la Sección 2, **excepto los datos de ubicación**.
- **Datos técnicos de sincronización:** un identificador del dispositivo generado por la App, la hora de los cambios y el estado de la sincronización.
- **Registro del consentimiento:** la versión de esta Política de Privacidad y de los Términos de Uso que aceptaste, y cuándo.
- **Señales de integridad de la App:** información que confirma que las solicitudes provienen de una copia original de la App (Firebase App Check con Google Play Integrity).

### 3.2 Para qué y con qué base jurídica
- **Finalidad:** solo guardar tus registros y sincronizarlos entre los dispositivos con tu cuenta iniciada, y permitirte recuperarlos en un dispositivo nuevo.
- **Base jurídica:** tu **consentimiento explícito** (RGPD art. 6(1)(a) y art. 9(2)(a); LGPD art. 7, I y art. 11, I; y normas equivalentes en otras jurisdicciones). Los datos de la cuenta y los datos técnicos se tratan porque son necesarios para prestar el servicio que solicitaste (RGPD art. 6(1)(b); LGPD art. 7, V).
- Puedes **retirar tu consentimiento en cualquier momento** eliminando tus datos de la nube en la App (Sección 9). Desactivar la Sincronización en la nube solo detiene la sincronización: la copia que ya está en la nube sigue allí hasta que la elimines, y la App te ofrece eliminarla al desactivar la sincronización. La retirada no afecta al tratamiento realizado antes.
- **No** usamos tus datos de la nube para análisis, publicidad, elaboración de perfiles, investigación, entrenamiento de inteligencia artificial ni ninguna otra finalidad distinta de prestarte la Sincronización en la nube.

### 3.3 Dónde se guardan tus datos
Los datos de la Sincronización en la nube se guardan en servidores de Google Cloud ubicados en la **Unión Europea** (multirregión "eur3" de Firestore). Google actúa como nuestro encargado del tratamiento según los Términos de Tratamiento de Datos y Seguridad de Firebase.

### 3.4 Quién puede acceder
- **A través de la App, solo tu cuenta.** Las reglas de seguridad de los servidores impiden que cualquier otra cuenta lea o escriba tus datos.
- **El desarrollador, solo en casos excepcionales.** Los datos están cifrados en tránsito y en reposo, pero no de extremo a extremo: técnicamente, pueden verse a través de la consola de administración del servicio. Esa consola está restringida a la cuenta del desarrollador, protegida con verificación en dos pasos, y sus accesos quedan registrados. Solo miramos tus datos de la nube si nos pides expresamente ayuda con tu cuenta, o si la ley nos obliga.
- **Google**, como nuestro proveedor de infraestructura, trata los datos solo para alojarlos en nuestro nombre.

### 3.5 Disponibilidad por región
La Sincronización en la nube puede no estar disponible en algunos países o regiones por motivos legales o técnicos. Si deja de estar disponible donde estás, la sincronización se detiene, los datos de tus dispositivos no se ven afectados y sigues pudiendo eliminar tu cuenta y tus datos de la nube en cualquier momento en Menú > Privacidad.

## 4. Publicidad

- La App muestra anuncios proporcionados por **Google AdMob**. AdMob puede tratar el identificador de publicidad de tu dispositivo, tu dirección IP e información sobre los anuncios mostrados y pulsados.
- En el Espacio Económico Europeo, el Reino Unido, Suiza y donde lo exija la ley, pedimos tu consentimiento antes de personalizar los anuncios, usando la herramienta de consentimiento de Google. Puedes cambiar tu elección en cualquier momento en el menú de la App, en **Opciones de privacidad de anuncios** (se muestra donde esta elección se aplica).
- En Android también puedes restablecer o eliminar tu identificador de publicidad en la configuración del dispositivo.
- **El contenido de tus registros de salud nunca se comparte con AdMob ni se usa para elegir anuncios.**
- Si compras "Eliminar anuncios", los anuncios dejan de mostrarse.
- Más información: https://policies.google.com/technologies/partner-sites

## 5. Análisis e informes de fallos

- Usamos **Google Analytics para Firebase** para entender cómo se usa la App (por ejemplo, qué pantallas se abren y qué funciones se usan) y **Firebase Crashlytics** para recibir informes de fallos y errores.
- Estos servicios tratan un identificador de la instalación de la App, información del dispositivo y del sistema operativo, la ubicación aproximada derivada de la dirección IP (país y región) y eventos de uso.
- Los eventos de uso registran **que** se usó una función (por ejemplo, "se creó un registro"), **nunca el contenido** de lo que registraste.
- **Base jurídica:** nuestro interés legítimo en mantener la App funcionando y mejorarla (RGPD art. 6(1)(f); LGPD art. 7, IX), o tu consentimiento donde la ley lo exija.
- Analytics está vinculado a Google AdMob solo para medir el rendimiento y los ingresos de los anuncios mostrados en la App. **Los datos de Analytics no se usan para personalizar anuncios** (la personalización de anuncios y Google Signals están desactivados en nuestra configuración de Analytics) y no se comparten con otros socios publicitarios.
- **Conservación:** los datos de eventos de Analytics se conservan 2 meses, y los datos de Analytics a nivel de usuario hasta 14 meses. Los informes de fallos se conservan hasta 90 días.

## 6. Compras

Las compras (como "Eliminar anuncios") las procesa **Google Play**. Solo recibimos la información necesaria para confirmar la compra (como un token y su estado). No recibimos tus datos de pago. Al pago se le aplica la política de privacidad de Google.

## 7. Correos de soporte

Si nos escribes, tratamos tu dirección de correo electrónico y el contenido de tu mensaje solo para responderte, y conservamos la conversación como historial de nuestro soporte hasta que nos pidas que la eliminemos. Por favor, no envíes información de salud por correo salvo que sea necesario.

## 8. Con quién compartimos datos

No vendemos datos personales y no los "compartimos" para publicidad comportamental entre contextos.

Usamos los siguientes proveedores de servicios (encargados del tratamiento), que tratan los datos en nuestro nombre y según nuestras instrucciones, o como responsables independientes cuando se indica:

| Proveedor | Servicio | Datos | Función |
|---|---|---|---|
| Google (Firebase Authentication, Cloud Firestore, App Check) | Sincronización en la nube | Cuenta, datos de la Sincronización en la nube | Encargado del tratamiento |
| Google (Analytics para Firebase, Crashlytics) | Análisis e informes de fallos | Eventos de uso, datos del dispositivo, identificadores | Encargado del tratamiento |
| Google (AdMob) | Publicidad | Identificador de publicidad, IP, interacciones con anuncios | Responsable independiente para los anuncios, ver Sección 4 |
| Google (Google Play) | Compras | Datos de la compra | Responsable independiente |

También podemos revelar datos cuando lo exija la ley, o para proteger los derechos, la seguridad o la integridad de los usuarios o de la App, pero solo en la medida estrictamente necesaria, y te avisaremos cuando la ley lo permita.

## 9. Tus opciones y tus derechos

### 9.1 Disponibles en la App en cualquier momento
- **Desactivar la Sincronización en la nube:** tus datos siguen en tu dispositivo y la App sigue funcionando en el Modo local.
- **Eliminar tu cuenta y tus datos de la nube:** en la App (Menú > Privacidad > Eliminar una cuenta de Sincronización en la nube, o Menú > Sincronización en la nube > Eliminar la cuenta y los datos de la nube), o en [https://etcho.github.io/poopify-legal/es-ES/delete-account/](https://etcho.github.io/poopify-legal/es-ES/delete-account/).
- **Exportar tus datos** (copia de seguridad SQL, CSV, JSON, PDF), para acceso y portabilidad.
- **Corregir o eliminar registros** directamente en la App.

### 9.2 Tus derechos
Según dónde vivas, puedes tener derecho a: acceder a tus datos; rectificarlos; suprimirlos; limitar el tratamiento u oponerte a él; la portabilidad de los datos; retirar el consentimiento; no ser objeto de decisiones basadas únicamente en el tratamiento automatizado; y ser informado de con quién se comparten los datos.
- **Unión Europea / EEE / Reino Unido (RGPD / UK GDPR):** todos los derechos anteriores. También puedes presentar una reclamación ante la autoridad de protección de datos de tu país.
- **Brasil (LGPD, art. 18):** confirmación de la existencia del tratamiento, acceso, corrección, anonimización, bloqueo o eliminación de datos innecesarios, portabilidad, eliminación de los datos tratados con consentimiento, información sobre el uso compartido, información sobre la posibilidad de no dar el consentimiento y sus consecuencias, y revocación del consentimiento. También puedes presentar una reclamación ante la ANPD (Autoridad Nacional de Protección de Datos de Brasil).
- **Estados Unidos:** ver Secciones 11 y 12.
- **Otros países:** respetamos los derechos equivalentes de tu legislación local.

Para ejercer cualquier derecho que no esté disponible directamente en la App, escribe a **poopify.dev@gmail.com**. Responderemos en el plazo que exija la ley para cada tipo de solicitud (por ejemplo, hasta 15 días para la confirmación completa y el acceso a tus datos según la LGPD, y un mes según el RGPD, que el RGPD permite prorrogar en algunos casos). Puede que necesitemos comprobar que la solicitud procede del titular de la cuenta.

## 10. Cuánto tiempo conservamos los datos

| Datos | Conservación |
|---|---|
| Datos del Modo local | En tu dispositivo, hasta que los borres o desinstales la App |
| Datos de la Sincronización en la nube | Hasta que elimines tu cuenta o tus datos de la nube; o, como máximo, hasta que la cuenta lleve 24 meses seguidos sin que ningún dispositivo la use; o hasta que se interrumpa la Sincronización en la nube. En ninguno de estos casos se ven afectados los datos de tus dispositivos |
| Datos de la nube eliminados | Se eliminan de nuestros sistemas activos de inmediato; las copias residuales en los sistemas de copia de seguridad de Google se borran en los plazos fijados por las condiciones de eliminación de datos de Google Cloud |
| Registros del consentimiento (qué versiones de estos documentos aceptaste, y cuándo) | Se guardan con tu cuenta de Sincronización en la nube y se eliminan junto con ella, o cuando eliminas tus datos de la nube |
| Análisis / informes de fallos | Ver Sección 5 |
| Correos de soporte | Ver Sección 7 |

## 11. Información adicional para residentes en Estados Unidos

- **Categorías recopiladas:** identificadores (ID de la cuenta, ID de la instalación de la App, identificador de publicidad, dirección IP); actividad en internet o electrónica (eventos de uso de la App); geolocalización aproximada (a partir de la IP, para análisis); **información personal sensible / datos de salud del consumidor** (solo con la Sincronización en la nube, ver Sección 12); información comercial (estado de la compra).
- No vendemos información personal ni la compartimos para publicidad comportamental entre contextos, y no lo hemos hecho en los últimos 12 meses.
- Usamos la información personal sensible solo para prestar el servicio que solicitaste, por lo que el derecho a limitar su uso se aplica por defecto.
- **California, Colorado, Connecticut, Virginia, Oregón, Texas y otros estados con leyes de privacidad del consumidor:** tienes derecho a saber, acceder, corregir y eliminar tu información personal, y a no ser discriminado por ejercer estos derechos. Puedes recurrir cualquier decisión sobre tu solicitud respondiendo a nuestra respuesta.
- No recopilamos a sabiendas información personal de menores de 13 años mediante cuentas de Sincronización en la nube (ver Sección 13).

## 12. Política de Privacidad de Datos de Salud del Consumidor (Washington, Nevada, Connecticut y leyes similares)

{% include es-ES/consumer-health-data.md %}

## 13. Menores

- La App es un diario personal de salud y no está dirigida a menores.
- **Las cuentas de Sincronización en la nube son solo para adultos** (18 años o la mayoría de edad donde vivas).
- Los padres y tutores pueden usar la App para llevar registros de sus hijos, en perfiles separados. En ese caso, el padre, la madre o el tutor es responsable de esa información y da el consentimiento en nombre del menor.
- Si crees que un menor ha creado una cuenta de Sincronización en la nube, contacta con nosotros y la eliminaremos.

## 14. Seguridad

Protegemos tus datos con medidas técnicas y organizativas adecuadas a su sensibilidad, entre ellas:
- cifrado en tránsito (TLS) y en reposo;
- reglas en los servidores que solo permiten a cada cuenta acceder a sus propios datos;
- verificación de que las solicitudes provienen de la App original;
- acceso administrativo restringido, protegido con verificación en dos pasos y registrado;
- minimización de datos (por ejemplo, los datos de ubicación nunca se sincronizan);
- pruebas automatizadas de nuestras reglas de seguridad.

Ningún sistema es completamente seguro. Si un incidente de seguridad afecta a tus datos personales, lo notificaremos a las autoridades competentes y a ti, cuando y como lo exija la ley (por ejemplo, en un plazo de 72 horas a la autoridad de control según el RGPD).

## 15. Transferencias internacionales

Estamos en Brasil, y nuestros proveedores pueden tratar datos en otros países. Los datos de la Sincronización en la nube se guardan en la Unión Europea. Cuando se transfieren datos personales a otros países, nos basamos en garantías adecuadas, como las Cláusulas Contractuales Tipo de la Comisión Europea, el Marco de Privacidad de Datos UE-EE. UU. cuando proceda, y los mecanismos previstos en el art. 33 de la LGPD, tal como los ofrece Google en sus condiciones de tratamiento de datos.

## 16. Cambios en esta política

Te avisaremos en la App de los cambios importantes antes de que entren en vigor. Si un cambio afecta a cómo tratamos los datos de la Sincronización en la nube, volveremos a pedirte el consentimiento. Las versiones anteriores siguen disponibles en la dirección de la versión en inglés seguida del número de versión (por ejemplo, https://etcho.github.io/poopify-legal/privacy-policy/1.0/).

Esta política puede traducirse a otros idiomas. En caso de conflicto entre una traducción y la versión en inglés, prevalece la versión en inglés, salvo que la ley de tu país exija lo contrario.

## 17. Contacto

Correo electrónico: **poopify.dev@gmail.com**

## Historial de versiones

| Versión | Fecha de entrada en vigor | Cambios |
|---|---|---|
| 1.0 | 21 de octubre de 2026 | Primera versión |
