# Desarrollo de una aplicación web con panel de administración

Se requiere desarrollar una aplicación web que permita a los usuarios registrarse, iniciar sesión y gestionar sus perfiles. Además, se necesita un panel de administración para que los administradores puedan crear, leer, actualizar y eliminar usuarios. La aplicación debe manejar la autenticación y autorización de usuarios, y el panel de administración debe ser accesible solo para usuarios con rol de administrador.

## Informacion General

| Campo | Valor |
|-------|-------|
| **Tema** | Aplicación web con panel de administración |
| **Nivel** | junior-l1 |
| **Tipo** | practical |
| **Tiempo estimado** | 1 semana |

## Fases del Reto

### Fase 0: Configuración del Proyecto

**Objetivo:** Obtener el proyecto base funcional enviando el Código Base a un asistente de IA, que lo analizará, corregirá errores y generará un ZIP listo para usar.

**Tiempo estimado:** 15-30 minutos

**Instrucciones:**

- Asegúrate de tener instalado para ejecutar el proyecto: Un IDE o editor de código.
- Copia todo el contenido del campo **Código Base** de este reto — incluyendo el texto de instrucciones que aparece al inicio.
- Abre un asistente de IA (Claude en claude.ai, ChatGPT o Gemini — se recomienda Claude), pega el contenido copiado en el chat y envíalo.
- El asistente analizará los archivos, corregirá errores y generará un archivo ZIP descargable. Descárgalo y extráelo en la carpeta donde quieras trabajar.
- Verifica que el proyecto arranca sin errores.

**Entregable:** El proyecto compila/arranca sin errores.

<details>
<summary>Pistas de conocimiento</summary>

- Copia el Código Base completo incluyendo el texto de instrucciones al inicio — esas instrucciones le indican al asistente exactamente qué hacer con los archivos.
- Si el asistente no genera el ZIP automáticamente al terminar el análisis, escríbele: "genera el ZIP ahora".
- Si el proyecto tiene errores al arrancar, comparte el mensaje de error con el mismo asistente para que lo corrija.

</details>

### Fase 1: Configuración inicial del proyecto

**Objetivo:** Configurar el entorno de desarrollo y crear el proyecto básico con Django.

**Tiempo estimado:** 1 día

**Instrucciones:**

- Configurar el entorno virtual y las dependencias necesarias.
- Crear un nuevo proyecto Django.
- Configurar las aplicaciones necesarias para la autenticación y el panel de administración.

**Entregable:** Proyecto Django configurado con aplicaciones de autenticación y panel de administración.

<details>
<summary>Pistas de conocimiento</summary>

- Investigar sobre la configuración de entornos virtuales en Python.
- Consultar la documentación oficial de Django para crear y configurar un nuevo proyecto.

</details>

### Fase 2: Implementación de la autenticación de usuarios

**Objetivo:** Implementar la funcionalidad de registro y autenticación de usuarios.

**Tiempo estimado:** 3 días

**Instrucciones:**

- Crear los modelos necesarios para representar usuarios y perfiles.
- Implementar las vistas y formularios para el registro y autenticación de usuarios.
- Configurar las URLs y las vistas del panel de administración para la gestión de usuarios.

**Entregable:** Aplicación web con funcionalidad de registro y autenticación de usuarios, y panel de administración básico.

<details>
<summary>Pistas de conocimiento</summary>

- Investigar sobre la implementación de modelos en Django.
- Consultar la documentación de Django para crear vistas y formularios.

</details>

### Fase 3: Mejora del panel de administración

**Objetivo:** Mejorar la funcionalidad del panel de administración para la gestión de usuarios.

**Tiempo estimado:** 3 días

**Instrucciones:**

- Añadir funcionalidades adicionales al panel de administración, como la edición y eliminación de usuarios.
- Implementar la autorización basada en roles para restringir el acceso al panel de administración solo a usuarios con rol de administrador.
- Mejorar la interfaz de usuario del panel de administración para una mejor experiencia de usuario.

**Entregable:** Panel de administración mejorado con funcionalidades de edición y eliminación de usuarios, y autorización basada en roles.

<details>
<summary>Pistas de conocimiento</summary>

- Investigar sobre la implementación de la autorización basada en roles en Django.
- Consultar recursos sobre buenas prácticas de diseño de interfaces de usuario.

</details>

## Dimensiones Evaluadas

- **queEs**: ¿Qué es un panel de administración en el contexto de una aplicación web con Django?
- **paraQueSirve**: ¿Para qué sirve la autenticación de usuarios en una aplicación web?
- **comoSeUsa**: ¿Cómo se utiliza la autorización basada en roles para restringir el acceso a ciertas funcionalidades en una aplicación web?
- **erroresComunes**: ¿Cuáles son los errores comunes que pueden ocurrir al implementar la autenticación y autorización en una aplicación web con Django?
- **queDecisionesImplica**: ¿Qué decisiones implica la implementación de un panel de administración en una aplicación web con Django?

## Criterios de Evaluacion

- Configuración correcta del entorno de desarrollo y proyecto Django.
- Implementación funcional de la autenticación y registro de usuarios.
- Configuración correcta de las URLs y vistas del panel de administración.
- Implementación de la autorización basada en roles para el panel de administración.
- Mejora de la interfaz de usuario del panel de administración.

---

*Reto generado automaticamente por Challenge Generator - Pragma*
