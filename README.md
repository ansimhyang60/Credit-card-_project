# [새싹 미니프로젝트](https://dacon.io/competitions/official/235713/data)

# 월간 데이콘 신용카드 사용자 연체 예측 AI 경진대회
## 알고리즘 | 정형 | 분류 | 금융 | LogLoss

# 배경
안녕하세요 여러분! 🙌 신용카드 사용자 연체 예측 AI 경진대회에 오신 것을 환영합니다. 

신용카드사는 신용카드 신청자가 제출한 개인정보와 데이터를 활용해 신용 점수를 산정합니다. 

신용카드사는 이 신용 점수를 활용해 신청자의 향후 채무 불이행과 신용카드 대급 연체 가능성을 예측합니다. 

현재 많은 금융업계는 인공지능(AI)를 활용한 금융 서비스를 구현하고자 합니다. 



신용카드 사용자들의 개인 신상정보 데이터로 사용자의 신용카드 대금 연체 정도를 예측할 수 있는 

인공지능 알고리즘을 개발해 금융업계에 제안할 수 있는 인사이트를 발굴해주세요!


# 목적
신용카드 사용자 데이터를 보고 사용자의 대금 연체 정도를 예측하는 알고리즘 개발 

데이터 변수 설명


train.csv

train 데이터 : 신용카드 사용자들의 개인 신상정보
credit 열 포함
train.shape : (26457, 20)


test.csv

test 데이터 : 신용카드 사용자들의 개인 신상정보
credit 열 미포함
test.shape : (10000, 19)


sample_submission.csv

![image](https://github.com/user-attachments/assets/794b59f8-ffa4-405c-9f0f-92b36fa96ef3)
![image](https://github.com/user-attachments/assets/2a01ef84-a724-44da-9336-3f39a6036d92)
![image](https://github.com/user-attachments/assets/3c5fb439-7ac6-4794-a43e-50e59ea85114)
![image](https://github.com/user-attachments/assets/6c81cc71-29a7-4f46-8dfe-64663776232f)
모델 성능비교했을 때 catboost로 높았음
![image](https://github.com/user-attachments/assets/ebbdbd39-3697-4a62-8f11-dcdbfff4ac17)

1. 역할분담
   ![image](https://github.com/user-attachments/assets/f799b66b-6787-4915-87da-c0d8755d303d)





정답 제출 파일
sample_submission.shape :(10000, 4)


![최종모델 cv log score](https://github.com/user-attachments/assets/8304446c-d684-43fe-b80d-81fadfb68c85)



※ 출처:  https://mp.weixin.qq.com/s/upjzuPg5AMIDsGxlpqnoCg
