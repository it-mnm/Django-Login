# Django-Login

## 사용방법
1. 환경세팅
    pip install -r requirements.txt 




---
2. docker에서 mysql 컨테이너 실행
   (cmd)  docker run -dit --name=mysql -p 3306:3306 -e MYSQL_ROOT_PASSWORD=1234 -e MYSQL_DATABASE=userinfo mysql




---
3. database 연결 확인 (dbeaver)


---
   ![image](https://github.com/it-mnm/Django-Login/assets/137988290/86e7d01f-3cb8-49a9-a45a-746647fffc44)
   password :1234




---
4. 서버 실행
   python manage.py runserver
