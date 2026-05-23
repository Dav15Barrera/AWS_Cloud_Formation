# Infraestructura en Alta Disponibilidad con NGINX usando AWS CloudFormation

**Curso:** Análisis y Diseño de Arquitectura de Sistemas  
**Estudiante:** David Enrique Lux Barrera  
**Carnet:** 9990-21300  
**Año:** 2026  

---

# Descripción del Proyecto

Este proyecto consiste en el despliegue automatizado de una infraestructura web de alta disponibilidad en Amazon Web Services (AWS) utilizando AWS CloudFormation e infraestructura como código (IaC).

La arquitectura implementada utiliza:

- Amazon EC2
- Application Load Balancer (ALB)
- AWS CloudFormation
- NGINX
- Security Groups
- Plantillas YAML

El objetivo principal fue comprender el funcionamiento de arquitecturas resilientes y tolerantes a fallos mediante automatización cloud.

---

# Arquitectura Implementada

La infraestructura desplegada está compuesta por:

- 2 instancias Amazon EC2
- 1 Application Load Balancer
- Security Groups para HTTP y SSH
- Balanceo de tráfico HTTP
- NGINX como servidor web
- Plantilla YAML automatizada con CloudFormation

El Load Balancer distribuye automáticamente las solicitudes entrantes entre las instancias EC2 activas para garantizar alta disponibilidad.

---

# Tecnologías Utilizadas

- AWS CloudFormation
- Amazon EC2
- Application Load Balancer
- NGINX
- YAML
- GitHub

---

# Objetivos del Laboratorio

- Automatizar infraestructura mediante CloudFormation.
- Implementar una arquitectura de alta disponibilidad.
- Configurar balanceo de carga entre instancias EC2.
- Validar tolerancia a fallos.
- Comprender principios de infraestructura como código (IaC).

---

# Despliegue de la Infraestructura

## 1. Crear la pila en CloudFormation

Cargar la plantilla YAML desde la consola de AWS CloudFormation y desplegar la infraestructura.

## 2. Verificar las instancias EC2

Comprobar que ambas instancias EC2 se encuentren en estado:

```bash
Running (2/2 checks passed)
