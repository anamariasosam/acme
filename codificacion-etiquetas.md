# Gestión de cambios - FASES

---

### 1. Solicitud

Cuando se esté en proceso de desarrollo, el equipo de trabajo o el cliente, realiza la solicitud para ejecutar algún cambio, esto se hace a través de WhatsApp, llamada telefónica, conferencias virtuales, correo electrónico, reuniones presenciales, encuentros de pasillo.

| Tipos de cambios | Encargado de registrarlo |
| :--- | :--- |
| Historia de usuario | Project Manager |
| Criterio de aceptación | Product Owner |
| Estructura en la base de datos | Equipo de SRE o DevOps |
| Cambios en los pasos del deploy de los módulos | Equipo de SRE o DevOps |
| Código | Equipo de desarrollo |

### 2. Registro de Solicitud

La nueva petición quedará registrada en Jira y Confluence, donde se especificará quien solicitó el cambio, quien lo atendió, la fecha y la urgencia con la que el cliente la necesite.

La petición tendrá un rango la cual se puede asignar en Jira:

* Blocker: Este problema bloquea el progreso del desarrollo
* Critical: Este problema puede bloquear el progreso del desarrollo
* Major: Tiene gran probabilidad de afectar el progreso
* Minor: Problema con nivel bajo con un impacto pequeño en el progreso
* Trivial: Problema con nivel muy bajo, con un impacto mínimo o bajo en el progreso

### 3. Evaluación

Una vez se haya generado la solicitud, el jefe de proyecto, en las reuniones SCRUM, junto con su equipo de trabajo, analizan si es conveniente dichos cambios y se procede a su evaluación de dicha petición.

Si la petición está en el rango:

* **Blocker:** se debe realizar en el Sprint actual y tener una reunión de urgencia con las personas implicadas.
* **Critical:** se programará una reunión dirigida por el SM al siguiente día en la daily meeting para acordar e implementar el nuevo cambio.

### 4. Aprobación e implementación

Una vez sea evaluada, si se optó por realizar los cambios pertinentes, el jefe de proyecto informa sobre la aceptación e implementación de los cambios. El equipo de desarrollo procede a realizar los cambios dejando constancia de actualizaciones y cambios por medio de la herramienta Git y actualizando su estado en Jira

Las decisiones se toman en conjunto, contribuyendo todos los miembros del equipo, tal como lo dicen los principios de scrum, pero las aprobaciones las realizan el analista de sistemas, el scrum master y el gerente del proyecto.

