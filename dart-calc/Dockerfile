FROM dart:stable AS build
#FROM - Указывает базовый образ.
LABEL version = "1.0.1"
#LABEL - Добавляет метаданные к образу
WORKDIR /testdir/dart
#WORKDIR - Устанавливает рабочий каталог для инструкций
COPY . /testdir/dart/
#COPY - Копирует файлы или директории в образ
CMD [ "dart", "calc.dart" ]
#CMD - Устанавливает команду по умолчанию