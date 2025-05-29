# Proyecto Final : Sistema de Control de Reciclaje por Familias

**Integrantes:** 
- Brajham Steven Vanegas
- Camilo 
- Karen Beltran
- Juana Sofia Rodriguez

## Requisitos Previos
- Tener Python 3.8 o superior instalado en tu equipo.
- Un entorno de consola o terminal para ejecutar el script (cmd, Terminal, PowerShell, etc).

## Instrucciones para Ejecutar el Programa:
1. Descarga el archivo Proyecto final.py.
2. Abre la consola (cmd) en la carpeta donde está guardado el archivo.
3. Ejecuta el script con: python "Proyecto final.py"

## ¿Cómo Funciona el Sistema?
**Menú principal:**
Al iniciar el programa, verás un menú con estas opciones:
  - Registrar familia: Introduce nombre, número de integrantes y dirección.
  - Registrar material recogido: Introduce el nombre de una familia previamente registrada, tipo de material, peso y fecha.
  - Mostrar resumen de familia: Muestra todos los materiales reciclados por una familia y el total de puntos acumulados.
  - Salir: Cierra el programa.
  
## Tipos de materiales y puntos
Cada material reciclado otorga puntos según su peso (en kilogramos):
- Plástico: 9 puntos por kg
- Vidrio: 11 puntos por kg
- Papel: 8 puntos por kg
- Cartón: 10 puntos por kg

## Notas
- Asegúrate de ingresar el tipo de material en minúsculas y sin tilde para evitar errores: plastico, vidrio, papel, carton.
- Si introduces un tipo de material incorrecto, el sistema te lo notificará.

## EJEMPLO DE USO:
OPC1: Registrar familia

Nombre de la familia: García
Número de integrantes: 4
Dirección de recolección: Calle 123

OPC2: Registrar material recogido

Nombre de la familia: García
Tipo de material: Plástico
Peso en kg: 2
Fecha: 25/05/2025

OPC3: Mostrar resumen de familia

Resumen de reciclaje - Familia: García
plastico - 2kg - 25/05/2025
Total de puntos acumulados: 18
