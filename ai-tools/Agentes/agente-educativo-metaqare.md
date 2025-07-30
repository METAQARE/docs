## Agente IA Educativo Médico

El **Agente IA Educativo Médico de MetaQare** es el tutor digital inteligente que acompaña y empodera al paciente y su familia en cada etapa de su proceso de salud. Esta IA revoluciona la educación terapéutica y la prevención, personalizando contenidos multimedia y asegurando la comprensión y adherencia a tratamientos y procedimientos.

---

## ¿Qué permite este agente?

- Ofrecer explicaciones claras y adaptadas al diagnóstico, tratamiento o procedimiento médico, en formato texto, vídeo, imágenes y simulaciones interactivas.
- Personalizar el contenido educativo según edad, idioma, nivel cultural y necesidades especiales del paciente (ej: infanto-juvenil, senior, diversidad funcional).
- Generar itinerarios de aprendizaje, módulos de formación y cuestionarios de comprensión para el paciente y sus cuidadores.
- Enviar recordatorios de autocuidado, revisiones, alimentación o ejercicio físico basados en la historia clínica.
- Certificar la comprensión y adherencia mediante microevaluaciones, generando badges digitales y reporting para profesionales o aseguradoras.
- Servir de canal para campañas de prevención, promoción de salud pública y educación a colectivos de riesgo.

---

## Funciones disponibles

| Función                        | Descripción                                                                                 |
| ------------------------------ | ------------------------------------------------------------------------------------------- |
| **explicarDiagnostico**        | Proporciona una explicación personalizada del diagnóstico en lenguaje claro.                |
| **generarVideoExplicativo**    | Ofrece acceso a vídeos interactivos o animados sobre procedimientos, medicación o cuidados. |
| **enviarCuestionario**         | Envía tests o quizzes para certificar la comprensión de las indicaciones médicas.           |
| **recomendarContenido**        | Sugiere materiales educativos adicionales (PDF, web, simulaciones) adaptados al perfil.     |
| **crearItinerarioAprendizaje** | Planifica un itinerario formativo adaptativo según la evolución clínica y necesidades.      |
| **certificarAdherencia**       | Verifica la comprensión y cumplimiento del paciente, generando badge o informe digital.     |

---

## Ejemplos de uso e integración

Este agente puede desplegarse en apps móviles, portales de paciente, tablets en sala de espera, chatbots y programas corporativos de salud:

### 1. Explicar diagnóstico

```js
await explicarDiagnostico("hipertensión arterial", "es", "adulto");
```

**Respuesta:**

```txt
"La hipertensión arterial significa que la presión con la que la sangre circula por tus arterias es más alta de lo recomendable. Puede no dar síntomas, pero a largo plazo puede afectar al corazón, riñones y cerebro..."
```

---

### 2. Generar vídeo educativo

```js
await generarVideoExplicativo("preparación colonoscopia", "es", "senior");
```

**Respuesta:**

```txt
"Vídeo enviado: Mira este vídeo de 3 minutos donde te explicamos cómo prepararte para una colonoscopia de manera sencilla y segura. [enlace]"
```

---

### 3. Enviar cuestionario de comprensión

```js
await enviarCuestionario("tratamiento diabetes", "Juan García");
```

**Respuesta:**

```txt
"Juan, antes de tu próxima consulta, completa este breve cuestionario sobre tu tratamiento. [enlace]"
```

---

### 4. Recomendar contenido adicional

```js
await recomendarContenido("cuidados tras cirugía de cataratas", "PDF, vídeo");
```

**Respuesta:**

```txt
"Te recomendamos este PDF con los cuidados tras la operación y un vídeo con ejercicios visuales fáciles de seguir."
```

---

### 5. Crear itinerario de aprendizaje

```js
await crearItinerarioAprendizaje("asma infantil", "niño");
```

**Respuesta:**

```txt
"Itinerario generado: Educación sobre el asma, uso del inhalador, medidas preventivas y control ambiental. Duración: 7 días."
```

---

### 6. Certificar adherencia y comprensión

```js
await certificarAdherencia("Juan García", "manejo hipertensión");
```

**Respuesta:**

```txt
"Juan ha completado el itinerario formativo y ha aprobado la evaluación. Badge de Paciente Proactivo emitido."
```

---

## Valor diferencial y monetización

- Reduce la tasa de errores y abandonos por desconocimiento, aumentando el éxito terapéutico y la satisfacción.
- Mejora la calidad y reputación de clínicas y aseguradoras al certificar la educación y empoderamiento real del paciente.
- Permite modelos de pago por curso, licencias para hospitales/seguros, paquetes a farmacéuticas y campañas de prevención patrocinadas.
- Facilita reporting y auditoría de impacto para acreditación y compliance.

---

## Requisitos

- Consentimiento para el envío de materiales y microevaluaciones.
- Dispositivo compatible (app, web, tablet) y perfil activo en MetaQare.
- API Key válida para integraciones externas.

---

## Consejos de uso

- Ajusta el contenido a la edad y el nivel de alfabetización sanitaria.
- Realiza seguimiento de la evolución y refuerza la educación en cada contacto.
- Vincula los itinerarios formativos a los agentes de seguimiento y triaje para experiencia integral.

---

## Soporte

¿Dudas o sugerencias?\
Contacta: [soporte@metaqare.ai](mailto:soporte@metaqare.ai)\
Más información y documentación: https://docs.metaqare.ai/ai-tools/educativo

---

> **MetaQare — Pacientes más informados, pacientes más sanos. La educación médica como pilar de la salud digital.**