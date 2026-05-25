# HR Buddy 

Asistente virtual de Recursos Humanos desarrollado con n8n, Telegram, PostgreSQL e Inteligencia Artificial.

##  Descripción

HR Buddy es un asistente diseñado para automatizar consultas internas de Recursos Humanos de una empresa ficticia llamada **ChocolaTech**.

El sistema autentica automáticamente a los usuarios mediante su Telegram ID y permite consultar únicamente información del empleado autenticado, evitando el acceso a datos de terceros.

---

##  Funcionalidades

- Autenticación automática mediante Telegram ID
- Consultar días de vacaciones disponibles
- Consultar puesto y departamento
- Consultar fecha de ingreso
- Consultar modalidad de trabajo
- Consultar banco de horas
- Respuestas con IA
- Protección de información de otros empleados
- Restricción de acceso a datos sensibles

---

##  Tecnologías utilizadas

- n8n
- Telegram Bot API
- PostgreSQL
- Cohere AI
- SQL
- Memoria contextual

---

## Seguridad

Este proyecto implementa medidas de seguridad para evitar acceso no autorizado:

- Los usuarios son identificados mediante Telegram ID
- No se permite consultar datos de otros empleados
- No se solicitan credenciales manuales
- Las credenciales reales fueron eliminadas del repositorio público

---

##  Estructura del proyecto

```text
HR-Buddy/
├── hr-buddy-flow-public.json
├── README.md
```

##  Nota

Por motivos de seguridad, las credenciales, webhooks y configuraciones sensibles fueron removidas.

Para utilizar este flujo:

1. Importar el archivo JSON en n8n
2. Configurar credenciales propias:
   - Telegram Bot API
   - PostgreSQL
   - Cohere AI
3. Ejecutar el flujo

---

##  Vista del proyecto

Próximamente se agregarán capturas y demostraciones.

---

Desarrollado por Valentin Martinez 
