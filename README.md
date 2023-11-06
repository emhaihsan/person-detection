# Person Detection

Data yang diambil untuk pelatihan adalah COCO 3500 yang diambil dari MSCOCO dan hanya khusus pada data yang berisi `person`.

<img src="https://github.com/mhihsan/person-detection/blob/main/img/dataset.png" width="640" />

Link dataset bisa diambil [di sini](https://app.roboflow.com/adalovelace/cocopersondetection/1).

Yang ada di repository ini:

- [COCO3500YOLOv5.ipynb](https://github.com/mhihsan/person-detection/blob/main/COCO3500YOLOv5.ipynb): Notebook untuk melatih YOLOv5 di data kita
- [yolov5coco.pt](https://github.com/mhihsan/person-detection/blob/main/yolov5coco.pt): Weight YOLOv5 yang sudah dilatih di dataset [COCO3500](https://app.roboflow.com/adalovelace/cocopersondetection/1)
- [COCO3500FasterRCNN.ipynb](https://github.com/mhihsan/person-detection/blob/main/COCO3500FasterRCNN.ipynb): Notebook untuk melatih Faster-RCNN di data kita
- [app.py](https://github.com/mhihsan/person-detection/blob/main/app.py): Contoh aplikasi sederhana untuk deteksi orang menggunakan YOLOv5 dengan streamlit

Contoh Hasil Prediksi YOLOv5:

<img src="https://github.com/mhihsan/person-detection/blob/main/img/yolopred.png" width="400" />

Contoh Hasil Prediksi Faster RCNN:

<img src="https://github.com/mhihsan/person-detection/blob/main/img/fasterrcnnpred.png" width="400" />

Tampilan Yolov5 di Streamlit:

<img src="https://github.com/mhihsan/person-detection/blob/main/img/streamlit.png" width="400" />
