# GBot-Tiny-Mark-II

<a href="https://discord.gg/KYU2nGtZ2r" style="height: 40px !important;"><img src="https://discordapp.com/api/guilds/877551542272684082/widget.png?style=banner2" alt="Join us on Discord" style="height: 60px !important;width: 270px !important;border-radius: 19px !important;" ></a>

Это вторая версия моего первого принтера GBot Tiny. Новый принтер теперь чуточку компактней по XY, но выше, при этом зона печати стала слегка больше.  [Список комплектующих для постройки принтера.](./docs/BOM_GBot_Tiny_Mark_II.md)

![Внешний вид принтер](./pics/GBot-Tiny-Mark-II-290522.png)

## Обзор конструкции
Рама теперь состоит из профиля 2040. Из-за того, что рама стала меньше, она стала жёстче. Первая версия не имела отсека под электронику, новая - целых два (легкодоступный под столиком и сзади). Материнскую плату и блок питания предполагается ставить сзади. Таким образом можно добиться максимально компактной компоновки и "подключать движки проводами 10см". Я для себя буду собирать принтер на клиппере, поэтому в переднем отсеке прекрасно разместится одноплатный компьютер со своим блоком питания или понижающим преобразователем.

[![Preview](./pics/Fusion360-Preview-GBot-Tiny-Mark-II-030722.png)](https://myhub.autodesk360.com/ue2ddbd59/shares/public/SH35dfcQT936092f0e43e492bbc572dd28c1?mode=embed)

> https://myhub.autodesk360.com/ue2ddbd59/g/shares/SH35dfcQT936092f0e43e492bbc572dd28c1?mode=embed

## Что изменилось?

- Рама стала жёстче
- Занимает меньше места на столе

- Появились отсеки для электроники (я говорил, что их два?)
- Каретки рельс не выходят за границы корпуса => корпус можно накрыть куполом и сделать пассивную термокамеру
- Концевики на датчиках Холла [А3144](./docs/Datasheet_A3144.pdf)
- Появилось нормальное крепление экрана (совмещено с подвальчиком)
- Появился подвальчик, доступ к которому есть сверху (принтер не требуется переворачивать)
- Катушка пластика меняется сверху, это позволяет ставить принтеры вплотную друг к другу
- Верхняя и нижняя плиты стали проще по геометрии, теоретически можно вырезать кустарно
- Рюкзак *aka* backpack/задний отсек имеет активное охлаждение (два осевых 4010, радиальный 4020)

## Примечание
В папке [CAD] вы найдёте актуальные модели для производства данного принтера. [DXF] - для лазерной резки, [STL] - для печати. В этих папках лежат детали с минимальным риском изменения. Остальные детали всегда можно взять из актуальной step-сборки принтера из папки [STEP].

Вся документация и вспомогательные файлы будут находиться здесь [docs].

[CAD]: ./CAD
[DXF]: ./CAD/DXF
[STL]: ./CAD/STL
[STEP]: ./CAD/STEP
[docs]: ./docs
