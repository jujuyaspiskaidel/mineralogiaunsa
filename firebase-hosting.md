# Desplegar en Firebase Hosting

Este repositorio contiene un sitio estático que puede publicarse en Firebase Hosting.
A continuación se muestran los pasos básicos para ponerlo en línea.

## Requisitos

- Tener instalado [Node.js](https://nodejs.org/) en tu equipo.
- Instalar la herramienta de línea de comandos de Firebase:
  ```bash
  npm install -g firebase-tools
  ```

## Pasos para el despliegue

1. Inicia sesión en Firebase (solo es necesario la primera vez):
   ```bash
   firebase login
   ```
2. Inicializa el proyecto dentro del repositorio:
   ```bash
   firebase init
   ```
   - Selecciona **Hosting** y sigue las instrucciones.
   - Cuando se te pregunte la carpeta pública, puedes indicar `public` o la carpeta que contenga tu sitio estático.
3. Una vez configurado, despliega con:
   ```bash
   firebase deploy
   ```

Al finalizar, Firebase mostrará la URL donde se aloja tu sitio.
