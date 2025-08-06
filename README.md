# 🧪 QA OpenCart Abstracto – Practica de Testing Funcional

> ### 📈 Actualizo este repositorio constantemente mientras practico técnicas y herramientas de testing semana a semana

Testing funcional documentado profesionalmente usando:
- ✅ Jira (para reporte de bugs)
- ✅ Xray (para gestión de test cases)
- ✅ Markdown y GitHub (para portafolio público)

---

## 📂 Estructura del repositorio

- `/test-cases`: Casos de prueba (positivos y negativos)
- `/bug-reports`: Reportes de bugs reales (con enlaces a Jira)
- `/docs`: Checklist QA, reporte funcional y documentación extra
- `/evidencias`: Capturas de herramientas utilizadas

---

## 📋 Casos de prueba

| ID     | Título                                   | Tipo      | Resultado |
|--------|--------------------------------          |-----------|-----------|
| TC-001 | Registro con credencial inválida                            | Negativo  | ✅ Pasó   |
| TC-002 | Registro con nombre inválido             | Negativo  | ❌ Falló  |
| TC-003 | Registro con email inválido (sin @)      | Negativo  | ✅ Pasó   |
| TC-004 | Registro con email inválido (longitud menor a la exigida)      | Negativo  | ✅ Pasó   |
| TC-005 | Registro exitoso                            | Positivo  | ✅ Pasó   |
| TC-006 | Registro con "Last Name" inválido (longitud de 1 caracter)             | Negativo  | ❌ Falló  |
| TC-007 | Registro exitoso con 32 caracteres válidos en el campo "Last Name"             | Positivo  | ✅ Pasó  |
| TC-008 | Registro con campo "Last Name" inválido (números en vez de letras)             | Negativo  | ❌ Falló  |

Ver más en la carpeta [`/test-cases`](./test-cases)

---

## 🐞 Reportes de bugs

Todos los bugs fueron detectados durante la ejecución de pruebas.

- [BUG-tc-900 – Advertencia de conexión insegura al acceder al sitio](./bug-reports/bug-tc-900.md)
- [BUG-tc-002 – Error de validación de datos al registrarme](./bug-reports/bug-tc-002.md)
- [BUG-tc-006 – Registro con "Last Name" inválido (longitud de 1 caracter)](./bug-reports/bug-tc-006.md)
- [BUG-tc-008 – Registro con "Last Name" inválido (caracteres númericos en vez de letras)](./bug-reports/bug-tc-008.md)

Ver todos en [`/bug-reports`](./bug-reports)

---

## 🧠 Técnicas de caja negra aplicadas

- ✅ Tabla de decisión
- ✅ Partición de equivalencia 
- ✅ Análisis de valores frontera

Ver más en la carpeta [`/techniques`](./techniques)

## ✅ Checklist QA

Ver checklist completo en (aún en preparación).

---

## 🖼️ Evidencias visuales

Capturas de Xray y Jira incluidas en la carpeta [`/evidencias`](./evidencias)

---
