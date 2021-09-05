# Полезная информация о жизни в Нидерландах
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fru-nl%2Ffaq.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fru-nl%2Ffaq?ref=badge_shield)


В этом репозитории находится исходный код сайта [https://ru-nl.github.io](https://ru-nl.github.io).

## Как добавить информацию

Сделайте форк репозитория [ru-nl/faq](https://github.com/ru-nl/faq), внесите необходимые изменения,
закомитьте их и отправьте [PR-реквест](https://github.com/ru-nl/faq/pulls) к главному репозиторию.

После принятия вашего PR-реквеста, будет автоматически [сгенерирован](https://github.com/ru-nl/ru-nl.github.io)
новый сайт, и изменения станут видны на странице [https://ru-nl.github.io/](https://ru-nl.github.io/).

## Инструкции по локальному запуску

Чтобы запустить этот сайт локально и увидеть свои изменения до отправки PR-реквеста,
сделайте следующее:

1. Установите [hugo](https://gohugo.io/getting-started/installing/)
2. Склонируйте этот репозиторий (или свой форк), и обновите подключенную тему hugo:

  ```
  git clone --recurse-submodules https://github.com/ru-nl/faq.git
  cd faq
  ```
3. Запустите `hugo serve`, чтобы получить доступ к сайту

  ```
  hugo serve
  ```

После шагов выше, сайт будет доступен по адресу [http://127.0.0.1:1313/](http://127.0.0.1:1313/)
и будет автоматически обновляться, когда вы будете сохранять изменения к файлам в репозитории.


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fru-nl%2Ffaq.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fru-nl%2Ffaq?ref=badge_large)