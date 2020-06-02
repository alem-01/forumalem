# forumalem

Конкурс на лучший форум для alem.school. Команда победителей получит подарки от teamalem, уважение от студентов и развернет свой форум для внутреннего использования. 

## Условия оценивания

- Чистый код
- Структура проекта
- Безопасность форума: авторизация, токены, валидации
- UI/UX: адаптивность и прогрессивность фронта
- Архитектура базы данных

___

## Важно

Проект должен иметь MIT лицензию.

Проект должен запускаться в Docker контейнере.

В проекте должна быть папка `scripts` со следующими файлами.
```sh
-- forum
 |....
 |___scripts
      |- start.sh  # запуск проекта
      |- reload.sh # перезапуск проекта (для обновлении)
      |- stop.sh   # остановка проекта
```

start.sh и reload.sh должны принимать аргумент и запускать/перезапускать на указанном порту.

Пример:
```sh
export PORT=8080
sh start.sh $PORT
sh reload.sh $PORT
```

___

## Условия участия

1. Делаете pull request в файл `participants.md`
2. Добавляете новую линию следующим форматом:
```sh
https://git.01.alem.school/atlekbai/forum - atlekbai, Adilyam, Zulbukharov, sakenism
```

Нужно отправить ссылку на репозиторий и логины сокомандников через запятую.

3. Ждете апрува от teamalem
