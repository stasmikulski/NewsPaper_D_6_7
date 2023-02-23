# NewsPaper_D7.5 #
### for SkillFactory Модуль D7.5 ###
### Приложение, создающее сайт "Портал новостей" ###
##### Для запуска приложения понадобится три окна Терминала #####
В двух из них должно быть одно и то же виртуальное окружение.   
Активируем виртуальное окружение в папке ~/django-projects  
В первом окне Терминала активируем его командой **source venv/bin/activate**  
Должен появиться промт с **(venv)** в начале строки.  
В втором окне Терминала также активируем его командой **source venv/bin/activate**  
Должен появиться промт с **(venv)** в начале строки.  
Запускать наше приложение нужно в папке NewsPaper, переходим в нее в обоих \
окнах Терминала командой **cd NewsPaper**  
Далее, в первом окне запускаем **python3 manage.py runserver**   
во втором окне запускаем **celery -A NewsPaper worker -l INFO**   
в третьем окне должен быть запущен сервер **redis-server**  
Сайт смотрим по адресу ht<span>tp://</span>127.0.0.1:8000/news_list/ 
