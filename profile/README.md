# 🌐 Desarrollo Web en Entorno Servidor

Repositorio de trabajo de la asignatura **Desarrollo Web en Entorno Servidor (DWES)** del ciclo de **Desarrollo de Aplicaciones Web — 2.º curso**.

**IES La Laboral · Gijón · Curso 2026/2027**

---

## 📚 Sobre la asignatura

Desarrollo Web en Entorno Servidor es uno de los módulos profesionales de segundo curso del ciclo formativo de grado superior de **Desarrollo de Aplicaciones Web (DAW)**.

El módulo aborda el desarrollo de aplicaciones web desde el lado del servidor:

- Arquitectura cliente-servidor.
- Programación backend.
- Procesamiento de peticiones HTTP.
- Formularios y gestión de datos.
- Persistencia y acceso a bases de datos.
- Arquitecturas de aplicaciones web.
- Frameworks de desarrollo.
- Sesiones, autenticación y seguridad.
- APIs y servicios web.
- Desarrollo y despliegue de aplicaciones.

La asignatura tiene una carga curricular de:

> **130 horas · 6 horas semanales**

---

# 🗓️ Horario

| Día | Horario |
|---|---|
| Lunes | 17:20 – 19:30 |
| Martes | 15:30 – 16:30 |
| Jueves | 15:30 – 16:30 |
| Viernes | 15:30 – 17:20 |

**Total: 6 horas semanales**

---

# 🎯 Resultados de aprendizaje

El módulo se estructura en torno a **9 Resultados de Aprendizaje**.

### RA1
Selecciona las arquitecturas y tecnologías de programación web en entorno servidor, analizando sus capacidades y características propias.

### RA2
Escribe sentencias ejecutables por un servidor web reconociendo y aplicando procedimientos de integración del código en lenguajes de marcas.

### RA3
Escribe bloques de sentencias embebidos en lenguajes de marcas, seleccionando y utilizando las estructuras de programación.

### RA4
Desarrolla aplicaciones web embebidas en lenguajes de marcas analizando e incorporando funcionalidades según especificaciones.

### RA5
Desarrolla aplicaciones web identificando y aplicando mecanismos para separar el código de presentación de la lógica de negocio.

### RA6
Desarrolla aplicaciones de acceso a almacenes de datos, aplicando medidas para mantener la seguridad y la integridad de la información.

### RA7
Desarrolla servicios web reutilizables y accesibles mediante protocolos web, verificando su funcionamiento.

### RA8
Genera páginas web dinámicas analizando y utilizando tecnologías y frameworks del servidor web que añadan código al lenguaje de marcas.

### RA9
Desarrolla aplicaciones web híbridas seleccionando y utilizando librerías de código y repositorios heterogéneos de información.

---

# 🧭 Organización del curso

La asignatura se plantea como una evolución desde los fundamentos del desarrollo backend hasta la construcción de aplicaciones web completas.

```text
Internet y HTTP
      │
      ▼
Arquitectura cliente-servidor
      │
      ▼
Programación en servidor
      │
      ▼
Persistencia y bases de datos
      │
      ▼
Arquitectura de aplicaciones
      │
      ▼
Frameworks backend
      │
      ▼
Seguridad y sesiones
      │
      ▼
APIs y servicios web
      │
      ▼
Aplicación web completa
```

---

# 🧩 Unidades de trabajo

La organización de referencia del módulo contempla las siguientes áreas:

| UT | Unidad | Área principal |
|---:|---|---|
| 01 | Arquitecturas y tecnologías de programación web | Fundamentos |
| 02 | Acceso a datos | Persistencia |
| 03 | Patrones de diseño en desarrollo web | Arquitectura |
| 04 | Persistencia avanzada y ORM | Datos |
| 05 | Desarrollo de aplicaciones web en servidor | Backend |
| 06 | Desarrollo con frameworks | Frameworks |
| 07 | Sesiones y seguridad | Seguridad |
| 08 | Servicios Web | APIs |

> La secuenciación y las tecnologías concretas utilizadas pueden adaptarse durante el curso.

---

# 🐙 Organización de GitHub

Esta organización de GitHub será nuestro **espacio de desarrollo durante el curso**.

Aquí se publicarán:

- ejemplos realizados en clase;
- proyectos base;
- ejercicios;
- prácticas;
- retos;
- documentación;
- recursos;
- repositorios plantilla;
- proyectos individuales y colaborativos.

La intención es trabajar de una forma similar a un **entorno real de desarrollo de software**.

---

# 📂 Estructura de los repositorios

Los repositorios podrán seguir una estructura similar a:

```text
DesWebEntornoServidor/
│
├── 00-entorno/
├── 01-fundamentos-backend/
├── 02-http/
├── 03-php/
├── 04-formularios/
├── 05-bbdd/
├── 06-arquitectura/
├── 07-framework/
├── 08-seguridad/
├── 09-api-rest/
│
├── ejemplos/
├── ejercicios/
└── proyectos/
```

La estructura definitiva irá evolucionando con el desarrollo del curso.

---

# 🔄 Flujo de trabajo

En las actividades utilizaremos Git y GitHub como herramientas habituales de desarrollo.

Flujo básico:

