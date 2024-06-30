---
navigation:
  title: Советы и хитрости
  position: 20
---

# Советы и хитрости

Кучка разных рекомендаций.

* Удалите OptiFine;
* Вы можете поворачивать и приближать сцены в руководстве, которые имеют кнопки масштабирования и скрытия/показа аннотаций;
* Держите вашу сеть древообразной и избегайте петель;
* Используйте полноразмерные [устройства](ae2-mechanics/devices.md) в группах не более 8, если только вы глубоко не понимаете, как [каналы](ae2-mechanics/channels.md) маршрутизируются через сеть;
* Выберите один тип дерева и используйте его для всех своих шаблонов. Да, включение замен иногда работает, но использование одного типа дерева повсеместно значительно уменьшает проблемы;
* Располагайте свои [шаблоны](items-blocks-machines/patterns.md) вертикально в <ItemLink id="pattern_access_terminal" /> или распределяйте их между вашими поставщиками, чтобы рецепты могли выполняться параллельно;
* Добавьте энергоячейку, чтобы ваша сеть могла справляться со скачками энергии;
* Вы можете использовать воду в <ItemLink id="condenser" />;
* Лучший способ поддерживать чистоту вашей сети — не помещать туда случайную добычу с мобов, такую как мечи и броня. Каждая уникальная комбинация зачарований и прочности является новым типом;
* Событие «поступление предмета в систему» должно происходить при возврате результата [шаблона обработки](items-blocks-machines/patterns.md), например, с помощью <ItemLink id="import_bus" />, <ItemLink id="interface" /> или в слоте возврата <ItemLink id="pattern_provider" />; нельзя просто перенаправить результат в сундук с помощью <ItemLink id="storage_bus" />;
* Не забывайте, что можно поворачивать и приближать сцены в руководстве, которые имеют кнопки масштабирования и скрытия/показа аннотаций;
* <ItemLink id="pattern_provider" /> будет отправлять только полные партии рецептов и только через одну сторону. Это полезно, чтобы убедиться, что машины не получают частичные партии, но иногда нужно, чтобы ингредиенты поступали в несколько мест. Это можно сделать, используя <ItemLink id="interface" />, либо как [подсеть «трубы»](example-setups/pipe-subnet.md), либо используя его способность удерживать несколько различных стаков предметов, жидкостей, химикатов и т. д., чтобы использовать его как своего рода промежуточный сундук/резервуар;
* Вы можете увеличивать и вращать сцены в руководстве, которые имеют кнопки масштабирования и скрытия/показа аннотаций.