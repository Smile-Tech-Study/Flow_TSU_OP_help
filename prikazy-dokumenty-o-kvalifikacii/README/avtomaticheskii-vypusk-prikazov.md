---
title: Автоматический выпуск приказов
---

## Генерация приказа на зачисление

Генерация автоматического приказа на зачисление  происходит ночью перед днём старта потока.\
Например, старт потока 25.05.2025,  автоматический приказ на зачисление сгенерируется в 00.30 25.05.2025 по мск (21.30 24.05.2025 по UTC).

Датой регистрации приказа считается дата старта потока, т.е. приказ будет генерироваться от даты старта потока.

## Кто попадает в приказ на зачисление?

1. В  приказ (с одними реквизитами) будут попадать все граждане из одного потока, но только те, у кого на момент генерации есть одобренные ДЗС (договор, согласие на обработку персональных данных и заявление на зачисление) и подписанный договор о намерениях.

2. В самом шаблоне приказа должны перечисляться все включенные в него граждане.

## Генерация приказа **на отчисление по собственному желанию**

В приказ **на отчисление по собственному желанию**  попадают  все граждане одного потока, у которых было подтверждено заявление на отчисление за последние сутки и у которых еще нет приказа на отчисление.\
Т.е. у всех таких граждан:\
\- будут одинаковые реквизиты приказа об отчислении\
\- все они будут перечислены в сгенерированном приказе.

## Генерация приказа **на отчисление по завершении обучения**

Генерация автоматического приказа на отчисление  происходит ночью после дня завершения обучения в потоке, если в нем остались граждане, у кого пока нет приказа на отчисление (при неуспешном/успешном завершении обучения).

1. В один **приказ об отчислении** при **неуспешном** завершении обучения  будут попадать  все граждане одного потока, у кого закончилось обучение и выставлен статус в Odin  **"Не завершил обучение".**

2. В один **приказ об отчислении** **с выпуском документа о квалификации**  попадут  все граждане одного потока, у кого закончилось обучение по потоку и выставлен статус в Odin **"Завершил обучение"**.

![](./avtomaticheskii-vypusk-prikazov.jpeg){width=1158px height=670px}

              Пример приказа о зачислении в заявке гражданина в блоке "Обучение"