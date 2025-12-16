# 📝 Test Plan: Pruebas Funcionales en Mercado Libre (Web y Mobile)

## 1. Objetivo del Testing

Verificar que las funcionalidades principales de **Mercado Libre** funcionen correctamente en dispositivos de escritorio (PC) y móviles. Esto garantiza una experiencia de usuario consistente, segura y sin errores críticos.

## 2. Alcance (Scope)

### ✅ In Scope (Dentro del Alcance)

* Registro / Inicio de sesión.
* Búsqueda de productos.
* Navegación de categorías.
* Detalle de producto.
* Agregar al carrito.
* Proceso de **Checkout** (hasta antes del pago real).
* Filtros y ordenamiento.

### ❌ Out of Scope (Fuera del Alcance)

* Proceso de pago real.
* Mercado Pago completo.
* Envíos.
* Publicaciones de vendedor.
* Notificaciones *push*.
* Funcionalidades administrativas.

## 3. Entornos de Prueba

### 🖥️ Web (PC)

| Tipo | Especificación |
| :--- | :--- |
| **Navegadores** | Chrome (última versión), Firefox, Edge. |
| **Resolución** | 1920x1080 (desktop). |
| **SO** | Windows 11. |

### 📱 Mobile

| Tipo | Especificación |
| :--- | :--- |
| **Dispositivos** | Android (Samsung Galaxy S23 o emulador Pixel 6), iOS (iPhone 14 o simulador). |
| **App** | Mercado Libre oficial (versión más reciente desde Play Store/App Store). |
| **Navegador móvil** | Chrome y Safari (para comparar *responsive web*). |
| **Orientación** | Portrait y Landscape. |

## 4. Tipos de Pruebas

* Funcionales
* Usabilidad
* Compatibilidad (navegadores y dispositivos)
* Exploratorio
* Regresión (después de encontrar y corregir *bugs*)

## 5. Áreas/Funcionalidades a Probar

* Inicio de sesión / Registro
* Búsqueda de productos
* Navegación por categorías
* Detalle de producto
* Carrito de compras
* Filtros y ordenamiento
* Checkout (hasta resumen de compra)
* Responsividad (solo web)

## 6. Casos de Prueba Principales

Los casos de prueba detallados se encuentran en una **Hoja de Excel** separada con las siguientes columnas:

* `ID`
* `Descripción`
* `Pasos`
* `Resultado Esperado`
* `Resultado Obtenido`
* `Dispositivo`
* `Navegador`

## 7. Criterios de Aceptación

Un criterio de aceptación debe cumplirse para que la prueba se considere exitosa:

* Todas las funcionalidades críticas funcionan **sin errores 500** o *crashes*.
* No hay **regresiones** en funcionalidades ya probadas.
* Tiempo de carga de páginas/app **< 5 segundos** (en conexión promedio).
* Mensajes de error **claros y en español**.

## 8. Herramientas Utilizadas

* Navegadores: Chrome, Edge, Firefox, Safari.
* **DevTools** (Inspector para verificar *responsive*).
* Capturas de pantalla / Grabación de pantalla (función de grabación de Amd Software: Adrenaline Edition).
* Excel/Google Sheets (para casos de prueba y *bug tracking*).
* Emuladores: (A definir)

## 9. Bugs Reportados (Ejemplo para Portfolio)

Los *bugs* se registrarán con el siguiente esquema de información:

| Campo | Descripción |
| :--- | :--- |
| **Bug ID** | Identificador único del error. |
| **Severidad** | Crítico, Alto, Medio, Bajo. |
| **Descripción** | Resumen del problema. |
| **Pasos para reproducir** | Guía detallada para replicar el error. |
| **Evidencia** | *Screenshot* o video. |
| **Plataforma afectada** | Web / Mobile (iOS, Android). |

### Ejemplo Real

> **Bug-001** | Severidad: **Alto** | En mobile Android, al rotar a *landscape* en detalle de producto, las imágenes no se ajustan y quedan cortadas.

## 10. Conclusiones

* La mayoría de funcionalidades funcionan correctamente en ambas plataformas.
* Se detectaron **X bugs** (detallar cuántos críticos, altos, etc.).
* Recomendaciones: Mejorar *responsive* en ciertos componentes *mobile*, etc.
