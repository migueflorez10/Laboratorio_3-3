### Info de la Materia: Topicos Especiales en Telematica-st0263
# Link de Sustentación:

### Estudiantes:
- Miguel Angel Martinez Florez, mamartinef@eafit.edu.co
- Mateo Muñoz Cadavid, mmunozc4@eafit.edu.co

### Profesor:  Edwin Nelson Montoya Munera, emontoya@eafit.edu.co  

# Laboratorio 3-3: Implementación de una Data Warehouse con AWS REDSHIFT y REDSHIFT SPECTRUM

##  Objetivo
El objetivo de este laboratorio es aprender a implementar un Data Warehouse utilizando AWS Redshift y Redshift Spectrum. Se realizará la carga de datos en Redshift 
desde archivos planos ubicados en Amazon S3, y se ejecutarán consultas SQL en la base de datos de ejemplo 'tickit' para realizar análisis de datos.

## Descripción de la Actividad 
En este laboratorio, se seguirán los siguientes pasos:

- Crear un cluster de Redshift en la consola de AWS.
- Configurar el cluster y realizar la carga inicial de la base de datos de ejemplo 'tickit'.
- Configurar Redshift Spectrum para acceder a datos externos en Amazon S3.
- Ejecutar consultas SQL en Redshift para realizar análisis de datos en la base de datos 'tickit'.

## Guia paso a paso 
- Crear un cluster y ejecutar consultas básicas en la base de datos demo ‘tickit’:
![image](https://github.com/migueflorez10/Laboratorio_3-3/assets/68928440/d97fb708-14b0-4cf9-9f90-ce687e15837f)

- Al ingresar al Amazon Redshift, debes darle click a la opción "Crear Cluster":
![image](https://github.com/migueflorez10/Laboratorio_3-3/assets/68928440/de3a24ba-0713-4a52-899f-c12feecec138)

- Configura el cluster de la siguiente manera:
![image](https://github.com/migueflorez10/Laboratorio_3-3/assets/68928440/60db2d4c-8a09-44cf-b3e0-34697e4b68a6)
![image](https://github.com/migueflorez10/Laboratorio_3-3/assets/68928440/10d3c28d-2dc7-448d-9e48-5a17309bf030)
![image](https://github.com/migueflorez10/Laboratorio_3-3/assets/68928440/094c3ffd-7814-4eda-bd2f-021840b9d4ac)
- Ingresas un usuario y contraseña (Recuerdalo ya que se utilizara mas adelante)
![image](https://github.com/migueflorez10/Laboratorio_3-3/assets/68928440/3d9fb572-1502-4e30-963b-4a4dd2ca3143)
![image](https://github.com/migueflorez10/Laboratorio_3-3/assets/68928440/b52eca39-7cfd-4f10-b090-ffa5700886ea)
![image](https://github.com/migueflorez10/Laboratorio_3-3/assets/68928440/49ae5f5f-1170-423f-9710-a197ad5b4920)
![image](https://github.com/migueflorez10/Laboratorio_3-3/assets/68928440/5c1a3fe7-8d06-4ed3-8ec6-7c62e2175621)
![image](https://github.com/migueflorez10/Laboratorio_3-3/assets/68928440/aeb36c9a-de21-4bbf-b9bd-06d251ea10e6)
- Darle a la opción craer Cluster
- 







## Descripción del Ambiente de Desarrollo y Técnico
Para este laboratorio, se utilizarán los siguientes recursos:

- AWS Account: Se requiere una cuenta de AWS para acceder a los servicios.
- AWS Redshift: Se utilizará Redshift como el Data Warehouse principal.
- Amazon S3: Se utilizará S3 para almacenar archivos planos y acceder a ellos a través de Redshift Spectrum.
- Dataset 'tickit': Se utilizará el dataset 'tickit' como ejemplo de base de datos para realizar consultas SQL. (https://docs.aws.amazon.com/redshift/latest/gsg/samples/tickitdb.zip)
