# deployignore
bash-скрипт, позволяющий удалять ненужные файлы, указанные в файле `.deployignore`.

## Пример файла
```
# Скрипт поддерживает комментарии, для упрощения группировки
# и документирования

# Удалить директорию вместе со всеми файлами
some-dir

# Удалить конкретный файл
another-dir/some-file.txt

# Удалить всё в директории dir, но саму директорию оставить
dir/**

# Не удалять конкретный файл
!build/script.min.js

# Удалить все файлы с конкретным расширением
fonts/**/*.ttf
```