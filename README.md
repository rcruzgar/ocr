### Procesamiento de documentos para OCR

3 notebooks:

- [1_train.ipynb](https://github.com/rcruzgar/ocr/blob/master/1_train.ipynb): Entrena un modelo de detección de objetos 
para detectar anotaciones y layouts de documentos.

- [2_extract_annotations.ipynb](https://github.com/rcruzgar/ocr/blob/master/2_extract_annotations.ipynb): Extrae las anotaciones predichas por el modelo de detección.

- [3_character_recognition.ipynb](https://github.com/rcruzgar/ocr/blob/master/3_character_recognition.ipynb): Aplica OCR sobre los recortes predichos por el modelo de detección.

3 carpetas:

- Imágenes reales del dataset con sus anotaciones [aquí](https://github.com/rcruzgar/ocr/tree/master/real_images).

- Imágenes predichas por nuestro modelo entrenado [aquí](https://github.com/rcruzgar/ocr/tree/master/predicted_images).

- Recortes predichos sobre los que hacemos el OCR [aquí](https://github.com/rcruzgar/ocr/tree/master/predicted_crops).

