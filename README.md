
<h2> Выполненные работы, примеры написания bash-скриптов и плейбуков/ролей для ansible</h2>

---

<h3>Выполненные работы:</h3>

| Файл | Описание |
| :--- | :--- |
| [Итоговый проект](pdf/sf_final_certification_SAV.pdf) | - итоговый проект по курсу "Системный администратор Linux" онлайн-школы Skillfactory |
| [Jenkins](pdf/jenkins.pdf) | - пример выполненного паплайна в Jenkins |
| [Kubernetes](pdf/k8s.pdf) | - в работе. Текущее состояние: развернут minikube с веб-доступом через Rancher |

---

<h3>Примеры написания ролей для ansible:</h3>

|Имя|Описание|
|:-|:-|
| [ubuntu_sys_config](ansible/roles/ubuntu_sys_config/README.md) | - роль для конфигруции ВМ после создания. <br>ОС: Ubuntu |
| [ubuntu_web_nginx_php74fpm](ansible/roles/ubuntu_web_nginx_php74fpm/README.md) | - роль для установки и настройки: nginx, php7.4-fpm, vsftpd. <br>ОС: Ubuntu |
| [docker_nginx_php_mysql](/ansible/roles/docker_nginx_php_mysql/README.md) | - роль для разворачивания приложения "Nginx+PHP+Mysql" в docker-контейнерах с использованием docker-compose.yml |

