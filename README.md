# pragmatic
Django &amp; Docker &amp; MariaDB &amp; Nginx


### 개발한 웹사이트 주소 (도메인은 구매하지않아 ip로 접속)
http://141.164.44.144/

Pycharm에서 장고를 이용해 다양한 플랫폼들을 생성해서 각 앱들에 맞게 뷰와 urls, form 등등 맞게 구성하고  
각 url들을 자연스럽게 연결하고 다 만든 웹페이지를 vultr에서 docker를 설치한 가상 서버를 구매해 
내 도커 컨테이너에 깃허브 레포지토리를 올리고 nginx를 이용해 css파일이 적용되지 않는 문제를 해결.  
또한 혹시 모를 에러로 컨테이너가 손상되면 DB파일까지 손상될 우려로 인해 mariaDB로 따로 DB를 관리.
