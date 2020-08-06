# Исходники сайта [matematika.info](https://matematika.info)

<br/>

### Запустить matematika.info для разработки

    $ docker-compose up

<br/>

### Запустить matematika.info локально как сервис

<a href="https://sysadm.ru/linux/servers/containers/docker/install/">Docker</a> должен быть установлен.

    # cp matematika.info.service /etc/systemd/system/matematika.info.service

<br/>

    # systemctl enable matematika.info.service
    # systemctl start  matematika.info.service
    # systemctl status matematika.info.service

http://localhost:4018
