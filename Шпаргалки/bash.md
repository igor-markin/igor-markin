# Шпаргалка по терминалу Bash

**Вырезать определённое количество символов из файла**

```bash
truncate -s 100 filename  # Удалит 100 символов от начала файла
truncate -s -50 filename  # Удалит 50 символов с конца файла
truncate -s 0 filename  # Очистит содержимое файла
truncate –s 0 /home/*.sh  # Очистит содержимое всех файлов .sh в директории
truncate –s 0 /home/**/*.sh  # Очистит содержимое всех файлов .sh во всех поддиректориях
```
