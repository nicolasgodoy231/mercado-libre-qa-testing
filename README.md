# Mercado Libre - Proyecto de Testing Manual (Web & Mobile)

![Mercado Libre Banner](https://i.imgur.com/0n5Z0wM.png)
<!-- Reemplazar el link de arriba por una captura propia del home de Mercado Libre -->

**Proyecto de QA Manual** realizado como parte de mi portfolio profesional.  
Se probaron las funcionalidades principales de **Mercado Libre** en entorno web (PC) y aplicación móvil (Android/iOS), cubriendo flujo de compra completo (sin realizar pagos reales).

## Objetivo
Validar funcionalmente la experiencia de usuario en Mercado Libre, identificando posibles defectos en:
- Navegación y búsqueda
- Filtros y ordenamiento
- Detalle de producto
- Carrito y checkout
- Compatibilidad y responsividad

## Alcance del Testing
- **Plataformas**: Web (Chrome, Firefox) y App Mobile (Android e iOS)
- **Tipos de prueba**: Funcional, usabilidad, compatibilidad, exploratorio
- **Casos ejecutados**: 50 casos de prueba manuales
- **Out of scope**: Pagos reales, publicaciones, área de vendedor, notificaciones push

## Entornos Probados
| Plataforma   | Dispositivo / Navegador                  | Resolución / SO              |
|--------------|------------------------------------------|------------------------------|
| Web          | Google Chrome (última versión)           | 1920x1080 - Windows 11       |
| Web          | Mozilla Firefox                          | 1920x1080 - Windows 11       |
| Mobile (App) | Samsung Galaxy / Emulador Android        | Android 14                   |
| Mobile (App) | iPhone 14 / Simulador iOS                | iOS 17+                      |
| Web Mobile   | Chrome DevTools (vista responsive)       | 375px (mobile view)          |

## Documentación del Proyecto

- **[Test Plan completo](docs/Test-Plan-MercadoLibre.md)** → Objetivos, alcance, criterios de aceptación y estrategia.
- **[Hoja de Casos de Prueba (Google Sheets)](https://docs.google.com/spreadsheets/d/[ACA_PONES_EL_LINK_DE_TU_HOJA])**  
  (50 casos de prueba con ID, pasos, datos, resultado esperado/obtenido, evidencias e incidencias)
- **[Carpeta de Evidencias](/evidencias)** → Screenshots y videos cortos de ejecución (nombrados por TC).
- **[Reporte de Bugs](/bugs/BUGS.md)** → Lista de defectos encontrados con severidad, pasos para reproducir y evidencias.

## Resultados Resumidos
| Métrica                  | Cantidad      |
|--------------------------|---------------|
| Total casos de prueba    | 50            |
| Casos aprobados (Pass)   | XX            |
| Casos fallidos (Fail)    | XX            |
| Bugs reportados          | XX (X críticos, X altos, X medios, X bajos) |
| Cobertura principal      | Búsqueda, filtros, carrito, checkout, responsividad |

> Los valores de Pass/Fail y bugs los completarás una vez que ejecutes todos los casos.

## Herramientas Utilizadas
- Google Chrome / Firefox + DevTools
- Aplicación oficial Mercado Libre (Play Store / App Store)
- Google Sheets (gestión de casos de prueba)
- Capturas de pantalla y grabación nativa del dispositivo
- Imgur / GitHub para alojar evidencias

## Estructura del Repositorio

O, si preferís una versión más simple y limpia (tabla), también queda muy profesional:

## Estructura del Repositorio

| Carpeta/Archivo                  | Descripción                                      |
|----------------------------------|--------------------------------------------------|
| `docs/`                          | Test Plan completo en Markdown                   |
| `evidencias/`                    | Screenshots y videos de ejecución de casos       |
| `bugs/`                          | Reporte de bugs encontrados (BUGS.md + imágenes) |
| `Test-Cases-MercadoLibre.xlsx`   | Hoja de casos de prueba descargable (opcional)    |
| `README.md`                      | Documentación principal del proyecto             |
| `LICENSE`                        | Licencia del repositorio (MIT recomendada)       |



## ¿Por qué este proyecto?
Este proyecto demuestra:
- Capacidad para diseñar casos de prueba claros y estructurados
- Conocimiento de flujos críticos de e-commerce
- Atención al detalle en diferentes dispositivos y navegadores
- Buena documentación y presentación profesional (clave en QA)

## Próximos pasos (futuras mejoras)
- Automatización de casos críticos con Selenium/WebDriverIO
- Pruebas de regresión visual
- Testing de rendimiento básico (tiempos de carga)

---

**¡Gracias por visitar mi portfolio!**  
Si tenés feedback o querés charlar sobre testing, ¡dejá un comentario o contactame!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Conectar-blue?logo=linkedin)](https://www.linkedin.com/in/javier-nicol%C3%A1s-godoy-8427651b1/)
[![Email](https://img.shields.io/badge/Email-Contactar-red?logo=gmail)](nicolasgodoy231@gmail.com)

---
*Proyecto realizado en diciembre 2025 - Javier Nicolás Godoy*
