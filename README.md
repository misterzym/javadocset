RU:javadocset
==========
Это порт javadocset инструмента. Я портировал этот инструмент в качестве упражнения для использования Golang, а также для содействия пользователям Zealdoc, поскольку большинство пользователей Dash, использующих Mac, могут запускать инструмент Kavli javadocset который можно найти [здесь](https://github.com/Kapeli/javadocset)).

# Инструкции по сборке

## Предпосылки
Вам необходимо установить Go 1.8.3 и выше, чтобы использовать этот инструмент

## Инструкции
Это так просто, как:
```
go get github.com/inconshreveable/log15
go get github.com/mattn/go-sqlite3
go get github.com/misterzym/jdocset
```

## Использование
```
javadocset <имя документа> <папка Javadoc>
# где:
# <docset name> = имя документа, которое появится на Dash / Zeal
# <Папка Javadoc> = папка, содержащая сгенерированный HTML-документ Java
```

# Основы
Кредиты поступают в Kapeli: [https://github.com/Kapeli/javadocset](https://github.com/Kapeli/javadocset)

Zeal: [https://github.com/zealdocs/zeal](https://github.com/zealdocs/zeal)

Dash: [https://kapeli.com/dash](https://kapeli.com/dash)

## Заметка
Нет гарантии, что это будет работать на 100%. Я старался изо всех сил проверить, что у меня есть документ на Java, но могут быть ошибки, которые у меня не было возможности обнаружить. Пожалуйста, откройте вопрос, если у вас возникли проблемы!


EN:javadocset
==========

This is a port of Kapeli's javadocset tool in Golang. I ported this tool as an exercise for me to use Golang and also to contribute to Zealdoc's users as most Dash users who use a Mac are able to run Kapeli's javadocset tool (which can be found [here](https://github.com/Kapeli/javadocset)).

# Build Instructions

## Prerequisites
You need to have Go 1.8.3 and above installed to be able to use this tool

## Instructions
It's as simple as:
```
go get github.com/misterzym/jdocset
```

## Usage
```
javadocset <docset name> <Javadoc folder>
# where:
#	<docset name> = the name of the docset that will appear on Dash/Zeal
#	<Javadoc folder> = the folder containing the generated HTML Java doc 
```

# Credits
Credits go to Kapeli: [https://github.com/Kapeli/javadocset](https://github.com/Kapeli/javadocset)

Zeal: [https://github.com/zealdocs/zeal](https://github.com/zealdocs/zeal)

Dash: [https://kapeli.com/dash](https://kapeli.com/dash)

## Note
There is no guarantee that this will work 100%. I've tried my best to verify against a Java doc that I own but there may be bugs that I've not had the chance to discover. Please open an issue if you're having any trouble!

Pull requests are welcome :)
