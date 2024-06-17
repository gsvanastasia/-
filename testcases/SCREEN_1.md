## Тест-кейсы первого экрана

### Coffee

###### t-1. Выбирается напиток Coffee объемом 0.2 л.
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Выбрать кофе объемом 0.2 л.
Ожидаемый результат: Напиток добавлен в очередь заказа.

###### t-2. Формируется очередь в заказе из 5-ти напитков Coffee
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Добавить 5 напитков кофе объемом 0.2 л.
Ожидаемый результат: 5 напитков кофе добавлено в очередь заказа.

###  Nuka-Cola

###### t-3. Выбирается напиток Nuka-Cola объемом 0.2 л.
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Выбрать Nuka-Cola объемом 0.2 л.
Ожидаемый результат: Напиток добавлен в очередь заказа.

###### t-4. Выбирается напиток Nuka-Cola объемом 0.5 л.
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Пользователь выбирает Nuka-Cola объемом 0.5 л.
Ожидаемый результат: Напиток добавлен в очередь заказа.

###### t-5. Выбирается напиток Nuka-Cola объемом 1 л.
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Выбрать Nuka-Cola объемом 1 л.
Ожидаемый результат: Напиток добавлен в очередь заказа.

###### t-6. Формируется очередь в заказе из 5-ти напитков Nuka-Cola
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Добавить 5 напитков Nuka-Cola объемом 0.2 л.
Ожидаемый результат: 5 напитков Nuka-Cola добавлены в очередь заказа.

###### t-7. Добавляется напиток Nuka-Cola с разными фиксированными объемами
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Добавить напиток Nuka-Cola объемом 0.2 л.
2. Добавить напиток Nuka-Cola объемом 0.5 л.
3. Добавить напиток Nuka-Cola объемом 1 л.
Ожидаемый результат: Напитки добавлены в очередь заказа.

###### t-8. Проверка расчета стоимости для разливного объема 0.4 л. напитка Nuka-Cola
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Добавить напиток Nuka-Cola объемом 0.4 л.
Ожидаемый результат: Напиток Nuka-Cola объемом 0.4 л добавляется в очередь заказов, отображается стоимость 100 рублей
Итоговая стоимость рассчитывается как: 50р/2*0.4/0.1 = 100

###### t-9. Проверка расчета стоимости для разливного объема 0.6 л. напитка Nuka-Cola
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Добавить напиток Nuka-Cola объемом 0.6 л.
Ожидаемый результат: Напиток Nuka-Cola объемом 0.6 л добавляется в очередь заказов, отображается стоимость 84 рубля
Итоговая стоимость рассчитывается как: 70р/5*0.6/0.1 = 84

###### t-10. Проверка расчета стоимости для разливного объема 0.9 л. напитка Nuka-Cola
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Добавить напиток Nuka-Cola объемом 0.9 л.
Ожидаемый результат: Напиток Nuka-Cola объемом 0.9 л добавляется в очередь заказов, отображается стоимость 126 рублей
Итоговая стоимость рассчитывается как: 70р/5*0.9/0.1 = 126

###### t-11. Проверка расчета стоимости для разливного объема 1.1 л. напитка Nuka-Cola
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Добавить напиток Nuka-Cola объемом 1.1 л.
Ожидаемый результат: Напиток Nuka-Cola объемом 1.1 л добавляется в очередь заказов, отображается стоимость 94 рубля
Итоговая стоимость рассчитывается как: 85р/10*1.1/0.1 = 93.5

###### t-12. Проверка расчета стоимости для разливного объема 5 л. напитка Nuka-Cola
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Добавить напиток Nuka-Cola объемом 5 л.
Ожидаемый результат: Напиток Nuka-Cola объемом 5 л добавляется в очередь заказов, отображается стоимость 425 рублей
Итоговая стоимость рассчитывается как: 85р/10*5/0.1 = 425

###### t-13. Проверка расчета стоимости для разливного объема 10 л. напитка Nuka-Cola
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Добавить напиток Nuka-Cola объемом 10 л.
Ожидаемый результат: Напиток Nuka-Cola объемом 10 л добавляется в очередь заказов, отображается стоимость 850 рублей
Итоговая стоимость рассчитывается как: 85р/10*10/0.1 = 850

