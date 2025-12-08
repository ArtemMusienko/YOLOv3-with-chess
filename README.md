![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)![YOLO](https://img.shields.io/badge/YOLO-111F68?style=for-the-badge&logo=yolo&logoColor=white)

## YOLOv3 with chess

В данном коде используется модель **YOLOv3** для детектирования шахматных фигур на шахматных досках. Более подробное описание архитектуры данной модели представлено в самом **Google Colab** файле.

В качестве датасета используется [этот](https://storage.yandexcloud.net/academy.ai/CV/chess_yolo.zip). Структура файла `data.yaml` в представленном архиве: 

    path: ../chess_yolo
    train: train/images
    val: valid/images
    test: test/images

Названия меток:

    names: 
      0: слон
      1: черный слон
      2: черный король
      3: черный конь
      4: черная пешка
      5: черный ферзь
      6: черная ладья
      7: белый слон
      8: белый король
      9: белый конь
      10: белая пешка
      11: белый ферзь
      12: белая ладья

В финальной части кода демонстрируется работа модели в виде выполнения предсказаний на **4** случайных изображениях.

    Настоятельно рекомендую использовать графический ускоритель T4 
    в Google Colab для запуска этого кода!
