# Contenerización y optimización de una aplicación web

Una aplicación web necesita ser contenerizada para mejorar su despliegue y escalabilidad. El objetivo es usar Docker y Docker Compose para contenerizar la aplicación y aplicar estrategias de optimización de imágenes para reducir el tamaño y mejorar el rendimiento.

## Informacion General

| Campo | Valor |
|-------|-------|
| **Tema** | Implementar contenerización de una aplicación web usando Docker y Docker Compose, con estrategias de optimización de imágenes |
| **Nivel** | junior-l2 |
| **Tipo** | practical |
| **Tiempo estimado** | 4-6 horas |

## Fases del Reto

### Fase 0: Configuración del Proyecto

**Objetivo:** Obtener el proyecto base funcional enviando el Código Base a un asistente de IA, que lo analizará, corregirá errores y generará un ZIP listo para usar.

**Tiempo estimado:** 15-30 minutos

**Instrucciones:**

- Asegúrate de tener instalado para ejecutar el proyecto: Python 3.10+, pip, VS Code o similar.
- Copia todo el contenido del campo **Código Base** de este reto — incluyendo el texto de instrucciones que aparece al inicio.
- Abre un asistente de IA (Claude en claude.ai, ChatGPT o Gemini — se recomienda Claude), pega el contenido copiado en el chat y envíalo.
- El asistente analizará los archivos, corregirá errores y generará un archivo ZIP descargable. Descárgalo y extráelo en la carpeta donde quieras trabajar.
- Ejecuta `pip install -r requirements.txt` y luego arranca el proyecto. Si no hay errores, estás listo.

**Entregable:** El proyecto compila/arranca sin errores.

<details>
<summary>Pistas de conocimiento</summary>

- Copia el Código Base completo incluyendo el texto de instrucciones al inicio — esas instrucciones le indican al asistente exactamente qué hacer con los archivos.
- Si el asistente no genera el ZIP automáticamente al terminar el análisis, escríbele: "genera el ZIP ahora".
- Si el proyecto tiene errores al arrancar, comparte el mensaje de error con el mismo asistente para que lo corrija.

</details>

### Fase 1: Contenerización básica de la aplicación

**Objetivo:** Tener una versión contenerizada de la aplicación que se pueda ejecutar localmente.

**Tiempo estimado:** 1-2 horas

**Instrucciones:**

- Identificar los componentes de la aplicación que necesitan ser contenerizados.
- Crear un Dockerfile para la aplicación.
- Construir la imagen Docker y verificar que la aplicación se ejecuta correctamente dentro del contenedor.

**Entregable:** Imagen Docker de la aplicación que se ejecuta correctamente.

<details>
<summary>Pistas de conocimiento</summary>

- Considera las dependencias y el entorno de ejecución necesario para la aplicación.
- Piensa en cómo puedes verificar que la aplicación funciona dentro del contenedor.

</details>

### Fase 2: Uso de Docker Compose para gestionar servicios

**Objetivo:** Configurar Docker Compose para gestionar múltiples servicios de la aplicación.

**Tiempo estimado:** 1-2 horas

**Instrucciones:**

- Crear un archivo docker-compose.yml para definir los servicios de la aplicación.
- Asegurar que los servicios se comuniquen entre sí correctamente.
- Verificar que la aplicación completa se ejecuta con Docker Compose.

**Entregable:** Archivo docker-compose.yml que permite ejecutar la aplicación completa con múltiples servicios.

<details>
<summary>Pistas de conocimiento</summary>

- Considera cómo los servicios se comunicarán entre sí.
- Piensa en las dependencias entre servicios y cómo gestionarlas.

</details>

### Fase 3: Optimización de imágenes Docker

**Objetivo:** Aplicar estrategias de optimización para reducir el tamaño de las imágenes Docker.

**Tiempo estimado:** 2 horas

**Instrucciones:**

- Identificar oportunidades de optimización en el Dockerfile.
- Aplicar técnicas como multi-stage builds o uso de imágenes base pequeñas.
- Verificar que la imagen optimizada se construye y ejecuta correctamente.

**Entregable:** Imagen Docker optimizada que se ejecuta correctamente.

<details>
<summary>Pistas de conocimiento</summary>

- Considera el uso de imágenes base pequeñas y multi-stage builds.
- Piensa en cómo puedes verificar que la imagen optimizada funciona como se espera.

</details>

## Dimensiones Evaluadas

- **queEs**: ¿Qué es Docker y para qué se usa en el contexto de esta aplicación?
- **comoSeUsa**: ¿Cómo configuraste Docker Compose para gestionar los servicios de la aplicación?
- **erroresComunes**: ¿Qué errores comunes encontraste al contenerizar la aplicación y cómo los resolviste?
- **queDecisionesImplica**: ¿Qué decisiones tomaste al optimizar las imágenes Docker y por qué?

## Criterios de Evaluacion

- Crear un Dockerfile para la aplicación.
- Construir una imagen Docker y verificar su ejecución.
- Configurar Docker Compose para gestionar servicios.
- Aplicar técnicas de optimización de imágenes Docker.

---

*Reto generado automaticamente por Challenge Generator - Pragma*