###### t-14. Применяется скидка 5% для разливного объема 2 л. Nuka-Cola
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Выбрать напиток Nuka-Cola объемом 2 л.
Ожидаемый результат: Стоимость напитка Nuka-Cola объемом 2 л равна 161 рубль
Итоговая стоимость рассчитывается как: 85р/10*2/0.1 - 5% = 161

###### t-15. Применяется скидка 5% для разливного объема 2.1 л. Nuka-Cola
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Выбрать напиток Nuka-Cola объемом 2.1 л.
Ожидаемый результат: Стоимость напитка Nuka-Cola объемом 2.1 л равна 170 рублей
Итоговая стоимость рассчитывается как: 85р/10*2.1/0.1 - 5% = 169.5

###### t-16. Применяется скидка 5% для разливного объема 4.9 л. Nuka-Cola
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Выбрать напиток Nuka-Cola объемом 4.9 л.
Ожидаемый результат: Стоимость напитка Nuka-Cola объемом 4.9 л равна 396 рублей
Итоговая стоимость рассчитывается как: 85р/10*4.9/0.1 - 5% = 395.6

###### t-17. Применяется скидка 10% для разливного объема 5 л. Nuka-Cola
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Выбрать напиток Nuka-Cola объемом 5 л.
Ожидаемый результат: Стоимость напитка Nuka-Cola объемом 5 л равна 383 рубля
Итоговая стоимость рассчитывается как: 85р/10*5/0.1 - 10% = 382.5

###### t-18. Применяется скидка 10% для разливного объема 5.1 л. Nuka-Cola
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Выбрать напиток Nuka-Cola объемом 5.1 л.
Ожидаемый результат: Стоимость напитка Nuka-Cola объемом 5.1 л равна 390 рубль
Итоговая стоимость рассчитывается как: 85р/10*5.1/0.1 - 10% = 390.15

###### t-19. Применяется скидка 10% для разливного объема 9.9 л. Nuka-Cola
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Выбрать напиток Nuka-Cola объемом 9.9 л.
Ожидаемый результат: Стоимость напитка Nuka-Cola объемом 9.9 л равна 758 рублей
Итоговая стоимость рассчитывается как: 85р/10*9.9/0.1 - 10% = 757.35

###### t-20. Применяется скидка 10% для разливного объема 10 л. Nuka-Cola
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Выбрать напиток Nuka-Cola объемом 10 л.
Ожидаемый результат: Стоимость напитка Nuka-Cola объемом 10 л равна 765 рублей
Итоговая стоимость рассчитывается как: 85р/10*5.1/0.1 - 10% = 765

###### t-21. Добавляется 5 напитков Nuka-Cola по 10 л.
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Выбрать напиток Nuka-Cola объемом 10 л. 5 раз
Ожидаемый результат: Добавилось 50 л напитка Nuka-Cola объемом по 10 л.
Slurm

###### t-22. Выбирается напиток Slurm объемом 0.2 л.
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Выбрать напиток Slurm объемом 0.2 л.
Ожидаемый результат: Напиток добавлен в очередь заказа.

###### t-23. Выбирается напиток Slurm объемом 0.5 л.
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Выбрать напиток Slurm объемом 0.5 л.
Ожидаемый результат: Напиток добавлен в очередь заказа.

###### t-24. Выбирается напиток Slurm объемом 1 л.
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Выбрать напиток Slurm объемом 1 л.
Ожидаемый результат: Напиток добавлен в очередь заказа.

###### t-25. Формируется очередь в заказе из 5-ти напитков Slurm.
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Добавить 5 напитков Slurm объемом 0.2 л.
Ожидаемый результат: 5 напитков Slurm добавлено в очередь заказа.

###### t-26. Добавляется напиток Slurm с разными фиксированными объемами
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Добавить напиток Slurm объемом 0.2 л.
2. Добавить напиток Slurm объемом 0.5 л.
3. Добавить напиток Slurm объемом 1 л.
Ожидаемый результат: Напитки добавлены в очередь заказа.

###### t-27. Добавляется 5 напитков Slurm по 10 л.
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Выбрать напиток Slurm объемом 10 л. 5 раз
Ожидаемый результат: Добавилось 50 л напитка Slurm объемом по 10 л.

