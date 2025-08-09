
## Primeros pasos

Asegúrate de tener **conda** disponible en tu terminal y ejecuta el siguiente comando para crear el entorno de desarrollo con las dependencias.

```bash
conda env create -f environment.yml
```

Luego agrega en el root del proyecto la carpeta **input_images** y dentro agrega las imágenes que contengan los rostros a detectar.

Finalmente activa el entorno de conda y ejecuta en programa:

```bash
conda activate face-recognition
python f_recognition.py
```

## Funcionamiento

- Las imágenes de los rostros a detectar se cargan en la carpeta **input_images**, las imágenes pueden tener varias personas
- **extracting_faces.py**: El algoritmo reconoce un conjunto de rostro enumerándolos de 0 a n según la cantidad de rostros detectados guardándolos en la carpeta **detected_faces**.
- **f_recognition.py** se encarga de correr el algoritmo para detectar rostros y generar un archivo .txt con las coincidencias encontradas.

## Tareas

- [ ] Modularizar el código. Se puede empezar por extraer la configuraciones básicas como las rutas y el target FPS en un archivo de configuración. Luego hay que corregir la documentación.
- [ ] Aumentar los FPS
- [ ] Agregar una interfaz web que no de vergüenza (####)