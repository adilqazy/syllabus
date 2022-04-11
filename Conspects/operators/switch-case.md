**switch-case**

``` 
Рассмотрим пример работы switch-case:

var command = 'close'; // проверяемое значение
switch (command) {
 case 'close': // если значение в command == 'close'
 print('closed'); // <- closed
 break;
 case 'open': // если значение в command == 'open'
 print('open');
 break;
 default: // если не подошел ни один вариант
 print('default');
}
```
