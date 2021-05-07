# _Introducción a la protección puntos de conexión Win10_
#
---
### Bloquear ataques con reducción de superficie de ataque

Puede reducir la superficie expuesta a ataques (ASR) de Windows 10.
Ayudando a evitar las acciones y aplicaciones que suelen aprovechar las vulnerabilidades del malware para infectar máquinas. Estas reglas controlan cuándo y cómo se pueden ejecutar los archivos ejecutables. 
> Por ejemplo:
> 1 . puede impedir que JavaScript o VBScript inicien un archivo ejecutable descargado
> 2 . bloqueen llamadas API Win32 o procesos que se ejecuten desde unidades USB.

#
---

La tarjeta Reglas de reducción de la superficie ofrece información general sobre la implementación de reglas en los dispositivos y la cantidad de estos. Modos de implementación:

- **Modo de bloqueo:** dispositivos con al menos una regla configurada para bloquear actividad detectada
- **Modo de auditoría:** dispositivos sin reglas establecidas para bloquear la actividad detectada, con al menos una regla definida para auditar la actividad detectada
- **Desactivado:** dispositivos con todas las reglas de ASR desactivadas