```text
Repositorio
    ↓
Clone
    ↓
Desarrollo
    ↓
Commit
    ↓
Push
    ↓
Revisión
```

En proyectos determinados podremos incorporar además:

```text
Issue
  ↓
Branch
  ↓
Código
  ↓
Commit
  ↓
Pull Request
  ↓
Code Review
  ↓
Merge
```

---

# 🌿 Ramas

Cuando el proyecto lo requiera utilizaremos ramas para separar el desarrollo.

Ejemplo:

```text
main
 │
 ├── feature/login
 ├── feature/api
 ├── feature/database
 └── fix/session-error
```

La rama `main` debe representar una versión estable del proyecto.

---

# 💬 Commits

Los mensajes de commit deben explicar de forma clara qué modificación se ha realizado.

### ✅ Ejemplos

```bash
git commit -m "Añade conexión con la base de datos"
git commit -m "Implementa formulario de registro"
git commit -m "Corrige validación del usuario"
git commit -m "Añade endpoint GET /usuarios"
```

### ❌ Evitar

```bash
git commit -m "cosas"
git commit -m "cambios"
git commit -m "prueba"
git commit -m "final"
git commit -m "ahora si"
```

---

# 📋 Issues

En algunos proyectos utilizaremos **GitHub Issues** para organizar el trabajo.

Una issue puede representar:

- una funcionalidad;
- una tarea;
- un error;
- una mejora;
- una investigación técnica.

Ejemplo:

```text
#12 Implementar autenticación de usuarios

Objetivo:
Permitir que un usuario pueda iniciar sesión.

Tareas:
- Crear formulario.
- Validar credenciales.
- Crear sesión.
- Implementar logout.
```

---

# 🔀 Pull Requests

Los proyectos colaborativos podrán utilizar **Pull Requests**.

Una Pull Request permite:

1. proponer un cambio;
2. revisar el código;
3. discutir una implementación;
4. realizar modificaciones;
5. integrar finalmente el código en `main`.

El objetivo no es únicamente aprender GitHub, sino incorporar progresivamente prácticas habituales de **desarrollo profesional de software**.

---

# 🧪 Desarrollo y experimentación

Los repositorios de la asignatura son también un entorno de aprendizaje.

Eso significa que:

> equivocarse forma parte del proceso.

Se podrá:

- experimentar;
- romper código;
- utilizar el debugger;
- analizar errores;
- comparar soluciones;
- refactorizar;
- volver a versiones anteriores mediante Git.

Lo importante es comprender **por qué funciona una solución y cómo está construida**.

---

# 🤖 Inteligencia Artificial

Las herramientas de inteligencia artificial pueden formar parte del entorno de desarrollo.

Su utilización debe estar orientada a:

- comprender código;
- investigar documentación;
- detectar errores;
- plantear alternativas;
- generar pruebas;
- refactorizar;
- documentar.

Pero el alumnado debe ser capaz de:

> **explicar, modificar y defender el código que entrega.**

La responsabilidad sobre el código entregado corresponde siempre a quien lo presenta.

---

# 🧠 Filosofía del módulo

En DWES no buscamos únicamente que una aplicación:

> **“funcione”.**

Buscamos aprender a construir software que sea:

- comprensible;
- mantenible;
- modular;
- seguro;
- documentado;
- verificable;
- evolucionable.

Por eso trabajaremos progresivamente conceptos de:

```text
Código
  +
Arquitectura
  +
Datos
  +
Seguridad
  +
Testing
  +
Git
  +
Documentación
  =
Aplicación Web
```

---

# 🛠️ Herramientas

A lo largo del curso podremos utilizar herramientas como:

- Git
- GitHub
- Visual Studio Code
- PHP
- Composer
- MySQL / MariaDB
- Docker
- Postman / Bruno
- Frameworks backend
- APIs REST
- herramientas de desarrollo del navegador

La selección exacta podrá evolucionar durante el curso.

---

# 📖 Documentación

Una competencia fundamental para un desarrollador es aprender a trabajar con documentación técnica.

Durante el módulo utilizaremos:

- documentación oficial;
- especificaciones;
- manuales;
- repositorios;
- README;
- documentación de APIs;
- documentación generada por los propios proyectos.

---

# 👨‍💻 Metodología

El módulo tendrá un enfoque eminentemente práctico.

Trabajaremos mediante:

1. explicación de conceptos;
2. pequeños ejemplos;
3. ejercicios guiados;
4. ejercicios autónomos;
5. retos;
6. prácticas;
7. proyectos progresivamente más completos.

La programación será una actividad diaria.

---

# 🎓 Ciclo formativo

**CFGS Desarrollo de Aplicaciones Web**

**Curso:** 2.º DAW  
**Módulo:** Desarrollo Web en Entorno Servidor  
**Código:** 0613  
**Curso académico:** 2026/2027  
**Centro:** IES La Laboral · Gijón

---

## 🚀 Objetivo

Al finalizar el módulo, el alumnado debería ser capaz de pasar de:

```text
GET /hola
```

a diseñar, desarrollar y comprender una aplicación web backend completa.

---

> **Aprender desarrollo web no consiste en memorizar código.**
>
> Consiste en aprender a analizar problemas, diseñar soluciones y convertirlas en software.
