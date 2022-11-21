# API

запуск контейнеров по апи
```
 curl -v -d '{"api_key":"vXkD)x110CXEXBY8Fpt2u6_pOyGjXu4lg8-Gmq93RJMniviqsM", "server_id":"11", "role_id": "12",   "services": {} }' -H "Content-Type: application/json" -X POST localhost:5000/api/v1/run_container
```
в services пишется композ. в json. конвертер yaml в json будет в веб интерфейсе.

что происходит:  
создается связь роли с сервером, контейнеры добавляются в композ. композ обновляется в базе и на сервере, запускются добавленыне контейнеры