# hackatomsk2017-Jack_siberian

Карточная игра "Дурак" с возможностью делать ставки на фантики или Биткоины

Разработка ведется в 3 направлениях:
 * Дизайн 
 * Алгоритм Игры (ветка cpp_serv)
 * Фрондэнд и Бэкенд (ветка m_sylack)
 * Биткоины 


Product manager: @Jack_siberian


# Frontend + Backend = one love
* Node.js v8
* Socket.IO
* ReactJS v16
* jQuery


## Start
Step -1:
```
docker run -d -p 6379:6379 redis --port 6379
```

Step 0:
```
cd ./server
```

Step 1:
```
yarn install
```

Step 2:
```
yarn start:wallet
```

Step 3:
```
yarn start
```

Step 4 (for frontend):
```
yarn watch
```
