# _Introducción a las etiquetas de confidencialidad_
#
---
Las personas de su organización colaboran con otros usuarios tanto dentro como fuera de la organización. Esto quiere decir que el contenido ya no permanece detrás de un firewall sino que viaja a todas partes, a través de dispositivos, aplicaciones y servicios. Y cuando se desplace, quiere que lo haga de forma que se ajuste a las directivas empresariales y de cumplimiento de su organización.

#
---
### Identificar y clasificar datos confidenciales

![](https://docs.microsoft.com/es-es/learn/m365/m365-security-sensitivity-labels/media/persistent-labels.png)

Las etiquetas de confidencialidad son etiquetas de metadatos que tienen las características siguientes.

- **Personalizable.** Puede crear categorías para distintos niveles de contenido confidencial, como Personal, Público, General, Confidencial y Extremadamente confidencial.
- **Texto no cifrado.** Dado que la etiqueta está en texto no cifrado, las aplicaciones y servicios de terceros pueden aplicar acciones de protección al contenido etiquetado.
- **Persistente.** Después de aplicarla al contenido, la etiqueta de confidencialidad persiste en los metadatos de ese correo electrónico o documento.

Con las etiquetas de confidencialidad, se puede:

- Aplicar la configuración de protección como el cifrado o marcas de agua en contenido etiquetado.
- Proteger el contenido de las aplicaciones de Office en distintos dispositivos y plataformas.
- Evitar que el contenido confidencial de los dispositivos que ejecutan Windows abandonen su organización.
- Proteger el contenido en los servicios y aplicaciones de terceros.
- Ampliar las etiquetas a los servicios y aplicaciones de terceros.
- Clasificar contenido sin usar configuración de protección.

#
---
### Etiquetas de clasificación

1 . Establecer la **taxonomía** para definir niveles de contenido confidencial. Debe utilizar nombres o términos comunes que tengan sentido para sus usuarios. Por ejemplo, puede usar o modificar estas etiquetas predeterminadas:

- Personal
- Público
- General
- Confidencial
- Extremadamente confidencial

2 . Defina la función de cada etiqueta. Configure los ajustes de protección que desea asociar a cada etiqueta.

Por ejemplo, el contenido de **confidencialidad** más baja **(etiqueta "General")** puede tener un encabezado o pie de página aplicado. El contenido de mayor **confidencialidad (etiqueta "Confidencial")** puede tener cifrado y trabajo en curso (WIP).

3 . Definir quién puede ver las **etiquetas**.

Una vez que defina las **etiquetas** de su organización, las publicará en una directiva de **etiquetas** que controla qué usuarios y grupos ven las **etiquetas**. Una sola **etiqueta** es reutilizable: la define una vez y después puede incluirla en varias directivas de **etiquetas** asignadas a diferentes usuarios.

#
---
### Configuración de protección

> La protección de datos puede continuar de varias maneras en distintas situaciones. Aunque algunas personas piensan que la protección de datos se limita al cifrado, puede ser mucho más.

La protección puede controlar los derechos de los usuarios que pueden acceder a los datos y lo que pueden hacer con ellos. Además, puede configurar derechos y restricciones de uso, como los siguientes.

- Solo los usuarios de su organización puedan abrir un correo electrónico o documentos confidenciales de la empresa.
- Solo los usuarios del departamento de marketing puedan editar e imprimir documentos o correos electrónicos de anuncios de promociones, mientras que todos los demás usuarios de su organización solo puedan leer el documento o el correo electrónico.
- Los usuarios no puedan reenviar un correo electrónico o copiar información de un documento que contenga noticias sobre una reorganización interna.
- Después de una fecha especificada, los usuarios no pueden abrir una lista de precios actual que se envía a socios comerciales.

Configuración más comun para configurar los derechos de uso son:

- Visor (ver, responder, responder a todos)
- Revisor (ver, editar, responder, responder a todos y reenviar)
- Coautoría (ver, editar, copiar, imprimir, responder, responder a todos y reenviar)
- Copropietario (todos los derechos)
- Personalizado (derechos que se pueden asignar individualmente):