###### t-28. Проверка расчета стоимости для разливного объема 0.4 л. напитка Slurm
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Добавить напиток Slurm объемом 0.4 л.
Ожидаемый результат: Напиток Slurm объемом 0.4 л добавляется в очередь заказов, отображается стоимость 140 рублей
Итоговая стоимость рассчитывается как: 70р/2*0.4/0.1 = 140

###### t-29. Проверка расчета стоимости для разливного объема 0.6 л. напитка Slurm
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Добавить напиток Slurm объемом 0.6 л.
Ожидаемый результат: Напиток Slurm объемом 0.6 л добавляется в очередь заказов, отображается стоимость 108 рублей
Итоговая стоимость рассчитывается как: 90р/5*0.6/0.1 = 108

###### t-30. Проверка расчета стоимости для разливного объема 0.9 л. напитка Slurm
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Добавить напиток Slurm объемом 0.9 л.
Ожидаемый результат: Напиток Slurm объемом 0.9 л добавляется в очередь заказов, отображается стоимость 162 рубля
Итоговая стоимость рассчитывается как: 90р/5*0.9/0.1 = 162

###### t-31. Проверка расчета стоимости для разливного объема 1.1 л. напитка Slurm
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Добавить напиток Slurm объемом 1.1 л.
Ожидаемый результат: Напиток Slurm объемом 1.1 л добавляется в очередь заказов, отображается стоимость 121 рубль
Итоговая стоимость рассчитывается как: 110/10*1.1/0.1 = 121

###### t-32. Проверка расчета стоимости для разливного объема 5 л. напитка Slurm
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающ Slurm объемом 5 л.
Ожидаемый результат: Напиток Slurm объемом 5 л добавляется в очередь заказов, отображается стоимость 550 рублей
Итоговая стоимость рассчитывается как: 110/10*5/0.1= 550

###### t-33. Проверка расчета стоимости для разливного объема 10 л. напитка Slurm
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Добавить напиток Slurm объемом 10 л.
Ожидаемый результат: Напиток Slurm объемом 10 л добавляется в очередь заказов, отображается стоимость 1100 рублей
Итоговая стоимость рассчитывается как: 110р/10*10/0.1 = 1100

###### t-34. Применяется скидка 5% для разливного объема 2 л. Slurm
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Выбрать напиток Slurm объемом 2 л.
Ожидаемый результат: Стоимость напитка Slurm объемом 2 л равна 209 рублей
Итоговая стоимость рассчитывается как: 110/10*2/0.1 - 5% = 209

###### t-35. Применяется скидка 5% для разливного объема 2.1 л. Slurm
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Выбрать напиток Slurm объемом 2.1 л.
Ожидаемый результат: Стоимость напитка Slurm объемом 2.1 л равна 219 рублей
Итоговая стоимость рассчитывается как: 110р/10*2.1/0.1 - 5% = 219.45

###### t-36. Применяется скидка 5% для разливного объема 4.9 л. Slurm
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Выбрать напиток Slurm объемом 4.9 л.
Ожидаемый результат: Стоимость напитка Slurm объемом 4.9 л равна 512 рублей
Итоговая стоимость рассчитывается как: 110р/10*4.9/0.1 - 5% = 512.05

###### t-37. Применяется скидка 10% для разливного объема 5 л. Slurm
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Выбрать напиток Slurm объемом 5 л.
Ожидаемый результат: Стоимость напитка Slurm объемом 5 л равна 495 рублей
Итоговая стоимость рассчитывается как: 110р/10*5/0.1 - 10% = 495

###### t-38. Применяется скидка 10% для разливного объема 5.1 л. Slurm
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Выбрать напиток Slurm объемом 5.1 л.
Ожидаемый результат: Стоимость напитка Slurm объемом 5.1 л равна 504 рублей
Итоговая стоимость рассчитывается как: 110р/10*5.1/0.1 - 10% = 504.9

###### t-39. Применяется скидка 10% для разливного объема 9.9 л. Slurm
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Выбрать напиток Slurm объемом 9.9 л.
Ожидаемый результат: Стоимость напитка Slurm объемом 9.9 л равна 980 рубль
Итоговая стоимость рассчитывается как: 110р/10*9.9/0.1 - 10% = 980.1

