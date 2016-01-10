创建mysql数据库
CREATE DATABASE IF NOT EXISTS book DEFAULT CHARSET utf8 COLLATE utf8_general_ci;

django 新建项目
python django-admin.py startproject project-name

django 新建应用
python manage.py startapp app-name

django 同步数据库
python manage.py syncdb
注意：Django 1.7.1及以上的版本需要用以下命令
python manage.py makemigrations
python manage.py migrate

django 使用开发服务器
python manage.py runserver
# 当提示端口被占用的时候，可以用其它端口：
python manage.py runserver 8001
python manage.py runserver 9999
# 监听所有可用 ip
python manage.py runserver 0.0.0.0:8000
# 如果是外网或者局域网电脑上可以用其它电脑查看开发服务器
# 访问对应的 ip加端口，比如 http://172.16.20.2:8000

django 清空数据
python manage.py flush

django 创建管理员
python manage.py createsuperuser

django导入导出数据
python manage.py dumpdata appname > appname.json
python manage.py loaddata appname.json

django 项目环境终端
python manage.py shell

django 数据库命令行
python manage.py dbshell

