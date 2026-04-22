# bigdata-test-prep
빅데이터 분석기사 준비를 위한 저장소
# 📊 빅분기 실기 준비

## 📌 목표

* 빅데이터 분석기사 실기 대비 (1유형 / 2유형 / 3유형)
* 코랩 기반 실습

## 📂 구성

* `colab/type1/` : 데이터 처리 및 계산 문제
* `colab/type2/` : 머신러닝 문제
* `colab/type3/` : 통계 및 가설검정
* `data/` : 데이터셋
* `output/` : 결과 파일
* `practice/` : 핵심 코드 정리

## 🛠 사용 기술

* Python
* Google Colab
* Pandas, Numpy
* Scikit-learn

## ✨ 진행 내용

* [ ] type1 정복
* [ ] type2 모델링
* [ ] type3 통계

## Github와 Colab 연결
https://velog.io/@shong676/Colab%EA%B3%BC-GitHub-%EC%97%B0%EB%8F%99%ED%95%98%EA%B8%B0

```
from google.colab import drive
drive.mount('/content/drive')
```

### Google Drive 접근
```
from google.colab import drive
drive.mount('/content/drive')
```
### Commit을 원하는 폴더로 이동
```
cd /content/drive/MyDrive/bigdata-test-prep
```

### 본인임을 확인
```
!git config --global user.email 'yangseoeun3462@gmail.com'
!git config --global user.name 'Yangseoeun'
```

### 폴더 add
```
!git add 원하는 폴더명
```

### 폴더 내에 모든 파일을 commit하고 싶은 경우
```
add -all
```

### commit하기
```
!git commit -m '원하는 아무 메시지'
!git push
```
