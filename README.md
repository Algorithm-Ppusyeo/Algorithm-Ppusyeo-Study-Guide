# **Algorithm Ppusyeo Study Guide 📚**

**알쓰(알고리즘 쓰터디)들의 알고리즘 뿌셔!!!!!!!!!!** 운영 가이드입니다!

---

## **👥 Collaborator**
| | | | |
|:---:|:---:|:---:|:---:|
| <img src="https://github.com/str-leshs.png" width="120" height="120"/> | <img src="https://github.com/2sseul.png" width="120" height="120"/> | <img src="https://github.com/baeksohyun12.png" width="120" height="120"/> | <img src="https://github.com/Hwangyerin.png" width="120" height="120"/> |
| [@str-leshs](https://github.com/str-leshs) <br> **Java** | [@2sseul](https://github.com/2sseul) <br> **Java, Python** | [@baeksohyun12](https://github.com/baeksohyun12) <br> **Java** | [@Hwangyerin](https://github.com/Hwangyerin) <br> **JavaScript** |

---

## **🚀 GOAL**
- 꾸준한 알고리즘 문제 풀이 습관 형성
- 코드 리뷰를 통한 사고력 확장

---

## **🤝 Rules**
1. 각자 **개인 전용 레포지토리**(`Algorithm-Study-이름`)에서 풀이 진행
2. 최소 **3일에 1문제** 문제 풀이 후 PR 생성
3.  **문제 카테고리별 디렉토리**에 풀이 업로드   
   ex)<br> 
   `/stack/boj_1874.java`<br>
   `/math/boj_17427.py`<br>
   `/greedy/boj_1931.js`
4. 풀이 후 **Pull Request(PR)** 작성 (풀이 설명, 복잡도 분석 필수)
5. 다른 팀원의 레포에 방문해 **PR 리뷰 주 2회 이상** 작성

---

## **🌿 Branch Rule**
- 브랜치 네이밍: `session{차시}/{이름}`<br>
  ex) session1/eunseo
- 같은 차시 내 여러 문제 풀이 시: `session{차시}/{이름}-{카테고리}`  <br>
  ex) session1/eunseo-stack, session1/eunseo-math
- 메인 브랜치: `main` (풀이 기록 보관)  
- 작업 흐름:
```bash
git checkout -b session1/eunseo
# 코드 작성
git add .
git commit -m "feat: [스택] BOJ 1874 문제 풀이 (Java)"
git push origin session1/eunseo-stack
```
---

## **🌟 Convention Rule**
### ✅ 플랫폼
  - [BOJ] - 백준
  - [PGS] - 프로그래머스
  - [LTC] - 리트코드
  - [ETC] - 그외 <br><br>
### 💾 Commit
- feat: [카테고리] {플랫폼} 문제 풀이 (언어) 
- fix: [카테고리] {플랫폼} 코드 수정 
- docs: README 업데이트
<br><br>
### 🔀 Pull Request
- 형식: `[SessionN] 이름 [플랫폼] 문제 풀이` <br>
   ex) `[Session1] eunseo [BOJ] A+B 문제 풀이` <br>
     
    
  본문 구성 예시:
  ```markdown
  ## 📝 문제
  - 번호 및 이름 (링크 포함)

  ## 💡 풀이 아이디어
  - 접근 방법 설명

  ## ⌛ 복잡도
  - 시간 복잡도:
  - 공간 복잡도:

  ## 📌 코드
  ```코드블록

---

## **📝 Record**

| 차시 | 날짜       | 문제 유형   | 문제 | 풀이 링크 |
|-----|-----------|-----------|----------------|-----------|
| 1차시 | 2025-09-05 | 스택       | [올바른 괄호](https://www.acmicpc.net/problem/9012) | PR #3 |
| 2차시 | 2025-09-08 | 큐         | [요세푸스 문제](https://www.acmicpc.net/problem/1158) | PR #7 |
| 3차시 | 2025-09-12 | 수학       | [한수](https://www.acmicpc.net/problem/1065) | PR #11 |
| 4차시 | 2025-09-15 | 정렬       | [국영수](https://www.acmicpc.net/problem/10825) | PR #15 |
| 5차시 | 2025-09-19 | 그리디     | [회의실 배정](https://www.acmicpc.net/problem/1931) | PR #20 |

> 실제 스터디가 진행되면 **문제 유형별 디렉토리에 풀이 코드 업로드** + **README 기록 테이블 업데이트** 방식으로 관리합니다.

### 📝 Record Template

| 차시 | 날짜       | 문제 유형   | 문제 | 풀이 링크 |
|-----|-----------|-----------|----------------|-----------|
| N차시 | YYYY-MM-DD | 카테고리 | [문제 이름](문제 링크) | PR # |
> 레파지토리 **리드미 파일에 해당 템플릿 추가** 후 PR시 수정하여 관리합니다. 