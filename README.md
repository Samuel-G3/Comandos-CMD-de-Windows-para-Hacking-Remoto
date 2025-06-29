# Comandos CMD de Windows para Hacking Remoto

**Autor:** Samuel García

Este proyecto es un tutorial práctico para aprender a usar comandos CMD de Windows en un contexto de hacking ético. Te guía para establecer una reverse shell desde Windows 10 hacia Kali Linux y ejecutar comandos para obtener información del sistema.

## Requisitos

- Máquina atacante: Kali Linux con Netcat preinstalado.  
- Máquina objetivo: Windows 10 con PowerShell y permisos para ejecutar scripts.  
- Ambas máquinas deben estar en la misma red con comunicación activa.

## Instrucciones

1. Verificar la comunicación entre las máquinas con `ping`.  
2. En Kali, iniciar listener en puerto 4444 con `nc -lvnp 4444`.  
3. En Windows, ejecutar script PowerShell para establecer la reverse shell (reemplazando IP de Kali).  
4. Desde Kali, enviar comandos CMD para interactuar con la máquina Windows (ej. `dir`, `systeminfo`, `ipconfig`).  
5. Con privilegios, ejecutar comandos administrativos (apagar, reiniciar, agregar usuarios).  
6. Para cerrar sesión, enviar `exit` desde Kali.

## Comandos útiles

- `dir`  
- `systeminfo`  
- `ipconfig`  
- `tasklist`  
- `hostname`  
- `net user`  
- `netstat -an`  
- `mkdir <ruta>`  
- `shutdown /s /t 0`  
- `net user <usuario> <contraseña> /add`  

## Advertencias

Practica sólo en entornos controlados y con autorización. Este tutorial es para fines educativos y éticos.

---

Este proyecto está abierto a colaboraciones y mejoras.

