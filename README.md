# :baseball: :email: KBO-Match-Result-Mail-System

## 🖥️ 프로젝트 소개

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
