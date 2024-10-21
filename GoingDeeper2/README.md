
# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 진민준
- 리뷰어 : 박형철


# PRT(Peer Review Template)
- [O]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
    - https://github.com/ParkHyoungChul/AIFFEL_quest_rs_minjoon/blob/master/GoingDeeper2/seq2seq_project.ipynb.ipynb
    - 한국어 전처리를 잘 진행함
    - <img width="518" alt="image" src="https://github.com/user-attachments/assets/d2e4e4ac-4361-48bd-9a50-e85a416f3a8d">
    - 코드가 정상 구현됨
    - 학습시간이 길어서 아직 번역 결과가 나오지는 않음

- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
    - <img width="371" alt="image" src="https://github.com/user-attachments/assets/486a9327-5fb6-4408-8b41-f46e83b73d4f">
    - 데이터를 불러오는 파트에 주석을 잘 달아놨다

- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
    - 실험 자체가 길게 진행되고있어서 그부분을 디버깅하고 기다리는데 시간을 쓰고계신듯하다.
    - 추가 실험을 진행할계획    
- [X]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
    - 시간 부족으로 회고 작성은 못한듯 합니다.
    - 학습이 끝난 이후 회고를 잘 작성해주실것같습니다    
- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
    - <img width="461" alt="image" src="https://github.com/user-attachments/assets/196eb3c7-7ed0-410a-93f1-3b96768221cf">
    - 모델 설계를 노드에서 처럼 클래스 단위로 잘 코딩해주셨습니다


# 회고(참고 링크 및 코드 개선)
```
학습시간이 엄청나게 길게 잡히시는 민준님..! 고생하십니다.
데이터를 28,000개 정도 사용을 하셨네요
LMS말고 개인 컴퓨터 CPU로 사용해서 학습을 진행하시는건가요?
정서연님이 데이터가 60,000개 정도였는데 LMS서버로 한 에포크당 10분정도 걸리셨다고 합니다!
다음에는 LMS도 사용해보는것도 추천드림다 !
```
