# Examen Final Arquitectura de Computadores

## Objetivo del proyecto

Desplegar y administrar una infraestructura en AWS mediante CloudFormation y GitHub Actions, implementando una instancia EC2 con una página web personalizada y aplicando buenas prácticas de control de versiones mediante Git Flow.

---

## Tecnologías utilizadas

- AWS EC2
- AWS CloudFormation
- GitHub Actions
- Git
- Git Flow
- Amazon Linux
- HTML
- CSS
- JavaScript

---

## Funcionalidad de Deploy

El workflow de Deploy valida el template de CloudFormation y despliega la infraestructura en AWS, creando una instancia EC2 y los recursos necesarios para alojar una página web.

---

## Funcionalidad de Destroy

El workflow de Destroy elimina el stack de CloudFormation y todos los recursos asociados, incluyendo la instancia EC2 y el Security Group.

---

## Objetivo del Template EC2

El template de CloudFormation automatiza la creación de una instancia EC2 Amazon Linux con un Security Group que permite conexiones HTTP por el puerto 80. Además, configura automáticamente un servidor web mediante UserData para mostrar una página personalizada con la información del estudiante.

---

## Autora

**Yuliany Michell Sánchez Becerra**

**Código:** 0192372