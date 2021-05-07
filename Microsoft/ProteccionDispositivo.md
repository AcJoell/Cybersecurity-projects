### Protección de los dispositivos
Las **estaciones de trabajo de acceso con privilegios (PAWs)** proporcionan un sistema operativo dedicado, que está protegido frente a los ataques de **Internet** y los vectores de amenazas. Ofrece una protección muy robusta frente a:
- Vulneraciones de suplantación de identidad
- Vulneraciones de aplicaciones
- VUlneraciones de sistema operativo
- Ataques de suplantación
- Robo de credenciales
- Registro de pulsaciones de teclas
- El pass-the-hash y el pass-the-ticket.

![](https://docs.microsoft.com/es-es/learn/m365/m365-identity-secure-administrators/media/paw.png)

> Las **PAWs** son estaciones de trabajo reforzadas y bloqueadas, que están diseñadas para ofrecer altas garantías de **seguridad** para las tareas y cuentas **confidenciales**.

1. Las **PAWs** se recomiendan para administrar sistemas de identidades, servicios y estructuras privadas en la nube, así como funciones comerciales confidenciales.
2. Para máxima seguridad, las **PAWs** deben ejecutarse siempre en el **sistema operativo** más actual y seguro disponible.

>Aislar la **PAW** del Internet abierto es fundamental para asegurar que no estará comprometida.

Reducen ataques en el entorno y los riesgos que puedan disminuir la efectividad de los controles de PAW con el tiempo:

- **Ataques de Internet.** La mayoría de los ataques se originan de forma directa o indirecta desde fuentes de Internet y usan la red para la filtración, el comando y el control (C2).

- **Riesgo de uso.** Si una **PAW** es demasiado difícil de usar para las tareas diarias, los administradores deberán involucrar y facultar a los usuarios con **PAWs** para mitigar estos problemas de facilidad de uso de forma segura.

- **Riesgos del entorno.** Como otros equipos y cuentas se exponen a los riesgos de forma in/directa, una **PAW** debe estar protegida frente a ataques procedentes de activos comprometidos en el entorno de producción.

- **Manipulación de la cadena de suministro.** Hacer validación de la integridad de todos los medios de instalación y el uso de un proveedor de software y hardware de confianza y buena reputación.

- **Ataques físicos.** Como las **PAWs** pueden ser físicamente móviles y usarse fuera de las instalaciones físicamente seguras, deben protegerse frente a los ataques que aprovechan el acceso físico no autorizado al equipo.


#
---
### Entidad aislada

Asegurar el **acceso con privilegios** es un primer paso crítico para proteger los activos de la empresa en una organización moderna. La seguridad de los activos empresariales en una organización de sistemas de la información **depende de** la integridad de las cuentas con privilegios utilizadas para la administración, el control y el desarrollo. 

![](https://docs.microsoft.com/es-es/learn/m365/m365-identity-secure-administrators/media/attackers.png)

Para ayudar a separar los riesgos de Internet (ataques de suplantación de identidad o phishing, exploración web) de los riesgos de cuentas de acceso con privilegios, cree una cuenta específica para todo el personal con acceso con privilegios. Los administradores **`NO`** deben navegar por la web, revisar su correo electrónico o realizar tareas de productividad con cuentas con muchos privilegios.

# 
---
---
### Privilegios just-in-time
El acceso **Just in time (JIT)** es un modelo en el que los usuarios reciben permisos temporales para realizar tareas con privilegios, lo que impide que usuarios malintencionados o no autorizados tengan acceso una vez expirados los permisos.

> El acceso se concede únicamente cuando lo necesitan los usuarios

### Administración del riesgo
Puede proteger su organización aplicando los principios del **privilegio mínimo y el acceso puntual.**
Al minimizar el número de asignaciones permanentes a usuarios de roles con privilegios y exigir aprobaciones y MFA para la elevación, se **reducen** considerablemente **los riesgos** de seguridad relacionados con el acceso con privilegios.

---
---