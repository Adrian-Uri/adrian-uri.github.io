---
title: SMB
parent: Redes
has_children: false
nav_order: 0
---
# SMB 
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Introducción
SMB -Server Message Block Protocol- es un protocolo de comunicación cliente-servidor utilizado para compartir el acceso a archivos, impresoras, puertos serie y otros recursos en una red.

## Herramientas

### smbclient

Cliente de SMB

``smbclient //[IP]/[SHARE]``

#### Parametros
{: .no_toc }

| -U [name] | to specify the user
| -p [port] | to specify the port |




### enum4linux

Herramienta de Enumeración de SMB

``enum4linux params host``

#### Parametros
{: .no_toc }

| -U   	|            get userlist
| -M     |        get machine list
| -N      |       get namelist dump (different from -U and-M)
| -S       |      get sharelist
| -P        |     get password policy information
| -G         |    get group and member list
| -A          |   all of the above (full basic enumeration) |

## Misc
 
- Por defecto, el usuario Anonymous tiene permisos de lectura
