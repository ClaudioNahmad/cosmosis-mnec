# CosmoSIS

Hola a todos, este repositorio contendrá la charla, láminas, código, y todo el contenido necesario para instalar y ejecutar comandos simples con CosmoSIS. Debajo dejo dos cosas, una es la traducción de la breve descripción que hacen los creadores de CosmoSIS sobre el framework, y luego el proceso de instalación para CosmoSIS-Docker, ambas traducciones son mías.

## ¿Qué es CosmoSIS?

CosmoSIS es un código para la estimación de parámetros cosmológicos.

Es un framework para estructurar estimaciones a parámetros cosmológicos, en una 
manera que facilita la reusbilidad, depuración, verificabilidad y compartir código 
en la forma de módulos de cálculo. 

Consolida y conecta los códigos existentes para predecir observables cósmicos, y hace 
mucho más accesible el mapeo de likelihoods experimentales con un rango de diferentes técnicas.

CosmoSIS está descrito en Zuntz et al: http://arxiv.org/abs/1409.3409.

## Instalación de CosmosSIS-Docker (asegúrate que tengas instalado [Git](https://git-scm.com/))

To install CosmoSIS with this tool:

1. Instala Docker (paso uno de https://docs.docker.com/docker-for-mac/ para OSX) desde 
www.docker.com
2. Arranca Docker siguiendo las instrucciones del sitio. No hace falta leer los tutoriales
3. Descarga esta herramienta corriendo:

```
git clone https://bitbucket.org/joezuntz/cosmosis-docker
```
4. Con el comando `cd`muévete al nuevo directorio de cosmosis-docker y corre:

```
./get-cosmosis-and-vm ./cosmosis
```
5. Para obtener la versión de dasarrollo que tiene algunos bugs corregidos y los ùltimos updates corre el comando:
```
update-cosmosis --develop
```
6. La primera vez que hagas todos estos pasos debe correr `make`.

En el futuro solo hace falta que hagas el paso 5. 
