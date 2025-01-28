# Notificaciones de Meraki en Google Worksplace-Chat
Template para envío de notificaciones de Meraki a algun chat de google.
Comparto el siguiente Template para el envío de notificaciones mediante Webhooks desde el Dashboard de Meraki a un grupo de chat de google Worksplace.

*Actualmente estos templates solo se pueden configurar independientemente en cada Red de la oganizacion.

**Puntos a revisar antes de crear el Webhook**.

**1.** Validar que la Organizacion en Worksplace permita las aplicaciones y webhooks en los chats.

**2.** Definir las alertas a recibir en el grupo creado, la idea es tener alertas de nivel citico para acciones rapidas y no saturar con alertas inecesarias. Favor de revisar los tipos de alertas en la documentacion de Meraki.  https://documentation.meraki.com/MI/Alert_Management_in_Meraki_Insight/Alerts_Management_Overview **(Esto tambien funcionará para agregar el webhook una vez creado)**.


**3.** Crear grupo de notificaciones en chat de google y generar dentro de aplicaciones el link para recepcion de webhooks.
puedes basarte en este link o mas adelante te muestro como hacerlo. https://cloud.google.com/integration-connectors/docs/connectors/webhook/configure?hl=es-419

**4.** Manual para creacion de webhooks Meraki. https://developer.cisco.com/meraki/webhooks/introduction/#assign-alerts


_aun sigo documentando se paciente @jazzkell_
