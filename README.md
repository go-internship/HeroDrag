# HeroDrag
**Для запуска игры:**
***
- 1.В терминале перейдите в рабочую директорию, куда хотите сохранить проект.
- 2.Далее в терминале выполните эту команду "git clone https://github.com/go-internship/HeroDrag.git"
- 3.После клонирования репозитория с помощью команды "cd" пройдите в папку проекта и запустите программу с помощью команды "go run main.go".

**Особенности игры**
***
***Легкий уровень:***
- В принципе при легком уровне особенностей нету, Герой первым наносит удар, Дракон дает сдачу. И у Героя, и у Дракона есть возможность атаковать, лечиться.(Во всех уровнях)
*** 
***Средний уровень:***
***
В среднем уровне есть такие фичи как:
- 1.Усталость.Когда усталость персонажей игры достигает определенного значения, то при ударе у них есть шанс промахнуться.Значение пареметра усталости поднимается при каждой атаке Героя или Дракона.
- 2.Случайное событие. Событие может произойти в любое время игры, и дать персонажам в зависиммости от рандомных значений  преимущество Герою или Дракону.
- 3.Оружие тупится.При каждом ударе Героя оружие тупится, и наносимый им урон становится все меньше и меньше.
***
***Сложный уровень:***
***
- 1.Броня. У Героя может активироваться броня при определнных условиях.Броня увеличивает уровень жизни Героя.
- 2.Злость. Когда злость персонажей игры достигает определенного значения, то при атаке сила удара возрастает и наносит соответсвенно больше урона, но при этом также во много раз увеличивается шанс того, что персонажы промахнутся.Значение параметра злости возрастает с каждым ударом противника по Вам и наоборот.
- 3.Также у Героя уменьшено рандомное значения урона.Ниже на 10 пунктов, чем в первых двух уровнях.
- 4.Время хода Героя ограничено.Так что недолго думая нажимайте на цифры.
- 5.Но при всех этих минусов у Героя , он обладает Супер Ударом. Так что если Герой выиграет при сильной разнице уровней жизни(ваша меньше), то не удивляйтесь!
***
***Общие фичи***
***
- 1.Можно задавать имя Героя и Дракона
- 2.Можно задать имя Дракона случайным образом
- 3.Отображение информации о ходе игры (уровень жизни, количество ходов,действие пресонажей)
- 4.Герой может выбирать оружие, но толку от того какое оружие он выберит, нету!
- 5.Есть бонус, если Герой побеждает, то он получает крутую цитату.
- 6.Сохранение игры
