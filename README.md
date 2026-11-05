<h1 align="center">안녕하세요, 김기욱입니다 👋</h1>

<p align="center"><strong>백엔드 개발 · API 설계 · 데이터베이스 · 컴퓨터 비전</strong></p>

<p align="center">
  <a href="https://kwkim2013.github.io/"><strong>포트폴리오 보기 ↗</strong></a> ·
  <a href="https://kwkim2013.github.io/projects">전체 프로젝트</a> ·
  <a href="https://github.com/kwkim2013">GitHub</a> ·
  <a href="mailto:dnr0409@nate.com">이메일</a>
</p>

## 소개

웹 서비스의 예약·결제 흐름부터 영상 인식과 센서 데이터 처리까지, 데이터를 서비스 기능으로 연결하는 개발 경험을 쌓고 있습니다.

- **PetPalace**에서 기획부터 예약 API·DB 설계, 결제 연동, 관리자 화면까지 개인 개발로 구현했습니다.
- **CGI_MOA**에서 이미지 합성 결과의 평가 기준을 탐색하고 Bruno로 API 요청·응답을 검증했습니다.
- **컴퓨터 비전·IoT 팀 프로젝트**에서 모델 학습, 데이터 저장, 실시간 모니터링 GUI 개발을 담당했습니다.

## 프로젝트 한눈에 보기

**상세 소개**에서는 프로젝트의 기능·담당 업무·문제 해결 과정을, **코드**에서는 개인 또는 팀 저장소를 확인할 수 있습니다.

