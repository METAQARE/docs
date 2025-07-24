# 🧾 Agente IA de Transcripción Médica Automática

El **Agente de Transcripción Médica Automática de MetaQare** transforma radicalmente la documentación clínica, automatizando el paso de cualquier consulta —presencial, telefónica o por videoconsulta— a texto estructurado, sugerencia de informe médico y receta electrónica, ahorrando tiempo, reduciendo errores y mejorando la trazabilidad.

---

## ¿Qué permite este agente?

- Transcribir en tiempo real el audio de la consulta en múltiples idiomas.
- Identificar automáticamente los datos clínicos clave (motivo, antecedentes, exploración, diagnóstico, tratamiento, pautas).
- Generar un borrador de informe médico estructurado, editable por el profesional.
- Proponer la receta electrónica y vincularla con el sistema REMPE, lista para firma digital.
- Archivar automáticamente la transcripción y los informes en el historial del paciente (cumplimiento RGPD y ENS).
- Integrarse con el resto de agentes IA (Einstein, Coordinador, Paciente, etc.) para enriquecer la información clínica y la seguridad.

---

## Funciones disponibles

| Función                         | Descripción                                                                                 |
| ------------------------------- | ------------------------------------------------------------------------------------------- |
| **transcribirConsulta**         | Convierte el audio o vídeo de la consulta en texto estructurado y reconoce entidades médicas.|
| **generarInformeDesdeAudio**    | A partir de la transcripción, genera automáticamente un informe clínico completo.           |
| **sugerirReceta**               | Propone recetas electrónicas basadas en la conversación médico-paciente.                    |
| **archivarEnHistorial**         | Guarda la transcripción y los documentos generados en el historial clínico del paciente.    |
| **exportarPDF**                 | Permite descargar la transcripción y los informes generados en PDF.                         |

---

## Ejemplos de uso e integración

Tus aplicaciones, asistentes conversacionales o plataformas clínicas pueden llamar estas funciones fácilmente:

### 1. Transcribir una consulta médica

```js
await transcribirConsulta(audioStream, {
  idioma: "es-ES",
  tipoConsulta: "videollamada",
  paciente: "Juan García"
});
```
**Respuesta:**
```txt
"Transcripción registrada: Motivo de consulta: dolor abdominal; Exploración: abdomen doloroso, sin fiebre;..."
```

---

### 2. Generar informe médico

```js
await generarInformeDesdeAudio(transcripcion);
```
**Respuesta:**
```txt
"Informe sugerido: Paciente con dolor abdominal de 3 días de evolución. No fiebre, no vómitos. Exploración: dolor en FID. Diagnóstico: probable apendicitis aguda. Recomendación: derivación a urgencias."
```

---

### 3. Sugerir receta electrónica

```js
await sugerirReceta(transcripcion, "Dr. López", "Juan García");
```
**Respuesta:**
```txt
"Receta sugerida: Paracetamol 1g cada 8h durante 5 días. ¿Desea enviar al sistema REMPE?"
```

---

### 4. Archivar en historial y exportar PDF

```js
await archivarEnHistorial(transcripcion, informe, receta);
```
**Respuesta:**
```txt
"Documentos archivados correctamente. PDF generado y disponible para descarga."
```

---

## Valor diferencial y monetización

- **Reduce hasta un 70% el tiempo de documentación clínica,** permitiendo que el médico dedique más tiempo al paciente y menos a tareas administrativas.
- **Minimiza errores humanos** y asegura que toda la información relevante quede registrada y trazada.
- **Mejora la calidad y valor legal** del historial clínico y el cumplimiento normativo (ENS, RGPD, eIDAS).
- **Modelo de ingresos:** Licencia SaaS por profesional, pago por transcripción, integración OEM/API con hospitales y aseguradoras, facturación por volumen.

---

## Requisitos

- Audio o vídeo compatible (WebRTC, mp3, wav, ogg…).
- Autorización profesional y consentimiento informado del paciente.
- API Key válida de MetaQare.

---

## Consejos de uso

- Informa siempre al paciente de la grabación y transcripción (cumplimiento RGPD).
- El profesional debe revisar y firmar el informe generado antes de archivarlo.
- Configura la integración con otros agentes (Ej: Einstein, Coordinador) para máximo valor añadido.

---

## Soporte

¿Dudas o sugerencias?  
Contacta: [soporte@metaqare.ai](mailto:soporte@metaqare.ai)  
Más información y documentación: https://docs.metaqare.ai/ai-tools/transcripcion

---

> **MetaQare — Digitaliza y automatiza la práctica clínica. El futuro del informe médico es ahora.**