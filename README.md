# 📊 Proyecto 2: Perfil demográfico de personas con limitación de locomoción 

## 🎯 Objetivo del análisis  
Este proyecto busca identificar y analizar la distribución de personas con **discapacidad motora** en el Perú, con el fin de:  

- Reconocer **zonas prioritarias** donde implementar soluciones tecnológicas como exoesqueletos, apps de asistencia y ayudas mecánicas.  
- Facilitar la **formulación de proyectos** que atiendan necesidades reales de la población con discapacidad.  
- Proveer **visualizaciones interactivas** que permitan explorar los datos de manera clara y accesible.  

---

## 📂 Columnas clave utilizadas (según el diccionario de datos)  
- **DomDepartamentoIns** → Departamento de domicilio de la persona inscrita.  
- **LimLocomocion** → Variable que indica si la persona presenta discapacidad motora.  
- **IdRegistro** (generado artificialmente) → Usado para contar registros únicos en el análisis.  
- **Edad** → Edad de la persona registrada.  
- **Genero** → Sexo/género declarado.  
- **EstadoCivil** → Estado civil de la persona.  
- **EducaNivelResum** (actualización) → Nivel educativo alcanzado.  

---

## 📈 Visualizaciones generadas  

🔹 **Distribución por Edad**  
🔗 [Ver gráfico](./graficos/grafico_distribucion_edad.html)  

🔹 **Distribución por Género**  
🔗 [Ver gráfico](./graficos/grafico_Distribución_por_Género.html)  

🔹 **Distribución por Estado Civil**  
🔗 [Ver gráfico](./graficos/grafico_Distribución_por_Estado_Civil.html)  

🔹 **Distribución por Nivel Educativo**  
🔗 [Ver gráfico](./graficos/grafico_Distribución_por_Nivel_Educativo.html)  

🔹 **Top 10 Departamentos con mayor número de personas con discapacidad motora**  
🔗 [Ver gráfico](./graficos/top10_departamentos.png)  

🔹 **Distribución total de personas con discapacidad motora en todos los departamentos del Perú**  
🔗 [Ver gráfico](./graficos/distribucion_total.png)  

---

## 🗂️ Fuente de datos y herramientas utilizadas  

- **Fuente de datos:**  
  Los registros provienen de la plataforma:  
  🔗 [Datos Abiertos del Estado Peruano](https://www.datosabiertos.gob.pe/)  

---

### 🛠️ Herramientas utilizadas
 
  - **Python 3**  
  - **Jupyter Notebook** (ejecución del análisis en `PortafoloCaso2.ipynb`)  
  - Librerías de análisis de datos:  
    - `pandas` → limpieza, filtrado y agrupamiento de datos  
    - `numpy` → cálculos y operaciones numéricas  
  - Librerías de visualización:  
    - `matplotlib` → generación de gráficos  
    - `seaborn` → visualizaciones estadísticas más estilizadas  
    - `plotly` → gráficos interactivos en HTML
---
### 👩‍💻 Sobre el análisis
La limitación de locomoción es más frecuente en personas de entre 40 y 70 años, con un pico alrededor de los 60 años. En cuanto al género, los hombres representan la mayoría de los casos con un 57.9%, superando a las mujeres. Respecto al estado civil, la mayoría son solteros, con un 73.9%, y en términos de nivel educativo, predominan aquellos con educación no especificada o nula, lo que indica que esta población presenta en su mayoría bajos niveles de escolaridad.
