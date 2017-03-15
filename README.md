最简单的用户登录或者注册





创建分支，并将本地代码上传到分支上去
1、Git init （在本地工程目录下。）
2、git add .
3、git commit -m "1a"  （”1a“为分支名）
4、git branch 1a（创建分支）
5、git checkout  1a（切换分支）
6、git remote add origin  https://github.com/ZacharyRZ/LeaPython.git      
7、git push origin 1a（将分支上传）
注意:如果提示 "please tell me who you are“
在.git 目录下的config文件，在最后添加
[user]
name = xxxx
email = xxxxxxx@xx.com



migrate迁移mysql报错No module named 'MySQLdb'

pip install  mysqlclient



python manage.py db init 生成migrations文件夹

python manage.py db migrate -m "initial migrateion"  生成迁移脚本

python manage.py db upgrade   运行脚本，同步数据库



