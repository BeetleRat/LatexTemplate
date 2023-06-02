# LatexDoxigenTemplate

## Установка
Для работы LaTeX, необходимо скачать сам [LaTeX](https://miktex.org/download), скачать python и установить pygmentize(python -m pip install Pygments).

Далее необходимо обновить LaTeX до последней версии. Для этого открываем MiKTeX Console от имени администратора и скачиваем все пакеты и обновления. 
<span style="color:red"> Консоль может ругаться, но продолжит обновлять пакеты - **дождитесь обновления пакетов**.</span>

![image](https://user-images.githubusercontent.com/86663719/226546812-cee77cee-b2e5-440e-a901-532f247520f3.png)


Перейдите в командную строку windows и наберите:

```java
xelatex -version
```

Командная строка затупит, а потом до установит нужные пакеты.

## Работа со сгенерированной Doxygen документацией
Скопируйте данный репозиторий в папку latex сгенерированную Doxygen, таким образом, чтобы файлы: «01. MakeDoc.bat», «generated_content.tex», «report.tex» и папка «preamble» находились в одной папке с файлами «refman.tex» и make.bat.

Запустите файл «01. MakeDoc.bat».
