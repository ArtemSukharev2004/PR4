FROM eclipse-temurin:17-jdk-alpine
#FROM - Указывает базовый образ.
LABEL version = "1.0.1"
#LABEL - Добавляет метаданные к образу
WORKDIR /testdir/java
#WORKDIR - Устанавливает рабочий каталог для инструкций
COPY . /testdir/java/
#COPY - Копирует файлы или директории в образ
CMD [ "java", "calc.java" ]
#CMD - Устанавливает команду по умолчанию