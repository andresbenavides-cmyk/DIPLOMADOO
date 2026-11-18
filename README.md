# ⚡ Proyecto Integrador: Energía Circular Inteligente 5.0
**Diagnóstico Energético, Línea Base ISO 50001, Pronóstico con Deep Learning y Transición Solar Fotovoltaica en una Finca Rural**

**Autores:** Andrés Felipe Benavides y Cristhian Vente  
**Institución:** Corporación Universitaria Comfacauca (Unicomfacauca)  
**Programa:** Diplomado en Energía Circular Inteligente 5.0  
**Ubicación del caso de estudio:** Vereda Cuatro Esquinas, El Tambo (Cauca), Colombia.

---

## 📖 Descripción del Proyecto
Este repositorio contiene el código fuente, los datos, los modelos de inteligencia artificial y los entregables del proyecto integrador de opción de grado. El objetivo principal fue resolver la problemática de los sobrecostos tarifarios en una vivienda rural mediante la implementación de un sistema de monitoreo IoT de bajo costo, analítica avanzada (Machine Learning/Deep Learning) y el diseño de una solución de autogeneración solar.

A través de la medición empírica (2,880 registros durante 30 días), se estableció una línea base energética bajo la norma **NTC-ISO 50001:2018** y se formuló una cartera de medidas de eficiencia y un sistema fotovoltaico **AGPE de 1.32 kWp** bajo la **Resolución CREG 174 de 2021**, logrando una reducción proyectada del 47.8% en la huella de carbono.

---

## 🗂️ Estructura del Repositorio

*   `📓 DIPLOMADO_FINAL.ipynb`: Cuaderno de Jupyter/Colab con el pipeline de datos, la auditoría de Data Leakage, el clustering K-Means 3D, la red recurrente (LSTM) y los modelos densos (Keras MLP).
*   `📊 mediciones_finca_30dias.csv`: Dataset original con 2,880 registros capturados cada 15 minutos (Tensión RMS, Corriente, Potencia Activa, Factor de Potencia).
*   `📱 app.py`: Código fuente del Dashboard interactivo (desarrollado en Gradio o Streamlit) que integra el simulador *What-If* y el tacómetro de demanda.
*   `🧠 /modelos/`: Carpeta que contiene los modelos entrenados exportados (`.h5` para Keras, `.pkl` para K-Means).
*   `🤖 /rag_local/`: Configuración del Asistente RAG Local. Incluye los documentos indexados y las instrucciones para ejecutarlo con AnythingLLM/Ollama.
*   `📄 /documentos/`: Memorias técnicas en formato PDF de los 7 módulos y la monografía final.

---
