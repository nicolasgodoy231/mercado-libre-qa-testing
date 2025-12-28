# Reporte de Incidentes Fallidos - Proyecto BarbeLink

### Incidente ML33: Error en validación de nombre
* **Descripción:** El sistema permite registrar nombres con números.
* **Resultado Esperado:** Bloqueo y mensaje de error según el criterio de aceptación.
* **Resultado Obtenido:** Registro exitoso con caracteres numéricos.

### Incidente ML35: Fallo en formato de teléfono
* **Descripción:** El sistema acepta caracteres no numéricos en el campo de celular.
* **Resultado Esperado:** Permitir únicamente caracteres numéricos.
* **Resultado Obtenido:** Registro procesado con letras en el número telefónico.

### Incidente ML37: Error en visualización de contraseña
* **Descripción:** El botón de "ojito" no cambia el estado del texto de la clave.
* **Resultado Esperado:** Mostrar u ocultar la contraseña al presionar el ícono.
* **Resultado Obtenido:** La contraseña permanece oculta en todo momento.

### Incidente ML42: Fallo en redirección automática
* **Descripción:** El usuario no es enviado al inicio tras completar el registro.
* **Resultado Esperado:** Redirección automática al Home.
* **Resultado Obtenido:** El usuario permanece en la pantalla de registro con los campos vacíos.
