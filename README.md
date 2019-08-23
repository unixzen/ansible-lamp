# ansible
## Плейбук для установки Nginx, Apache, PHP, MySQL, Joomla


### Описание
В качестве провайдера для вагрант используется digital ocean (https://digitalocean.com). 
При запуске устанавливается на локальную машину плагин для digital ocean, вагрант, поднимается
виртуалка в digital ocean и устанавливается стек Nginx, Apache, PHP, MySQL, Joomla



### Использование
Для корректного запуска нужно иметь API Digital Ocean token (пример, https://www.digitalocean.com/community/tutorials/how-to-use-the-digitalocean-api-v2)

Из каталога с Vagrantfile выполнить
```
vagrant up
```





