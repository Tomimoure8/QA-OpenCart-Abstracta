# 🧪 Caso de prueba – register rechazado

- **ID**: TC-001
- **Título**: Registro con credencial inválida
- **Tipo**: Negativo
- **Precondiciones**: No hay.
- **Pasos**:
  1. Ir a la página de register.
  2. Ingresar todos los campos válidos, excepto el campo "First Name", en el cual se ingresan más de 32 carácteres (por arriba del máximo permitido).
  4. Hacer clic en "continue".
- **Resultado esperado**: Aviso de que el campo "First Name" es incorrecto debido a que supera el limite de caracteres permitido.
- **Resultado real**: Aviso de que al campo "First Name" debe tener entre 1 y 34 caracteres.
- **Estado**: Pasó
- **Evidencia**: ![captura](../evidencias/captura-usuario-incorrecto.png)