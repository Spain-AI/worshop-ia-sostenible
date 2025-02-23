# Workshop Sostenibilidad IA
Este repositorio contiene notebooks de ejemplos del uso de codecarbon que analiza el coste energético de la inferencia del modelo Phi de Microsoft. El notebook está estructurado de la siguiente manera:
```
- notebooks/
  - 01_MSFT_workshop-sost-ai_codecarbon.ipynb
  - 02_MSFT_workshop-sot-ai_cc-visualize.ipynb
- outputs/
- README.md
```

# Requisitos
Python 3.10 o superior

Librerías especificadas en el notebook (transformers, accelerate, codecarbon, etc.) o en requirements.txt


# Uso
Asegúrese de tener instaladas todas las dependencias necesarias.

Ejecute el notebook workshop_sostenibilidad.ipynb en un entorno de Jupyter.

Siga las instrucciones del notebook para realizar el análisis de consumo energético.

## Notas Adicionales
El notebook está diseñado para funcionar con CPU o GPU. Para usar GPU, asegúrese de especificarlo en los parámetros de configuración.

Los resultados del análisis de emisiones se guardarán en el directorio outputs/.

Para más información sobre el modelo utilizado, visite Phi-3.5-mini-instruct en Hugging Face.