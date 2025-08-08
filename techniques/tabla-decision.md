# 🧠 Tabla de Decisión 

## Objetivo:
Verificar distintos escenarios de acceso con combinaciones de usuario y contraseña válidos o inválidos.

- **Fecha**: 2025-08-6
## Condiciones de entrada:

| Condición                 | Combinación 1      | Combinación 2      | Combinación 3     |
|---------------------------|--------------------|--------------------|-------------------|
| First name con simbolo    | Sí                 | No                 | No                |
| Newsleter                 | no                 | No                 | Si                |
| Politica de privacidad    | si                 | No                 | No                |
| **Resultado esperado**    | registro rechazado | registro rechazado | registro rechazado|

```bash
# git pull origin master --rebase
```
## Casos de prueba basados:
- TC-011: registro invalido con @.
- TC-012: Registro rechazado por no aceptar la politica de privacidad.
- TC-013: Registro rechazado por no aceptar la política de privacidad con newsletter suscrito.
