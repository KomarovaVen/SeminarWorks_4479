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

---------------   ---------------- 
| First Header |  | Second Header | <br>
---------------   ----------------  <br> 
| Content Cell |  | Content Cell  | <br>
---------------   ----------------
| Content Cell |  | Content Cell  | <br>
---------------   ----------------

Для красоты можно и по бокам линии нарисовать:

---------------   ----------------
| First Header |  | Second Header |<br>
---------------   ----------------
| Content Cell |  | Content Cell  |<br>
---------------   ----------------
| Content Cell |  | Content Cell  |<br>
---------------   ----------------

Можно управлять выравниванием столбцов при помощи двоеточия.

-----------------    -----------------     --------------
| Left-Aligned  |	| Center Aligned  |	  | Right Aligned| <br>
-----------------    -----------------     --------------
| col 3 is      |	| some wordy text |   |         $1600| <br>
-----------------    -----------------     --------------
| col 2 is      |	| centered        |	  |           $12| <br>
-----------------    -----------------     --------------
| zebra stripes |	| are neat	      |   |            $1| <br> 
-----------------    -----------------     --------------

Внутри таблиц можно использовать ссылки, наклонный, жирный или зачеркнутый текст.

## Ссылки
Самый лёгкий способ поместить ссылку в Markdown — заключить её в угловые скобки. Несмотря на простоту, он не является основным и был добавлен только в спецификации CommonMark.

Чтобы оформить ссылкой часть текста, используется такой синтаксис: [текст](ссылка). Можно сделать всплывающую подсказку при наведении курсора. Для этого в круглых скобках после ссылки нужно поставить пробел и написать текст подсказки в кавычках.
Ещё один способ оформить ссылку — справочный. Он работает как сноски в книгах: [текст][имя_сноски]. При таком способе организации ссылок в конце документа нужно также написать и оформить саму сноску: [имя сноски]: ссылка. При желании после ссылки можно добавить подсказку — точно так же, как в предыдущем методе.

Имя сноски может быть любым сочетанием символов: цифрами, буквами и даже знаками препинания. На одну и ту же сноску в тексте можно ссылаться сколько угодно раз.

Ссылки, оформленные справочным методом, выглядят и работают точно так же, как и в предыдущем способе. Сами сноски в отформатированном документе не отображаются.