![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)![YOLO](https://img.shields.io/badge/YOLO-111F68?style=for-the-badge&logo=yolo&logoColor=white)

## YOLOv3 with chess

[![ru](https://img.shields.io/badge/README_на_русском-2A2C39?style=for-the-badge&logo=github&logoColor=white)](README.ru.md)  

This code uses the **YOLOv3** model, which is built from scratch to detect chess pieces on chess boards. A more detailed description of the model's architecture can be found in the **Google Colab** file.

The dataset used is [this one](https://storage.yandexcloud.net/academy.ai/CV/chess_yolo.zip). The structure of the `data.yaml` file in the provided archive is as follows:

    path: ../chess_yolo
    train: train/images
    val: valid/images
    test: test/images

Label names:

    names:
    
    0: bishop
    1: black bishop
    2: black king
    3: black knight
    4: black pawn
    5: black queen
    6: black rook
    7: white bishop
    8: white king
    9: white knight
    10: white pawn
    11: white queen
    12: White Rook

The final part of the code demonstrates the model's work by making predictions on **4** random images of chess boards.

> I strongly recommend using a **T4 graphics accelerator** or more powerful to run this code!