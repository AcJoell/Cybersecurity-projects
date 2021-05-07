## Administracion de la seguridad

Para poder ejecutar un programa de seguridad de forma satisfactoria y reducir los riesgos en la organización, es esencial identificar, evaluar y solucionar con eficacia las debilidades de los puntos de conexión. La administración de amenazas y vulnerabilidades funciona a modo de infraestructura para reducir la exposición en la organización, fortalecer la superficie de los puntos de conexión y aumentar la resistencia de la organización.

Esta infraestructura permite a las organizaciones detectar vulnerabilidades y errores de configuración en tiempo real por medio de sensores, sin necesidad de agentes ni análisis periódicos. Asigna prioridades a los problemas en función de una serie de factores. Estos factores pueden ser, entre otros, el panorama de amenazas, las detecciones en la organización, la información confidencial que contienen los dispositivos vulnerables y el contexto empresarial.

#
---
## Reducción de la superficie expuesta a ataques

Constituyen la primera línea de defensa de la pila, ya que garantizan que las opciones de seguridad están aplicandose correctamente y que se apliquen técnicas de mitigación de vulnerabilidades.

 - El aislamiento basado en hardware protege y mantiene la integridad del sistema cuando este se inicia y mientras se está ejecutando, y valida la integridad del sistema mediante la atestación local y remota.
 - El control de aplicaciones se aleja del modelo tradicional de confianza en las aplicaciones, donde todas las aplicaciones son consideradas de confianza de forma predeterminada.
 - La protección contra vulnerabilidades aplica técnicas de mitigación en las aplicaciones que usa la organización, tanto individualmente como en toda la organización.
 - Protección de red: Ampliar la protección contra malware e ingeniería social para cubrir la conectividad y el tráfico de red en los dispositivos de la organización.
 - El acceso controlado a carpetas ayuda a proteger los archivos de las carpetas clave del sistema frente a los cambios realizados por aplicaciones malintencionadas y sospechosas, incluido el malware ransomware de cifrado de archivos.
 - La reducción de la superficie expuesta a ataques por medio de reglas inteligentes que detengan los vectores utilizados por algun malware.
 - El firewall de red usa un filtrado de tráfico de red bidireccional basado en host que bloquea el tráfico de red no autorizado que entra o sale del dispositivo local.

#
---
## Amenazas en la red

Usar consultas de búsqueda de amenazas para crear reglas de detección personalizadas. Estas reglas se ejecutan automáticamente para buscar diversos eventos y estados del sistema, como actividades de vulneración sospechosas y equipos mal configurados, y responder a ellos.

![](https://docs.microsoft.com/es-es/learn/m365/m365-security-threat-protect/media/threat-hunting-query.png)

El código anterior se basa en el lenguaje de consulta Kusto. Los operadores válidos son los siguientes:

- where. Filtra una tabla hasta llegar al subconjunto de filas que satisfacen una consulta.
- summarize. Crea una tabla que agrega el contenido de la tabla de entrada.
- join. Combina las filas de dos tablas para formar una nueva tabla mediante la coincidencia de los valores de cada tabla.
- count. Devuelve el número de registros en el conjunto de registros de entrada.
- top Devuelve los primeros N registros ordenados.
- limit. Devuelve hasta el número de filas especificado.
- project. Selecciona las columnas que desee incluir, cambia el nombre o elimina e inserta nuevas columnas calculadas.
- extend. Crea columnas calculadas y las anexa al conjunto de resultados.
- makeset(). Devuelve una matriz dinámica (JSON) del conjunto de valores distintivos.
- find. Busca las filas que coinciden con una consulta en un conjunto de tablas.
#
--- 
---
## INTRODUCCION A MICROSOFT DEFENDER PARA PUNTO DE CONEXION

Es una plataforma concebida para ayudar a las redes empresariales a impedir, detectar e investigar amenazas avanzadas en sus puntos de conexión y actuar ante ellas.

![](https://docs.microsoft.com/es-es/learn/m365/m365-security-threat-protect/media/defender-configuration.png)

Funciones habilitadas: 
 - La administración de amenazas y vulnerabilidades en tiempo real.
 - La reducción de áreas innecesarias evitando que se ejecute algún código peligroso.
 - La protección avanzada usa el aprendizaje automático y un análisis detallado para protegerse frente al malware basado en archivos.
Detección y respuesta de extremos supervisa las técnicas de atacante para detectar y responder a ataques avanzados.
aprovecha la inteligencia artificial para investigar automáticamente alertas y remediar amenazas complejas en minutos.
Los expertos en amenazas de Microsoft proporcionan un conocimiento profundo y una búsqueda proactiva de amenazas al centro de operaciones de seguridad.

[Ejemplos de sus tecnologías](https://www.microsoft.com/es-es/videoplayer/embed/RE4D0Wz?postJsllMsg=true&autoCaptions=es-es)

---
---