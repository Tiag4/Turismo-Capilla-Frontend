# Turismo-Capilla-Frontend
# Frontend | Turismo Capilla del Monte

<p align="center">
  <img src="https://img.shields.io/badge/Proyecto-Turismo%20Capilla%20del%20Monte-2ea44f?style=for-the-badge" alt="Proyecto">
  <img src="https://img.shields.io/badge/Componente-Frontend%20%26%20UI-blueviolet?style=for-the-badge" alt="Frontend">
  <img src="https://img.shields.io/badge/Estado-En%20desarrollo-yellow?style=for-the-badge" alt="Estado">
</p>

<p align="center">
  <strong>Interfaz de usuario y aplicación web interactiva para promocionar la oferta turística y gestionar los servicios de Capilla del Monte.</strong>
</p>

---

## Sobre el proyecto

Este repositorio alberga el desarrollo de la interfaz de usuario (Frontend) de la plataforma **Turismo Capilla del Monte**.

Su propósito es ofrecer una experiencia de usuario (UX/UI) moderna, rápida, accesible y responsive. La aplicación se encarga de consumir las APIs del backend para presentar de forma visual e intuitiva los alojamientos de los socios de la Cámara, mapas interactivos, fichas técnicas con galerías multimedia y paneles diferenciados según el rol del usuario (Turista, Dueño de Hospedaje y Administrador).

El frontend se encuentra actualmente en una etapa inicial de análisis de requerimientos, arquitectura visual y prototipado.

---

## Problema

La oferta turística suele presentarse en plataformas fragmentadas, difíciles de navegar desde dispositivos móviles o sin una identidad visual unificada.

Este desarrollo frontend resuelve:
* **Fragmentación de la experiencia:** Unifica el acceso a los establecimientos asociados en una sola plataforma con diseño responsive e intuitivo.
* **Dificultad de contacto y localización:** Permite explorar alojamientos mediante filtros dinámicos, mapas interactivos y contacto directo (WhatsApp/formulario) sin fricciones.
* **Barreras idiomáticas:** Introduce soporte multi-idioma (Español / Inglés) para visitantes internacionales.

---

## Objetivo

Diseñar e implementar una aplicación web responsiva, accesible y de alto rendimiento que **facilite la navegación, consulta y contacto de la oferta turística** de Capilla del Monte.

### Objetivos específicos

* Diseñar wireframes y prototipos interactivos centrados en la usabilidad.
* Construir una arquitectura de componentes escalable y reutilizable.
* Integrar consumo asíncrono eficiente de la API REST del backend.
* Implementar vistas diferenciadas según roles: catálogo público para turistas, panel simple para socios (carga de datos, fotos y check-in) y vista administrativa.
* Integrar mapas interactivos georreferenciados de la localidad.
* Asegurar soporte responsive (mobile-first) y multi-idioma (i18n).

---

## Alcance inicial del Frontend

La primera versión contempla la implementación de las siguientes vistas y componentes:

* **Portal Turista:**
  * Landing page y catálogo general con filtrado dinámico por comodidades y servicios.
  * Ficha técnica detallada de cada cabaña con galería de hasta 10 fotos optimizadas.
  * Mapa interactivo de Capilla del Monte con marcadores de establecimientos habilitados.
  * Botones de contacto directo (integración con API de WhatsApp y formulario de consulta).
  * Selector de idioma (Español / Inglés).
* **Panel Socio / Dueño:**
  * Formulario de gestión de ficha técnica, comodidades y carga de imágenes.
  * Módulo simple de registro de ingresos (check-in de huéspedes).
* **Panel Administración (Cámara):**
  * Listado de control de socios para habilitar/deshabilitar visibilidad en la plataforma.
  * Página y formulario de contacto institucional.

---

## Tecnologías

El stack técnico definitivo está en proceso de evaluación y selección.

Se contemplan frameworks y herramientas modernas del ecosistema frontend (como React, Vue o Next.js/Astro, Tailwind CSS para estilos y bibliotecas de mapas como Leaflet/Mapbox).

> **Nota:** esta sección se actualizará con el stack oficial, versiones requeridas de Node.js/npm/yarn y variables de entorno (`.env`) una vez formalizadas.

---

## Equipo

Proyecto desarrollado por:

| Integrante               |
| ----------------------- |
| **Tiago Nicolitsis**    |
| **Martino Costigliolo** |
| **Juan Larcher**        |

---

## Etapas de desarrollo (Frontend)

### 1. Wireframing y Prototipado
Definición del flujo de navegación (UX), diseño de pantallas en Figma y selección del sistema de diseño (UI Kit).

### 2. Configuración de Arquitectura Base
Estructuración de carpetas, configuración de librerías de estilos, cliente HTTP (Axios / Fetch) y gestión de estado global.

### 3. Maquetación y Componentes
Construcción de componentes atómicos (botones, tarjetas, modales, barras de navegación, formularios).

### 4. Integración con Backend
Consumo de endpoints de la API REST, manejo de estados de carga (loaders/spinners) y captura de errores.

### 5. Optimización y Accesibilidad
Optimización de renderizado, compresión de assets, carga diferida de imágenes (lazy loading) y validación responsive.

### 6. Despliegue
Configuración del pipeline de integración y publicación en servidor o plataforma de hosting (Vercel, Netlify o VPS).

---

## Entregables

* Prototipos de alta fidelidad y wireframes.
* Aplicación web responsive funcional desplegada.
* Sistema de diseño y biblioteca de componentes documentada.
* Configuración de internacionalización (archivos de localización `es`/`en`).
* Documentación para ejecución en entorno local.

---

## Estado del proyecto

**Actualmente: En etapa de inicio, análisis de interfaz y definición de arquitectura frontend.**

---

## 📚 Documentación y Recursos

- **Wiki del repositorio:** Detalla los aspectos del marco PMI, manual de marca, diseño de interfaz y actas.
- **Google Drive:** Almacena los activos visuales y la documentación general.  
  [Acceder a la carpeta del proyecto en Google Drive](https://drive.google.com/drive/u/1/folders/1KQLWydgsWH7hCD0RqfqIrFO5AzJRqB5E)

---

<p align="center">
  <strong>Turismo Capilla del Monte - Frontend UI</strong><br>
  Capa de presentación y experiencia de usuario.
</p>
