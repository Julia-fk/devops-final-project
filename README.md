# Proyecto Final – DevOps y Cloud Computing

## Descripción del Proyecto

Este proyecto consiste en la implementación de una infraestructura DevOps básica utilizando contenedores Docker, integración continua y despliegue automático en la nube.

La aplicación desarrollada corresponde a una página web simple desplegada mediante Docker y publicada automáticamente utilizando GitHub y Render como plataforma cloud.

El objetivo principal fue comprender el funcionamiento de herramientas modernas utilizadas en entornos DevOps reales, aplicando conceptos de automatización, despliegue continuo e integración con servicios en la nube.

---

## Tecnologías Utilizadas

* Docker
* Docker Compose
* GitHub
* Render Cloud Platform
* HTML
* Nginx
* MySQL
* Git
* CI/CD

---

## Arquitectura del Proyecto

Usuario
↓
Cloud Platform
↓
Docker Compose
├── Contenedor Web (Nginx)
└── Contenedor Base de Datos (MySQL)

---

## Flujo CI/CD

1. El desarrollador realiza cambios en el proyecto.
2. Los cambios se suben a GitHub mediante Git.
3. Render detecta automáticamente los cambios.
4. Se construye nuevamente la imagen Docker.
5. La aplicación se despliega automáticamente en la nube.

---

## Repositorio GitHub

Repositorio del proyecto:

https://github.com/Julia-fk/devops-final-project

---

## Aplicación Desplegada

URL del proyecto en producción:

https://devops-final-project-hkv8.onrender.com

---

## Funcionalidades Implementadas

* Aplicación web contenerizada
* Dockerfile funcional
* Integración con GitHub
* Despliegue automático
* Infraestructura cloud
* CI/CD automático
* Arquitectura multicontenedor
* Docker Compose implementado
* Servicio de base de datos MySQL

---

## Autor

Proyecto desarrollado para el curso de Sistemas Operativos II.
