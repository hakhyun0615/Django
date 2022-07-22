<img width="751" alt="image" src="https://user-images.githubusercontent.com/88610333/180192043-7f137db2-641e-4253-b308-50123eac04c0.png">

# Model
* 데이터 구조 생성
* 데이터베이스와 소통

# View
* 웹 사이트의 로직을 담당(요청이 들어오면 요청을 처리)
* Model과 Template 사이를 연결

# Template
* 웹 사이트의 화면 구성 담당(큰 틀)(html)
* 매번 바뀌는 동적인 화면을 구성(바뀌는 내용들)(template language)
* Rendering(렌더링)을 통해 HttpResponse 객체로 변환됨 ex) render(request,'foods/index.html')
* <img width="773" alt="image" src="https://user-images.githubusercontent.com/88610333/180343661-cc3c3018-6146-4152-bcf0-598ec21a6611.png">

# 정적파일
* css,images,js,fonts
* 정적파일을 사용하기 위해 Template의 html 상단에 {% load static %} 기입
* css,images 등의 경로를 {% static 'foods/css/styles.css'%}와 같이 변경
* 정적파일도 Template과 같이 샌드위치 구조로 파일 저장
