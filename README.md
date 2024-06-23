# Проект электронной очереди
Был написан под restAPI на fastAPI. 
## Использованные технологии
* react-router
* axios
* mui/material
* vite
* typescript
## Состояние
Код можно рефакторить еще долго. Начиная от нормальной структуры компонентов и заканчивая человеческим неймингом + вынести все реквесты в отдельный файлик. По части производительности все неплохо - DomContentLoaded: 107ms, Finish: 326ms, полагаю если использовать системные шрифты скорость увеличится в разы, т.к. подгрузка шрифтов занимает 120ms (спасибо google fonts)

## TODO
* Сделать мобильную версию
* Динамический сайзинг компонентов через clamp
* Поменять названия компонентов на более четкие
* Вынести все реквесты в отдельный файл
* Разобраться с базовыми оптимизациями memo, lazy loading и т.д.
* Написать unit тесты
  
