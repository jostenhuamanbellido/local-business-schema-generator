# Generador de Schema.org para negocios locales

Herramienta web gratuita para generar datos estructurados **JSON-LD (Schema.org)** listos para clínicas, consultorios y negocios locales — pensada para el trabajo diario de SEO técnico en el sector salud.

🔗 **Demo en vivo:** https://jostenhuamanbellido.github.io/local-business-schema-generator/

## ¿Qué hace?

Completas un formulario (nombre, dirección, teléfono, horario, redes sociales, tipo de negocio) y la herramienta genera en tiempo real el bloque `<script type="application/ld+json">` listo para pegar en el `<head>` de cualquier sitio.

- Soporta los tipos de negocio más usados en salud: `MedicalClinic`, `MedicalBusiness`, `Physician`, `Dentist`, `Hospital`, `DaySpa`, además de `LocalBusiness` genérico y otros.
- Genera `PostalAddress`, `GeoCoordinates`, `OpeningHoursSpecification` por día y `sameAs` (redes sociales) solo con los campos que completes.
- Todo corre en el navegador — sin backend, sin envío de datos a ningún servidor.
- Incluye enlace directo a la [herramienta de resultados enriquecidos de Google](https://search.google.com/test/rich-results) para validar el resultado antes de publicarlo.

## Por qué lo construí

Genero este tipo de marcado en Schema.org constantemente para los sitios de salud que desarrollo y posiciono (clínicas, consultorios médicos, centros estéticos). En vez de escribir el JSON-LD a mano cada vez, automaticé el proceso.

## Stack

HTML, CSS y JavaScript puros — sin frameworks ni dependencias — desplegado con GitHub Pages.

## Autor

**Josten Marc Huamán Bellido** — Desarrollador Web & Especialista en SEO
[Portafolio](https://jostenhuamanbellido.github.io/portfolio/) · [LinkedIn](https://www.linkedin.com/in/jostenhuamanbellido/)
