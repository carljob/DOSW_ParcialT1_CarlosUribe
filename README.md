# DOSW - Parcial T1

## Información del Estudiante

- **Nombre:** Carlos Uribe Vargas
- **Grupo:** 1

---

### Parcial
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)

---

## Herramientas

### Modelado
### Lucidchart  

![warranty](https://img.shields.io/badge/warranty-Create%20With%20Acces-green)

![img.png](dosc/images/garantias/img.png)



### Diseño UI
### Figma  

![warranty](https://img.shields.io/badge/warranty-Create%20With%20Acces-green)

![img_1.png](dosc/images/garantias/img_1.png)


---

## Febrero 2026

# Requerimientos que selecionamos del punto 3

# RF01 

## descripcion :

el sistema debe permitir registrar dinamicamente la estructura academicadel 
bootcamp permitiendo crear nodos jerarquicos como bootcamp grupos estudiantes y futuras 
subcategorias.

## Actor : 

Administrativo academico

## Flujo de entrada :

Sistema operativo

## Flujo de salida :

la estructura queda almacenada en memoria
mantiene la relacion padre hijo 

## Reglas :

no se asume profundidad fija
un estudiante debe pertenecer a un grupo 


# RF03 Generar listado de estudiantes con riesgo :

## Descripcion :

se debe generar un listado de estudiantes cuto promedio ponderado no sea menor a tres 

## Actor :

Administrativo academico


## Regla de negocio :  

riesgo sea menor a tres

Gestion de calculo de promedio

Historia de usuario :

    * Como administrador quiero que el sistema calcule 
    automaticamente el promedio para conocer el rendimiento 
    del estudiante *


