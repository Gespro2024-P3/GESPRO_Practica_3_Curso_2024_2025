![header](https://cloud.githubusercontent.com/assets/6546265/22174630/785cdf04-dfe3-11e6-8cf4-024e8dc1c051.png)

[![ZenHub](https://raw.githubusercontent.com/ZenHubIO/support/master/zenhub-badge.png)](https://zenhub.com)
[![Build Status](https://travis-ci.org/davidmigloz/go-bees.svg?branch=master)](https://travis-ci.org/davidmigloz/go-bees)
[![codecov](https://codecov.io/gh/davidmigloz/go-bees/branch/master/graph/badge.svg)](https://codecov.io/gh/davidmigloz/go-bees)
[![Code Climate](https://codeclimate.com/github/davidmigloz/go-bees/badges/gpa.svg)](https://codeclimate.com/github/davidmigloz/go-bees)
[![SonarQube](https://sonarqube.com/api/badges/gate?key=go-bees)](https://sonarqube.com/component_measures/?id=go-bees)
[![Dependency Status](https://www.versioneye.com/user/projects/57f7b19e823b88004e06ad33/badge.svg?style=flat-square)](https://www.versioneye.com/user/projects/57f7b19e823b88004e06ad33)
[![Documentation Status](https://readthedocs.org/projects/go-bees/badge/?version=develop)](http://go-bees.readthedocs.io/es/develop/?badge=develop)

## License

Copyright (c) 2016 - 2017 David Miguel Lozano

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.



## Trabajo GesPro

## Guía de cómo se realiza toda la secuencia de acciones desde que nos posicionamos en un nuevo commit del repositorio Go Bees hasta que pasa a estar visible en nuestra rama master local.

1. Abrir el repositorio Go Bees en GitKraken

- Inicia GitKraken y selecciona el repositorio Go Bees.
  
- Localiza el commit en el que deseas posicionarte en el gráfico de commits.

2. Realizar un hard reset en la rama master al commit seleccionado

- Haz clic derecho en el commit deseado.
  
- Selecciona la opción Reset branch to this commit.
  
- Cuando se te pregunte, elige la opción Hard Reset.

¿Por qué usar un hard reset?

Un hard reset mueve la referencia de la rama master al commit especificado y sincroniza el contenido del directorio de trabajo y el índice con ese commit. 

3. Actualizar la carpeta en el sistema de archivos

- Accede a tu directorio local donde está ubicado el repositorio Go Bees.
  
- Copia todo el contenido del repositorio y reemplázalo en la carpeta correspondiente dentro 
  del directorio de tu proyecto GESPRO_Practica_3_Curso_2024_2025.

4. Volver a GitKraken para sincronizar los cambios

- Regresa a GitKraken y verifica que el repositorio Go Bees esté actualizado con el estado 
  del commit en la rama master.
  
- Desde la rama master, realiza un Fetch para obtener actualizaciones remotas.
  
- Luego, ejecuta un Pull para sincronizar la rama master local con la remota, incorporando 
  cualquier cambio adicional que no estuviera presente.

## Gráfico obtenido con una captura de pantalla con la lista de commits del repositorio:
Primeramente vemos el grafico de los commits donde podemos apreciar la fecha que se hicieron y la cantidad de estos

![image](https://github.com/user-attachments/assets/4d790219-91bf-434a-95d6-56f62ae66f89)

Por otra parte, tenemos la grafica de los commits hechos por cada uno en la grfica naranja que se muestra en la imagen, junto con las pull request que se han abierto cerrado

![image](https://github.com/user-attachments/assets/544dcaa4-175c-4fbd-bdb9-8176f74cb3b1)

## Capturas de commits

### Captura de pantalla del primer commit

<img width="1470" alt="image" src="https://github.com/user-attachments/assets/78ddee34-e47d-4063-a71a-d160917e61e0">

### Captura de pantalla del último commit antes de las actualizaciones del readme

<img width="1470" alt="image" src="https://github.com/user-attachments/assets/eb1e059e-f2d4-4e9b-9fa9-0c58f72f144b">

## La información del proyecto de Github obtenida desde la opción de menú "Insights→Pulse"

<img width="1470" alt="image" src="https://github.com/user-attachments/assets/a33401ef-3f28-4881-89bb-484769a7f349">

En esta captura podemos observar un resumen semanal de actividad en el repo de GitHub (22-29 de noviembre de 2024). Se destacan 8 pull requests y 8 issues activos, con 8 pull requests fusionados y 8 issues cerrados. Participamos 3 autores con 11 commits, afectando 408 archivos, con 114,182 adiciones y 185 eliminaciones.

## La información del proyecto de Github obtenida desde la opción de menú "Insights→Code frecuency"

![image](https://github.com/user-attachments/assets/4e6b63a9-e4ba-4040-aebf-2b02a132d072)

Este gráfico muestra las adiciones y eliminaciones de líneas de código del repo de GitHub durante un periodo de tiempo. Podemos observar un crecimiento significativo de las adiciones de líneas de código, lo que refleja una fase activa de implementación y dessarrollo. Las eliminaciones de código han sido mínimas, lo que sugiere equilibrar este crecimiento con revisiones para asegurar la calidad y sostenibilidad.


## Captura con la relacion de las PRQs relaizadas cerradas
Aqui se pueden ver las pull requests realizadas, las cuales ya se encuetran todas cerrada como se puede aprecia.

![image](https://github.com/user-attachments/assets/b87bb06a-99e8-4261-8787-53d8e0b49191)
 


