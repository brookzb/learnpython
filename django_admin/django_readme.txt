����mysql���ݿ�
CREATE DATABASE IF NOT EXISTS book DEFAULT CHARSET utf8 COLLATE utf8_general_ci;

django �½���Ŀ
python django-admin.py startproject project-name

django �½�Ӧ��
python manage.py startapp app-name

django ͬ�����ݿ�
python manage.py syncdb
ע�⣺Django 1.7.1�����ϵİ汾��Ҫ����������
python manage.py makemigrations
python manage.py migrate

django ʹ�ÿ���������
python manage.py runserver
# ����ʾ�˿ڱ�ռ�õ�ʱ�򣬿����������˿ڣ�
python manage.py runserver 8001
python manage.py runserver 9999
# �������п��� ip
python manage.py runserver 0.0.0.0:8000
# ������������߾����������Ͽ������������Բ鿴����������
# ���ʶ�Ӧ�� ip�Ӷ˿ڣ����� http://172.16.20.2:8000

django �������
python manage.py flush

django ��������Ա
python manage.py createsuperuser

django���뵼������
python manage.py dumpdata appname > appname.json
python manage.py loaddata appname.json

django ��Ŀ�����ն�
python manage.py shell

django ���ݿ�������
python manage.py dbshell

