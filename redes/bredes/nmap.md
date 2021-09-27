---
title: Nmap
parent: Redes
has_children: false
nav_order: 1
---

# Nmap 

## Tipos de Scan
Nmap -sn ip  PING
Nmap -Pn ip Comprobar vivo sin Ping, guay para hosts windows
Nmap -sP ip Comprobar si vivo en la red



(Nmap mira los 1000 mas conocidos)
Nmap -sT TCP
Nmap -sU udp

Nmap -O Operative System
Nmap -sV Versión de los servicios.
Nmap -A Full agresivo

Nmap --script xxx
		• Auth: ejecuta todos sus scripts disponibles para autenticación
		• Default: ejecuta los scripts básicos por defecto de la herramienta
		• Discovery: recupera información del target o víctima
		• External: script para utilizar recursos externos
		• Intrusive: utiliza scripts que son considerados intrusivos para la víctima o target
		• Malware: revisa si hay conexiones abiertas por códigos maliciosos o backdoors (puertas traseras)
		• Safe: ejecuta scripts que no son intrusivos
		• Vuln: descubre las vulnerabilidades más conocidas
		• All: ejecuta absolutamente todos los scripts con extensión NSE disponibles.
		


Nmap -sT -p puerto,puerto2 ip
			  -
	        -p- para todos los puertos
-n al final evitar resolución DNS IMPORTANTE POR TIEMPO Y EVITAR SERVIDOR DNS
-T1(2,3,4,5) para el tema de velocidad
--top-ports=233 Top puertos
--open para solo abiertos

Mirar los Outputs






