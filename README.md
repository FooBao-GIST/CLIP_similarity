# FooBao_ImageSimilarity

    conda env create --name food_detection --file environment.yaml

리눅스 환경에서 위의 가상환경을 설치 후 실행

### 1. 음식 detect 학습
YOLOv5_food_detection.ipynb에서 fooddataset파일을 이용하여 일반적인 음식 데이터 학습

### 2. 리뷰 사진 음식만 crop
crop.ipynb에서 학습된 파라미터 exp2를 이용해 datasets/차알/test/ 에 있는 리뷰 이미지 crop하기

### 3. CLIP feature 이용한 cosine 유사도 계산
run.ipynb에서 마지막으로 crop된 이미지들과 메뉴판의 이미지 유사도 비교
