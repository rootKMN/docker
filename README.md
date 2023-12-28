

Определите разницу между контейнером и образом

Образ - это шаблон, на основе которого создается контейнер, существует отдельно и не может быть изменен.
При запуске контейнерной среды внутри контейнера создается копия файловой системы (docker образа) для чтения и записи.
Можно создать неограниченное количество образов Docker из одного шаблона.
Каждый раз при изменении начального состояния образа и сохранении существующего состояния создается новый шаблон с дополнительным слоем поверх него.

Контейнер - это виртуализированная среда выполнения, в которой пользователи могут изолировать приложения от хостовой системы.
Эти контейнеры представляют собой компактные портативные хосты, в которых можно быстро и легко запустить приложение.

Ответьте на вопрос: Можно ли в контейнере собрать ядро?
Собрать ядро можно. Но при этом нельзя с него будет загрузиться
