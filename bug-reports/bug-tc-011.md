# 🐞 Bug Report – Advertencia de registro con @ en campo "First Name"

- **ID**: BUG-TC-011
- **Título**: Registro con campo "First Name" inválido (uso de simbolo).
- **Fecha**: 2025-08-06
- **Criticidad**: baja
- **Tipo de defecto**: Validación de datos
- **Pasos para reproducir**:
  1. Ingresar a la página de [inicio](https://opencart.abstracta.us/).
  2. Hacer clic en el ícono de usuario del menú de navegación y seleccionar la opción "Register".
  3. Completar todos los campos con datos válidos, excepto el campo "First Name", en el cual se ingresa un nombre con el @ (ej: "tom@s").
  4. Aceptar los términos y condiciones.
  5. Hacer clic en el botón "Continue".
- **Resultado esperado**: El sistema debería mostrar un mensaje de validación indicando que el campo "First Name" no permite símbolos y debe contener solo letras.
- **Resultado real**: El sistema te redirije a la sección account donde indica que el registro fue un éxito.
- **Evidencia**: ![captura](../evidencias/captura-registro-exitoso.png)