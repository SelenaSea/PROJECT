# PROJECT Quiz Freeze


ЛЕГЕНДА Вы продолжаете работу над мобильной игрой Quiz Freeze.

Коллеги были впечатлены тем, как вы справились с анализом пути пользователей. А ещё до них дошли слухи о том, как вы помогли букмекерской конторе выйти из онлайна в офлайн :)

В общем, коллеги вновь обратились к вам за помощью. На сей раз вам необходимо проверить несколько гипотез.

Вот список вопросов, который вы составили после встречи с командой.

Гипотеза 1

По идее, должна быть разница в поведении групп, которые проходят и не проходят обучение. Но так ли это? Влияет ли обучение на скорость прохождения других этапов игры? Гипотеза 2

Кажется, повторное прохождение обучения положительно влияет на оплату, верно? Гипотеза 3

Если пользователь сначала выбирает сложность, будет ли он потом проходить обучение? Ну что, готовы как следует потрудиться?

Сроки горят, но задача (как, впрочем, и всегда) весьма интересна!

Этапы игры На всякий случай напомним ключевые этапы пути пользователя.

Регистрация

Старт обучения Завершение обучения Выбор уровня сложности вопросов Выбор пакетов вопросов Покупка платных пакетов вопросов Регистрация (registration) — это обязательный этап. Без регистрации пользователь не может пройти на следующие этапы работы с приложением.

Старт обучения (tutorial start) — опциональный этап. Пользователь после регистрации может перейти к обучению работе с приложением, а может и не перейти. При этом вернуться к обучению можно в любой момент. А ещё можно пройти обучение несколько раз.

Завершение обучения (tutorial finish) может произойти только в случае, если ранее произошло событие «Старт обучения», но при этом пользователь может не завершить обучение.

Выбор уровня сложности вопросов (level choice) — это обязательное событие, которое нужно для того, чтобы перейти к выбору пакетов вопросов. Таким образом, пользователь может не пройти обучение или даже не начинать его, но прежде чем начать отвечать, он обязан выбрать уровень сложности.

Выбор пакетов вопросов (pack choice, другое название training choice) — это этап, на котором пользователь выбирает себе бесплатный набор пакетов вопросов, на которые он будет отвечать.

Покупка платных пакетов вопросов (purchase) — это факт совершения оплаты за вопросы, которые не доступны в списке бесплатных вопросов.

ЦЕЛЬ Исследовать поведение пользователей в обновлённом приложении.

ЗАДАЧИ В рамках проверки гипотез вам необходимо решить три задачи:

Определить, насколько обучение сокращает время прохождения этапов игры. Доказать, что успешное обучение само по себе влияет на оплату и не имеет значения то, каким этапом оно шло. Определить, насколько прозрачен процесс взаимодействия с игрой. КОНКРЕТНЫЕ ШАГИ (ФОРМАЛИЗОВАННЫЕ ЗАДАЧИ) Сравнить время прохождения различных этапов для пользователей, которые завершили обучение, и пользователей, не начинавших обучение. Если показатель отличается, выяснить, насколько. Проверить, существует ли зависимость между вероятностью оплаты вопросов и количеством обучений, которые начинал или завершал пользователь. Выяснить, как часто пользователи начинают обучение после выбора уровня сложности. (Это позволит оценить прозрачность процесса взаимодействия с игрой: если пользователи после выбора уровня сложности обращаются к обучению, значит, работа с приложением непонятна.)