| 프로젝트 | 소개 | 참여 형태 | 링크 |
| --- | --- | --- | --- |
| PetPalace | 반려동물 호텔 예약·결제 웹 서비스 | 개인 개발 | [상세 소개](https://kwkim2013.github.io/projects/pet-palace) · [코드](https://github.com/kimkale12/petpalace) |
| CGI_MOA | 생성형 이미지 합성 결과 평가 서비스 | 팀 프로젝트 | [상세 소개](https://kwkim2013.github.io/projects/cgi-moa) · [코드](https://github.com/Jenny5789/CGI_MOA) |
| 자동차 번호판 인식 시스템 | 번호판 검출·OCR 및 실시간 모니터링 | 5인 팀 | [상세 소개](https://kwkim2013.github.io/projects/license-plate-recognition) · [코드](https://github.com/JHKINI/nextframe_opencv) |
| 난폭운전 감지 시스템 | 도로 객체 인식 및 주행 위반 분석 | 5인 팀 | [상세 소개](https://kwkim2013.github.io/projects/reckless-driving-detection) · [코드](https://github.com/addinedu-ros-6th/deeplearning-repo-1) |
| 스마트 화재 대응 시스템 | 센서 기반 경보 및 주차 관제 | 5인 팀 | [상세 소개](https://kwkim2013.github.io/projects/smart-fire-response) · [코드](https://github.com/addinedu-ros-6th/iot-repo-5) |

## 프로젝트별 안내

### 1. PetPalace

반려동물 호텔의 객실·날짜 선택부터 예약, 결제, 관리자 조회까지 연결한 웹 서비스입니다.

- **담당 업무:** 기획, Vue 3 예약 화면, Express API와 PostgreSQL DB 설계, JWT 인증·인가, Toss Payments 연동
- **주요 기능:** 회원가입·로그인, 호텔 예약·결제, 게시판 CRUD, 관리자 예약 현황·일별 매출 조회
- **문제 해결:** 프론트엔드와 백엔드에 예약 날짜 검증을 적용하고, 결제 준비 성공 시에만 결제 화면으로 이동하도록 예외 처리를 개선했습니다.
- **기술:** Vue 3, Pinia, Node.js, Express, PostgreSQL, Sequelize, JWT, Toss Payments

[포트폴리오 상세 보기 →](https://kwkim2013.github.io/projects/pet-palace) · [GitHub 저장소 →](https://github.com/kimkale12/petpalace)

### 2. CGI_MOA

생성형 이미지 합성 결과를 평가하고 관리하는 팀 프로젝트형 웹 서비스입니다.

- **담당 업무:** 합성 결과 비교·평가 기준 탐색, Bruno 기반 GET·POST API 기능 테스트
- **검증 내용:** API 요청 형식과 응답 데이터를 확인하고 기능별 동작을 테스트했습니다.
- **협업:** 테스트 시나리오를 정리하고 기능 검증 결과와 이슈를 팀원들과 공유했습니다.
- **사용 기술·도구:** JavaScript, REST API, Bruno, GitHub

[포트폴리오 상세 보기 →](https://kwkim2013.github.io/projects/cgi-moa) · [GitHub 저장소 →](https://github.com/Jenny5789/CGI_MOA)

### 3. 자동차 번호판 인식 시스템

영상에서 번호판을 검출하고 인식한 문자와 최근 기록을 실시간으로 확인하는 데스크톱 프로그램입니다.

- **담당 업무:** 번호판 데이터 라벨링, YOLO 모델 학습·검출, 번호판 영역 크롭, PySide6 GUI 개발
- **주요 기능:** 동영상 선택·재생·일시정지, EasyOCR 문자 인식, 최근 인식 기록 5건 표시, CSV 저장·다운로드
- **문제 해결:** 5프레임 다수결 투표를 적용해 프레임별 인식 결과를 안정화하고 중복 저장을 제거했습니다.
- **기술:** Python, YOLO, EasyOCR, OpenCV, PySide6

[포트폴리오 상세 보기 →](https://kwkim2013.github.io/projects/license-plate-recognition) · [GitHub 저장소 →](https://github.com/JHKINI/nextframe_opencv)

### 4. 난폭운전 감지 시스템

도로 표지판과 어린이 보호구역을 인식하고, 속도·정지선 위반에 따른 벌점을 계산해 표시하는 시스템입니다.

- **담당 업무:** 차량 움직임 감지 데이터 라벨링·학습, 도로 객체 인식, 사용자·차량·인식 로그 DB 설계, 벌점 계산, GUI 개발
- **주요 기능:** 실시간 도로 객체 인식, 주행 위반 판별, 벌점 기록, PyQt5 모니터링
- **문제 해결:** 라벨링 기준과 학습 전처리를 개선하고, 비동기 GUI 처리와 로깅 경량화로 표시 지연을 줄였습니다.
- **기술:** Python, YOLOv8, OpenCV, PyQt5, MySQL, Ubuntu, AWS

[포트폴리오 상세 보기 →](https://kwkim2013.github.io/projects/reckless-driving-detection) · [GitHub 저장소 →](https://github.com/addinedu-ros-6th/deeplearning-repo-1)

### 5. 스마트 화재 대응 시스템

수위·화재 감지 센서, 경보, 주차 현황을 하나의 관제 흐름으로 연결한 IoT 프로젝트입니다.

- **담당 업무:** Arduino·초음파 센서 수위 측정, Python 데이터 수집과 MySQL 저장, 알람 GUI·이벤트 이력 관리, 주차 현황 DB 연동
- **주요 기능:** 센서 데이터 모니터링, 이상 신호 알람·경고음, 이벤트 로그 관리, 구역별 주차 가능 여부 표시
- **문제 해결:** 수집 모듈을 멀티스레드로 구성하고 ROS2 통신 구조와 알람 조건을 개선해 센서 처리 지연과 오탐을 줄였습니다.
- **기술:** Python, Arduino, ROS2, MQTT, MySQL, PyQt5, Node.js, Ubuntu

[포트폴리오 상세 보기 →](https://kwkim2013.github.io/projects/smart-fire-response) · [GitHub 저장소 →](https://github.com/addinedu-ros-6th/iot-repo-5)

## 사용 기술

| 분야 | 기술·도구 |
| --- | --- |
| 웹 프론트엔드 | JavaScript, Vue 3, Pinia |
| 백엔드·인증 | Node.js, Express, REST API, JWT |
| 데이터베이스·결제 | PostgreSQL, MySQL, Sequelize, Toss Payments |
| 컴퓨터 비전·GUI | Python, OpenCV, YOLO, EasyOCR, PySide6, PyQt5 |
| IoT·협업·테스트 | Arduino, ROS2, MQTT, Bruno, Git, GitHub |

## 포트폴리오 사이트

이 포트폴리오 사이트는 **React · Vite · React Router**로 구현하고 GitHub Pages에 배포했습니다.

- [사이트 방문](https://kwkim2013.github.io/)
- [사이트 소스 코드](https://github.com/kwkim2013/kwkim2013.github.io)
- [GitHub Pages 배포 및 운영 가이드](https://github.com/kwkim2013/kwkim2013.github.io/blob/main/docs/github-pages.md)
