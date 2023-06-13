# Справка (туториал) по основам системы контроля версий GIT 
# Справка (туториал) по основам системы контроля версий GIT 


## Как инициализировать GIT
**Чтобы инициализировать репозиторий, необходимо прописать в терминале следующую команду:**

```
git init
```
## Привет, Мир! ##
### Я изучаю GIT ###
***Учиться всегда интересно и важно!***
***Учение свет,***~~Неучение тьма~~
<u>Не устраивает время начала семинаров</u>
<br>
- [text]
<br>
[GeekBrains](https://gb.ru/ "Перейди по ссылке")

# Туториал (справка) для работы с языком MarkDown

## Заголовки

Чтобы добавить заголовки, используйте символ (#).
Виды заголовков:

```
# Заголовок первого уровня #
## Заголовок h2
### Заголовок h3
#### Заголовок h4
##### Заголовок h5
###### Заголовок h6

```

В декоративных целях заголовки можно «закрывать» с обратной стороны.

## Цитаты

Цитаты оформляются как в емейлах, с помощью символа >.

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse id sem consectetuer libero luctus adipiscing.

Или более ленивым способом, когда знак > ставится перед каждым элементом цитаты, будь то абзац, заголовок или пустая строка:

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse id sem consectetuer libero luctus adipiscing.

В цитаты можно помещать всё что угодно, в том числе вложенные цитаты:

> ## This is a header.
>
>1. This is the first list item.
>2. This is the second list item.
>
>>Вложенная цитата.
>
>Here's some example code:
>
>   return shell_exec("echo $input | $markdown_script");


## Исходный код

В чистом Маркдауне блоки кода отбиваются 4 пробелами в начале каждой строки.

Но в GitHub-Flavored Markdown (сокращенно GFM) есть более удобный способ: ставим по три апострофа (на букве Ё) до и после кода. Также можно указать язык исходного кода.

``` 
<nav class="nav nav-primary">
  <ul>
    <li class="tab-conversation active">
      <a href="#" data-role="post-count" class="publisher-nav-color" data-nav="conversation">
        <span class="comment-count">0 комментариев</span>
        <span class="comment-count-placeholder">Комментарии</span>
      </a>
    </li>
    <li class="dropdown user-menu" data-role="logout">
      <a href="#" class="dropdown-toggle" data-toggle="dropdown">
        <span class="dropdown-toggle-wrapper">
          <span>
            Войти
          </span>
        </span>
        <span class="caret"></span>
      </a>
    </li>
  </ul>
</nav>

```

Самое приятное, что в коде не нужно заменять угловые скобки < > и амперсанд & на их html-сущности.

## Таблицы

В чистом Маркдауне нет синтаксиса для таблиц, а в GFM есть.

```
---------------   ---------------- 
| First Header |  | Second Header | 
---------------   ----------------  
| Content Cell |  | Content Cell  | 
---------------   ----------------
| Content Cell |  | Content Cell  | 
---------------   ----------------

Для красоты можно и по бокам линии нарисовать:

---------------   ----------------
| First Header |  | Second Header |
---------------   ----------------
| Content Cell |  | Content Cell  |
---------------   ----------------
| Content Cell |  | Content Cell  |
---------------   ----------------

Можно управлять выравниванием столбцов при помощи двоеточия.

-----------------    -----------------     --------------
| Left-Aligned  |	| Center Aligned  |	  | Right Aligned| 
-----------------    -----------------     --------------
| col 3 is      |	| some wordy text |   |         $1600| 
-----------------    -----------------     --------------
| col 2 is      |	| centered        |	  |           $12| 
-----------------    -----------------     --------------
| zebra stripes |	| are neat	      |   |            $1|  
-----------------    -----------------     --------------
```

Внутри таблиц можно использовать ссылки, наклонный, жирный или зачеркнутый текст.

## Ссылки