<h1>장고 앱 만들기</h1>
cmd창에</br>
django-admin startproject mySite</br>
python manage.py startapp Overview</br>

1. Overview/templates/overview 만들어 index.html(외부템플릿)</br>
2. Overview아래 1)view.py에 render함수 수정 2)urls.py만들어 view와 연결</br>
3. mySite/Settings.py에 INSTALLED_APPS에 추가</br>
4. mySite/urls.py에 연결</br>

참고로 css,js등은 Overview/static/css로 따로 넣어야함</br>

<h1>MySQL과 연동</h1>
1. mysql_settings.py 만들고 .gitignore에 포함</br>
2. python manage.py inspectdb</br>
3. 복붙해 쓸 앱의 models.py에 넣음</br>
4. view.py와 urls.py에 반영</br>