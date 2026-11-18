<div align="center">

<img src="https://raw.githubusercontent.com/Mingo20/dtech/main/assets/brand/dg-logo-512.png" width="84" alt="DGTech" />

# Andrea IA

**Andrea IA, asistente inteligente de DGTech instalable en el celular.**

![Versión](https://img.shields.io/badge/versión-1.2.0-FF6A13?style=flat-square) ![Estado](https://img.shields.io/badge/estado-Producción-2EA44F?style=flat-square) ![Tipo](https://img.shields.io/badge/tipo-PWA_%2B_proxy_Base44-0B2545?style=flat-square) ![DGTech](https://img.shields.io/badge/by-DGTech-FF6A13?style=flat-square)

[**Abrir la aplicación**](https://mingo20.github.io/andrea-ia-pwa/) · [Hub DGTech](https://mingo20.github.io/dtech/) · [Guía para agentes](AGENTS.md) · [Cambios](CHANGELOG.md)

<img src="https://raw.githubusercontent.com/Mingo20/dtech/main/assets/shots/andrea.jpg" alt="Andrea IA" width="720" />

</div>

## El problema

Un asistente conversacional propio, siempre disponible.

## Qué hace

- Chat con memoria de conversación
- Instalable como PWA
- Proxy seguro hacia el agente

## Cómo está construido

**Tipo:** PWA + proxy Base44

La PWA habla con andreaChatProxy, que reenvía al agente.

**Tecnologías**

- HTML, CSS y JavaScript
- Service Worker (andrea-v1.2)
- Proxy andreaChatProxy en Base44

**Backend**

- andreaChatProxy

**Datos**

- Conversación local (andrea_conversation)

## Datos sensibles

Conversaciones del usuario.

## Reglas del proyecto

- Esta es la versión vigente: andrea-ia y andrea-chat son anteriores

## Pendientes conocidos

- Archivar andrea-ia y andrea-chat

## Estructura del repositorio

Consulta [AGENTS.md](AGENTS.md) para el mapa de archivos y las instrucciones de trabajo.

## Parte de DGTech

Este proyecto forma parte del ecosistema **DGTech**, un estudio de software dominicano que construye aplicaciones instalables para resolver problemas reales. Todas las aplicaciones están en [https://mingo20.github.io/dtech/](https://mingo20.github.io/dtech/).

---

<sub>© 2026 DGTech · Domingo Guerra · Todos los derechos reservados. Consulta el archivo NOTICE.</sub>
