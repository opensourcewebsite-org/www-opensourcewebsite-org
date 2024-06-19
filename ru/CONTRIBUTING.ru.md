# Руководство контрибьютора

[English version](CONTRIBUTING.md)

Прежде всего, спасибо, что нашли время внести вклад!

Ваш вклад увеличивает ваш Рейтинг в нашем сообществе.

Пожалуйста, прочитайте нашу [Инструкцию по установке](INSTALL.ru.md).

## Начнём

При внесении вклада в этот репозиторий, прежде чем вносить изменения, сначала обсудите изменения, которые вы хотите внести, при помощи issue, электронной почты или любым другим способом, с основной командой.

- Удостоверьтесь, что у вас есть [аккаунт GitHub](https://github.com/login).
- Отправьте GitHub issue для вашей проблемы если таковой еще нет.
  - Issue не нужно для незначительных изменений.
- Сделайте [fork](https://help.github.com/en/articles/working-with-forks) репозитория на GitHub.
    - [Настройка удалённого репозитория для fork](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/configuring-a-remote-for-a-fork)
    - [Синхронизация fork](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/syncing-a-fork)
      - `git fetch upstream`
      - `git checkout master`
      - `git merge upstream/master`
    - [Слияние (merge) upstream-репозитория в ваш fork](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/merging-an-upstream-repository-into-your-fork)
      - `git checkout master`
      - `git pull upstream master`
      - Сделать commit слияния (merge)
      - `git push origin master`
- При работе над issue, создайте новую ветку (branch) от `master` названную номером issue или другим именем. Назовите ветку `issue/<issue-number>` или `issue/<custom-name>`. Например, `issue/22` при работе над issue #22.
- Внесите изменения.
  - Следуйте [Руководству по стилю](#style-guides).
  - [Избегайте платформозависимого кода](https://flight-manual.atom.io/hacking-atom/sections/cross-platform-compatibility/).
  -   Добавьте тесты если ваши изменения содержат новые, тестируемые поведения.
  - Сделайте тесты проходимыми (успешными).
- Создайте [pull request](https://help.github.com/en/articles/creating-a-pull-request-from-a-fork) к репозиторию.

### Советы и рекомендации по использованию Git

- [GitHub Cheat Sheet](https://github.com/tiimgreen/github-cheat-sheet)
- [git-tips](https://github.com/git-tips/tips)

### Ключевые ветки

- `main` - последняя, развёртываемая версия.

## Дополнительная информация

- [Adding content to your GitHub Pages site using Jekyll](https://help.github.com/en/articles/adding-content-to-your-github-pages-site-using-jekyll)
- [Jekyll - Static Site Generator / Tutorial](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB)
