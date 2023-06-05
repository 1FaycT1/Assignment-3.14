[< На главную ](./readme.md)

## git commit


Команда `git commit` используется для фиксации изменений в репозитории Git и создания коммита с сообщением о внесенных изменениях.

Например, чтобы создать коммит с сообщением "Добавлен новый файл":

```
git commit -m "Добавлен новый файл"
```

Есть вероятность что вы можете сталкнуться с таким сообщением 
```
On branch main

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   git_clone.md
        modified:   readme.md
```
Что бы принудительно пропустить индексацию используйте с командой `git commit` ключ `-a`
```
git commit -a -m "add git_clone"
```