NeoMessenger - плагин для InstantCMS, позволяющий вести переписку в всплывающем окне.
================================================================================

### Установка плагина

    1. Временно отключите личные сообщения в настройках профилей, для того чтобы в базе не появились новые сообщения во время установки плагина.
    2. Удалите плагин в админке.
    3. Удалите физически директорию со старой версией плагина.
    4. Распакуйте в корень сайта содержимое папки src.
    5. В админке установите плагин.
    6. Удалите установочный файл "plugins/p_neomessenger/install.php"
    7. Включите личные сообщения.
    
### Если вам понравился плагин, и вы хотите поблагодарить автора за проделанную работу а также придать стимул для дальнейшей работой над плагином - перечислите любую сумму на один из этих электронных кошельков

    яндекс кошелек: 410011597295266
    webmoney:       R227906422600

### История изменений

    Версия 2.1.1
    
        [=] - Переписан код плагина (структурирован)
        [=] - Исправлен баг с установщиком (плагин не составлял список контактов если сообщений меньше 1000)
        [=] - Кнопка массовой рассылки перенесена в правую часть, и добавлено подтверждение
        [=] - Исправлено несколько опечаток в css
        [=] - немного изменен внешний вид при отправке сообщений
    
    Версия 2.1.0
    
        [=] - Перписан код плагина.
        [=] - Исправлено: при большом количестве смайлов окно вылазило за пределы страницы.
        [=] - Исправлено: Уведомление о новом сообщении отправлялось на почту даже если пользоваптель онлайн.
        [=] - Изменен внешний вид плагина.
        [+] - В админке можно выбрать способ отправки сообщений (Enter / Ctrl+Enter).
        [+] - Добавлена возможность показывать плагин только определенным пользователям во время отладки плагина.
        [+] - Окно со смайлами можно закрывать по кнопке Esc или нажав в любом месте страницы.
        [+] - Сохранение и восстановление набранного текста в поле ввода.
        [+] - Адаптивность под мобильные устройства.
        [+] - "Живой контакт лист" - Если вы написали сообщение контакту находящемуся в любом месте списка, он перемещается в верх списка, или вам написал контакт он тоже перемещается в верх списка.
        [+] - для администратора появилась возможность отправить сообщение всем пользователям сайта.
        [+] - В админке настраивается закрывать ли окно при клике на задний фон.
    
    Версия 2.0.1
    
        [=] - Плагин адаптирован под инстант версии 1.10.3
        [=] - Исправлено: при удалении сообщения одним участником переписки, сообщение не показывалось и у второго.
                  (Если вы удалили сообщение которое вы отправили но ваш контакт его еще не прочитал, то оно удалиться и у него)
        [=] - Изменен поиск контактов в списке
        [=] - несколько мелких исправлений
        [+] - Добавлена возможность удалить контакт из списка
        [+] - При входящем сообщении в заголовке страницы мигает текст: "****** у вас новое сообщение ******"