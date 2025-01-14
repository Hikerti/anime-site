<head>
    <link rel="stylesheet" href="public/style/styleDoc.css">
</head>
<body>
Сайт "" создан командой QIK. 

Привет всем, кто читает эту документацию, здесь я расскажу и покажу как базова работать с git и GitHub, что бы мы вместе смогли работать над одним проектом.

<span class="first__color__text">**Введение**</span>

**Git** — это инструмент для управления версиями вашего кода, а **GitHub** — это платформа для совместной работы над проектами.

Наш проект будет в себе хранить следующие структуры:

1. **Главная ветка**: она будет называться main - ней будет уже готовый и проверенный код.
2. Каждому разработчику нужно будет создавать собственную ветку в которая должна быть названа так (участок сайта за который вы отвечаете/ник) например nav-bar/Hikerti. 

<span class="second__color__text">Настройка VS Code</span>

1. Скачай **Git**: [https://git-scm.com](https://git-scm.com)
2. Установи его на компьютер.
3. Проверь установку, выполнив команду в терминале:

   <pre><code>git --version</code></pre>

🚀<span class="second__color__text"> Как начать работу?</span>

1. Склонируйте репозиторий 

    <div>
        <pre><code>git clone <a>https://github.com/Hikerti/anime-site</a></code></pre><br>
        <pre><code>cd anime-site</code></pre>
    </div>

2. Создать свою ветку

    <div>
        <pre><code>git checkout -b название-ветки</code></pre>
        <p>Пример</p>
        <pre><code>git checkout -b nav-bar/Hikerti</code></pre>
    </div>

💾<span class="second__color__text"> Как отправить изменения</span>

1. Проверить статус изменений

    <div>
        <pre><code>git status</code></pre>
    </div>

2. Добавить изменения

    <div>
        <pre><code>git add .</code></pre>
    </div>

3. Сделать коммит

    <div>
        <pre><code>git commit -m "описание изменения"</code></pre>
    </div>

4. Отправить изменения на GitHub

    <div>
        <pre><code>git push origin название ветки</code></pre>
    </div>

🔄<span class="second__color__text"> Как обновить код из ветки main</span><br>
Если кто-то внёс изменения в main, их нужно скачать:

1. Переключись на ветку main:
    <pre><code>git chechout main</code></pre>
2. Обнови код:
    <pre><code>git pull origin main</code></pre>
3. Вернись в свою ветку:
    <pre><code>git checkout название ветки</code></pre>
4. Обнови свою ветку:
    <pre><code>git merge main</code></pre>
</body>

🔀<span class="second__color__text"> Слияние ветки через Pull Request</span><br>
1. Перейди на GitHub (Например: <a>https://github.com/Hikerti/anime-site/branches</a>).
2. Нажми "Compare & pull request" рядом со своей веткой.
3. Опиши изменения и отправь запрос (например: я сделал nav-bar в хедере сайта).

📝 <span class="second__color__text"> Полезные команды Git</span><br>

Проверить статус изменений
<pre><code>git status</code></pre>
Показать все ветки
<pre><code>git branch</code></pre>
Переключиться на ветку
<pre><code>git checkout название	</code></pre>
Добавить все изменения
<pre><code>git add .</code></pre>	
Зафиксировать изменения
<pre><code>git commit -m "Комментарий"</code></pre>	
Отправить ветку на GitHub
<pre><code>git push origin ветка</code></pre>
Скачать изменения из main	
<pre><code>git pull origin main</code></pre>	
Слить main в свою ветку
<pre><code>git merge main</code></pre>	
