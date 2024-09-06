# 📈 SOL 학생 로드맵

> 💡 선후배 연결을 통한 고객의 취업과 재산 관리를 해주는 SOL 학생 로드맵 서비스 입니다.

<p align = "center" >
  <b>
  🏆 신한은행 해커톤 <span style="background-color: #0000ff">최우수상</span>
  </b>
</p>
<p align = "center" >
  <img width="600" src="https://github.com/user-attachments/assets/50abfd91-4142-49f5-91a0-7066c210b992">  
</p>

<br />

## 📌 주요 기능

> 학생, 직장, 은퇴, 타사 정보 등 **분절된 Data**를 플랫폼으로 통합하여 동문 선배의 학습 경험 **포트폴리오**와 재산축적 과정의 **모범 금융 로드맵** 제공

### Func1. 학업 포트폴리오
<p align = "center" >
  <img width="600" src="https://github.com/user-attachments/assets/9bb4c24a-e708-4097-855b-0bc833c231bb">  
</p>
<br />

### Func2. 모범 금융 로드맵 제공 및 AI 피드백
<p align = "center" >
  <img width="600" src="https://github.com/user-attachments/assets/e22bc6f1-1e00-4d56-863d-fb61bb7e401f">
</p>

<br />

## 📅 개발 진행 방식

### WBS 일정관리
<p align = "center" >
  <img width="500" src="https://github.com/user-attachments/assets/fa8ed1c4-da34-40d2-bb21-7d17137eaded">  
</p>

### KPT 회고
> Keep, Problem, Try로 매일 일지를 작성하며 진행 상황을 공유했습니다.

#### FE 회고

```
● Keep
- 로그인 API 연결했습니다.
- 로그인에 따른 페이지 렌더링 로직 구현했습니다.
- 메인페이지에 과거 전체 자산 분석 그래프 추가했습니다.

URL : https://github.com/team-conSOLtant/Frontend/issues/28

● Problem
- 로그인 API 연결시 401에러 해결에 어려움을 겪었습니다.
- 로그인 성공과 실패에 따른 다른 화면 렌더링 로직을 분리하는데에 어려움이 있었습니다.

● Try
- 로그인 데이터를 form 형식으로 보내는 과정에서 데이터 전달이 잘 되지 않는 부분을 찾아 내어 해결했습니다.
(중괄호의 유무 문제)
- 로그인 성공시 들어오는 promise내의 true와 false의 값에 따라 다른 로직 실행하도록 구현했습니다.
- 로그인 성공시 상단바의 메뉴가 로그인이 아닌 프로필 이미지가 나오며 드롭다운 메뉴가 나오도록 구현했습니다.
```

#### BE 회고
```
● Keep
메인 페이지에서 사용하는 API를 개발하고 있습니다.
- 메인 페이지 정보 제공 API

URL : https://github.com/team-conSOLtant/Backend/issues/6

● Problem
금융 API가 필요한 부분이 많아서 개발이 지연되고 있습니다.
정보 전달에 필요한 API 개수가 많아서 컴포넌트 단위로 API를 호출 시
네트워크 지연이 얼마나 발생하는지 검증하고 있습니다.

● Try
RestTemplate을 활용하여 금융 API를 모듈화하겠습니다.
```

<br />

## 🌈 TEAM_ 컨SOL턴트

| 이름   | 역할      | Github                        | 구글 ID                  |
| ------ | --------- | :---------: | ------------------------ |
| 고다현 | 팀장 / BE / FE   | <a href="https://github.com/dahyunko" target="_blank"><img src="https://img.shields.io/badge/dahyunko-181717?style=flat-square&logo=github&logoColor=white"/> </a>    | dahyunbless@gmail.com   |
| 김준우 | FE | <a href="https://github.com/rlawnsdn" target="_blank"><img src="https://img.shields.io/badge/rlawnsdn-181717?style=flat-square&logo=github&logoColor=white"/> </a>    | junoo1997@naver.com   |
| 지수영 | FE | <a href="https://github.com/SooYoungJi" target="_blank"><img src="https://img.shields.io/badge/SooYoungJi-181717?style=flat-square&logo=github&logoColor=white"/> </a> | jisooyoung97@gmail.com   |
| 박상욱 | BE | <a href="https://github.com/sw0501" target="_blank"><img src="https://img.shields.io/badge/sw0501-181717?style=flat-square&logo=github&logoColor=white"/> </a>    | dkxkqkrtkddn@gmail.com   |
| 이동열 | BE | <a href="https://github.com/DDongYul" target="_blank"><img src="https://img.shields.io/badge/DDongYul-181717?style=flat-square&logo=github&logoColor=white"/> </a>    | comeme0101@naver.com   |


<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
