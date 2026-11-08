Sistema de Gestion Comercial — ASOCIADOS Spa

Solucion tecnica SQL desarrollada por SOLUINFO para ASOCIADOS (Etapa 3).
 
Esquema y Base de Datos

Motor: Oracle Cloud Autonomous Database

Esquema: PRY2205_S3

Script Entregable: Encargo_Semana3.sql

Modulos de Reportes

1. Analisis de Propiedades (Caso 1)

Resumen por tipo de propiedad con metricas (COUNT, MAX, MIN, AVG, SUM).

Clasificacion en ESTANDAR (hasta $1.000.000) o PREMIUM (sobre $1.000.000).

Filtro de gastos comunes mediante variable de sustitucion (&VALOR_TOTAL_GASTO_COMUN).

2. Antiguedad y Bonos de Empleados (Caso 2)

Filtro para Ejecutivos de Arriendo con mas de 5 años de servicio.

Exclusion parametrica por sucursal (&CODIGO_SUCURSAL).

Calculo de bonificacion sobre sueldo: 5% (5-10 años), 10% (11-20 años) y 15% (>20 años).

3. Segmentacion de Clientes por Renta (Caso 3)

Clasificacion en tramos: PREMIUM, ALTA, MEDIA y BAJA.

Control de contactabilidad (Clientes con Telefono / Clientes Sin Telefono).

Filtro para promedios de renta superiores a $200.000.

Instrucciones de Ejecucion

Conectar a PRY2205_ACTIVIDAD_S3 en Oracle SQL Developer.

Ejecutar PRY2205_Exp1_S3_CreaEsquemaPoblado.sql para poblar el esquema.

Ejecutar Encargo_Semana3.sql usando los parametros:

Caso 1: 100000

Caso 2: 30 (Providencia)

Duoc UC | Consulta de Bases de Datos (PRY2205)

Cliente: ASOCIADOS | Desarrollo: SOLUINFO
