# ССЫЛКА НА ВИДЕО С ДЕМОНСТРАЦИЕЙ: https://disk.yandex.ru/i/6mi0vXQxAj1JWw
Степан Буряк Александрович, ФИТ-1

Облочный сервер был аредован на сайте cloud.reg.ru, в принципе я его не планирую отключать ещё некоторое время, так что вот ссылка: [http:](http://89.111.174.94:8080/login?from=%2F)

1) Установка Java на сервер:
sudo apt update
sudo apt install fontconfig openjdk-17-jre
java -version

3) Установка Jenkins на сервер:
sudo wget -O /usr/share/keyrings/jenkins-keyring.asc \
  https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key
echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
  https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
  /etc/apt/sources.list.d/jenkins.list > /dev/null
sudo apt-get update
sudo apt-get install jenkins

Команды в этом файле почему-то плохо отображаются, хотя при редактировании файла всё показывается нормально, по отдельным стрчокам
