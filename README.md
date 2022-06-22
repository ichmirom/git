# git
All Git commands for development

// Инициализация проекта через GitHub 
1) git clone [url]

// Инициализация проекта вручную
1) Создать папку на компьютере
2) git init // добавление папки .git в директорию
3) git remote -v //проверка, связана ли данная папка с репозиторием на github
4) git remote add origin [url] //связка папки с репозиторием


// Показать все файлы внутри директории
1) ls
2) ls -a

// Настройка git репозитория
1) git config
2) git config user.name (git config user.name "[new name]")
3) git config user.email (git config user.name "[new email]")

// Основные команды Git
1) git status
2) git add [files]
3) git commit -m "comment"
4) git log / git log --oneline
5) git push [rep_link] [branch_name]