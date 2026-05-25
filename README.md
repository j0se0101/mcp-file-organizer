
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

```

### Paso 2: 
Guía Rápida de Instalación

Sigue estos pasos para tener el proyecto funcionando en tu equipo local.
Clonar el repositorio

Abre una terminal (PowerShell, CMD o Git Bash) y ejecuta:
# Clona el repositorio en tu máquina
```bash
git clone https://github.com/j0se0101/mcp-file-organizer.git

# Accede al directorio del proyecto
cd mcp-file-organizer

```
### Paso 3: 
# 1. Copia el archivo de ejemplo (no lo edites directamente)
cp mcp-config.example.json mcp-config.local.json

# 2. Ahora edita `mcp-config.local.json` con tus rutas reales de Windows
# Reemplaza "TU_USUARIO" con tu nombre de usuario real


## Demo
```bash
MCP conectado en Claude Desktop

```
<div align="center">
  <img width="100%" max-width="800px" alt="image" src="https://github.com/user-attachments/assets/65c48469-6b00-4161-b6fc-cbbcef1d0806" />
    </div>
    
```bash
Prompt sencillo de ejemplo
```
<div align="center">
  <img width="100%" max-width="800px" alt="image" src="https://github.com/user-attachments/assets/cb87955b-4c1f-4a01-ad13-54f2c2abd9ec" />
   </div>

```bash
Instrucción para eliminar archivos de la Papelera de Reciclaje
```
<div align="center">
  <img width="100%" max-width="800px" alt="image"  src="https://github.com/user-attachments/assets/34068086-5a05-4afc-b340-f69c4a2c3fad" />

   </div>
   
```bash
Demostración del MCP eliminó los archivos de la Papelera siempre y cuando ya no se ocupen 
```


<div align="center">
  <img width="100%" max-width="800px" alt="image"  src="https://github.com/user-attachments/assets/b8b9dc47-da93-4bda-b44e-acd97f4e2763" />
  
   </div>

