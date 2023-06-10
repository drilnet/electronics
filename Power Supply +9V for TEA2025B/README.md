# Hobby
[GITHUB](https://github.com) - Моя записная книжка (наброски, заметки и т.д. и т.п.)!

<hr>

## Стабилизированный блок питания +9В/0.5А для TEA2025B

Лицензия (License): **Free**.

![](https://github.com/drilnet/electronics/blob/master/Power%20Supply%20%2B9V%20for%20TEA2025B/UA.png)

### Схема блока питания

![](https://github.com/drilnet/electronics/blob/master/Power%20Supply%20%2B9V%20for%20TEA2025B/SCH%20-%20Images/PS%207809%20(72dpi)%2C%20720x211.png)
<br>
В 600dpi: [здесь](https://github.com/drilnet/electronics/blob/master/Power%20Supply%20%2B9V%20for%20TEA2025B/SCH%20-%20Images/PS%207809%20(600dpi).png)

```
    X1, X2 - Клемники.
       VD1 - KBU608 (диодный мост)
  VD2, VD3 - Светодиоды (VD3 на корпус)
        C1 - 4700мкФ х 35В
    C2, C3 - 0.1мкФ х 100В
C4, C5, C6 - 680мкФ х 16В
    R1, R2 - 820
        R3 - 2K
       DA1 - L7809CV
```

### Расположение радиодеталей на печатной плате

![](https://github.com/drilnet/electronics/blob/master/Power%20Supply%20%2B9V%20for%20TEA2025B/PCB%20-%20Images/Printed%20circuit%20board%201%20(72dpi)%2C%20640x.png)
<br>
В 600dpi: [здесь](https://github.com/drilnet/electronics/blob/master/Power%20Supply%20%2B9V%20for%20TEA2025B/PCB%20-%20Images/Printed%20circuit%20board%201%20(600dpi).png)

Диаметры отверстий на плате:
```
3.2мм - Крепление (самые большие отверстия)
1.5мм - VD1 (диодный мост)
1.2мм - Клемники, C1, DA1
  1мм - VD3
0.8мм - Всё остальное
```

### Печатная плата (позитив)

![](https://github.com/drilnet/electronics/blob/master/Power%20Supply%20%2B9V%20for%20TEA2025B/PCB%20-%20Images/Printed%20circuit%20board%203%20(72dpi)%2C%20640x.png)
<br>
В 600dpi: [здесь](https://github.com/drilnet/electronics/blob/master/Power%20Supply%20%2B9V%20for%20TEA2025B/PCB%20-%20Images/Printed%20circuit%20board%203%20(600dpi).png)

### Печатная плата (негатив)

![](https://github.com/drilnet/electronics/blob/master/Power%20Supply%20%2B9V%20for%20TEA2025B/PCB%20-%20Images/Printed%20circuit%20board%204%20(72dpi)%2C%20640x.png)
<br>
В 600dpi: [здесь](https://github.com/drilnet/electronics/blob/master/Power%20Supply%20%2B9V%20for%20TEA2025B/PCB%20-%20Images/Printed%20circuit%20board%204%20(600dpi).png)

**Внимание!**
<br>
Специальную **плёнку** для фотошаблонов или **бумагу** для термопереноса ([технология ЛУТ](https://uk.wikipedia.org/wiki/Лазерно-праскова_технологія "Украинская Википедия")) можно купить [здесь](https://voron.ua/catalog/materials-for-production-and-repair/materials-for-pcb-manufacturing/printer_film "https://voron.ua/")

### Собранный блок питания

![](https://github.com/drilnet/electronics/blob/master/Power%20Supply%20%2B9V%20for%20TEA2025B/Images%20-%20Photo/IMG_(72dpi)_512x.png)

Небольшой тест!
```
Напряжение подаваемое на X1: ~16В.
Нагрузка: 5Вт резистор с сопротивлением 27 Ом.
Ток: 9В / 27 Ом = 0.333А (333мА).
Время тестирования: 1 час.

Температура радиатора - Около 40 градусов.
Температура диодного моста - Тёплый.
```

Где купить радиатор?
<br>
[http://www.kosmodrom.com.ua](http://www.kosmodrom.com.ua)

Мысли вслух!
<br>
Надо было зашлифовать радиатор! :)

<hr>

Ещё полезная информация:
* [pdf-файл (схема, печатная плата)](https://github.com/drilnet/electronics/blob/master/Power%20Supply%20%2B9V%20for%20TEA2025B/ps%207809.pdf "")
* [L78_STMicroelectronics (datasheet).pdf](https://github.com/drilnet/electronics/blob/master/Power%20Supply%20%2B9V%20for%20TEA2025B/L78_STMicroelectronics%20(datasheet).pdf "")

<hr>

Схема выполнена в редакторе [TinyCAD](https://www.tinycad.net)
<br>
Разводка платы - [DesignSpark PCB](https://www.rs-online.com/designspark/home)

Файл: [TinyCADLibrarySt_Power_Supply_+9V.TCLib](https://github.com/drilnet/electronics/blob/master/Power%20Supply%20%2B9V%20for%20TEA2025B/TinyCADLibrarySt_Power_Supply_%2B9V.TCLib)
<br>
Условные графические обозначения радиодеталей для программы [TinyCAD](https://www.tinycad.net/)
<br>
Использовались при рисовании схемы!
<br>
Подключить библиотеку в [TinyCAD](https://www.tinycad.net/) можно: Library => Add...

Посадочные места радиодеталей для программы [DesignSpark PCB](https://www.rs-online.com/designspark/home) - я не выкладываю!
<br>
Перед загрузкой печатной платы в [DesignSpark PCB](https://www.rs-online.com/designspark/home), необходимо установить шрифт Liberation Mono!

[Ukraine](https://en.wikipedia.org/wiki/Ukraine) (Украина). (C) Демидов С.В.

<hr>

<div align="center">
<a href="https://github.com/drilnet/electronics">
[ Вернуться в начало репозитория Electronics ]
</a>
</div>

<hr>
