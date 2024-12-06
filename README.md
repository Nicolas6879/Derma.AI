# **Derma.AI**  
![Derma.AI](Banner_Derma_AI.png)  

**Autores:**  
- Juan Nicolás García Vega, Miguel Enrique Quintero Suárez  

---

## **Objetivo**  
**Derma.AI** es una herramienta diseñada para realizar un diagnóstico básico del tipo de acné que padece un paciente, facilitando una evaluación inicial y promoviendo una atención temprana.  

---

## **Video**  
[**Ver el video en YouTube**](https://youtu.be/uThvUOYUAAA) 

---

## **Dataset**  
El proyecto utiliza el conjunto de datos **Acne Grading Classification Dataset** disponible en Kaggle.  
[**Accede al dataset aquí.**](https://www.kaggle.com/datasets/rutviklathiyateksun/acne-grading-classificationdataset)  

---

## **Documentación**  
### **Diapositivas**  
La presentación del proyecto está disponible en el archivo PDF adjunto:  
[📂 **Diapositivas_Derma_AI.pdf**](Diapositivas_Derma_AI.pdf)  

### **Notebook**  
El código y desarrollo del proyecto están documentados en el siguiente archivo Jupyter Notebook:  
[📓 **DermaAI.ipynb**](DermaAI.ipynb)  

---

## **Modelos Utilizados**  
El desarrollo de **Derma.AI** se basa en una combinación de arquitecturas preentrenadas y un modelo propio:  

- **EfficientNetB7**: Transfer learning, pesos congelados, fine-tuning en capas superiores.  
- **ResNet50**: Transfer learning, pesos preentrenados, ajuste específico para clasificación de acné.  
- **Modelo propio**: Arquitectura personalizada, entrenamiento desde cero, optimizada para bajo consumo computacional.  
- **EfficientNetB0**: Transfer learning, pesos iniciales congelados, adaptado para mejorar eficiencia en dispositivos con recursos limitados.  

---
