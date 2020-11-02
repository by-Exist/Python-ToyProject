# 국비지원교육 과정 프로젝트 목록

---

## 목차
* [Barcode Scanner](##Barcode-Scanner)
* [Cat Humer School](##Cat-Humer-School)
* [Password Maker](##Password-Maker)

---

## [Barcode Scanner]
### 기간
* 2020.08 (일주일 소요)
### 부제
* 공공기관 Open API Json 데이터 다운로더
### 링크
* [Github](https://github.com/by-Exist/Public_Data_Json_Downloader)
### 사진
* ![image](https://github.com/by-Exist/school_projects/blob/master/images/barcode_scanner/app_image.jpg?raw=true)
### 담당 파트
* REST API로 json으로 제공되는 제품 데이터 80만개를 모두 DB에 저장해야 하는 조건
* json과 request모듈을 활용하여 공공기관 OPEN API로 제공되는 데이터를 pickle로 직렬화하는 프로그램 제작
* ChainMap과 namedtuple을 활용하여 DB에 저장하는 테스팅 코드 작성
### 후기
* Python의 기본 라이브러리를 학습하는 것이 추후 얼마나 큰 도움이 되는가를 깨달을 수 있었던 계기.
* 문제를 분석, 흐름 정의, 코드 설계, 디버깅하는 과정에서 즐거움을 느낄 수 있었다.

---

## [Cat Humer School]
### 기간
* 2020.07 (한달 소요)
### 링크
* [Github](https://github.com/bigmacaron/cat_humor_school)
### 부제
* flask를 활용하여 제작된 커뮤니티 사이트.
### 사진
* ![image](https://github.com/by-Exist/school_projects/blob/master/images/cat_humer_school/index_page.jpg?raw=true)
### 설명
* 관리자 계정으로 로그인할 시 크롤링 페이지 연결
* 여러 커뮤니티중 하나를 선택하면 해당 커뮤니티의 게시물 목록 페이지 구성
* 원하는 게시물을 선택하여 자동 크롤링
* 다운로드 된 게시물은 인덱스 페이지에서 보여질 수 있도록 구성
### 담당 파트
* 커뮤니티 사이트 포스트 크롤링 모듈 설계
* DAO 설계
* flask 관리자 페이지와 크롤링 모듈 연동
### 후기
* 웹 개발 지식의 부족함을 절실하게 깨달아 토론 끝에 실력을 향상시키기 위한 개인 공부를 우선시함으로 결론내려 예정된 실제 서비스까지 진행시키지 못한 프로젝트.
* 주기적인 코드 리뷰 및 진행상황 점검을 통하여 협업의 흐름을 체험할 수 있었다.
* 팀원간의 마찰이 발생할 때 어떻게 처리해야 하는가에 대하여 다시 생각해보게 된 계기.
* 각 페이지마다 다른 인코딩을 사용하고 있었고, 인코딩에 대한 지식이 있었다면 하는 아쉬움이 남는다.

---

## [Password Maker]
### 기간
* 2020.06 (1주 소요)
### 부제
* tkinter를 활용하여 만든 비밀번호 생성 및 관리 GUI 프로그램.
### 사진
* ![image](https://github.com/by-Exist/school_projects/blob/master/images/password_maker/password_maker.PNG?raw=true)
### 설명
* 사용자가 원하는 비밀번호의 형식을 지정할 시 랜덤하게 비밀번호를 생성해주고, 해당 비밀번호를 최대 3개까지 저장 및 관리할 수 있도록 만들어진 프로그램.
### 담당 파트
* 레이아웃을 제외한 전반.
### 후기
* 처음으로 진행한 협업 프로젝트.
* SQLite를 알고 있었다면 효율적으로 비밀번호를 저장하고 읽어오는 과정을 설계할 수 있었겠지만 단순하게 txt 파일에 비밀번호와 배치 순서를 기록하도록 설계하였던 점이 아쉬움.