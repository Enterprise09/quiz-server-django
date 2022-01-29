# quiz-server-django

<div>
    <img src="https://img.shields.io/badge/Python-3.10.2-3776AB?logo=Python&logoColor=3776AB">
    <img src="https://img.shields.io/badge/Django-4.0.1-092E20?logo=Django&logoColor=092E20">
</div>

> django rest-api server

## Set up project

1. intall python
2. make virtual enviroment
   ```shell
       pip install --user virtualenv
       python -m venv $[Your Loacation]
   ```
3. check install modules at `/requirements.txt` & install with `pip install $[Module Name]`

   ```python
       asgiref==3.5.0
       dj-database-url==0.5.0
       Django==4.0.1
       django-cors-headers==3.11.0
       djangorestframework==3.13.1
       gunicorn==20.1.0
       psycopg2-binary==2.9.3
       pytz==2021.3
       sqlparse==0.4.2
       tzdata==2021.5
       whitenoise==5.3.0
   ```

## API Documents

- Request[GET]<br />
  `https://quiz-server-django.herokuapp.com/quiz/3/`

  > it return 3 different quizes

- Response<br />

  ```json
  [
    {
      "title": "Material App에서 기본버튼 위젯은?",
      "body": "FlatButton/ElevatedButton/Button",
      "answer": 1
    },
    {
      "title": "화면을 좌우로 스크롤하여 다른 페이지를 볼 수 있는 위젯은?",
      "body": "PageView/Text/Navigator",
      "answer": 0
    },
    {
      "title": "Flutter에서 이미지를 보여주려면?",
      "body": "asset 등록이 필요/등록따윈 필요없음/바로 쓰면됨",
      "answer": 0
    }
  ]
  ```

    <img src="https://user-images.githubusercontent.com/73864148/151669103-942e0abf-959a-4d63-9dc6-28cd49ab6085.png">
