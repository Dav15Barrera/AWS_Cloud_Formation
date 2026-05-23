# Infraestructura en Alta Disponibilidad con NGINX usando AWS CloudFormation

**Curso:** Análisis y Diseño de Arquitectura de Sistemas  
**Estudiante:** David Enrique Lux Barrera  
**Carnet:** 9990-21300 
---

# Introducción

En el ámbito moderno de la ingeniería de sistemas y la administración de infraestructuras en la nube, la evolución desde configuraciones manuales hacia paradigmas de Infraestructura como Código (IaC) representa un estándar operativo fundamental. El despliegue manual de recursos presenta limitaciones importantes en términos de escalabilidad, repetibilidad y tolerancia a fallos.

Durante el laboratorio se realizaron pruebas de despliegue, validación de instancias y funcionamiento de la infraestructura, fortaleciendo conocimientos relacionados con servicios cloud, automatización y diseño de arquitecturas resilientes.

---

# Objetivos del Proyecto

- Automatizar el despliegue de infraestructura mediante AWS CloudFormation.
- Implementar una arquitectura básica de alta disponibilidad.
- Configurar múltiples instancias EC2 utilizando plantillas YAML.
- Comprender el funcionamiento de Infraestructura como Código (IaC).
- Fortalecer conocimientos en administración de servicios cloud.

---

# Tecnologías Utilizadas

- AWS CloudFormation
- Amazon EC2
- NGINX
- YAML
- GitHub
- AWS Console

---

# Arquitectura Implementada

La infraestructura implementada se encuentra compuesta por:

- 2 instancias Amazon EC2
- Configuración automatizada mediante CloudFormation
- NGINX como servidor web
- Plantilla YAML para despliegue automático
- Security Groups para acceso HTTP y SSH

La automatización permitió desplegar todos los recursos desde una única plantilla declarativa, facilitando la administración y reutilización de la infraestructura.

---

# Desarrollo Técnico y Evidencias

## 1. Despliegue mediante CloudFormation

La infraestructura fue desplegada utilizando AWS CloudFormation mediante una plantilla YAML previamente configurada. El servicio permitió automatizar el aprovisionamiento de los recursos cloud necesarios para la práctica.

El estado final de la pila alcanzó correctamente el estado:

```bash
CREATE_COMPLETE
```

---

## 2. Implementación de Instancias EC2

Se desplegaron múltiples instancias EC2 configuradas con NGINX como servidor web. Las instancias fueron creadas automáticamente mediante la plantilla YAML definida en CloudFormation.

---

## 3. Configuración del Servidor Web

Cada instancia EC2 fue configurada automáticamente para ejecutar NGINX, permitiendo publicar contenido web básico y validar la disponibilidad del servicio desde el navegador.

El uso de automatización facilitó considerablemente el proceso de configuración y despliegue de los servidores.

---

## 4. Infraestructura como Código (IaC)

El laboratorio permitió aplicar el concepto de Infraestructura como Código mediante archivos YAML en AWS CloudFormation. Esto permitió:

- Reutilizar configuraciones
- Estandarizar despliegues
- Reducir errores manuales
- Facilitar mantenimiento y escalabilidad

---

# Estructura del Proyecto

```bash
.
├── template.yaml
└── README
```

---

El repositorio contiene los archivos necesarios para desplegar la infraestructura y documentar el laboratorio realizado.

---

# Aprendizajes Obtenidos

Durante el desarrollo de este laboratorio aprendí a desplegar infraestructura automatizada en AWS utilizando CloudFormation y plantillas YAML, lo cual facilitó la creación y administración de recursos de manera más rápida y organizada. También comprendí el funcionamiento de las instancias EC2 y la importancia de automatizar configuraciones para mejorar la administración de servicios en la nube. Además, identifiqué las limitaciones de la capa gratuita de AWS y cómo estas pueden influir en el diseño de arquitecturas cloud y el tipo de recursos utilizados. Finalmente, esta práctica fortaleció mis conocimientos sobre automatización, tolerancia a fallos, administración de infraestructura y escalabilidad en entornos cloud.

---

# Comentario Final

La práctica permitió comprender de manera más clara cómo funciona el despliegue automatizado de infraestructura en la nube mediante AWS CloudFormation. Asimismo, se logró evidenciar la importancia de utilizar Infraestructura como Código para simplificar tareas administrativas, reducir errores y facilitar la escalabilidad de proyectos tecnológicos.

El laboratorio también permitió reforzar conocimientos sobre servicios EC2, automatización mediante YAML y administración de servidores web utilizando NGINX, aplicando conceptos fundamentales del análisis y diseño de arquitecturas de sistemas.

---

# Autor

**David Enrique Lux Barrera**  
