# 🏨 호텔 예약 취소 여부 예측 프로젝트
### [프로젝트 결과 보고서](https://github.com/sseoyun/predicting_hotel_reservation_cancellation/blob/main/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%20%EA%B2%B0%EA%B3%BC%20%EB%B3%B4%EA%B3%A0%EC%84%9C.pdf)

<br>

## 📅 진행 일정
### 2022.11.22~2022.11.29


<br>

## ✍ 프로젝트 소개 및 진행방법
### 소비자가 호텔 예약을 취소할 지 실제 이용할 지를 예측 > 이진 분류 

<br>

- 결측치 찾고 해결방안 생각하기
- 인코딩 방안 생각하기
- 타겟변수의 분포 확인하기
- 개별 변수들 사이의 상관관계 파악하기
- 개별 변수들의 분포 확인하기
- 개별 변수들과 타겟 변수사이의 관계 파악하기
- 존재하는 변수들로 새로운 변수 만들기

<br>

## 🛠 기술 스택

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white">
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=Jupyter&logoColor=white">
  <img src="https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=Numpy&logoColor=white">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=Pandas&logoColor=white">
</p>



<br>

## 🔎 진행하면서 아쉬웠던 점 및 배웠던 점
결과적으로 예측한 취소 여부의 정확도는 다른 팀에 비해 낮은 수준이었다.  팀별로 사용했던 model은 비슷했기 때문에 modeling과정은 다들 비슷했다.  전처리와 변수 선택 과정에 있어서 옳지 않은 판단을 한 것 같다. 결측치가 많은 변수에서 결측치를 0으로 대체했던 것과 여러 인코딩 방법중 target 인코딩을 사용했던 것이 문제인 것 같다. 모델의 성능만을 높이는 데에만 집중하다보니 전처리 과정을 놓친것 같다. 이 데이터는 특히 변수가 많기 때문에 변수 선택에 있어서 target 변수간의 중요도를 잘못판단 했을 수 있다는 생각을 했다.  변수 중요도를 EDA를 통해 확인했지만 다중공선성의 문제도 생각해봐야한다. 

<br>

👉 내가 생각한 해결 방법 : 변수 줄이기, 다른 인코딩 방법 사용해보기, 결측치를 0말고 데이터를 더 보존할 수 있는 값으로 대체 해보기…


<br>

