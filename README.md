Проект игра жизнь

Описание игры

В игре "Жизнь" вы не управляете клетками напрямую, а наблюдаете за их эволюцией на игровом поле. Каждая клетка может находиться в двух состояниях: "Живая" (0) и "Пустая" (1). Игра происходит в двухмерном пространстве на квадратном игровом поле.

Игровые правила:

Если у клетки ровно три соседа, и она пуста, то в следующем поколении она станет живой. Если у живой клетки два или три соседа, то она продолжает оставаться живой. В противном случае, если у клетки меньше двух или больше трех соседей, она умирает в следующем поколении. Ваша задача заключается в наблюдении за эволюцией клеток на игровом поле. Вы можете запустить игру, нажав кнопку "Start" в главном меню. После запуска, клетки будут развиваться автоматически в соответствии с правилами игры. Вы можете наблюдать, как появляются новые клетки, как они взаимодействуют друг с другом и как некоторые клетки исчезают.

Если вы хотите посмотреть результаты предыдущих запусков игры, вы можете нажать кнопку "Results" в главном меню. Там будет отображена таблица с номерами выполнений игры и их продолжительностью (количество циклов).

Вы также можете выйти из игры, нажав кнопку "Exit" в главном меню.

Примечание: В предоставленном коде игра "Жизнь" просто запускается и продолжает работу, пока не будет достигнуто условие окончания (например, повторение предыдущего состояния). Вы можете изменить это поведение, добавив дополнительные элементы управления или условия окончания, чтобы сделать игру более интерактивной.

Запуск

pip install -r libs.txt
python main.py
