
#  MCP File Organizer for Claude Desktop

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Node.js Version](https://img.shields.io/badge/node-%3E%3D18.0-brightgreen)](https://nodejs.org/)
[![MCP](https://img.shields.io/badge/MCP-Compatible-blue)](https://modelcontextprotocol.io)

> Un servidor MCP que permite a Claude Desktop organizar automáticamente tus archivos locales en Windows (Descargas, Documentos, Imágenes) de forma segura e inteligente.

##  Características Principales

-  **Organización Inteligente**: Mueve archivos automáticamente según su tipo (documentos, imágenes, instaladores, comprimidos)
-  **Modo Seguro**: Todas las eliminaciones van a la Papelera de Reciclaje (nada se borra permanentemente)
-  **Búsqueda Avanzada**: Localiza archivos por nombre, extensión o fecha
-  **Renombrado por Lotes**: Agrega prefijos/sufijos a múltiples archivos
-  **Resúmenes Detallados**: Recibe informes completos de las operaciones realizadas
-  **Operaciones Rápidas**: Copia, mueve, renombra y elimina archivos eficientemente

##  Para Qué Sirve

Este proyecto soluciona el problema de tener **Descargas, Documentos e Imágenes desorganizados**. Con comandos simples en lenguaje natural, puedes pedirle a Claude que:

- "Organiza mi carpeta de Descargas por tipo de archivo"
- "Mueve todos los PDF de los últimos 7 días a Documentos"
- "Renombra todas las fotos de Imágenes agregando el prefijo 'vacaciones_'"
- "Limpia archivos temporales de Descargas que tengan más de 30 días"

##  Requisitos Previos

| Requisito | Versión | Verificar con |
|-----------|---------|----------------|
| **Node.js** | v18 o superior | `node --version` |
| **Claude Desktop** | Última versión | Configuración > Acerca de |
| **Windows** | 10 u 11 | `winver` |

##  Instalación y Configuración

### Paso 1: Verificar Node.js

```bash
node --version  # Debe mostrar v18.x.x o superior
npx --version   # Debe mostrar la versión de npx


##  Demo 



<p align="center">
  <img src="Imágenes\Captura de pantalla 2026-05-24 163640.png"" alt="Diagrama de flujo del MCP File Organizer" width="600"/>
</p>

*Figura 1: Flujo de trabajo del organizador de archivos.*

