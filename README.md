# aviato.kz.test

В даном репозитории находится код для тестового задания для компанию aviata.kz 

проект написан на Flask отоброжения с помощю REST API

# Реализация

Изночально в бд присуствуют записи рейсов на месяц с ценой boking_token и другими параметрами

каждый день в 00:00 удаляются все записи предыдущего дня и записываются новые на 32 дня вперёт при поиски билетов указывается город fly_from fly_to количество пассажиров дата а на стороне api идёт поиск нужных рейсов проверка рейса по boking_token перевод цен в KZT фильтр по цене и отправка клиенту
