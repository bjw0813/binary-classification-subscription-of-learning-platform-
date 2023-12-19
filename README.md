# 학습 플랫폼 이용자 구독 갱신 예측 해커톤
DACON의 학습 플랫폼 이용자의 구독 갱신 여부를 예측하는 AI 알고리즘 개발에 대한 코드입니다.


데이터 출처: https://dacon.io/competitions/official/236179/overview/description


결과: 상위 25%
마지막 test셋 예측하는 과정에서 데이터셋을 표준화할때 fit_transform으로 잘못 입력하였습니다. test셋은 학습셋 결과물을 가지고 예측해야 하므로 transform이 맞습니다. 
