# pole_chudes
Это игра, в которой пользователю предлагается угадать слово.

**Название: «Поле чудес»**

Описание, правила и механизмы игры: Это игра, в которой пользователю предлагается угадать слово.
Осуществляется ввод по одной букве алфавита, и если такая буква в слове присутствует, то она открывается на импровизированном «экране»,
представляющим из себя набор звездочек (количество звездочек строго по длине слова).
В случае если игрок не угадал букву в слове, то выводится сообщение «Вы не угадали букву», и предлагается ввод новой буквы.
В случае, когда пользователь угадал слово по буквам, или угадал слово целиком, выводится само слово, сообщение о победе и количестве сделанных попыток.

**Возможности игры, используемые команды, другие особенности:**

-	Ввод осуществляется по одной букве или словом целиком

-	Есть возможность вызвать справку по игре, написав команду «!help»

**Технологии в проекте:**

•	Справа по игре вызываемая с помощью команды !help реализована с помощью отдельной функции в коде проекта

•	В проекте используется случайный выбор «random.choice» одного слова из кортежа «start_word_1»

•	Происходит формирование «маски» слова, состоящей из символа «*», по количеству букв в слове.




This is a game in which the player is going to guess the word.

**Heading: "The field of wonders"**

Description and rules of the game: In this game the player is asked to guess the word.

One letter of the alphabet is given by the player, and if the letter is presented in the word, it becomes opened on the screen.

The screen is a set of asterisks, the number of which equals to the length of the word.

If the player gave the wrong ansewer, the message "You did not guess the letter" is displayed, and a new letter guess is offered to the player.

In the case when the player named the word by a letter or guessed the whole word, the word itself is displayed and a message about the victory is shown along with the number of made attempts.

**The abilities, commands are used:**

- Input is required by one letter or by the whole word

- It is possible to call The Help Window for the game by writing the command "!help"

**Technologies of the project:**

- The Help Window is implemented using a separate function in the project code

- The project uses random selection "random.choice" of one word from the "start_word_1" tuple

- There is a formation of the word "mask" of the word consists of the symbol "*". The length of the mask is based on the number of letters in the word.
