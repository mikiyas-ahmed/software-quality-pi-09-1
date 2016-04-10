# Інструкція для запуску проекту #

**В кого нема TortoiseSVN качаєм проект тут**
  * http://code.google.com/p/software-quality-pi-09-1/downloads/detail?name=TouristAgency.rar&can=2&q=#makechanges
  * архів потрібно розпакувати

**Кому потрібний Eclipse**
  * http://www.eclipse.org/downloads/

**Також для роботи проекту потрібний MySQL**
  * http://dev.mysql.com/downloads/installer/
  * щоб скачати потрібно зареєструватись на сайті)

**Установка MySQL:**

  * запустити установку
  * нажати Install MySQL Products
  * в меню Setup Type вибрати Full
  * в меню Configuration -> Security Setting поставити пароль root
  * перезагрузити комп`ютер

**Eclipse:**

  * запускаєм Eclipse
  * в package Explorer нажимаєм правою кнопкою мишки і в меню вибираєм Import
  * у вікні Import вибираем Existing Projects into Workspace, Next
  * в пункті Select root directory нажимаєм на кнопку Browse..
  * вказуєм папку з проектом, Finish

**Створення бази даних:**

  * запустити MySQL Workbench 5.2 CE
  * нажати Local instance MySQL55
  * в Eclipse в імпортованому  проекті відкрити файл database.sql
(Kursova\database\database.sql)
  * скопіювати код створення бази
  * вставити у MySQL Workbench і нажати на кнопку Execute
  * запустити проект в Eclipse і перевірити чи все працює)