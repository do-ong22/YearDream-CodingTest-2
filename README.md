# 코딩테스트

이 프로젝트는 SQL과 Python을 활용한 데이터 분석 실습을 포함하고 있습니다. 각 실습 폴더에는 문제.md와 해설.md 파일이 포함되어 있습니다.

## 프로젝트 구조

- **SQL 실습 (실습 1-8)**: SQL 쿼리 작성 및 데이터 분석
  - NTILE, UNION, DENSE_RANK, JOIN, 서브쿼리 등 SQL 기능 활용
  
- **알고리즘 문제 (실습 9-11)**: 코딩 테스트 유형의 알고리즘 문제 해결
  - 자료구조, 그래프 탐색, 다이나믹 프로그래밍 등 알고리즘 개념 적용
  
- **Python 데이터 분석 (실습 12-20)**: pandas, matplotlib, seaborn 등을 활용한 데이터 분석
  - 데이터 조작, 시각화, 통계 분석 등 다양한 데이터 분석 기법 적용

## 내용

각 실습 폴더는 다음과 같은 파일을 포함합니다:

- **문제.md**: 실습 문제 설명
- **해설.md**: 정답 코드와 설명

## 필요 패키지

필요한 패키지는 requirements.txt 파일에 명시되어 있으며, 다음 명령어로 설치할 수 있습니다:

```bash
pip install -r requirements.txt
```

## 실행 방법

1. Python 3.9 버전을 사용해야 합니다.

2. 가상환경 설정하기 (선택 사항)
   
   > **참고**: 가상환경 설정은 필수가 아닙니다. 패키지 충돌 방지와 환경 격리를 위해 권장되지만, 기존 Python 환경에서 직접 패키지를 설치하여 실행할 수도 있습니다.
   
   ### Windows에서 가상환경 설정
   ```bash
   # 가상환경 생성
   python -m venv venv
   
   # 가상환경 활성화
   venv\Scripts\activate
   ```
   
   ### macOS에서 가상환경 설정
   ```bash
   # 가상환경 생성
   python3 -m venv venv
   
   # 가상환경 활성화
   source venv/bin/activate
   ```

3. 필요한 패키지 설치
   ```bash
   # 활성화된 가상환경에 패키지 설치
   pip install -r requirements.txt
   ```

4. 각 실습 폴더에서 문제.md 파일 참고하여 문제 이해

5. 직접 문제 해결 후 해설.md 또는 나만의_해설.md 파일로 답안 확인 






## Git fork 하는 법
> fork : 다른사람의 저장소(레포지토리)를 내 계정으로 복사하는 의미!!


1. 우측 상단 fork 클릭


![image](https://github.com/user-attachments/assets/4f0dcf54-4bc3-456f-852b-8198b487a875)

2. 본인의 프로필을 선택하고 Create fork 클릭

   
![image](https://github.com/user-attachments/assets/0494b281-555b-45d6-8b20-466e0aa3d896)


3. 짠! 그럼 내 Github 레포지토리에 똑같이 복사가 된다.

<br>

## Git Clone 하는 법
> clone : 저장소(레포지토리)를 내 컴퓨터에서 열 수 있도록 프로젝트를 컴퓨터의 폴더로 복사하는 의미!!

1. Code를 누른 후 HTTPS 경로를 복사한다.

![image](https://github.com/user-attachments/assets/0b4fe028-8f73-4cbb-8f36-e5bdeffe06e1)


2. vscode (IDE)에서 터미널을 열어준다.

![image](https://github.com/user-attachments/assets/4d520e98-5ee5-49b6-9b0d-bbb4c47f18f4)


3. 아래 명령어를 실행한다.

```
git clone https://github.com/Onesoonduck/yeardream-codingtest.git
```
- 이때 뒤에 나오는 경로는 아까 복사했던 HTTPS 경로이다. 


4. 그럼 해당 프로젝트가 열린다!


![image](https://github.com/user-attachments/assets/fe69ee25-a5b1-4445-abc4-48a58bca6150)
