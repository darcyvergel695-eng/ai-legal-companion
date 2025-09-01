[README_AI_Legal_Companion (1).md](https://github.com/user-attachments/files/22077320/README_AI_Legal_Companion.1.md)

# AI Legal Companion: Asistente Inteligente de Regularización Migratoria

Final project for the Building AI course

---

## 🧭 Summary

**AI Legal Companion** es una plataforma interactiva basada en IA que **evalúa automáticamente la situación legal de personas migrantes en España** y les orienta sobre el mejor camino para su regularización (arraigo, asilo, reagrupación, etc.) según la **normativa vigente de extranjería**. Utiliza un enfoque adaptativo y multilingüe para ofrecer asesoramiento legal accesible, preciso y actualizado. Proyecto de curso de desarrollo de IA.

---

## 🌍 Background

La regularización de personas extranjeras en España es un proceso complejo, burocrático y desigual. Muchos migrantes **no saben qué tipo de procedimiento pueden solicitar** o cómo demostrar los requisitos exigidos (tiempo en el país, vínculos, empleo, etc.). Las actualizaciones recientes de la ley (RD 1155/2024) abren nuevas vías, pero **no son conocidas por quienes más las necesitan**.

### Problemas:
* El 65% de las personas migrantes desconoce qué trámite es aplicable a su caso.
* Alta dependencia de ONGs y abogados sobrecargados.
* Gran cantidad de trámites rechazados por **falta de información o documentación incorrecta**.

**Objetivo:** ofrecer una solución que **evalúe la situación jurídica de cada usuario** y le sugiera la opción legal más adecuada conforme al reglamento vigente.

---

## 🧠 ¿Cómo funciona?

**1. Diagnóstico legal automatizado**
El usuario responde a una serie de preguntas guiadas sobre su situación:

- ¿Cuánto tiempo lleva en España?
- ¿Está empadronado?
- ¿Tiene tarjeta roja o NIE?
- ¿Ha trabajado con contrato?
- ¿Está estudiando o tiene formación acreditada?
- ¿Tiene vínculos familiares en España?
- ¿Tiene pasaporte válido?

**2. Análisis legal**
El sistema cruza las respuestas con los requisitos de:

- Arraigo social
- Arraigo laboral
- Arraigo para la formación
- Protección internacional (asilo)
- Reagrupación familiar
- Residencia por circunstancias excepcionales

**3. Sugerencia personalizada**
El sistema devuelve al usuario:

- Opción legal más viable
- Requisitos y pasos específicos
- Documentos que debe reunir
- Plantillas descargables (modelos oficiales EX)
- Enlace a cita previa
- Posibilidad de descargar resumen en PDF

**4. Revisión ONG (opcional)**
El usuario puede enviar su caso a una ONG colaboradora para revisión humana si lo desea.

---

## 💬 Ejemplo interactivo (flujo simplificado)

```
📍 ¿Cuánto tiempo lleva en España?
> Más de 2 años

📍 ¿Está empadronado?
> Sí, desde 2023

📍 ¿Tiene oferta de trabajo?
> Sí

📍 ¿Tiene pasaporte vigente?
> No, mi embajada no lo emite

✅ Resultado: Puede solicitar ARRAIGO SOCIAL.
🧾 Documentos: empadronamiento, informe de integración, contrato laboral.
🔗 Enlace a sede electrónica: https://sede.administracionespublicas.gob.es/
📄 Descargar modelo EX10 relleno automáticamente
```

---

## 🧩 Técnicas de IA utilizadas

| Técnica | Finalidad |
|--------|-----------|
| NLP y transformers | Comprender preguntas, extraer intenciones |
| Árbol de decisión / lógica difusa | Evaluar condiciones legales y sugerir opciones |
| Generación de texto (LLMs) | Redacción de recomendaciones personalizadas |
| RAG (Retrieval-Augmented Generation) | Consultar artículos del RD 1155/2024 |
| Clasificación de situación legal | Según condiciones del usuario |
| Generación de formularios EX dinámicos | Rellenar modelos con datos proporcionados |
| Traducción automática neuronal | Versión en español, inglés, francés, árabe |

---

## 🔎 Fuentes legales y datos

- **Ley Orgánica 4/2000** sobre derechos y libertades de los extranjeros en España
- **Reglamento RD 1155/2024**, en vigor desde mayo 2025
- Documentos y formularios del Ministerio de Inclusión y Extranjería
- Webs oficiales: [https://www.boe.es](https://www.boe.es), [https://extranjeros.inclusion.gob.es](https://extranjeros.inclusion.gob.es)
- Preguntas frecuentes recopiladas de ONGs como CEAR, Accem, Cáritas, Cruz Roja
- Datos anonimizados de asistencia social real

---

## ⚠️ Challenges

- Algunas situaciones complejas (expulsiones, recursos, menores) requieren siempre abogado humano.
- El sistema debe ser **actualizado constantemente** conforme a cambios legislativos.
- Personas sin conectividad digital siguen excluidas: hay que desarrollar módulos offline.
- Requiere controles éticos sobre almacenamiento, anonimización y uso responsable.

---

## 🚀 ¿Qué sigue?

- Desarrollar prototipo web funcional con streamlit + modelo LLM + lógica de decisión.
- Vinculación con sistemas de cita previa, calendarios y envío automatizado de documentos.
- Crear versiones regionalizadas (Cataluña, Madrid, Andalucía).
- Obtener feedback real de personas migrantes a través de ONGs.
- Publicar como **proyecto de código abierto socialmente responsable**.

---

## 🙌 Agradecimientos

- Curso “Building AI” por inspiración.
- Repositorios de CEAR y Cruz Roja como base documental.
- Datos legales del BOE, bajo dominio público.
- LLMs y librerías: HuggingFace, LangChain, scikit-learn, OpenAI API.

**Imagen destacada:** [Pixabay Legal Help AI – CC0 Public Domain]

---
