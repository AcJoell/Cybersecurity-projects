# _Introducción a la autenticación de identidades_
#
---
### Modernice sus flujos de automatización
La mayoría de los intentos de inicio de sesión peligrosos provienen de la **autenticación heredada**, debido a que no es compatible con la **autenticación multifactor (MFA)** y puede omitirla en culaquier caso **(MFA)**.

> La mejor forma de proteger la cuenta contra las solicitudes de autenticación malintencionadas realizadas por protocolos heredados es bloquearlos totalmente.

La **autenticación moderna** es un método de administración de identidades que ofrece autenticación y autorización de usuarios más seguras.
Esto permite habilitar las características de inicio de sesión, como:
- La autenticación multifactor **(MFA)**
- La **tarjeta inteligente**
- La **autenticación basada en certificados**.

> **(MFA)**. Proceso en el que se piden a los usuarios otras formas de identificación durante un evento de inicio de sesión. Se podría pedir un código para recibir en el teléfono móvil o un análisis de huella digital.

#
---
### Reducir flujos de autenticación heredada

Para poder bloquear la autenticación heredada, primero tiene que saber si los usuarios tienen aplicaciones que usen la autenticación heredada y cómo afecta esto al directorio global.

#
---
### Explorar e implementar alternativas de contraseña

> Una de cada 250 cuentas corporativas se ve comprometida cada mes.

Sabemos que depender de las contraseñas no es una buena estrategia para la defensa empresarial. A medida que las empresas siguen agregando aplicaciones empresariales a sus carteras, el coste de usar contraseñas no hace más que aumentar. Teniendo en cuenta lo poco eficaces que pueden ser las contraseñas, es sorprendente el número de empresas que siguen sin habilitar la **autenticación multifactor (MFA)** para sus clientes o empleados.

![](https://docs.microsoft.com/es-es/learn/m365/m365-identity-authentication/media/password-multi-factor-authentication.png)

La **autenticación** sin contraseña es una forma de **MFA** que sustituye la contraseña por una alternativa segura, esta requiere de dos o más factores de comprobación para iniciar sesión y está protegido con un par de claves criptográficas.

- El dispositivo crea una **clave pública y privada** cuando se registra.
- La **clave privada** solo se puede desbloquear con un gesto local, como una biometría o un PIN.
- Los usuarios tienen la opción de iniciar sesión directamente mediante el **reconocimiento biométrico** o con un **PIN** que está bloqueado y protegido en el dispositivo.