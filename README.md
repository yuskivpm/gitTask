# Завдання: спільно сформувати у правильному порядку текст пісні.

1. Кожен має свою частину рядків з пісні (вони спеціально перемішані для провокації конфліктів) записану у файлі readme.md.
2. Прямий запис у гілки master/develop – **ЗАБОРОНЕНИЙ**.
3. Кожен працює у своїй (самим створеній) гілці, назва якої має вигляд "**feature/_yourName_"** (де "_yourName_" - визначається вами).
4. Додавання результату до зведеної роботи (до **develop**-а) ТІЛЬКИ через `pull request`, який самі й погоджуєте, усуваючи при цьому конфлікти.
5. За один `pull request` можна додати лише один рядок з своєї частини пісні (ну, просто, щоб повторити ці дії декілька разів для кращого запам’ятовування).

Кожен учасник для додаванні рядка:

-   створює НОВУ гілку "**feature/…**" (на кожен рядок - нову), яка є відгалуженням від гілки "**master**" (для першої половини рядків) або "**develop**" (для другої половини рядків).
-   додає до вже наявної частини пісні у відповідну (по відношенню до інших вже присутніх у файлі) позицію свій рядок (пусті строки до/після свого рядка – не вставляти).
-   пушить свою гілку на віддалений репозиторій.
-   переходить на `github.com` і створює `pull request` для злиття даних своєї гілки у **develop**.
-   самостійно підтверджує `pull request` та вирішує конфлікти, які при цьому можуть виникнути.

<code>
1. Ініціалізація завдання (робиться один раз)
   1.1. Клонуємо репозиторій на свій комп’ютер
   `git clone https://github.com/yuskivpm/gitTask.git`
   1.2. Заходимо у нього
   `cd gitTask`
   1.3. З’єднуємось з гілкою **develop**
   `git checkout -b develop origin/develop`
   1.4. Скачуємо її оновлення
   `git pull`
   1.5. Повертаємось на **master**
   `git checkout master`
</code>

# Мікс:

<pre><code>
As if nothing really matters
Mama, life had just begun
Mama, ooh
But now I've gone and thrown it all away
Put a gun against his head
Carry on, carry on
Didn't mean to make you cry
Gotta leave you all behind and face the truth
I don't want to die
I sometimes wish I'd never been born at all
If I'm not back again this time tomorrow
Mama, just killed a man
Goodbye everybody, I've got to go
Mama, ooh
Body's aching all the time
Pulled my trigger, now he's dead
Sends shivers down my spine
Too late, my time has come
</code></pre>

# Кінцевий результат має бути таким:

<pre><code>
Mama, just killed a man
Put a gun against his head
Pulled my trigger, now he's dead
Mama, life had just begun
But now I've gone and thrown it all away

Mama, ooh
Didn't mean to make you cry
If I'm not back again this time tomorrow
Carry on, carry on
As if nothing really matters

Too late, my time has come
Sends shivers down my spine
Body's aching all the time
Goodbye everybody, I've got to go
Gotta leave you all behind and face the truth

Mama, ooh
I don't want to die
I sometimes wish I'd never been born at all
</code></pre>

#Спойлер

-   [інструкція](https://docs.google.com/document/d/11qNa09Wnv2KUQtzfVJNyFpbyHk6IIAGU8jnC_Fn3Nvg/edit?usp=sharing) на крайній випадок)))
