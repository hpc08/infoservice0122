Решение

    Подготовительные работы. Настройка:

        Создаём новый раздел и пункт меню;

        Создаём пользовательское свойство для пользователей - "Тип пользователя" (UF_AUTHOR_TYPE) согласно требованиям;

        Создать трех тестовых пользователей, логины: test1, test2, test3. Задаём значения свойства «Тип пользователя»;

        В информационном блоке "Новости" добавляем множественное свойство – "Автор" (AUTHOR), тип - привязка к пользователю;

        Добавляем три тестовые новости с произвольным контентом;

        Задаём значение свойства "Автор" для новостей;

    Написание компонента:

        Для ускорения процесса, копируем системный компонент Битрикс,и получаем всю необходимую структуру компонента, которую редактируем в соответствии с условиями задания;

        Копируем заготовку компонента из локальных материалов;

        Добавляем описание и параметры компонента:
           
        Логика реализации:
            Получаем всех пользователей такого же типа, как у текущего, кроме текущего
            Получаем новости, принадлежащие пользователям такого же типа, как у текущего, кроме текущего
            Группируем новости по пользователям
            Получаем количество уникальных новостей для подсчета