###### t-40. Применяется скидка 10% для разливного объема 10 л. Slurm
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Открыть выпадающее меню “Купить на розлив”
2. Выбрать напиток Slurm объемом 10 л.
Ожидаемый результат: Стоимость напитка Slurm объемом 10 л равна 990 рублей
Итоговая стоимость рассчитывается как: 110р/10*5.1/0.1 - 10% = 990

### Общие тест-кейсы

###### t-41. Нажатие на кнопку “Перейти к оплате” ведет на второй экран
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Добавить напиток Coffee объемом 0.2 л.
Ожидаемый результат: Кнопка “Перейти к оплате” переводит на экран с оплатой.

###### t-42. Добавление разных видов напитков с фиксированным объемом
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Добавить напиток Coffee объемом 0.2 л.
2. Добавить напиток Nuka-Cola объемом 0.5 л.
3. Добавить напиток Slurm объемом 1 л.
Ожидаемый результат: Напитки добавлены в очередь заказа.

###### t-43. Добавление разных видов напитков с разными объемами
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Добавить напиток Coffee объемом 0.2 л.
2. Открыть выпадающее меню “Купить на розлив”
3. Выбрать напиток Nuka-Cola объемом 3 л.
4. Нажать кнопку “Готово”.
5. Открыть выпадающее меню “Купить на розлив”
6. Выбрать напиток Slurm объемом 6 л.
7. Нажать кнопку “Готово”.
Ожидаемый результат: Напитки добавлены в очередь заказа.

###### t-44. Удаление 1 напитка из очереди
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Добавить напиток Coffee объемом 0.2 л.
2. Нажать кнопку удаления напитка.
Ожидаемый результат: Напиток удаляется из очереди.

###### t-45. Удаление 5 напитков из очереди
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Добавить 5 напитков Coffee объемом 0.2 л.
2. Нажать кнопку удаления каждого напитка
Ожидаемый результат: Все напитки удаляются из очереди.

###### t-46. Проверка итоговой суммы в заказе из разных напитков с фиксированной стоимостью
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Добавить напиток Coffee объемом 0.2 л.
2. Добавить напиток Nuka-Cola объемом 0.5 л.
3. Добавить напиток Slurm объемом 1 л.
Ожидаемый результат: Итоговая сумма заказа 230 рублей.
Итоговая стоимость рассчитывается как: 50 + 70 + 110 = 230

###### t-47. Проверка итоговой суммы в заказе из разных напитков на розлив
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Добавить напиток Nuka-Cola объемом 1.9 л.
2. Добавить напиток Slurm объемом 1.1 л.
Ожидаемый результат: Итоговая сумма заказа 283 рубля.
Итоговая стоимость рассчитывается как: 162 + 121= 283

###### t-48. Проверка итоговой суммы в заказе из разных напитков на розлив с учетом скидки 5% и 10%
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Добавить напиток Nuka-Cola объемом 2.1 л.
2. Добавить напиток Slurm объемом 10 л.
Ожидаемый результат: Итоговая сумма заказа 1160 рублей.
Итоговая стоимость рассчитывается как: 170 + 990 = 1160

###### t-49. Проверка итоговой суммы в заказе при удалении 1 напитка
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Добавить 5 напитков Coffee объемом 0.2 л.
2. Нажать кнопку удаления 1 Coffee объемом 0.2 л.
Ожидаемый результат: Итоговая сумма заказа 200 рублей.
Итоговая стоимость рассчитывается как: 50*5 - 50 = 200

###### t-50. Проверка итоговой суммы в заказе при удалении всех напитков
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Добавить 5 напитков Coffee объемом 0.2 л.
2. Нажать кнопку удаления всех напитков Coffee объемом 0.2 л.
Ожидаемый результат: Итоговая сумма заказа 0 рублей.

###### t-51. Проверка орфографии на первом экране
Предусловие: Открыто приложение “Автомат для напитков” на первом экране
Шаги воспроизведения:
1. Проверить правильность слов на орфографические ошибки
Ожидаемый результат: Орфографические ошибки отсутствуют.