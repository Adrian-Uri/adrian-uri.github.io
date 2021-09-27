---
title: Nmap
parent: Redes
has_children: false
nav_order: 1
---

# Nmap 

## Tipos de Scan
|Nmap | -sn ip | ip ping scan|
|     | -Pn ip | ip Comprobar vivo sin Ping, tratando todo como up, guay para hosts windows|

|Nmap | -sT |TCP
|     | -sU |UDP

##Params guays
|Nmap | -O | Operative System |
|     | -sV | Versión de los servicios |
|     | -A | Full agresivo |
|     | -n | Evitar resolución DNS IMPORTANTE POR TIEMPO Y EVITAR SERVIDOR DNS |

##Scripts
Nmap --script xxx
		| Auth | ejecuta todos sus scripts disponibles para autenticación |
		| Default | ejecuta los scripts básicos por defecto de la herramienta |
		| Discovery | recupera información del target o víctima |
		| External | script para utilizar recursos externos |
		| Intrusive | utiliza scripts que son considerados intrusivos para el target |
		| Malware | revisa si hay conexiones abiertas por códigos maliciosos o backdoors (puertas traseras) |
		| Safe | ejecuta scripts que no son intrusivos |
 		| Vuln | descubre las vulnerabilidades más conocidas |
		| All | ejecuta absolutamente todos los scripts con extensión NSE disponibles. |
		
'Nmap mira los 1000 mas conocidos por defecto'

Nmap -p puerto,puerto2 ip
			  -
	        -p- para todos los puertos
-T1(2,3,4,5) para el tema de velocidad
--top-ports=233 Top puertos
--open para solo abiertos

Mirar los Outputs






