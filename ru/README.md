# SManager

Панель управления сервером как оркестратор контенйеров.

## Description

Shared-оркестратор: одна панель позволяющая разным пользователям устанавливать на свои серверы любое ПО, безопасно делиться ресурсами сервера друг с другом или орагнизовать виртуальный хостинг  
В основе деплой docker-compose с помощью ansible.  



Возможности:

* Минимальный порог вхожедния-управление в простом веб интерфейсе
* Гибкость - имеется возможность редактирвоать docker-compose файлы и сценарии ansible
* Развертка docker контейнеров на удаленных серверах
* docker-compose файлы как роли и шаблоны ролей
* Компонент виртуального хостинга из 2х ролей(для владельца сервера и пользователя хостинга)
* Облачное и self-hosted решение
* Не требует установки агентов(только ssh)
* Не изменяет конфигурацию серверов(только установка и использование docker)
* Возможность предоставить другому пользователю ресурсы сервера не давая доступ на него
* Интеграция с Hashicorp Vault


## Getting Started

### Dependencies

* Describe any prerequisites, libraries, OS version, etc., needed before installing program.
* ex. Windows 10

### Installing

* How/where to download your program
* Any modifications needed to be made to files/folders

### Executing program

* How to run the program
* Step-by-step bullets
```
code blocks for commands
```

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Contributors names and contact info

ex. Dominique Pizzie  
ex. [@DomPizzie](https://twitter.com/dompizzie)

## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]()
* 0.1
    * Initial Release

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
* [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)

https://gist.github.com/privateip/879683a0172415c408fb2afb82a97511
https://github.com/networktocode/ntc-ansible/issues/108
https://overcoder.net/q/222146/%D0%B7%D0%B0%D0%BF%D1%83%D1%81%D0%BA-ansible-playbook-%D1%81-%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%D0%BC-python-api
https://stackoverflow.com/questions/5867985/full-screen-iframe-with-a-height-of-100
http://htmlbook.ru/html/iframe
https://medium.com/customorchestrator/simple-reverse-proxy-server-using-flask-936087ce0afb

https://bulma.io/documentation/layout/level/

http://saladinkzn.github.io/blog/2016/04/nginx-consul.html
https://learn.hashicorp.com/tutorials/consul/docker-container-agents?in=consul/docker
https://github.com/hashicorp/consul-template/blob/main/examples/nginx.md
https://www.consul.io/api-docs/catalog

https://docs.docker.com/compose/networking/