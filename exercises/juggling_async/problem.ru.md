Эта задание похоже на предыдущее (HTTP COLLECT) тем, что Вам снова придется использовать `http.get()`. Но в этот раз, Вы получите **три** адреса (URL) в качестве трех первых аргументов командной строки.

Соберите контент с каждого адреса, который получите, и выведите его в консоль (stdout). Не нужно выводить общее количество полученных данных, просто выведите содержимое каждого адреса на новой строке. Учтите, что Вы **должны** вывести содержимое в том порядке, в каком Вы получили адреса.


----------------------------------------------------------------------
## ИНФОРМАЦИЯ

Не ожидайте привычной работы от всех трех серверов. Они не вернут Вам полный ответ в том порядке, в котором Вы ожидаете, таким образом, Вы не сможете просто вывести поочередно ответ с каждого сервера, потому что они будут в неверном порядке.

Для начала Вам нужно будет собрать все данные и отследить, какое количество адресов вернуло контент, и только потом вывести их в консоль.

Подсчет количества вызовов функций-обработчиков является основным из способов управления асинхронностью в Node. Вместо того, чтобы делать это самостоятельно, Вам может показаться более удобным воспользоваться такими библиотеками, как: [async](http://npm.im/async) или [after](http://npm.im/after). Но в этом случае попытайтесь все сделать без дополнительных средств.

----------------------------------------------------------------------
