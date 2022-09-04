# Контроль версий GIT

## Инструкция по установке и настройке GIT и VSCode

## Команды GIT

**git init**
>git init
>>позволяет установить git в папку с проектом делая из неё репозиторий.



**git add**
>git add <название файла>
>>позволяет добавить изменения файла в репозиторий для дальнейших действий с ним.


**git commit**
>git commit -a
>>совершит **коммит**, автоматически индексируя изменения в файлах проекта. При этом новые файлы индексироваться не будут. Удаление же файлов будет учтено.

>git commit -m "commit comment"
>>комментируем **коммит** прямо из командной строки вместо текстового редактора.

**git diff**
>git diff
>>позволяет увидеть разницу между сохраненным файлом репозитория и программной среды.
>>
>>![Пример использования команды](git_diff.png)

**git log**
>git log
>>позволяет посмотреть журнал изменений.
![Пример использования команды](https://sun9-west.userapi.com/sun9-68/s/v1/ig2/RQ12UzuNUHDMP6iS0N_fPktL7RVRsTWPNwnbXedpK-bOCiUxifOBFeonQOe3H9YM3amBpCJ8bm1Ydwgt6ohtCsnN.jpg?size=503x592&quality=96&type=album)

>git log --graph
>>позволяет увидеть лог всех сохранений веток.
![Пример использования команды](https://sun9-east.userapi.com/sun9-41/s/v1/ig2/CCax3PkRojovDjTUkeiQwtzuS1v1xA9szy9IGlkMCp_eGOffZVmpg4LOV4kdfNVZTRYccp5yYxZWngFOmShu5qXW.jpg?size=505x598&quality=96&type=album)

**git branch**
>git branch
>>позволяет просмотреть ветки контроля версий.
>>
>>![Пример использования команды](https://sun9-west.userapi.com/sun9-38/s/v1/ig2/a6JQBOA4QsnFELFLv81ZiSVia1U0c_Sn-JeWQTrtpASuLsy-yz9HPYmdTconY6yHcXLcdShKV37aXJejH4F9WxL1.jpg?size=387x74&quality=96&type=album)

>git branch branch_name
>>позволяет удалить ветку.

>git branch -d branch_name
>>позволяет создать новую ветку.

**git checkout**
>git checkout branch_name
>>позволяет перемещаться между ветками контроля версий.
>>
>>![Пример использования команды](https://sun9-west.userapi.com/sun9-70/s/v1/ig2/bLcvxzeaLMikeD5ccpS4H2xwfLp1FG5Yp5sKGXpm6o4HorYp4ok7Niq_rXNCVPVdH3DNRnweXjJ2q_UmQyDcJ_dj.jpg?size=485x41&quality=96&type=album)

**git merge**
>git merge branch_name
>>позволяет делать слияние указанной ветки в текущую ветку.
>>
>>![Пример использования команды](git_merge.jpg)

**git status**
>git status
>>позволяет просмотреть статус репозитория с отслеживаемыми и неотслеживаемыми файлами.
>>
>>![Пример использования команды](git_status.png)

**clear**
>clear
>>очищает терминал.

**Более подробно о командах Git можно узнать [тут](https://github.com/cyberspacedk/Git-commands).**