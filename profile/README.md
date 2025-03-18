# "CS 지식 퀴즈"

### 🎏주요 기능
#### 1. 닉네임 입력 후 게임 시작
- 사용자는 **원하는 닉네임**을 입력하여 게임을 시작할 수 있습니다.
- **이미 사용 중인 닉네임**은 사용할 수 없으니 주의!

#### 2. 랜덤한 CS 퀴즈 문제 출제
- 게임을 시작하면 **정보처리기사** 기출 문제들과 **CS 지식** 문제들이 랜덤하게 출제됩니다.
- **문제 유형**: 자료구조, 네트워크, 운영체제, 데이터베이스 등

#### 3. 객관식 문제 및 정답 선택
- 각 문제마다 **4개의 선택지**가 제공됩니다.
- 정답을 선택하면 **즉시** 결과가 반영되며, 점수가 계산됩니다.

#### 4. 점수 시스템
- 난이도 별로 **점수가 다르게** 측정됩니다.**(Easy: 10 / Normal: 20 / Hard: 30)**
- 문제를 맞힐 때마다 **점수가 증가**합니다.
- **오답 시** 점수는 변하지 않습니다.

#### 5. 게임 종료 및 최종 점수 확인
- 정해진 문제 수를 모두 풀면 게임이 **종료**되고, **최종 점수가 표시**됩니다.
- 게임이 종료된 후, **모든 참가자의 순위**를 볼 수 있습니다.

---

### 🎬화면 구성
- 초기 시작
  
    https://github.com/user-attachments/assets/ce1ff58c-d03b-4f2d-8467-91994d91b163

- 게임 진행

    https://github.com/user-attachments/assets/015ffab6-bcc8-4b94-9371-f60e23a90d2a

- 타이머 종료

    https://github.com/user-attachments/assets/d13f44de-2549-4b4e-a29b-6b693ff09d52
- 최종 스코어 및 전체 순위 확인
  
    https://github.com/user-attachments/assets/6f1c96c8-1ff4-4513-b140-e6c1750100d1

---

### 📚STACKS
**FRONTEND**  
<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black">
<img src="https://img.shields.io/badge/vite-646CFF?style=for-the-badge&logo=vite&logoColor=white">

**BACKEND**  
<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white">
<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
<img src="https://img.shields.io/badge/gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white">
<img src="https://img.shields.io/badge/redis-FF4438?style=for-the-badge&logo=redis&logoColor=white">
<img src="https://img.shields.io/badge/caddy-1F88C0?style=for-the-badge&logo=caddy&logoColor=white">
<img src="https://img.shields.io/badge/amazonec2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white">  

**공통**  
<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
<img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white">

---
### 🌠 전체 시스템 아키텍처
![image](https://github.com/user-attachments/assets/cc41e3d4-ca44-4eae-9124-6440cffeec1c)

- 사용자(User)가 **React + Vite**로 개발된 프론트엔드에 접근
- 프론트엔드가 **Caddy(Reverse Proxy & TLS)**를 통해 **Spring Boot 백엔드 API** 요청
- 백엔드는 **MySQL**에서 데이터를 조회/저장하고, **Redis**를 캐싱 레이어로 활용
- 모든 백엔드 관련 서비스(Caddy, Spring Boot, MySQL, Redis)는 **AWS EC2** 내에서 실행

---

### 🐙MEMBER🐹
|<image src="https://github.com/user-attachments/assets/07845cb5-97ea-454e-b79e-3bab41e8c71f" width="80">|<img src="https://github.com/user-attachments/assets/ab400a82-cc18-439a-969d-f9818720975b" width="80">|
|:---:|:---:|
|[AYEOOON](https://github.com/AYEOOON)|[yunadada](https://github.com/yunadada)|
|백엔드|프론트엔드|
