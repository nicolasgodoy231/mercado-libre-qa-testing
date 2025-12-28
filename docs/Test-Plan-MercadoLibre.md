# Test Plan: Pruebas Funcionales en Mercado Libre (Web y Mobile)

## 1. Objetivo del Testing
Verificar que las funcionalidades principales de Mercado Libre funcionen correctamente en dispositivos de escritorio (PC) y móviles, garantizando una experiencia de usuario consistente, segura y sin errores críticos.

## 2. Alcance (Scope)
* **In Scope:** Registro/inicio de sesión, búsqueda de productos, navegación de categorías, detalle de producto, agregar al carrito, proceso de checkout (hasta antes del pago real), filtros y ordenamiento.

---

## 3. Entornos de Prueba

### 💻 Web (PC)
* **Navegadores:** Chrome (última versión), Edge.
* **Resolución:** 1280x800 (desktop).
* **SO:** Windows 11.

### 📱 Mobile
* **Dispositivos:** Android (Motorola One Fusion).
* **App:** Mercado Libre oficial (versión más reciente desde Play Store).
* **Navegador móvil:** Chrome y Edge (para comparar responsive web).
* **Orientación:** Vertical y Horizontal.

---

## 4. Tipos de Pruebas
* **Funcionales**
* **Usabilidad**
* **Compatibilidad** (navegadores y dispositivos)
* **Exploratorio**
* **Regresión** (después de encontrar bugs)

---

## 5. Áreas / Funcionalidades a Probar
1.  Inicio de sesión / Registro.
2.  Búsqueda de productos.
3.  Navegación por categorías.
4.  Detalle de producto.
5.  Carrito de compras.
6.  Filtros y ordenamiento.
7.  Checkout (hasta resumen de compra).
8.  Responsividad.

---

## 6. Casos de Prueba Principales
Se utiliza una **Hoja de Excel** con las siguientes columnas:
* ID, Descripción, Pasos, Resultado Esperado, Resultado Obtenido, Dispositivo, Navegador.

---

## 7. Criterios de Aceptación
* Todas las funcionalidades críticas funcionan sin errores 500 o crashes.
* No hay regresiones en funcionalidades ya probadas.
* Tiempo de carga de páginas/app < 5 segundos (en conexión promedio).
* Mensajes de error claros y en español.

---

## 8. Herramientas Utilizadas
* **Navegadores:** Chrome, Edge.
* **DevTools:** Para verificar responsive.
* **Capturas / Grabación de pantalla:** AMD Software: Adrenalin Edition.
* **Gestión:** Excel/Google Sheets para casos de prueba.
* **App Mobile:** Screen Recorder.

---

## 9. Incidencias Reportadas (Ejemplo)
Cada reporte incluye: **Incidencia ID, Severidad, Descripción, Pasos para reproducir, Evidencia y Plataforma afectada.**

> **Ejemplo Real:**
> * **Incidencia-01 | Severidad: Alto**
> * **Descripción:** En mobile Android, al rotar la pantalla en detalle de producto, las imágenes no se ajustan y quedan cortadas.

---

## 10. Conclusiones
* La mayoría de funcionalidades funcionan correctamente en ambas plataformas.
* Se detectaron **X** incidencias (detallar cuántos críticos, altos, etc.).
* **Recomendaciones:** Mejorar el diseño responsive en ciertos componentes específicos de la versión mobile.
