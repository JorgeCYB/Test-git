# Test-git

Este repositorio contiene una recopilación de conceptos y comandos básicos de **Git**, aplicados en proyectos desarrollados con **UiPath Studio**.

## 📌 Objetivo

Practicar y documentar el uso de Git como sistema de control de versiones para automatizar flujos de trabajo en UiPath Studio. Este repositorio sirve como base para gestionar versiones, colaborar con otros desarrolladores y mantener un historial de cambios claro.

## ⚙️ Requisitos

- UiPath Studio instalado
- Git instalado y configurado
- Cuenta en GitHub, GitLab u otra plataforma de repositorios remotos

## 🧰 Comandos Básicos de Git

A continuación, se detallan algunos de los comandos más comunes utilizados en este proyecto:

### 🔹 Configuración inicial

```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tu.email@ejemplo.com"

### 🔹 Crear repositorio
- git init
### 🔹Clonar repositorio existente
- git clone https://github.com/usuario/repositorio.git
### 🔹Ver estado del repositorio
- git status
### 🔹  Agregar archivos al staging
- git add archivo.xaml
# o todos los archivos:
-git add .
### 🔹Confirmar cambios (commit)
- git commit -m "Mensaje descriptivo del cambio"
### 🔹Ver historial de cambios
- git log
### 🔹Conectar con repositorio remoto
- git remote add origin https://github.com/usuario/repositorio.git
### 🔹Subir cambios al repositorio remoto
-git push -u origin main
### 🔹 Traer cambios del repositorio remoto
-git pull origin main

### 🔹 Jorge cazarez
