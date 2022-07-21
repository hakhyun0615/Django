# 디렉토리 생성 및 가상환경 구축

# 프로젝트(웹 서비스 전체) 생성
* django-admin startproject 프로젝트_이름

# 개발서버 실행
* cd 프로젝트_이름
* python manage.py runserver

# 앱(기능을 나타내는 단위) 생성
* python manage.py startapp 앱_이름
* 앱 생성시 settings.py의 INSTALLED_APPS에 앱_이름 추가

<img width="751" alt="image" src="https://user-images.githubusercontent.com/88610333/180192043-7f137db2-641e-4253-b308-50123eac04c0.png">

# Model
* 데이터 구조 생성
* 데이터베이스와 소통

# Template
* 웹 사이트의 화면 구성 담당(큰 틀)(html)
* 매번 바뀌는 동적인 화면을 구성(바뀌는 내용들)(template language)
* Rendering(렌더링)을 통해 HttpResponse 객체로 변환됨 ex) render(request,'foods/index.html')

# View
* 웹 사이트의 로직을 담당(요청이 들어오면 요청을 처리)
* Model과 Template 사이를 연결

# 아키텍처 패턴(Architecture Pattern)
* 클라이언트 - 서버 패턴
* MVC 패턴
* 등등...
