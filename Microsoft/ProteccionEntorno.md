# _Protege tu entorno_
#
---
### Monitorear y perfilar
- Monitorear y analizar las actividades de los usuarios y la información a través de su red, como los permisos y la pertenencia a grupos.
- Crear una línea de base de comportamiento para cada usuario.
- Identifica las anomalías mediante inteligencia adaptable incorporada, dándole una visión de las actividades y eventos sospechosos, revelando las amenazas avanzadas que enfrenta su organización.

### Proteger y reducir ataques
- Reducir la superficie expuesta a ataques de su organización, haciendo más difícil comprometer las credenciales de los usuarios y avanzar en un ataque.
- Comprender de forma rápida cómo un atacante puede moverse dentro de su organización para comprometer cuentas sensibles y asi prevenir estos riesgos por adelantado.
- Identificar a los usuarios y dispositivos que se autentican utilizando contraseñas de texto claro y proporcionan información adicional para mejorar la postura y las directivas de seguridad de su organización.

### Identificar actividades sospechosas
#
> Por lo general, los ataques son iniciados contra cualquier entidad accesible, como un usuario con pocos privilegios, y luego se desplazan rápidamente lateralmente hasta que el atacante obtiene acceso a activos valiosos, como cuentas confidenciales, administradores de dominios y datos altamente confidenciales.
#

---
---
**Problema:**
La **información crítica sobre el entorno del dominio** ayuda a los atacantes a mapear la estructura del dominio, así como a identificar cuentas privilegiadas para su uso posterior. 

**Deteccion:**
Esta detección se desencadena en función de los ordenadores que realizan consultas de enumeración de **LDAP** sospechosas o consultas dirigidas a grupos confidenciales.
---
---
**Problema:**
Los **ataques de fuerza bruta** son una forma común de comprometer las credenciales. Ocurre cuando un atacante intenta autenticarse con múltiples contraseñas en diferentes cuentas hasta encontrar una contraseña correcta o utilizando una difusión de contraseñas a gran escala que funciona por lo menos para una cuenta. Una vez encontrado, el atacante se conecta usando la cuenta autentificada.

**Deteccion:**
Detectar este ataque cuando advierte múltiples fallos de autenticación que se producen usando **Kerberos, NTLM, o el uso de un difusor de contraseñas.**
---
---
**Problema:**
Cuando los atacantes intentan moverse lateralmente a través de su entorno, usando el **pass-the-ticket**, esta es una técnica de movimiento lateral en la que los atacantes roban un billete de Kerberos de un ordenador y lo utilizan para acceder a otro ordenador reutilizando el billete robado.

**Deteccion:**
En esta detección, un billete de **Kerberos** está siendo usado en dos (o más) ordenadores diferentes.
---
---
**Problema:**
Cuando los atacantes quieren establecer una dominación de los dominios. Un método, por ejemplo, es el ataque **DCShadow**. Este ataque está diseñado para cambiar los objetos del directorio usando una replicación malintencionada. Este ataque puede realizarse desde cualquier máquina mediante la creación de un controlador de dominio no autorizado utilizando un proceso de replicación. 
**Deteccion:**
Disparar una alerta cuando una máquina en la red trata de registrarse como controlador de dominio no autorizado.

---
---