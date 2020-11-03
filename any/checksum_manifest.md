# Алгоритм генерации чексуммы 

### [ТОЛЬКО ДЛЯ ТЕСТИРОВАНИЯ И РАЗРАБОТКИ МОДА!] 
### [МОДИФИКАЦИЯ ФАЙЛА НЕ ДАСТ ВАМ ДОСТУП К АЧИВКАМ ИЛИ ВОЗМОЖНОСТИ ИЗМЕНИТЬ ИГРУ] 

Файл: [checksum_manifest.txt](https://github.com/ParadoxModding-RU/documentation/blob/master/any/checksum_manifest.txt)

[Cкачать файл для разработки мода, чтобы игнорировать чексумму и для внутрененного тестирования мода](https://raw.githubusercontent.com/ParadoxModding-RU/documentation/master/any/checksum_manifest_modify.txt) 

Инструкция: 
1. Сохранить как -> .txt файл, название checksum_manifest
2. Закинуть в корень игры, где лежит hoi4.exe


## Информация:
**Шаблон**
```
directory
name = common (string) # папка, которая будет индексироваться
sub_directories = yes (bool) # будут ли индксироваться подпапки?
file_extension = .txt (string) # тип файлов.
```
**Перевод и адаптация:**
```
Папка: common (string) # папка, которая будет индексироваться
Подпапки: yes/no (bool) # будут ли индксироваться подпапки?
Тип файлов: (string) # тип файлов.
```
## **Ванильная генерация чексуммы:**

1.
```
Папка: common
Подпапки: да 
Тип файлов: .txt .lua 
```

2. 
```
Папка:  events
Подпапки: да
Тип файлов:  .txt
```

3. 
```
Папка: history
Подпапки: да
Тип файлов:  .txt
```

4.
```
Папка: map
Подпапки: да
Тип файлов:  .txt .map .bmp .csv
```
