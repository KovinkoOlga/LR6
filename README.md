#  Лабораторная работа №6
## Цель работы:

Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.

##  Ход работы

 1. Аккаунт GitHub был создан до выполнения лабораторной работы:<br>
 2. Сделан форк репозитория лабораторной:<br>

      ![1](https://github.com/KovinkoOlga/LR6/blob/report/screenshots/fork.png)

3. Git был установлен до выполнения лабораторной работы:<br>
4. Настройка клиента git bash:
   Установлены имя пользователя и почта <br>
   ![2](https://github.com/KovinkoOlga/LR6/blob/report/screenshots/username.png)
   ![3](https://github.com/KovinkoOlga/LR6/blob/report/screenshots/email.png)
5. Клонирован репозиторий на компьютер:<br>
   ![4](https://github.com/KovinkoOlga/LR6/blob/report/screenshots/clone.png)
6. Получена история операций:<br>
   ![5](https://github.com/KovinkoOlga/LR6/blob/report/screenshots/history.png)
7. При попытке слияния ветки branch1 в ветку master возникает merge-conflict:<br>
   ![6](https://github.com/KovinkoOlga/LR6/blob/report/screenshots/merge_0.png)<br>
   Текст конфликта:<br>
   ![7](https://github.com/KovinkoOlga/LR6/blob/report/screenshots/conf_text.png)<br>
   Решен конфликт путем удаления текста<br>
   ![8](https://github.com/KovinkoOlga/LR6/blob/report/screenshots/solved_conflict_text.png)<br>
   Зафиксированы изменения, конфликт решен и слияние завершено.
   ![9](https://github.com/KovinkoOlga/LR6/blob/report/screenshots/history_after_merge.png)<br>
8. Удаление ветки:<br>
    ![10](https://github.com/KovinkoOlga/LR6/blob/report/screenshots/branch_del.png)<br>
9. Изменения сделаны и зафиксированы, после чего был сделан откат последнего фиксированного изменения:<br>
    ![11](https://github.com/KovinkoOlga/LR6/blob/report/screenshots/revert.png) <br>
    ![12](https://github.com/KovinkoOlga/LR6/blob/report/screenshots/history_after_revert.png)
10. Получена история операций в форматированном виде<br>
    ![13](https://github.com/KovinkoOlga/LR6/blob/report/screenshots/end_log.png)
##  Вывод
В ходе выполнения лабораторной работы были изучены git и github, в частности инструменты для создания веток, решения конфликтов слияния и откатов последних зафиксированных изменений. 
