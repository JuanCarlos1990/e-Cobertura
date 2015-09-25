/*
Copyright (c) 2014, 2015 Jaramillo Juan Carlos, Gallardo Rafael

e-Cobertura is free software: you can redistribute it and/or modify
        it under the terms of the GNU General Public License as published by
        the Free Software Foundation, either version 3 of the License, or
        (at your option) any later version.
        e-Cobertura is distributed in the hope that it will be useful,
        but WITHOUT ANY WARRANTY; without even the implied warranty of
        MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
        GNU General Public License for more details.
        You should have received a copy of the GNU General Public License
        along with e-Cobertura.  If not, see <http://www.gnu.org/licenses/>.*/

e-Cobertura - Android App

La aplicación debe adquirir datos en intervalos regulares de tiempo de 1,2 segundos, debido al tiempo que demora 
el procesamiento y almacenamiento de los mismos. En cada intervalo de tiempo, la aplicación recupera parámetros 
fundamentales para su procesamiento y análisis posterior, tales como la potencia recibida en GSM medida en dBm, 
el identificador de celda, y la ubicación del dispositivo móvil; así como información adicional para el conocimiento 
del usuario de la aplicación.

Con la aplicación el usuario tendrá la opción de ver los detalles acerca de la red móvil, tales como: parámetros de la operadora
celular, del dispositivo móvil y su ubicación, además podrá medir la potencia recibida, con la cual verá estadísticas tanto de
la zona de cobertura como de la potencia recibida en función del tiempo, y generar un reporte.

## Files

e-Cobertura tiene archivos, los cuales por relevancia son:

*   app/libs/

	Este directorio contiene las librerías utilizadas para el correcto funcionamiento de la aplicación.  

*   add/src/main

	Este directorio contiene tanto el directorio java/ enfocado en los archivos .java, así como el directorio res/ para la interfaz gráfica.

