[![Generic badge](https://img.shields.io/badge/Ubuntu-18.04-green.svg)](https://shields.io/)
[![Generic badge](https://img.shields.io/badge/Language-Python,HTML-blue.svg)](https://shields.io/)
[![Generic badge](https://img.shields.io/badge/Framework-Flask-orange.svg)](https://shields.io/)

# 웹기반 대시보드 구축 프로젝트
- 중앙대학교 환경시스템 연구실과 협업하여 진행한 프로젝트로 서울시 악취 민원의 효율적인 분석을 위해 웹기반 대시보드 구축하고자 함

# 개발 환경
- goorm IDE(https://www.goorm.io/)
- Colab(https://colab.research.google.com/)

# 주요 패키지
- `Plotly` : 데이터 시각화 패키지로 Bokeh 처럼 Java scrpit 기반으로 작동한다.  
- `Folium` : 지리정보 시각화 패키지로 leaflet.js 기반으로 지도를 그려주고 모바일에서도 쓸 수 있을만큼 가볍다.  
- `Mapboxgl` : 브라우저에 지도 데이터를 렌더링해주는 해주는 자바스크립트 라이브러리이다.  
- `Flask` : 파이썬 기반 마이크로 웹 프레임워크로 확장과 커스터마이징이 편리하다. Django에 비해 가벼운 애플리케이션 구현에 알맞음

# 데이터
- 2014년 3월부터 2020년 5월까지 총 8,636건의 서울시 악취민원(위반장소, 위반일시 등등)  

# 화면 구성
- 상단 네비게이션바를 통해 메뉴 설정 가능
- 좌측 메뉴바를 통해 상세 기능 실행 가능(지도 및 그래프 시각화, 통계 추출, 결과 내려받기) 
![그림1](https://user-images.githubusercontent.com/33515088/107912249-88c59500-6fa1-11eb-8d75-98dd9fc25d5d.png)

# 회고
