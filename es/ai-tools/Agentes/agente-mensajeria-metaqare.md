---
title: "Agente IA de Mensajería Omnicanal"
---

#

El **Agente IA de Mensajería Omnicanal de MetaQare** es el puente inteligente entre el sistema de salud digital y el paciente, garantizando comunicación instantánea, personalizada y segura a través de los canales más utilizados del mundo: WhatsApp, SMS, email y notificaciones móviles. Optimiza la experiencia de usuario y la eficiencia operativa, convirtiendo la comunicación en una verdadera ventaja competitiva.

---

## ¿Qué permite este agente?

- Enviar confirmaciones, recordatorios y actualizaciones clínicas automáticamente vía WhatsApp, SMS, email y notificaciones push.
- Personalizar los mensajes según el estado de la cita, tipo de paciente, idioma y preferencia de canal.
- Recibir feedback inmediato del paciente (NPS, satisfacción, incidencias) y lanzar encuestas automáticas.
- Redirigir a los pacientes a videoconsulta, pago de cita o soporte con un solo clic desde el mensaje recibido.
- Integrar flujos de comunicación con campañas de prevención, programas crónicos y alertas de salud pública.
- Gestionar comunicaciones masivas segmentadas para hospitales, aseguradoras o campañas de marketing médico.

---

## Funciones disponibles

| Función                        | Descripción                                                                    |
| ------------------------------ | ------------------------------------------------------------------------------ |
| **enviarConfirmacionCita**     | Envía confirmación de cita con enlace y detalle vía canal preferido.           |
| **recordatorioAutomatico**     | Programa y envía recordatorios de citas, toma de medicación y revisiones.      |
| **enviarEncuestaNPS**          | Solicita feedback de satisfacción post-consulta de forma automática.           |
| **notificacionPago**           | Informa al paciente de pagos pendientes y envía enlace de pago seguro.         |
| **alertaSaludPublica**         | Envía avisos o campañas de prevención según alertas regionales o institucionales. |
| **feedbackPaciente**           | Recoge respuestas o incidencias para redirigirlas a soporte o a los agentes adecuados. |

---

## Ejemplos de uso e integración

El agente puede integrarse con el core MetaQare, CRMs médicos, apps móviles y portales web:

### 1. Enviar confirmación de cita

```js
await enviarConfirmacionCita("Juan García", "2024-08-21 10:00", "Videoconsulta", "WhatsApp");
```
**Respuesta:**
```txt
"Mensaje enviado: Hola Juan, tu cita de Videoconsulta está confirmada para el 21 de agosto a las 10:00h. Accede aquí: [enlace]"
```

---

### 2. Programar recordatorio automático

```js
await recordatorioAutomatico("Juan García", "2024-08-20 22:00", "Toma de medicación", "SMS");
```
**Respuesta:**
```txt
"Recordatorio programado: Se notificará a Juan vía SMS el 20 de agosto a las 22:00h."
```

---

### 3. Solicitar encuesta NPS post-consulta

```js
await enviarEncuestaNPS("Juan García", "Cardiología", "WhatsApp");
```
**Respuesta:**
```txt
"Mensaje enviado: Valora tu consulta en Cardiología de hoy con una puntuación del 1 al 10."
```

---

### 4. Notificar pago pendiente

```js
await notificacionPago("Juan García", "49.00 €", "2024-08-21", "email");
```
**Respuesta:**
```txt
"Mensaje enviado: Tienes un pago pendiente de 49.00 € por tu consulta del 21 de agosto. Paga aquí: [enlace seguro]"
```

---

### 5. Enviar alerta de salud pública

```js
await alertaSaludPublica("Campaña Vacunación Gripe 2024", "Todos los pacientes mayores de 65 años", "push");
```
**Respuesta:**
```txt
"Mensaje enviado: Nueva campaña de vacunación antigripal. Solicita tu cita aquí: [enlace]"
```

---

## Valor diferencial y monetización

- **Aumenta la asistencia a consultas y la adherencia terapéutica** mediante mensajes proactivos.
- Reduce costes de call center y tareas administrativas repetitivas.
- Permite modelos de pago por mensaje, paquetes para clínicas/aseguradoras y campañas patrocinadas (salud pública, farmacéuticas).
- Incrementa el NPS y la satisfacción global, facilitando la fidelización de pacientes y la prescripción social.

---

## Requisitos

- Consentimiento digital para comunicaciones electrónicas.
- Integración con el core MetaQare, CRM médico o plataforma externa compatible.
- API Key válida de MetaQare.

---

## Consejos de uso

- Segmenta mensajes y personaliza el contenido según perfil, idioma y canal favorito del paciente.
- Cumple siempre la normativa de protección de datos (RGPD, LOPDGDD) en envíos masivos.
- Monitoriza la respuesta y ajusta la frecuencia para evitar saturación o abandono.

---

## Soporte

¿Dudas o sugerencias?  
Contacta: [soporte@metaqare.ai](mailto:soporte@metaqare.ai)  
Más información y documentación: https://docs.metaqare.ai/ai-tools/mensajeria

---

> **MetaQare — Conecta, acompaña e impacta en la salud digital desde cualquier canal, en cualquier momento.**