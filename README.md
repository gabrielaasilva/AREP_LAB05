# AREP_LAB05

 [Ana Gabriela Silva.](https://github.com/gabrielaasilva)

## Arquitectura de seguridad del prototipo 

La arquitectura de seguridad se basa en una aplicacion desplegada en una maquina virtual ofrecida por AWS a la cual se accederá por medio del navegador. Para acceder a esta requerimos que el usuario se encuentre autenticado, ya que las peticiones a realizar estarán ligadas al protocolo Https. 
Una vez se logre esta conexion por medio del navegador, se utilizarán servicios ofrecidos por otra aplicación desplegada en otra máquina virtual totalmente diferente y por medio de protocolos https igualmente.

### Explique como escalaría su arquitectura de seguridad para incorporar nuevos servicios.

Para poder adicionar nuevos servicios que mejoren la seguridad de la aplicación implementada, se puede basar el sistema en uno de roles. Suponiendo que mucho usuarios acceden a la aplicación al mismo tiempo peor cada uno tiene un rol diferente. Esto da la posibilidad de que algunos usuarios no puedan acceder a servicios que no estén habilitados para este.

## Instalación
Para uso del proyecto requerimos clonar este repositorio. Siga los pasos:

1. Clonar el repositorio con ayuda de git
```
git clone https://github.com/gabrielaasilva/AREP_LAB05
```

2. Acceder a la carpeta donde hemos clonado
```
cd AREP_LAB05
```

3. Compilar el proyecto para generar el target
```
mvn package
```


