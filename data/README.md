# Documentación de Datos - AgroSmart Predict

## 1. Fuente de datos utilizada
* **Dataset:** `mohanty/PlantVillage`

* **Repositorio:** [Hugging Face - mohanty/PlantVillage](https://huggingface.co/datasets/mohanty/PlantVillage)

* **Acceso:** Público mediante la librería `datasets`de Hugging Face en Python (sin necesidad de API Key)


## 2. Cómo obtener los datos y generar la capa Silver
Por buenas prácticas de versionado, los ficheros CSV completos (`data/raw/` y `data/silver/`) están excluidos en `.gitignore`. Para reproducirlos localmente desde cero:


1. Instalar las dependencias desde la raíz del repositorio:

```bash
pip install -r requirements.txt