# California Lost Property SQLite Database generator

For full text searching, possibly over HTTP!

eg.

https://datasette-lite.mindflakes.com/index.html?url=https://datasette-lite.mindflakes.com/odb.sqlite#/odb?sql=SELECT+*+FROM+records+WHERE+records+MATCH+%223201+Dulzura+Dr%0A%22+ORDER+BY+CAST%28CURRENT_CASH_BALANCE+AS+FLOAT%29+DESC%3B
