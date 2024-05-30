# Задание на практику 30 05

# Написать кеширующий декоратор. 

1) Декоратор с кешем без ограничений

2) Декоратор с возможностью ограничить размер кеша

3) Декоратор с TTL - Time To Live - количество секунд в течении которых живут данные в кеше

```python
@cache(ttl = 10)
def hello():
    return 'hello'
```