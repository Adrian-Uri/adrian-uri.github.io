---
title: Nmap
parent: Redes
has_children: false
nav_order: 1
---
# Nmap 
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}


## Tipos de Escaneo

-sn | ping scan|
-Pn | Escaneo sin Ping, tratando todo como up, guay para hosts windows|

-sT |TCP
-sU |UDP

## Params guays

-O | Operative System |
-sV | Versión de los servicios |
-A | Full agresivo |
-n | Evitar resolución DNS IMPORTANTE POR TIEMPO Y EVITAR SERVIDOR DNS |
-T1(2,3,4,5)| Para el tema de velocidad
-iL | Leer desde fichero

## Scripts
`Nmap --script xxx`

| Auth | ejecuta todos sus scripts disponibles para autenticación |
| Default | ejecuta los scripts básicos por defecto de la herramienta |
| Discovery | recupera información del target o víctima |
| External | script para utilizar recursos externos |
| Intrusive | utiliza scripts que son considerados intrusivos para el target |
| Malware | revisa si hay conexiones abiertas por códigos maliciosos o backdoors (puertas traseras) |
| Safe | ejecuta scripts que no son intrusivos |
| Vuln | descubre las vulnerabilidades más conocidas |
| All | ejecuta absolutamente todos los scripts con extensión NSE disponibles. |
		

## Puertos
`Nmap mira los 1000 mas conocidos por defecto`

-p puerto,puerto2 | Puertos de uno en uno |
-p- | Para todos los puertos |
--top-ports=233 |Top N puertos |
--open | Para solo abiertos|

## Outputs

-oN *filename* | Normal |
-oX *filename* | XML |
-oG *filename* | Grepable |

