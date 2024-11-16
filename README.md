# Коннектор R-Vision SOAR для обогащения инцидентов, порождаемых PT NAD   

#

Позволяет обогатить инцидент данными о классе сработавшего правила, его сигнатурой и точным временем срабатывания на NAD.
  
Использование:
  
```shell 
python3 nad_connector.py <Отправитель> <Получатель> <Имя сработавшего правила> <Идентификатор инцидента в R-Vision SOAR> 
```

Пример:

```shell 
python3 nad_connector.py 1.1.1.1 2.2.2.2 'ET INFO Probably Evil Long Unicode string only string and unescape 2' 11-22-333 
```
#
