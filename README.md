# 🧩 Amplify — Ejemplo de despliegue con AWS Amplify (Hosting + API GraphQL)

> Ejemplo simple para uso y prueba con **AWS Amplify**: hosting y creación de API (GraphQL).

<p align="center">
  <img src="https://img.shields.io/badge/AWS%20Amplify-FF9900.svg?style=for-the-badge&logo=awsamplify&logoColor=white" alt="AWS Amplify"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/GraphQL-E10098.svg?style=for-the-badge&logo=graphql&logoColor=white" alt="GraphQL"/>
  <img src="https://img.shields.io/badge/Node.js-43853D.svg?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js"/>
</p>

## 🎯 Descripción

Proyecto de ejemplo para mostrar un flujo típico de:
- Inicializar un proyecto con **Amplify CLI**.
- Añadir hosting para publicar la app (Amplify Console / Managed hosting).
- Crear y desplegar una **API GraphQL** (AWS AppSync) desde Amplify. 

## 🌠 Requisitos previos

- Cuenta de AWS con permiso para crear recursos (IAM).  
- Node.js (versión LTS recomendada).  
- npm o yarn.  
- Amplify CLI instalado globalmente:
```bash
npm install -g @aws-amplify/cli
```

## ✨ Flujo rápido — desplegar en Amplify (CLI)

Los comandos principales que usarás: amplify init, amplify add hosting, amplify add api, amplify push / amplify publish

### 1. Clonar el repositorio
```
git clone https://github.com/StefanyPerezBz/amplify.git
cd amplify
```
### 2. Instalar dependencias
```
npm install
# o
yarn
```
### 3. Configura Amplify
```
amplify configure
```
### 4. Inicializa el proyecto Amplify
Esto te pedirá información como:
- Nombre del proyecto
- Entorno (dev, prod, etc.)
- Región de AWS
- Editor de preferencia
```
amplify init
```
### 5. Añade una API GraphQL
```
amplify add api
# selecciona: GraphQL
# escoge o crea un schema (p. ej. un schema básico tipo Todo)
```
### 6. Añade hosting
Selecciona Hosting con Amplify Console (Managed hosting).
```
amplify add hosting
# selecciona Amplify Console (Managed hosting) o el flujo que prefieras
```
### 7. Despliega los recursos al cloud
```
amplify push
```
### 8. Publica el sitio
```
amplify publish
```
## 🌐 Acceso a la aplicación
Una vez publicada, podrás acceder desde cualquier navegador al link generado por Amplify Console

## 📖 Documentación útil
- [Documentación oficial de AWS Amplify](https://docs.amplify.aws/)
- [CLI de Amplify](https://docs.amplify.aws/cli/)
- [Hosting con Amplify](https://docs.amplify.aws/hosting/)

## 📜 Licencia
MIT License – Ver LICENSE para detalles completos.

Nota: Proyecto desarrollado con fines academicos


