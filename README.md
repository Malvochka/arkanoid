# arkanoid
Вверху поля множество прямоугольных блоков. Внизу горизонтально перемещается каретка. По полю летает «мяч», отражаясь от стен, блоков и каретки. Если мяч попадает вниз (мимо каретки) начисляются отрицательные очки /уменьшается каретка/увеличивается число поражений. Блоки бывают разных типов:
1)	Неразрушаемые. От них мяч просто отскакивает.
2)	Блоки могут быть со спрятанными бонусами: при попадании вертикально вниз падает бонус
3)	Блоки, увеличивающие скорость шарика при столкновении
4)	Блоки имеют уровень здоровья = число попаданий, чтобы блок исчез. За каждое попадание +1 очко игроку, -1 очко здоровья блоку.
5)	Бонусы: меняют размер каретки, меняют скорость шарика, меняют прилипание шарика к каретке. 
6)	Бонус: одноразовое дно для шарика – можно один раз пропустить, дно сработает как каретка, и исчезнет. 
7)	Бонус: шарик в произвольный момент меняет траекторию.
8)	Бонус: появляется двигающий блок, не задевающий при движении остальные блоки (надо проверять коллизии), и живущий до 3 ударов
9)	Бонус: появляется второй шарик, способный оттолкнуться и от первого, и от блоков/стенок
Для сдачи: 1-6 + 1 на выбор из 7-9
