# 🚀 Infraestructura DMS y ERP en Rocky Linux 10

**Autor:** Begosaurus  
**Fecha:** 21 de febrero de 2026  
**Sistema:** Rocky Linux 10 (Compatible con RHEL 10)

## 📖 Descripción
Este repositorio contiene la guía definitiva para desplegar un entorno de servicios empresariales compuesto por **Mayan EDMS** (Gestión Documental) e **iDempiere 12** (ERP) utilizando **Docker Desktop** como plataforma de orquestación.

## 🎯 Objetivos
- ✅ Instalación limpia de Docker Desktop en Rocky Linux 10.
- ✅ Configuración de Mayan EDMS en puerto no estándar (9000).
- ✅ Construcción de imagen personalizada para iDempiere 12.
- ✅ Uso de archivos `.env` para gestión segura de variables.

## 📑 Índice de Guías
1. [Instalación de Rocky Linux y Servicios Base](docs/01-instalacion-rocky.md)
2. [Instalación de Docker Desktop](docs/02-docker-desktop.md)
3. [Despliegue de Mayan EDMS](docs/03-mayan-edms.md)
4. [Despliegue de iDempiere 12](docs/04-idempiere.md)

## ⚠️ Requisitos
- Mínimo 12GB de RAM asignados a Docker Desktop.
- Acceso root o sudo en el servidor.
