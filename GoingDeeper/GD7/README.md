# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 원균재
- 리뷰어 : 임정민


# PRT(Peer Review Template)
- [X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
          <img width="1769" height="1259" alt="image" src="https://github.com/user-attachments/assets/4b07b4b1-42e6-47f2-857a-283fdd848d42" />
          <img width="1806" height="1313" alt="image" src="https://github.com/user-attachments/assets/dd9dd132-df05-4b61-ab92-9af4eef962ae" />
          <img width="1798" height="331" alt="image" src="https://github.com/user-attachments/assets/b6847c59-398a-4061-9f72-c36d483f2a75" />
          - 학습 횟수마다 Loss와 Accuracy를 잘 나타내 주셨습니다. 학습률이나 Epoch를 조금 증가시키면 Loss가 더 많이 줄어들지 않을까 생각합니다. 


- [X]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img width="1514" height="1068" alt="image" src="https://github.com/user-attachments/assets/b0bc2e59-2876-4626-ad3c-1e87b769d2ea" />
          <img width="1447" height="169" alt="image" src="https://github.com/user-attachments/assets/b97e34d4-6c51-46a7-88fb-b9f36fe8140d" />
          모델 안에 있는 레이어들이 어떤 순서로 연결돼 있는지, 각 레이어의 출력 텐서 크기와 파라미터 수를 트리 형태로 보여주셨습니다. 모델 구조와 자원 소모량에 대해 알 수 있었습니다.


- [X]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img width="1326" height="972" alt="image" src="https://github.com/user-attachments/assets/73a4ca9a-f0dd-465f-bbba-5fa08e82268b" />
          다른 기수 분께서 이전에 진행한 내역을 바탕으로 실험을 진행하면서 인사이트를 얻고자 했습니다.


- [X]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img width="1768" height="1199" alt="image" src="https://github.com/user-attachments/assets/12da11e4-31b2-45de-87a7-c5df222d0261" />
          더 많은 실험을 진행하지 못해 아쉽다고 리뷰 시간에 말씀해 주셨습니다. 학습 결과를 그래프로 시각화하여 깔끔하게 표현했습니다.


- [X]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img width="1780" height="778" alt="image" src="https://github.com/user-attachments/assets/f6fe9991-6f00-4f1f-9eac-79eedd3fe7ec" />
          <img width="1895" height="639" alt="image" src="https://github.com/user-attachments/assets/0f55e86e-7dfa-4ac4-9072-1462f611daa4" />
          노드에 안내된 바와 같이 GELU 함수 등을 모듈화하여 구현했습니다.


# 회고(참고 링크 및 코드 개선)
```
https://github.com/mrsys/NLP_Going_Deeper/blob/main/NLP_Project_7.ipynb

공유해주신 실험 레퍼런스를 통해 실험 보고서를 어떻게 해야 잘 작성할 수 있는지 알 수 있었습니다.
실험 레퍼런스처럼 실험 결과뿐만 아니라 해당 기법의 정의와 사용 목적 등에 대해서도 작성하는 것이 좋다는 것을 깨달았습니다.
프로젝트 이후에 추가 실험을 진행하셔도 좋을 것 같습니다. 고생 많으셨습니다!
```

