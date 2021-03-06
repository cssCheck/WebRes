# GIT

### Создание нового репозитория

```bash
git init  # создать новый репозиторий в текущей папке
git init path/to/  # создать новый репозиторий в указанной папке
```

### Клонирование удаленного репозитория

```
git clone git@github.com:...                 # клонировать удаленный репозиторий в одноименную папку
git clone git@github.com:... foldername      # клонировать удаленный репозиторий в папку «foldername»
git clone git@github.com:... .               # клонировать репозиторий в текущую папку
```



 ключ | описание |
|--|--|
|```  ```|  |
|```  ```|  |
|```  ```|  |
|```  ```|  |

# Файловая структура

Перейти в директорию
```
cd /path-to-cat/
```
Перейти в домашнюю директорию
```
cd ~
```
Перейти в родительскую директорию
```
cd ..
```
Узнать путь к текущей директории
```
pwd
```
Список директорий и файлов в текущей директории
```
ls
``` 

| ключ | описание |
|--|--|
| ``` -l ```| Список директорий и файлов в текущей директории с подробной информацией о файлах |
| ``` -a ``` | Список директорий и файлов включая начинающиеся с . сокращенный список |
| ``` -all ``` | Список директорий и файлов включая начинающиеся с . полный список |
| ``` -clt ``` | Cортировать по времени изменения |
| ``` -cl ``` | Выдавать время изменения и сортировать по имени |
|``` -g ```| Список директорий и файлов в текущей директории с подробной информацией о файлах, но без имени владельца |
|``` -h ```| c -l, печатать размеры в удобном для человека виде |
|``` -m ```| выдавать список на всю ширину через запятую |
|``` -p ```| добавляет индикатор к каталогам |
|``` -o ```| не выводить информацию о группе, можено испольовать вместо -l |
|``` -S ```| сортировать по размеру файла |
|``` -t ```| сортировать по времени изменения |
|``` -1e ```| все записи в один столбец |

Скопировать содержимое файла file1 в file2 без изменения имен самих файов
```
cp
```

Скопировать файл или директорию и всё их содержимое (рекурсивное копирование)
```
cp -R {original_name} {new_name} 
```

Создание папки. Создаст папку с указанным именем или в текущем каталоге или по указанному пути. 
```
mkdir path/foldername
md path/foldername
```

| ключ | описание |
|--|--|
|``` -p, --parents ```| Создает родительский каталог если его нет, вместо ошибки. |



# Прочие утилиты и команды

Календарь. По умолчанию выведет текущий месяц текущего года.
```
cal
```
| ключ | описание |
|--|--|
|``` -j ```| Числа месяцев заменяются на порядковый день в году (Юлианский календарь). |
|``` -y yyyy ```| Выводит полный год. Можно указать год. |
|``` -m mm yyyy```| Позволяет указать месяц, который нужно отобразить. Можно комбинировать с годом. |
|``` ncal -o yyyy ```| Расчитывает дату православной Пасхи в указанный год. |
|``` ncal -e yyyy ```| Расчитывает дату католической Пасхи в указанный год. |
