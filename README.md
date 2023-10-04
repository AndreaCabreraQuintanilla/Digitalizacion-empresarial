# Digitalización empresarial

## Integrantes:
- Andrea Cabrera Quintanilla
- Griselle Alanís Morales
- Irene Nicolás Martínez
- Verónica Marina Ruiz

## Descripción:
Nuestro cliente está inmerso en un proceso activo de transformación digital, a raíz de esto, nos ha mandando una serie de diferentes ficheros que contienen datos sin limpiar, cuya información está relacionada entre sí. La empresa desea obtener una base de datos que agregue toda la información de forma estructurada.

De esta forma nos ha mandando tres ficheros:
- Archivo en formato XML.
- Archivo en formato txt.
- Archivo en formato sql.

Para ello deberemos:
1. Crear la base de datos, inserción, modificación y extracción los ficheros de la base de datos a un fichero   
  externo.
2. Limpiar los datos de los ficheros xml automatizados.
3. Limpiar los datos de los ficheros txt automatizados.
4. Insertar los datos de los ficheros xml y txt a la BBDD mediante Python.
5. Automatizar la lectura de los archivos procesados y actualización de los datos.

## Motivación:
Estamos trabajando para una empresa en pleno proceso de transformación digital. Quieren hacer un estudio de los datos que tienen, para ello nos piden realizar una serie de tablas finales que tengan la información parcialmente procesada y que se automatice todo el sistema de procesado de datos, ya que de forma periódica se recibirán otras remesas de datos similares actualizados.

## Librerías utilizadas:
* import re
* import os
* import xml.etree.ElementTree as ET
* import mysql.connector

## Estructura de las carpetas:

datos - SQLproyecto.sql - data_sql.sql - data_txt.txt - data_xml.xml
 
jupiter - SQL_creacion_BBDD.ipynb - read_xml_txt.ipynb - txt_limpio.ipynb - xml_limpio.ipynb

presentacion_demo - Proyecto_modulo_1.pptx
