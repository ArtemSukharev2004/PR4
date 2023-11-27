FROM python:alpine
#FROM - Указывает базовый образ.
LABEL version = "1.0.1"
#LABEL - Добавляет метаданные к образу
WORKDIR /testdir/python
#WORKDIR - Устанавливает рабочий каталог для инструкций
COPY . /testdir/python/
#COPY - Копирует файлы или директории в образ
CMD [ "python", "calc.py" ]
#CMD - Устанавливает команду по умолчанию