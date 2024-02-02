# Data Engineering CICD - Infrastructure as Code

Este repositorio es un proyecto de Infraestructura como Código (IaC) que utiliza Terraform para orquestar la aprovisionamiento de los servicios de Azure relacionados con la Ingeniería de Datos.

## Acerca de

Este proyecto muestra cómo integrar el mundo de DevOps, centrándose en la Integración Continua (CI) y el Despliegue Continuo (CD) en el ámbito de la ingeniería de datos moderna utilizando Terraform y Azure como caso de estudio.

## Prerrequisitos

- Cuenta de Azure con una suscripción.
- Azure CLI (Interfaz de línea de comandos de Azure).
- Terraform CLI (Interfaz de línea de comandos de Terraform).
- Cualquier Entorno de Desarrollo Integrado (IDE) de tu elección (VS Code, PyCharm, etc.).

## System Architecture

![system_architecture.jpg](images%2Fsystem_architecture.jpg)

## Primeros Pasos

1. Clona este repositorio.
2. Reemplaza el contenido del archivo llamado `terraform.tfvars` en el directorio raíz del proyecto.
3. Ejecuta los siguientes comandos en el directorio raíz del proyecto:
    - `terraform init` (para inicializar el proyecto de Terraform).
    - `terraform validate` (para validar el código de Terraform).
    - `terraform plan` (para ver los cambios que se aplicarán).
    - `terraform apply` (para aplicar los cambios).
    - `terraform destroy` (para destruir la infraestructura).
