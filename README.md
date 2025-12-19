# Mercado Libre - Proyecto de Testing Manual (Web & Mobile)

<img src="evidencias/banner.png" alt="Mercado Libre Banner" style="width: 35%;">

**Proyecto de QA Manual** realizado como parte de mi portfolio profesional.  
Se probaron las funcionalidades principales de **Mercado Libre** en entorno web (PC) y aplicación móvil (Android), cubriendo flujo de compra completo (sin realizar pagos reales).

## Objetivo
Validar funcionalmente la experiencia de usuario en Mercado Libre, identificando posibles defectos en:
- Navegación y búsqueda
- Filtros y ordenamiento
- Detalle de producto
- Carrito y checkout
- Compatibilidad y responsividad

## Alcance del Testing
- **Plataformas**: Web (Chrome, Edge) y App Mobile (Android)
- **Tipos de prueba**: Funcional, usabilidad, compatibilidad, exploratorio
- **Casos ejecutados**: 50 casos de prueba manuales
- **Out of scope**: Pagos reales, publicaciones, área de vendedor, notificaciones push

## Entornos Probados
| Plataforma   | Dispositivo / Navegador                  | Resolución / SO              |
|--------------|------------------------------------------|------------------------------|
| Web          | Google Chrome (última versión)           | 1280 X 800 - Windows 11      |
| Web          | Microsoft Edge                           | 1280 X 800 - Windows 11      |
| Mobile (App) | Samsung Galaxy / Emulador Android        | Android 10                   |
| Web Mobile   | Chrome DevTools (vista responsive)       | 375px (mobile view)          |

## Documentación del Proyecto

- **[Test Plan completo](docs/Test-Plan-MercadoLibre.md)** → Objetivos, alcance, criterios de aceptación y estrategia.
- **[Hoja de Casos de Prueba (Excel)](https://docs.google.com/spreadsheets/d/[ACA_PONES_EL_LINK_DE_TU_HOJA])**  
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
- Google Chrome / Edge + DevTools
- Aplicación oficial Mercado Libre (Play Store)
- Google Sheets (gestión de casos de prueba)
- Capturas de pantalla y grabación nativa del dispositivo
- GitHub para alojar evidencias

## Estructura del Repositorio

O, si preferís una versión más simple y limpia (tabla), también queda muy profesional:

## Estructura del Repositorio

| Carpeta/Archivo                  | Descripción                                      |
|----------------------------------|--------------------------------------------------|
| `docs/`                          | Test Plan completo en Markdown                   |
| `evidencias/`                    | Screenshots y videos de ejecución de casos       |
| `bugs/`                          | Reporte de bugs encontrados (BUGS.md + imágenes) |
| `Test-Cases-MercadoLibre.xlsx`   | Hoja de casos de prueba                          |
| `README.md`                      | Documentación principal del proyecto             |
| `LICENSE`                        | Licencia del repositorio                         |



## ¿Por qué este proyecto?
Este proyecto demuestra:
- Capacidad para diseñar casos de prueba claros y estructurados
- Conocimiento de flujos críticos de e-commerce
- Atención al detalle en diferentes dispositivos y navegadores
- Buena documentación y presentación profesional (clave en QA)

## Próximos pasos (futuras mejoras)
- Automatización de casos críticos con Selenium
- Pruebas de regresión visual
- Testing de rendimiento básico (tiempos de carga)

---

**¡Gracias por visitar mi portfolio!**  
Si tenés feedback o querés charlar sobre testing, ¡dejá un comentario o contactame!

<div align="left" style="margin: 40px 0;">

<div style="margin: 20px 0;">
  <a href="https://www.linkedin.com/in/javier-nicolás-godoy-8427651b1/">
    <img src="https://content.linkedin.com/content/dam/me/business/en-us/amp/brand-site/v2/bg/LI-Bug.svg.original.svg" alt="LinkedIn" height="50" style="vertical-align: middle;">
  </a>
</div>

<div style="margin: 20px 0;">
  <a href="mailto:nicolasgodoy231@gmail.com">
    <img src="https://cdn.worldvectorlogo.com/logos/official-gmail-icon-2020-.svg" alt="Email" height="50" style="vertical-align: middle;">
  </a>
  <span style="margin-left: 15px; font-size: 16px; vertical-align: middle; display: inline-block;">nicolasgodoy231@gmail.com</span>
</div>

<div style="margin: 20px 0;">
  <a href="https://nicolasgodoy231.github.io/Portfolio-QA-Javier-Nicolas-Godoy/">
    <img src="https://static.vecteezy.com/system/resources/thumbnails/013/362/600/small/brown-office-bag-free-png.png" alt="Portfolio QA" height="40" style="vertical-align: middle;">
  </a>
  <span style="margin-left: 15px; font-size: 16px; vertical-align: middle; display: inline-block;">Portfolio QA</span>
</div>

</div>

---
*Proyecto realizado en diciembre 2025 - Javier Nicolás Godoy*
