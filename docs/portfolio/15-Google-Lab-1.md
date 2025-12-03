---
title: "15 — Google Cloud: A Tour of Hands-on Labs"
date: 2025-11-26
---

# 15 — Google Cloud: A Tour of Hands-on Labs

Introducción práctica al ecosistema de Google Cloud Platform (GCP) mediante laboratorios guiados "Hands-on", cubriendo gestión de identidades, APIs y operaciones básicas.

## Contexto
La nube pública es el entorno estándar para desplegar soluciones de datos modernas. Google Skills Boost ofrece un entorno "sandbox" seguro para interactuar con servicios reales de GCP sin riesgo de costos imprevistos, permitiendo familiarizarse con la consola y los flujos de trabajo esenciales.

## Objetivos
- Navegar fluidamente por la Consola de Google Cloud.
- Comprender la jerarquía de recursos (Organización, Carpeta, Proyecto).
- Gestionar accesos mediante IAM (Identity and Access Management).
- Habilitar APIs y servicios, y utilizar Cloud Shell.

## Actividades (con tiempos estimados)
- Acceso a Qwiklabs/Skills Boost y arranque del lab — 10 min
- Exploración del Dashboard de Proyecto y facturación — 10 min
- Gestión de usuarios y roles en IAM — 15 min
- Habilitación de APIs (ej. Cloud Vision, Compute Engine) — 10 min
- Ejecución de comandos básicos en Cloud Shell — 15 min

## Desarrollo
### 1. Consola y Proyectos
Iniciamos un entorno de laboratorio temporal. Identificamos el `Project ID`, que es único globalmente. Exploramos el panel de navegación para localizar servicios clave como Compute Engine y Storage.

### 2. IAM y Seguridad
Accedimos al servicio de IAM & Admin para revisar los permisos concedidos a la cuenta de estudiante. Verificamos cómo los roles (Viewer, Editor, Owner) controlan el acceso a los recursos del proyecto.

### 3. APIs y Servicios
Navegamos a la biblioteca de APIs para habilitar servicios específicos requeridos para una solución (por ejemplo, Dialogflow API o Cloud Storage API). Entendimos que las APIs deben habilitarse explícitamente por proyecto.

### 4. Cloud Shell
Utilizamos la terminal integrada en el navegador (Cloud Shell) para interactuar con los recursos mediante la línea de comandos `gcloud`, listando configuraciones y recursos activos sin salir de la consola web.

## Reflexión
Este laboratorio fundacional destaca la importancia de la gestión estructurada de recursos en la nube. La consola de GCP centraliza miles de servicios, por lo que saber navegar y utilizar el buscador de productos es vital. El uso de Cloud Shell con `gcloud` ofrece una potencia de automatización superior a la interfaz gráfica para tareas repetitivas.

## Referencias
- Google Skills Lab GSP430

