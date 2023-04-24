Некоторые из эффектов, которые может использовать Redux-Saga:

takeEvery - запускает определенный генератор каждый раз, когда действие передается в хранилище.
takeLatest - запускает определенный генератор только для последнего переданного действия.
put - отправляет новое действие в хранилище.
call - вызывает функцию и ожидает ее завершения.
fork - запускает новый поток выполнения для выполнения определенного генератора.
join - ожидает завершения определенного потока выполнения.
select - получает данные из хранилища.
throttle - ограничивает частоту выполнения определенного генератора.
debounce - ограничивает частоту выполнения определенного генератора, игнорируя повторные вызовы в течение указанного интервала времени.
cancel - отменяет выполнение определенного потока выполнения. 
