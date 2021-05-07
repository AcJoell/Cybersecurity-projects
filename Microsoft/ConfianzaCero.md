### Introducción a la confianza cero

> Hoy en día, las organizaciones necesitan un nuevo modelo de seguridad que se adapte de manera más eficaz a la complejidad del entorno moderno, adopte la plantilla móvil y proteja a las personas, dispositivos, aplicaciones y datos dondequiera que estén ubicados. Este es el núcleo de la confianza cero.

El **nuevo perímetro** no se define por la ubicación/es física/s de la organización, sino que ahora se amplía a cada punto de acceso que hospeda, almacena o accede a los recursos y servicios corporativos. Las interacciones con servicios y recursos corporativos ahora suelen eludir modelos de seguridad locales basados en perímetro que dependen de firewalls de red y VPN.

El modelo de **confianza cero** asume la vulneración y comprueba cada solicitud como si se originara en una red no controlada. Independientemente de dónde se origina la solicitud o de los recursos a los que accede, la **confianza cero** nos enseña a _"desconfiar y comprobar siempre"_.

En un modelo de **confianza cero**, cada solicitud de acceso se autentica, se autoriza según las restricciones de las directivas y se inspecciona en busca de anomalías antes de conceder el acceso. **Se evalúa todo**, desde la identidad del usuario hasta el entorno de hospedaje de la aplicación para evitar la vulneración. Se aplican los principios de acceso de microsegmentación y privilegios mínimos para minimizar el movimiento lateral.

#
---
---

Un enfoque de **confianza cero** se lleva a cabo con la implementación de controles y tecnologías de **confianza cero** en seis elementos fundamentales:
- Identidades
- Dispositivos
- Aplicaciones
- Datos
- Infraestructura
- Redes

> Cada uno de estos seis elementos fundamentales es un origen de señal, un plano de control para el cumplimiento y un recurso crítico que se debe defender. Esto hace que sean áreas importantes en las que centrar la inversión

#
![](https://docs.microsoft.com/es-es/learn/m365/m365-identity-zero-trust/media/security-policy-enforcement.png)

1 . **Identidades**
Tanto si representan personas, servicios o dispositivos IOT, debe definir el plano de control de confianza cero por identidades. Cuando una identidad intenta acceder a un recurso, debemos comprobarla con una autenticación sólida, asegurarnos de que el acceso sea compatible y típico para esa identidad, y seguir los principios de acceso con privilegios mínimos.

2 . **Dispositivos**
Cuando a una identidad se le ha concedido acceso a un recurso, los datos pueden fluir hacia una gran variedad de dispositivos distintos (desde dispositivos IoT hasta smartphones, BYOD a dispositivos admin, etc). Esta diversidad crea un área de superficie expuesta a ataques masivos, lo que requiere supervisar y exigir el estado del dispositivo y el cumplimiento para un acceso seguro.

3 . **Aplicaciones**
Las aplicaciones y API proporcionan la interfaz por la que se consumen los datos. Pueden ser aplicaciones heredadas locales, movidas a las cargas de trabajo en la nube o SaaS modernas. Se deben aplicar controles y tecnologías para detectar TI en la sombra, asegurar los permisos de la aplicación adecuados, dar acceso en base a un análisis en tiempo real, supervisar el comportamiento anómalo, controlar las acciones del usuario y validar las opciones de configuración seguras.

4 . **Datos**
Por último, los equipos de seguridad se centran en la protección de datos. Siempre que sea posible, los datos deben permanecer seguros, incluso cuando dejan los dispositivos, las aplicaciones, la infraestructura y las redes que la organización controla. Los datos se deben clasificar, etiquetar y cifrar, y el acceso se debe restringir basándose en esos atributos.

5 . **Infraestructura**
La infraestructura (ya sean servidores locales, máquinas virtuales basadas en la nube, contenedores o microservicios) representa un vector de amenaza crítico. Evalúe la versión, la configuración y el acceso JIT para reforzar la defensa, use la telemetría para detectar ataques y anomalías, y bloquee y marque automáticamente el comportamiento peligroso y lleve a cabo acciones de protección.

6 . **Redes**
Se accede a todos los datos a través de la infraestructura de la red. Los controles de red pueden ofrecer controles "en canalización" críticos para mejorar la visibilidad y ayudar a impedir que los atacantes se muevan lateralmente a través de la red. Las redes se deben segmentar (incluyendo una microsegmentación más profunda en la red), y se deben emplear el cifrado de extremo a extremo, la supervisión y el análisis.