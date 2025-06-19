# Mnitoreo-Del-Personal
# 📊 Monitoreo de Personal en Excel

Este proyecto tiene como objetivo centralizar y visualizar información clave del personal de la organización mediante un dashboard interactivo desarrollado en **Microsoft Excel**, utilizando datos estructurados recolectados desde la hoja **`Data`**.

---

## 📁 Estructura del Proyecto

## Monitotoreo de personal.xlsx
- **Hoja `Data`:** Base de datos principal con 425 registros.
- **Hoja `Calculos`:** Fórmulas intermedias y consolidación de métricas.
- **Hoja `Dashboard`:** Visualización final de KPIs y gráficos interactivos.

---

## 📌 Campos Analizados desde la Hoja `Data`

Se utilizaron los siguientes campos clave:

| Campo                     | Descripción                                                         |
|--------------------------|---------------------------------------------------------------------|
| `Nombre`                 | Identificación del colaborador                                      |
| `Fecha`                  | Fecha de ingreso o referencia del registro                          |
| `Sexo`                   | Género del colaborador (Masculino/Femenino)                         |
| `Área`                   | Departamento o división donde labora el colaborador                |
| `Condición`              | Tipo de contrato (Planilla, CAS, etc.)                              |
| `Sede`                   | Ubicación física (Lima, San Miguel, Surco, etc.)                    |
| `Salario`                | Salario mensual asignado                                            |
| `Asignación familiar`    | Monto adicional por asignación familiar                             |
| `Bono`                   | Valor de bono recibido                                              |
| `Objetivo`               | Estado del objetivo: Terminado, En Proceso, No Iniciado             |
| `Satisfacción`           | Nivel de satisfacción del cliente interno (Satisfecho, Parcial, No) |
| `Indicador 1` al `8`     | Indicadores específicos de desempeño, cumplimiento o control        |

---

## 📊 Indicadores del Dashboard

El tablero interactivo incluye los siguientes KPI y visualizaciones:

- **Total de Personas:** `425`
- **Distribución por Sexo:**
  - Masculino: `67%`
  - Femenino: `33%`
- **Satisfacción del Cliente Interno:**
  - Medido desde la columna `Satisfacción`, resultado global: `49%`
- **Personas con Procesos Terminados:**
  - Calculado desde la columna `Objetivo`: `58%` del total
- **Personas que Aplica Indicadores:**
  - Tomado desde `Indicador 1`, valor `"Aplica"` representa el `52%`
- **Total Neto a Pagar:**
  - Suma total de la columna `Salario`: `S/ 24.148.068,4`
    

---

## 🎯 Segmentaciones Disponibles

El dashboard permite filtrar y analizar los datos por:

- **Sede:** (9 ubicaciones)
- **Área:** (Administración, Comunicaciones, Bioquímica, Resultados)
- **Año:** (2016–2019)
- **Mes:** (Enero a Diciembre)
  
## Dasboard 
![image](https://github.com/user-attachments/assets/b44e7711-4abe-4c74-b9c9-ed083f02ccb7)

---

## ⚙️ Proceso ETL

### 🔸 1. **Extracción**
- Fuente: hoja `Data` del archivo `Herramienta-de-Monitoreo-15.xlsx`
- Herramienta: Microsoft Excel

### 🔸 2. **Transformación**
- Normalización de valores (por ejemplo: `"si"` → `"SI"` en Indicadores)
- Cálculos de métricas agregadas en `Calculos` (porcentaje de cumplimiento, sumatorias)
- Clasificación de satisfacción y cumplimiento

### 🔸 3. **Carga**
- Visualización en la hoja `Dashboard` con:
  - Gráficos de velocímetro
  - Barras de cumplimiento
  - Tarjetas numéricas
  - Segmentadores de filtros

---

## 🛠️ Herramientas Utilizadas

- Microsoft Excel (Tablas dinámicas, Segmentadores, Gráficos personalizados)
- Power Query (opcional para transformación avanzada)
- Formato visual limpio y directo para toma de decisiones ejecutivas

---

## 👩‍💼 Autor

**Geraldin Carriazo**  
🔗 [LinkedIn](https://www.linkedin.com/in/geraldin-carriazo/)  
📧 geraldincarriazo09@gmail.com  

---


