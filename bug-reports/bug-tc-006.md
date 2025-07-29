# 🐞 Bug Report – Error de validación de datos en Last Name al registrarme

- **ID**: BUG-TC-006
- **Título**: Registro con "Last Name" inválido (longitud de 1 caracter)
- **Fecha**: 2025-07-28
- **Criticidad**: Baja
- **Tipo de defecto**: Validación de datos
- **Pasos para reproducir**:
  1. Ingresar a la página de registro.
  2. Completar todos los campos con datos válidos y el campo "Last Name" con una sola letra/caracter (ej: "M").
  3. Aceptar los términos y condiciones.
  4. Hacer clic en el botón "continue".
- **Resultado esperado**: El sistema debería mostrar un mensaje indicando que al campo "Last Name" está incompleto.
- **Resultado real**: El sistema te redirije a la sección account donde indica que el registro fue un éxito.
- **Evidencia**: ![captura](../evidencias/captura-apellido-invalido.png.png)