# Инструкция _"How to work with GidHub repository"_

## Как тянуть проект себе и заливать его обратно?

1. Находим интересующий нас репозиторий и выбираем команду "Fork"
2. В Visual Studio Code созданем папку / открываем готовую папку и кланируем через команду **_clone_**.( git clone https....)

3. *указываем директорию /cd "Название"

4. Внутри создаем ветку

5. заходим в ветку и добавляем код:
```
public static void main(String[] args) {
System.out.println("Hello, World!");
}
```
далее производим команды git add , git commit -m "";

И push-им файл на GidHub;

После того как залили файл на GitHub (он меняется на Git другими участниками проекта=) - это к примеру

и обратное вытягиваем его в Visual Studio Code  через команду git pull
