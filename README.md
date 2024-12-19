# 🚀 Proyecto de Detección de Fraude en Tarjetas de Crédito 💳  

## 📋 **Objetivo del Proyecto**  
Este proyecto forma parte del **Programa de Aprendizaje Basado en Proyectos en Inteligencia Artificial | IBM SkillsBuild y SkillUp Online**. El principal objetivo fue **desarrollar un modelo de Machine Learning para detectar fraudes** en transacciones bancarias.  

---

## 🛠️ **Desafíos y Técnicas Utilizadas**  
Durante el desarrollo del proyecto, **enfrenté varios desafíos**, entre los cuales destacaron:  
1. **Datos desbalanceados** entre transacciones fraudulentas y no fraudulentas.  
2. **Tiempo limitado** debido a las restricciones de recursos de Google Colab con la licencia gratuita.  

### ✅ **Técnicas Aplicadas**  
Para superar estos desafíos, apliqué las siguientes técnicas:  
- **Limpieza de Datos**: Traté valores nulos y eliminé columnas irrelevantes.  
- **Generación de Nuevos Datos**: Utilicé **SMOTE** para balancear la base de datos y asegurar una representación equitativa de fraudes y no fraudes.  
- **Selección de Características**: Reduje la complejidad del modelo filtrando atributos poco relevantes.  
- **Hiperparametrización Automática**: Ajusté los parámetros de cada modelo para **evitar sobreajuste**.  
- **Evaluación de Modelos**: Utilicé métricas como **Recall, Precision, F1-Score, Accuracy y AUPRC** para evaluar el rendimiento.  

---

## 🤖 **Modelos Probados**  
Durante el proyecto, probé diversos algoritmos y evalué su desempeño para elegir la mejor solución:  

1. **XGBoost**  
   - Es un modelo basado en árboles de gradiente optimizado, ideal para clasificación.  
   - **Ventaja**: Gran rendimiento y excelente manejo de datos desbalanceados.  
   - **Resultado**: Fue el modelo ganador del proyecto 🏆.  

2. **CatBoost**  
   - Facilita el manejo automático de variables categóricas.  
   - Se caracteriza por su rapidez y eficiencia en grandes volúmenes de datos.  

---

## 🏆 **Modelo Final Seleccionado**  
El modelo **XGBoost** optimizado, utilizando **Validación Cruzada SIN SMOTE**, fue seleccionado por:  
- **Recall**: 89.19%  
- **Precision**: 94.29%  
- **AUPRC**: 95.20%  
- **F1-Score**: 91.67%  
- **Accuracy**: 99.97%  

📊 Comparación de modelos:  
![Comparación de Modelos](informe_final.pdf)

---

## 📝 **Generación Automática de Informes**  
Al final del cuaderno, el proyecto genera automáticamente un **informe en formato PDF** con los resultados más relevantes y detallados. Este informe se descarga directamente al ordenador.

---

## 📦 **Exportación del Modelo**  
Exporté el modelo final en **formato .pkl** para facilitar su uso futuro. Además, almacené:  
- Los **parámetros optimizados** de cada modelo.  
- Información sobre las técnicas utilizadas en el proceso.  

De esta manera, puedo reutilizar o ajustar el modelo de forma eficiente en nuevos contextos.

---

## 🚀 **Trabajos Futuros**  
Si bien el proyecto alcanzó los objetivos propuestos, existen oportunidades para agregar más valor:  

1. **Desarrollo de una Aplicación Web**:  
   - Implementar el modelo en producción utilizando **Flask** o **Streamlit**.  
   - Crear una interfaz simple para que los usuarios puedan evaluar transacciones en tiempo real.

2. **Optimización Adicional de Hiperparámetros**:  
   - Probar métodos avanzados como **Grid Search**, **Random Search** o **Bayesian Optimization** para mejorar aún más el modelo.

3. **Monitoreo Continuo del Modelo**:  
   - Implementar un sistema de seguimiento que evalúe el rendimiento del modelo a lo largo del tiempo y permita ajustes automáticos.  

4. **Incorporación de Nuevos Algoritmos**:  
   - Probar otros algoritmos como **LightGBM** o **Redes Neuronales** para comparar resultados.

---

## 🤝 **Colaboración**  
Este proyecto es solo el comienzo y me encantaría seguir desarrollándolo. Si estás interesado en colaborar, proponer mejoras o explorar nuevas ideas, **¡no dudes en contactarme!**  

📧 **Correo**: erikaalvares@ejemplo.com  
🌐 **LinkedIn**: [LinkedIn de Erika Alvares](https://www.linkedin.com)  

---

**¡Gracias por tu interés en este proyecto! 😊**  

