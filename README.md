# megafon-klavogonki

Код встраивания можно увидеть в файле *index.html*. Вот пример:

    <div id="game-klavogonki"
         style="width:100vw;height:100vh;"
         data-base="./"
         data-share-url="https://tjournal.ru/special/megafon/"
         data-share-title="Клавогонки на TJournal"
         data-backend="http://localhost:8080/"
    >
    </div>
    <link rel="stylesheet" type="text/css" href="all.min.css">
    <script src="all.min.js"></script>

Параметр *data-base* — URL папки, в которой размещены изображения. Должен заканчиваться слешем.

Параметр *data-share-url* задает начало ссылки для шера. В этом примере для игрока, набиравшего текст со скоростью 245 символов в минуту, шер будет производиться на адрес https://tjournal.ru/special/megafon/245.

Параметр *data-share-title* — заголовок для шеров.

Параметр *data-backend* — адрес, на котором расположен бекенд.

Эта версия включает в себя библиотеку likely.js.