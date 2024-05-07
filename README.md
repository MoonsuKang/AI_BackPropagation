# Introduction to Artificial Intelligence - BackPropagation
하이퍼파라미터를 튜닝하고, 신경망 구조를 변경하여 훈련/테스트 정확도를 높이는 것이 목적

# 조건

   반복 횟수는 10000 번  

   learning_rate = ( 0.001 ~ 0.019 사이 ) 

   hidden_size = (  5 ~ 15 사이 ) 

   Affine 계층을 반드시 늘려야 함 (현재 2층이므로 3층 이상, 계층 추가는 제한 없음) 

   % 조건에 해당하지 않는 셋팅을 한 경우 감점 처리 ( 각 -1점, Affine 계층 : -2점) 

   #
   
  학습한 후에 훈련 정확도와 테스트 정확도가 각각 최소 95% 이상 되도록
   
