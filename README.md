## Инициализация

`make init` - первый запуск, после него останавливаем контейнеры  
`make up` - обычный запуск  
`make down`  - Остановить контейнр  
`make exec` - войти в контейнер с приложением  
`make exec.db` - войти в 
контейнер с БД  
`network.down` - удалить все сети

## IP
1. `100.70.1.0/24` - пул адресов
1. `100.70.1.10` - php
1. `100.70.1.9` - nginx
1. `100.70.1.20` - MySql

## TODO

- [x] Вынести в env настройки
- [ ] Обслуживание hosts
- [ ] Вынести докерфайл на сервер
- [ ] Разобраться с БД
- [ ] Подтянуть redis
- [ ] Подтянуть zsh