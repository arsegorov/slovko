SLOVKO
===
a WORDLE clone in Russian


Rules
---
The game selects a random 5-letter word, but doesn't show it to the player. The goal is to guess the word in 6 or fewer attempts.

On each attempt, the player types in their guess into the grid, and then clicks `Enter`. After the attempt, the game provides feedback on each letter in the attempt:

+ If the letter is present in the correct answer and is in the correct position, it's highlitghted green.
+ If the letter is present in the correct answer, but is not in the correct position, it's highlighted yellow.
+ If the letter is missing in the correct answer, it remains unhighlighted.

**Note:** Each letter in the guess word is highlighted at most as many times as it occurs in the correct answer.
The extra occurences of each letter in the guess word remain unhighlighted.

The prior attempts and feedback remain visible to the player. For player's convenience, the presence of the letters in the word is also shown on the on-screen keyboard.

### Russian-specific rules

+ The selected and guess words should be singular nouns in nominative (subject) case.
+ The Russian letter `Ё` is shown as `Е` and is like `Е` in the correct answer and in the feedback.  
  For example, if the game selects the word `ёршик`,
  which would be displayed by the game as `ЕРШИК`,
  and if the player guesses `ПЕРЕЦ`,
  the game will highlight the first `Е` and the `Р` yellow.

&nbsp;

&nbsp;


СЛОВКО
===
клон WORDLE на русском


Правила
---
Игра загадывает 5-буквенное слово, не показывая его игроку. Цель игры - угадать загаданное слово за 6 или менее попыток.

С каждой попыткой игрок вводит слово на игровое поле и жмёт `Enter`. После этого игра сообщает игроку о наличии каждой буквы из данной попытки в загаданном слове:

+ Если буква из попытки находится на том же месте, что и в загаданном слове, то буква подсвечивается зелёным.
+ Если буква встречается в загаданном слове, но на другом месте, то буква подсвечивается жёлтым.
+ Если буква не встречается в загаданном слове, то она остаётся неподсвеченной.

**Замечание:** Каждая буква в попытке подсвечивается не больше раз, чем она встречается в загаданном слове.
Лишние повторы буквы в попытке не подсвечиваются.

Предыдущие попытки остаются видны игроку вместе с подсветкой. Для удобства игрока, встречающиеся и невстречающиеся в загаданном слове буквы так же показаны на экранной клавиатуре.

### Правила, специфичные для русских игр со словами

+ Загаданное слово и попытки игрока должны быть существительными в единственном числе и именительном падеже.
+ Буква `Ё` приравнивается к букве `Е` во всех проверках и изображается так же.  
  Например, если загадано слово `ёршик`, то игра показала бы его как `ЕРШИК`,
  а если игрок проверит слово `ПЕРЕЦ`, то игра подсветит первую букву `Е` и букву `Р` жёлтым.
