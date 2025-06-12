# model-training

**블랙박스 영상 기반 교통 법규 자동 신고** 프로젝트에서 사용된  
Object Detection 모델 (`YOLOv8`) 과 OCR 모델 (`TPS-ResNet-BiLSTM-Attn-OCR`) 의  
학습 및 평가용 Jupyter Notebook 파일들을 모아두었습니다.

Notebook File `.ipynb`은 Google Colab에서 실행되었으며,
Google Colab Pro를 이용해 Computing Resource를 활용하여 Train and Test 하였습니다.

- 🗒️`2025_ajou_capstone_YOLO_fune_tuning.ipynb` : 차량(`Car`), 번호판(`Number_Plate`), 교통신호등(`Traffic_Light`) 클래스 검출 모델을 Fine-tuning
- 🗒️`DTRB_ocr_train.ipynb` : 번호판 문자 영역 인식용 OCR 모델 (`TPS-ResNet-BiLSTM-Attn`) 학습  
- 🗒️'helmet_detection_training.ipynb' : 이륜차, 헬멧, 머리, 번호판 클래스 검출 모델을 Fine-tuning
