# 📉 Análisis de Fuga de Clientes – Telecom X

Este repositorio contiene el análisis exploratorio, descriptivo y estratégico sobre la **fuga de clientes (churn)** en la Empresa Telecom X, dedicada al rubro de telecomunicaciones. El objetivo principal es comprender los factores que influyen en el abandono del servicio por parte de los clientes y proponer acciones que mejoren la retención.

---

## 📂 Contenido del Proyecto

- [`Challenge2_TelecomX.ipynb`](Challenge2_TelecomX.ipynb): Notebook principal de análisis de datos.
- [`Informe_Challenge2_TelecomX.ipynb`](Informe_Challenge2_TelecomX.ipynb): Notebook de presentación e informe final, basado en los hallazgos.
- `/imagenes/`: Carpeta con los gráficos generados.
- `README.md`: Este archivo.

---

## 🎯 Objetivos

- Identificar características y patrones de clientes que abandonan el servicio.
- Determinar factores de riesgo asociados a la fuga.
- Proponer estrategias de retención basadas en evidencia.
- Reforzar la capacidad predictiva del equipo de ciencia de datos.

---

## 🔍 Descripción de los Datos

La base de datos contiene más de 7.000 registros con información como:

- Atributos demográficos (género, edad, dependientes, etc.).
- Servicios contratados (teléfono, internet, streaming, etc.).
- Tipo de contrato y método de pago.
- Cargos mensuales y acumulados.
- Permanencia (tenure) y estado de fuga (Churn).

---

## 🛠️ Herramientas Utilizadas

- **Google Colab**: entorno de desarrollo para análisis y generación de informes.
- **Python (pandas, seaborn, matplotlib)**: procesamiento, análisis y visualización de datos.
- **GitHub**: control de versiones y documentación.
- **Markdown**: documentación en GitHub y celdas de texto enriquecido.

---

## 📊 Resultados Destacados

- La mayoría de las fugas ocurren dentro del primer mes de contrato (**62%**), lo que evidencia la necesidad de fortalecer la fidelización temprana.
- Los clientes senior tienen una tasa de fuga mayor (**41.7%**) comparado con los no senior (**23.7%**).
- El tipo de contrato influye fuertemente en la fuga: contratos mensuales muestran una tasa del **42.7%**, mientras que los de dos años solo un **2.8%**.
- Los clientes que se fugan presentan cargos mensuales más altos (**$74.44 vs $61.31**).
- También se observa que tienen un precio diario promedio más alto (**$2.48 vs $2.04**) y menor dispersión, lo que sugiere una percepción de mayor costo.
- En cuanto al gasto total acumulado, **los clientes con fuga tienden a gastar más que quienes se mantienen**, reforzando el vínculo entre percepción de valor y cancelación del servicio.
- El servicio de Fibra óptica presenta una tasa de fuga del **41.9%**, mientras que DSL y sin internet tienen tasas de **19%** y **7.4%**, respectivamente.


---

## 📈 Recomendaciones

- Incentivar contratos de mayor duración.
- Implementar programas de fidelización temprana.
- Ajustar ofertas a segmentos con alto riesgo.
- Mejorar la experiencia del servicio de fibra óptica.
- Monitoreo continuo y modelado predictivo de fuga.

---

## 🔗 Accesos Rápidos

- 📄 Puedes revisar el informe haciendo clic aquí [🔍 Ver en GitHub](./Informe_Challenge2_TelecomX.ipynb)
---


