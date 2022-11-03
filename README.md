# LatexTemplate

## Установка
Для работы LaTeX, необходимо скачать сам [https://miktex.org/download](LaTeX), скачать python и установить pygmentize.

## Компиляция
Для компиляции в консоли набираем следующую команду: xelatex -shell-escape -halt-on-error _имя_файла_

## Программа для работы
Для работы с LaTeX документами удобно использовать [https://texstudio.sourceforge.net/](TeXstudio).
Сразу после ее установки в настройках необходимо установить компилятор, который мы используем. Для этого переходим в Options→Configure TeXstudio…→Build→Default Compiler:
![image](https://user-images.githubusercontent.com/86663719/199741267-bfe09e86-5b81-4ea3-840b-f605b8ac88d7.png)
Далее идем в Commands и изменяем команду запуска нашего компилятора:
![image](https://user-images.githubusercontent.com/86663719/199741408-719dbdd5-56c0-4ebc-92f1-5ea7d56ac7d0.png)
Так же нужно включить проверку орфографии по [https://harrix.dev/blog/2013/spell-check-in-texstudio/](данному гайду).
