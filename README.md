# Despliegue-de-API-REST-en-GO-en-K8s

Proyecto que utiliza YAML para gestionar Kubernetes.
---
## Descripción

Este repositorio contiene archivos YAML que definen la infraestructura de mi aplicación en Kubernetes. Utilizo estas configuraciones para desplegar y orquestar mis servicios de manera eficiente.

---
## Estructura del Proyecto

- **/deployments**: Contiene archivos YAML para los despliegues de mis aplicaciones.
- **/services**: Define los servicios y configuraciones de red.
- **/ingress**: Archivo YAML para la exposición de la ruta HTTP desde afuera del cluster a servicios dentro del cluster donde se ve la parte del acceso a la api por el dominio api.jnajera.com y el puerto 8080.

---
## Uso

1. Clona este repositorio:

   ```bash
   git clone https://github.com/Rethory/Despliegue-de-API-REST-en-GO-en-K8s.git
   
2. Aplicaciones de los yaml:
    ```bash
    kubectl apply -f deployment.yaml
    kubectl apply -f service.yaml
    kubectl apply -f ingress.yaml
