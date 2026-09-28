# 🐾 HuellaVetPQR

![Logo HuellaVet](images/logo.png)

**Universidad de Antioquia — Facultad de Ingeniería**
**Departamento de Ingeniería Industrial**
**Curso:** Algoritmia y Programación 2026-2
**Profesor:** Victor Hugo Mercado Ramos

---

## 📋 Tabla de Contenido

1. [Integrantes](#1--integrantes)
2. [Vínculos Académicos y Descripción](#2--vínculos-académicos-y-descripción)
3. [Nombre del Proyecto y Detalles](#3--nombre-del-proyecto-y-detalles)
4. [Licencia del Software](#4--licencia-del-software)
5. [Reporte de Visión](#5--reporte-de-visión)
6. [Especificación de Requisitos](#6--especificación-de-requisitos)
7. [Plan de Proyecto](#7--plan-de-proyecto)

---

## 1. 👥 Integrantes

| # | Nombre completo | Cédula | Correo institucional | Rol |
|---|-----------------|--------|----------------------|-----|
| 1 | [Nombre 1] | [Cédula 1] | [correo1]@udea.edu.co | Líder / Desarrollador |
| 2 | [Nombre 2] | [Cédula 2] | [correo2]@udea.edu.co | Desarrollador Backend |
| 3 | [Nombre 3] | [Cédula 3] | [correo3]@udea.edu.co | QA / Validaciones |
| 4 | [Nombre 4] | [Cédula 4] | [correo4]@udea.edu.co | Documentación |

---

## 2. 🎓 Vínculos Académicos y Descripción

Todos los integrantes pertenecemos al programa de **Ingeniería Industrial** de la Universidad de Antioquia.

### [Nombre 1] — Líder del proyecto
- **Programa:** Ingeniería Industrial
- **Habilidades:** Liderazgo, Python, Git/GitHub, gestión de proyectos.
- **Fortalezas:** Organización, comunicación asertiva, resolución de conflictos.

### [Nombre 2] — Desarrollador Backend
- **Programa:** Ingeniería Industrial
- **Habilidades:** Python, manejo de archivos, estructuras de datos.
- **Fortalezas:** Pensamiento lógico, atención al detalle.

### [Nombre 3] — QA / Validaciones
- **Programa:** Ingeniería Industrial
- **Habilidades:** Expresiones regulares, testing, Python.
- **Fortalezas:** Rigurosidad, análisis de errores.

### [Nombre 4] — Documentación
- **Programa:** Ingeniería Industrial
- **Habilidades:** Redacción técnica, Markdown, LaTeX.
- **Fortalezas:** Claridad, síntesis, ortografía.

### [Nombre 5] — Analista Power BI
- **Programa:** Ingeniería Industrial
- **Habilidades:** Power BI, DAX, Excel, análisis de datos.
- **Fortalezas:** Visualización de datos, interpretación de KPIs.

---

## 3. 🏷️ Nombre del Proyecto y Detalles

### Nombre
**HuellaVet**

### Eslogan
*"Cuidamos sus huellas, gestionamos sus voces"*

### Logo
![Logo HuellaVet](images/logo.png)

### Descripción breve
**HuellaVet** es un sistema de consola desarrollado en Python que permite gestionar las Peticiones, Quejas, Reclamos y Sugerencias (PQRS) relacionadas con la atención veterinaria de perros y gatos en los campus de la Universidad de Antioquia, en apoyo al grupo estudiantil MEPEGA.

### ¿Por qué este nombre?
- **Huella** → representa a las mascotas (perros y gatos) y su rastro en el campus.
- **Vet** → hace referencia al servicio veterinario.
- Juntos, comunican cercanía, cuidado y profesionalismo.

### Ajuste acordado con el PO (profesor)
- **Tiempo máximo de respuesta:** reducido de **30 días** a **15 días calendario**.
  - Justificación: la atención veterinaria requiere respuestas más rápidas para garantizar el bienestar animal.

---

## 4. 📜 Licencia del Software

Este proyecto se distribuye bajo la licencia:

### **Creative Commons Atribución-NoComercial-CompartirIgual 4.0 Internacional (CC BY-NC-SA 4.0)**

**Resumen de la licencia:**

| Icono | Permiso | Descripción |
|-------|---------|-------------|
| ✅ | Compartir | Copiar y redistribuir el material en cualquier medio o formato. |
| ✅ | Adaptar | Remezclar, transformar y construir a partir del material. |
| ⚠️ | Atribución | Debes dar crédito al autor original. |
| ⚠️ | NoComercial | No puedes usar el material con fines comerciales. |
| ⚠️ | CompartirIgual | Si transformas el material, debes distribuirlo bajo la misma licencia. |

🔗 **Enlace oficial:** https://creativecommons.org/licenses/by-nc-sa/4.0/

### Cómo citar este proyecto:
> [Integrantes del grupo]. (2026). HuellaVet: Gestor de PQRS para la atención veterinaria de MEPEGA. Universidad de Antioquia. Licencia CC BY-NC-SA 4.0.

---

## 5. 🎯 Reporte de Visión

### 5.1 Descripción general del software

**HuellaVet** es una aplicación de consola desarrollada en **Python** que automatiza la gestión de PQRS (Peticiones, Quejas, Reclamos y Sugerencias) recibidas por el grupo estudiantil **MEPEGA** para la atención de perros y gatos en los campus de la Universidad de Antioquia.

Actualmente, MEPEGA registra las PQRS de forma manual (papel y lápiz), lo cual genera:
- Pérdida de información.
- Duplicidad de radicados.
- Dificultad para hacer seguimiento.
- Ausencia de estadísticas.

**HuellaVet** soluciona estos problemas digitalizando el proceso, validando los datos, generando radicados en formato ASCII y produciendo estadísticas exportables a Power BI.

### 5.2 Objetivos

#### Objetivo general
Desarrollar un sistema de consola en Python que permita gestionar de forma eficiente las PQRS de MEPEGA, garantizando la integridad de los datos, la trazabilidad de cada radicado y la generación de estadísticas.

#### Objetivos específicos
1. Implementar un módulo de autenticación con control de intentos.
2. Validar todos los campos de las PQRS según reglas estrictas.
3. Almacenar los registros en 4 archivos planos independientes por tipo de solicitud.
4. Generar comprobantes de radicado en formato ASCII de 120 caracteres.
5. Permitir la consulta y actualización del estado de las PQRS.
6. Calcular 6 estadísticas clave para la toma de decisiones.
7. Exportar los datos para su visualización en Power BI.

### 5.3 Beneficios

#### Para MEPEGA
- ✅ Reducción del 90% del tiempo de radicación.
- ✅ Eliminación de radicados duplicados.
- ✅ Trazabilidad completa del ciclo de vida de cada PQRS.
- ✅ Alertas automáticas de vencimiento.

#### Para los solicitantes
- ✅ Radicado inmediato con formato profesional.
- ✅ Seguimiento claro del estado de su solicitud.

#### Para la Universidad
- ✅ Estadísticas para la toma de decisiones sobre bienestar animal.
- ✅ Base para futuras integraciones con otros sistemas.

### 5.4 Alcance

El sistema **incluye**:
- Autenticación y control de sesión.
- Registro, consulta y actualización de PQRS.
- Generación de radicados ASCII.
- Estadísticas y exportación a Power BI.

El sistema **no incluye**:
- Interfaz gráfica (GUI) — es solo consola.
- Base de datos SQL — usa archivos planos.
- Envío de correos automáticos.
- App móvil.

---

## 6. 📋 Especificación de Requisitos

### 6.1 Requisitos Funcionales (RF)

| ID | Nombre | Descripción | Prioridad |
|----|--------|-------------|-----------|
| RF-01 | Autenticación | El sistema debe permitir el ingreso con usuario y contraseña validados contra `usuarios.txt`. | Alta |
| RF-02 | Control de intentos | Tras 3 intentos fallidos, la cuenta se bloquea 30 segundos. | Alta |
| RF-03 | Registrar PQRS | El sistema debe permitir registrar PQRS con todos los campos validados. | Alta |
| RF-04 | Validar datos del solicitante | Validar nombre, documento, teléfono, correo y dirección según reglas. | Alta |
| RF-05 | Validar información PQRS | Validar tipo, fecha, canal, asunto y descripción. | Alta |
| RF-06 | Generar ID auto-incremental | Cada tipo de PQRS tendrá su propio contador independiente. | Alta |
| RF-07 | Calcular fecha máxima de respuesta | Fecha de radicación + **15 días calendario** (ajustado). | Alta |
| RF-08 | Estado inicial | Toda PQRS se registra con estado "Registrada". | Alta |
| RF-09 | Flujo de estados | Registrada → En proceso → Solucionada. | Media |
| RF-10 | Imprimir radicado ASCII | Generar comprobante .txt de 120 caracteres por línea. | Alta |
| RF-11 | Gestionar 4 archivos planos | Peticion.txt, Queja.txt, Reclamo.txt, Sugerencia.txt. | Alta |
| RF-12 | Consultar PQRS | Listar registros por tipo de solicitud. | Media |
| RF-13 | Actualizar estado | Cambiar el estado de una PQRS respetando el flujo. | Media |
| RF-14 | Estadísticas | Calcular promedio de días + 5 estadísticas adicionales. | Alta |
| RF-15 | Asignar usuario registrador | Vincular automáticamente el usuario autenticado. | Media |
| RF-16 | Exportar a Power BI | Los archivos planos deben ser legibles por Power BI. | Media |

### 6.2 Requisitos No Funcionales (RNF)

| ID | Nombre | Descripción |
|----|--------|-------------|
| RNF-01 | Lenguaje | Desarrollado en Python 3.8+. |
| RNF-02 | Modularización | Código separado en `validaciones.py`, `archivos.py`, `reportes.py`. |
| RNF-03 | Portabilidad | Debe ejecutarse en Windows, Linux y macOS. |
| RNF-04 | Usabilidad | Interfaz de consola clara, con menús numerados. |
| RNF-05 | Rendimiento | Debe procesar 1000 registros sin demoras perceptibles. |
| RNF-06 | Persistencia | Uso de archivos planos (sin base de datos). |
| RNF-07 | Seguridad | Contraseñas almacenadas en archivo local. |
| RNF-08 | Mantenibilidad | Código comentado y con nombres descriptivos. |
| RNF-09 | Versionado | Uso de Git y GitHub con commits descriptivos. |
| RNF-10 | Documentación | README, manual de usuario y actas. |
| RNF-11 | Formato de radicado | Exactamente 120 caracteres de ancho. |
| RNF-12 | Cumplimiento de plazo | Fecha máxima = +15 días (ajustado por el equipo). |

### 6.3 Matriz de trazabilidad

| Requisito | Módulo | Archivo |
|-----------|--------|---------|
| RF-01, RF-02 | Login | `src/login.py` |
| RF-03 a RF-10 | Registro | `src/main.py` |
| RF-04, RF-05 | Validaciones | `src/validaciones.py` |
| RF-11 | Archivos | `src/archivos.py` |
| RF-12, RF-13 | Consulta/Actualización | `src/main.py` |
| RF-14 | Estadísticas | `src/reportes.py` |

---

## 7. 📅 Plan de Proyecto

### 7.1 Actividades del Proyecto

| # | Actividad | Responsable | Duración |
|---|-----------|-------------|----------|
| 1 | Análisis de requisitos (entrevista con el PO) | Todos | 1 semana |
| 2 | Diseño de la arquitectura modular | Líder | 3 días |
| 3 | Desarrollo de `validaciones.py` | QA | 1 semana |
| 4 | Desarrollo de `archivos.py` | Backend | 1 semana |
| 5 | Desarrollo de `login.py` | Líder | 3 días |
| 6 | Desarrollo de `main.py` | Líder + Backend | 2 semanas |
| 7 | Desarrollo de `reportes.py` | Analista | 1 semana |
| 8 | Pruebas unitarias | QA | 1 semana |
| 9 | Elaboración del radicado ASCII | Backend | 3 días |
| 10 | Creación del dashboard Power BI | Analista | 2 semanas |
| 11 | Documentación (README, manuales, actas) | Documentador | 2 semanas |
| 12 | Sustentación final | Todos | 1 día |

### 7.2 Cronograma — Diagrama de Gantt
