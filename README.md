**후보군 생성** → **학습 데이터 구축** → **학습 진행** → **테스트 데이터로 후보군 생성** → **후보군 정렬**  

클래스 추출
---
- 전체 후보군 그래프를 구축한 뒤, 유저별 상위 12개 상품을 추출하여 미리 저장한다.  
- 이후 새로운 데이터가 들어오면, 유저별 상위 12개 상품만 추출하여 반환한다.  
- 모델을 사용하는 경우* 에도 전체 후보군을 구축한 뒤 유저별 상위 12개를 추출해 저장한다.  
- 이후 해당 데이터와 실제 미래 데이터를 결합하여 **학습 데이터**를 생성한다.  
- **모델을 학습**한 후 새로운 예측 대상 데이터가 들어오면, 후보군을 모델로 점수화하여 정렬하고 실제 결과와 비교해 정확성을 확인한다.  
---




![Article Recommender Machine Learning - 1](https://github.com/user-attachments/assets/2c2e36d1-1a07-4df5-8192-bddd08de9ecc)
![Article Recommender Machine Learning - 2](https://github.com/user-attachments/assets/071e89fa-3fda-4b10-93f5-6df1dd98f67d)
![Article Recommender Machine Learning - 3](https://github.com/user-attachments/assets/39e8a25d-796a-4e84-8a3c-47063a2012dd)
![Article Recommender Machine Learning - 4](https://github.com/user-attachments/assets/97062929-1937-4833-8845-117bd7e764b8)
![Article Recommender Machine Learning - 5](https://github.com/user-attachments/assets/8be193ac-80e0-4ed7-8988-086fa8951073)
![Article Recommender Machine Learning - 6](https://github.com/user-attachments/assets/1335929a-8ddd-4497-9507-6c7ce49ff070)
![Article Recommender Machine Learning - 7](https://github.com/user-attachments/assets/946750ba-1d8e-4ae9-b2d4-6b62503722d3)
![Article Recommender Machine Learning - 8](https://github.com/user-attachments/assets/409dc205-fbda-4d89-a95b-fb9930cd76f0)
![Article Recommender Machine Learning - 9](https://github.com/user-attachments/assets/dbabb242-b2fd-4df6-9569-bb1109a607ab)





