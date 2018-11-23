# 🐱‍👤

### problem

    1. 사용자로부터 3가지 입력을 받습니다.
       URL(크롤링 해올 주소), 
       TYPE(크롤링 해온 텍스트의 타입. 'txt'; html태그 포함/ 'html'; html 태그 제외), 
       Length of Unit(출력단위).
    2. 웹 페이지의 모든 글자를 크롤링. 단, 영어와 숫자만 출력.
    3. 오름차순으로 출력. (e.g. 숫자: 012..., 영어: AaBbCc..)
    4. 영어와 숫자가 Mix시 교차출력. (e.g. '영어-숫자-영어'순)
    5. 출력단위를 기준으로 몫과 나머지를 나누어 출력.
    6. 웹 페이지 또는 커맨드라인에서 테스트 가능하도록.


### Solution

<img src="https://github.com/minh364/HTML_THEIF/blob/master/image/screenshot.png">


### Dependencies
- Python 3.6
- bs4 0.0.1
- beautifulsoup4 4.6.x
- requests 2.x
- Flask 1.0.x

### How to run
1. Git Clone
2. app.py 실행
3. 'Running on {{local host 주소}}' 메세지가 뜨면, 해당 주소로 접속.
4. 웹페이지에 문제가 있다면, command.py를 실행해 커맨드 창에서 테스트해 볼 수 있습니다.
