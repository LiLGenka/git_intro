я лучше всех
echo '* Перед коммитом изменений нужно убедиться, что все файлы добавлены в индекс.' >> commmit_help.md
echo '* Посмотреть состояние индекса можно командой `git status.`' >> commmit_help.md
echo '* Используйте `git add filename` для добавления конкретного файла или `git add .` для добавления всех файлов' >> commmit_help.md
echo '* Чтобы одной командой добавить все изменённые файлы и сделать коммит, выполните `git commit -am "commit message"`' >> commmit_help.md
echo '* Новые файлы добавлены не будут' >> commmit_help.md
echo '- [Как сделать новый коммит](./commmit_help.md)' >> README.md 
echo 'чтобы добавить формат вывода комментария напиши: >> git log --pretty=format:"%h -%an, %ar: %s" --stat
echo alies служит для псевдонима команд>>  git config --global>> для текущего пользователя>> git config --global alias.history --pretty=format:"%h-%an, %ar : %s" --stat
чтобы удалить
- [Ветвление](./branch_help.md)'
- [Гитхаб](./github.md)
- [Удалить](./delete.md)
- [Различия](diff.md)
- [Замена коммитов](zamena_commita.md)
- [Слияние веток](./merge_help.md)"