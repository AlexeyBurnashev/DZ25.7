# DZ25.7 Homework for Skillfactory. module 25

Реализована консольная программа чат с использование архитектуры клиент-сервер, хранение всех данных происходит в базе данных на сервере.
Клиент при своём старте связывается с сервером по IP-адресу сервера и порту, далее необходимо залогиниться на нём, передав ему свой логин и пароль.
После успешного входа, сервер в ответ высылает список пользователей и историю сообщений. Основным достоинством этой архитектуры является то, что все данные хранятся в одном месте, и так проще и надёжнее можно организовать целостность базы данных и синхронизацию данных между различными клиентами.
В базу данных занесены данные пользователей для теста (пользователи с логинами АА, GG, FF и паролем: 12345(для всех)).
