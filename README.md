# :baseball: :email: KBO-Match-Result-Mail-System

## 🖥️ 프로젝트 소개
KBO 경기 결과를 메일로 알려주는 서비스 프로젝트 입니다.

## ⏰ 개발기간
2024.04.01 ~ 2023.04.04
<br>
- 04.01 : 주제 및 기능 선정
- 04.02 ~ 04.04 : 개발

## ⚒️ 기술 스택
![Python versions](https://img.shields.io/badge/python-3.11.8-blue)

## 👨‍💻 팀원
Name|GitHub Address|
|------|---|
|:eagle:배창민|https://github.com/bbmini96|
|:frog:장희권|https://github.com/jang010505|
|:teddy_bear:조성민|https://github.com/EnjoyTime18|

## 💻 역할
| 이름     | 역할                  |
|---------|----------------------|
| :eagle: 배창민 | 이닝 별 정보, 전날 경기 뉴스, 구단 순위  |
| :frog: 장희권  | 선수별 순위{(타자:타율별, 안타, 홈런, 타점, 주루), (투수: 평균자책점, 승리, 삼진)} |
| :teddy_bear: 조성민 | 전날 경기 기록 및 박스 스코어, 오늘 경기 일정   |

## 💻 주요 기능 소개
- 원하는 구단별 경기 기록을 받아볼 수 있습니다.
  - 원하는 정보만 받아볼 수 있습니다.
- 전날 구단별 순위 및 선수 순위를 받아볼 수 있습니다.
- 매일 오전8시 결과를 메일로 알려줍니다. (경기가 있는 날)

## 📂 Project Structure

```sh
- src
│ main.py
│
├─controller
│      KBOController.py
│      MatchController.py
│      PlayerController.py
│      TeamInfoController.py
│
├─domain
│      BoxScore.py
│      Hitter.py
│      News.py
│      Pitcher.py
│      ScoreBox.py
│      TeamRank.py
│      T_Game.py
│      Y_Game.py
│
├─utils
│  │  HTMLChanger.py
│  │  Mail.py
│  │  PlayerSort.py
│  │  SleepTime.py
│  │
│  └─__pycache__
│          SleepTime.cpython-311.pyc
│
├─view
│      InputView.py
│
└─webdriver
    │  MyWebDriver.py
    │
    ├─crawling
    │      BoxScoreCrawler.py
    │      HitterCrawler.py
    │      NewsCrawler.py
    │      PitcherCrawler.py
    │      PlayerCrawler.py
    │      ScoreBoxCrawler.py
    │      Scraper.py
    │      TeamRankCrawler.py
    │      tempCodeRunnerFile.py
    │      T_GameCrawler.py
    │      Y_GameCrawler.py
    │
    └─__pycache__
            MyWebDriver.cpython-311.pyc
