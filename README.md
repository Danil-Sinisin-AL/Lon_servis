# Lon_servis
Сервис который решает выдовать ли клиенту кредит.
Решение принемает модель Логистической регрессии (да/нет) на основе заполненой анкеты которая записывается в JSON файл.
Это всё передаётся в web сервис, через постман.

Для запуска:
1) Заходим в терминале в папку проекта.
2) Нужно активировать виртуальное окружение например командой conda activate
3) Полсе пишем команду uvicorn main:app --reload
4) Заходим в постман вставляем полученный адрес. Гтово.
