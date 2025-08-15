# 🧠 Tabla de Decisión 

## Objetivo:
Verificar distintos escenarios de acceso con combinaciones de usuario y contraseña válidos o inválidos.

- **Fecha**: 2025-08-6
## Condiciones de entrada:

| Condición                 | Combinación 1      | Combinación 2      | Combinación 3     | Combinación 4      | Combinación 5      | Combinación 6      | Combinación 7      | Combinación 8      |
|---------------------------|--------------------|--------------------|-------------------|--------------------|--------------------|--------------------|--------------------|--------------------|
| First name con símbolo    | Sí                 | No                 | No                | Sí                 | Sí                 | No                 | Sí                 | No                 |
| Newsletter                | No                 | No                 | Sí                | Sí                 | No                 | Sí                 | Sí                 | No                 |
| Política de privacidad    | Sí                 | No                 | No                | Sí                 | No                 | Sí                 | No                 | Sí                 |
| **Resultado esperado**    | registro rechazado | registro rechazado | registro rechazado| registro rechazado | registro rechazado | registro aceptado  | registro rechazado | registro aceptado  |

```bash
# git pull origin master --rebase
```
## Casos de prueba basados:
- TC-011: registro invalido con @.
- TC-012: Registro rechazado por no aceptar la politica de privacidad.
- TC-013: Registro rechazado por no aceptar la política de privacidad con newsletter suscrito.


- **Fecha**: 2025-08-15

| Condición               | Combinación 1 | Combinación 2 | Combinación 3 | Combinación 4 |
|-------------------------|---------------|---------------|---------------|---------------|
|Tipo de producto         |               |               |               |               |
|Código de cupón          |               |               |               |               |
|Estima. envío e impuestos|               |               |               |
|Certificado de regalo    |               |               |               |               |
|Resultado esperado       |               |               |               |               |

## Casos de prueba basados: