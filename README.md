# 🎓 Django School (장고 스쿨)

[![Python Version](https://img.shields.io/badge/python-3.6-brightgreen.svg)](https://python.org)  
[![Django Version](https://img.shields.io/badge/django-2.0-brightgreen.svg)](https://djangoproject.com)

이 프로젝트는 **다양한 사용자 유형(Multiple User Types)**을 구현하는 예제를 보여주기 위해 만들어졌습니다.  
이 Django 애플리케이션에서 **교사는 퀴즈를 생성**할 수 있고, **학생은 회원가입 후 관심 있는 주제의 퀴즈를 응시**할 수 있습니다.

![Django School Screenshot](https://simpleisbetterthancomplex.com/media/2018/01/teacher-quiz.png)

관련 블로그 글:  
[장고에서 여러 사용자 유형 구현하는 방법 (How to Implement Multiple User Types with Django)](https://simpleisbetterthancomplex.com/tutorial/2018/01/18/how-to-implement-multiple-user-types-with-django.html)

---

## 🛠️ 로컬에서 실행하는 방법

### 1. 저장소를 클론하세요:

```bash
git clone https://github.com/sibtc/django-multiple-user-types-example.git
```

### 2. 필요한 패키지를 설치하세요:

```bash
pip install -r requirements.txt
```

### 3. 데이터베이스를 생성하세요:

```bash
python manage.py migrate
```

### 4. 개발 서버를 실행하세요:

```bash
python manage.py runserver
```

이제 프로젝트는 브라우저에서 다음 주소로 접속할 수 있습니다:

🔗 **http://127.0.0.1:8000**

---

## 📄 라이선스

이 소스 코드는 [MIT 라이선스](https://github.com/sibtc/django-multiple-user-types-example/blob/master/LICENSE)에 따라 공개되어 있습니다.
