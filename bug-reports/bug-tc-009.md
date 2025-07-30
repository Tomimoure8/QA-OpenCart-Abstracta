# 🐞 Bug Report – Error de validación de datos en Telephone al registrarme

- **ID**: BUG-TC-009
- **Título**: Registro con "Telephone" inválido (longitud de 22 caracteres).
- **Fecha**: 2025-07-29
- **Criticidad**: Media
- **Tipo de defecto**: Validación de datos
- **Pasos para reproducir**:
  1. Ingresar a la página de registro.
  2. Completar todos los campos con datos válidos y el campo "Telephone" con 22 números (ej: "0112250908911225090707").
  3. Aceptar los términos y condiciones.
  4. Hacer clic en el botón "continue".
- **Resultado esperado**: El sistema debería mostrar un mensaje de error indicando que el número es demasiado largo o inválido.
- **Resultado real**: El sistema te redirije a la sección account donde indica que el registro fue un éxito.
- **Evidencia**: ![captura](../evidencias/captura-registro-exitoso.png)