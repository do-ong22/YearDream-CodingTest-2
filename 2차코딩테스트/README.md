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