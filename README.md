# course_work_6
Логика работы системы:

Авторизованный в системе пользователь может создать рассылку, содержащую его сообщение и предназначенную его клиентам (получателям).
Пользователь может отслеживать процесс (видит логи рассылки), отредактировать параметры рассылки или завершить её раньше срока.
Пользователь не может видеть рассылки, сообщения и клиентов других пользователей системы.
После создания новой рассылки, если текущее время больше времени начала (последней рассылки) и меньше времени окончания, то системно выбираются из справочника все клиенты, которые указаны в настройках рассылки, и запускается отправка сообщения для всех этих клиентов.
После отправки рассылки время следующей отправки системно переносится на указанный интервал времени.
Если создается рассылка со временем старта в будущем, то отправка стартует автоматически по наступлению этого времени без дополнительных действий со стороны пользователя системы.
По ходу отправки сообщений собирается статистика (Logs) по каждой рассылке.
Модератор может отключить рассылку, а также заблокировать пользователя.
Для продвижения сервиса создан раздел Блог, статьи рандомно отображаются на Главной странице сайта.
