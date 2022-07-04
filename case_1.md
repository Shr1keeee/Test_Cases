TC ID: TC0001
Priority: 1
IDEA: Зарегистрировать новый аккаунт пользователя.
          SETUP and ADDITIONAL INFO:
E-mail: utest@mail.ru
Password: utest123
SQL1: SELECT u_id 
      FROM reg_users
      WHERE email = 'utest@mail.ru';  
      Revision History
Created on: 04/07/2022 by Pronin                                 | Новый тест кейс
      Execution part
PROCEDURE                                                        |     EXPECTED RESULT
1. Открой www.test.ru
2. Перейди на страницу регистрации нового пользователя.
3. Введи данные из секции SETUP and ADDITIONAL INFO.
4. Запроси базу данных с SQL1 и запиши результат.                |  > "u_id 1"
5. Проверь наличие страницы с сообщением о успешной регистрации. |  Шаг 1 - Шаг 3 > "Cтраница о успешной регистрации "Пользователь зарегистрирован"

