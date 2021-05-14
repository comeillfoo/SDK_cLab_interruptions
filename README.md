# ITMO.cLAB

## Лабораторная работа № 2 "Прерывания"
### Описание

В данной лабораторной работе выводится заготовленная анимация с базовой задержкой в _500мс_. Каждые 150мс генерируется прерывание от таймера TIM6 и задержка между кадрами увеличивается на 15мс. Несмотря на то, что в варианте указано T = 150мс, данный параметр было решено опустить до 15мс, так как ограничение выполнения программ cLAB в 8000мс не хватает для вывода всех 12 кадров, длительность которых увеличивается каждые 150мс.

В общей сложности для вывода всей анимации нужно: S = 12 * ( 500 + 11 * 150 + 500 ) / 2 = 15900мс.

В папочке __out__ хранится диаграмма полученная при данных параметрах.


 
