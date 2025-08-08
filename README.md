
## Primeros pasos

Asegúrate de tener **conda** disponible en tu terminal y ejecuta el siguiente comando para crear el entorno de desarrollo con las dependencias.

```bash
conda env create -f environment.yml
```

## Funcionamiento

**faceRecognition2** es una carpeta que contiene otra carpeta llamada **input_images** en ella puede tenerse una imagen con varias personas para que luego con **extracting_faces.py**. El algoritmo reconoce un conjunto de rostro enumerándolos de 0 a n según la cantidad de rostros detectados guardándolos en la carpeta faces.

**f_recognition.py** se encarga de correr el algoritmo para detectar rostros y generar un archivo txt con las coincidencias encontradas.

## Tareas

- [ ] Modularizar el código
- [ ] Aumentar los FPS
- [ ] Agregar una interfaz web que no de vergüenza (####)