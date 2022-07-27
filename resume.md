# Curso de Docker

## Las tres áreas en el desarrollo de software profesional

### Problemas cuando se construye Software:

- Entorno de desarrollo
- Dependencias
- Entorno de Ejecucion
- Equivalencia con entornos productivo
- Servicios externos

### Problemas en la Distribucion de Software:
El codigo debe transformarse en artefactos y deben poder ser transportados a donde seran ejecutados.
- Divergencia de repositorios
- Divergencia de artefactos
- Versionado

### Problems when executing:
La maquina deonde se escribe el software siempre es distinta a donde se ejecuta de manera productiva.
- Conpatibilidad con el entoprno productivo
- Dependencias
- Disponibilidad de servicios externos
- Recursos de hadware

Docker permite Construir, distribuir y ejecutar sofware en cualquier lado.

## Virtualización
Es la opcion que nos permite atacar los tres problemas en el desarrollo de software.
Pero las VM no son la mejor forma de hacerlo.
- Peso de la maquina
    - SO
- Costo de Administracion
    - Configuracion
    - Usuarios
    - paquetes de software
- Formatos
    - problemas en la distribucion
    - Compatibilidad con el entorno productivo

![](https://www.redeszone.net/app/uploads-redeszone.net/2016/02/docker-vs-virtual-machines.png)


### Containerización
El empleo de contenedores para construir y desplegar software
- Ventajas
    - Flexibles
    - livianos
    - Portables: funcionan igual en cualquier maquina
    - Bajo Acoplamiento: son autocontenidos y no compiten entre ellos
    - Escalables: se pueden escalar y desescalar
    - Seguros: se aseguran de que se acceda a los recursos necesarios

![captura](./Captura.png)

## Preparando tu entorno de Trabajo

- [Download Docker](https://www.docker.com/get-started/)
- [Cent OS](https://docs.docker.com/engine/install/centos/)
- [Debian](https://docs.docker.com/engine/install/debian/)
- [Fedora](https://docs.docker.com/engine/install/fedora/)
- [Ubuntu](https://docs.docker.com/engine/install/ubuntu/)

[Docker Hub](https://hub.docker.com/)

#### Docker Desktop
 - Resources: configurar los recursos de la maquina

