# ExlineAPI
Exline cost shipping calculate with API

Сделана функция автозаполнения. Начинайте вводить в поле "город"
название города и функция будет отфильтровывать список по мере ввода букв.
Для этого надо установить модификатор kazshippingsimple_a.
Если Вас устраивает выбор населенных пунктов из списка без автозаполнения,
установите модификатор kazshippingsimple_s.
Нельзя устанавливать оба модификатора одновременно.
Эти функции корректно работают только с модулем одностраничного заказа Simple.

При обновлении модуля, ОБЯЗАТЕЛЬНО ОЧИСТИТЕ КЭШ МАГАЗИНА, т.е. удалите все из папки
system/storage/cache.

Обязательно! Удалите прежний модификатор kazshippingsimple. Если вы хотите, чтоб заработала функция 
автозаполнения, то установите kazshippingsimple_a, если хотите, чтоб было как раньше, то установите
kazshippingsimple_s.
