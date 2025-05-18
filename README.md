как делать сообщение с переводом в коде

функция BREACH.TranslateString ищет фразы и переводит их в тексте
и возвращает весь переведённый текст

функция L эквивалентна функции выше
например: L"l:already_have_the_bag"

функция BREACH.TranslateNonPrefixedString ищет целый текст без l: в начале и переводит его по этой таблице

чтобы обозначить фразу для перевода в тексте ставим l: перед фразой
например: l:already_have_the_bag

вносим в таблицу сюда
например: kazakh.already_have_the_bag = "На вас уже надета сумка!"

и как это должно быть в коде
BREACH.TranslateString"l:already_have_the_bag"
или
str = BREACH.TranslateString(str)
или L"l:already_have_the_bag"