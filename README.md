#ССЫЛКА НА ВИДЕО С ДЕМОНСТРАЦИЕЙ: https://disk.yandex.ru/i/6mi0vXQxAj1JWw
Степан Буряк Александрович, ФИТ-1

Облочный сервер был аредован на сайте cloud.reg.ru

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

Внешний вид комманд в файле почему-то плохо отображается, хотя при редактировании этого текстового файла всё показывается нормально, по отдельным стрчокам
