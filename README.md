#### POST ```api/getInfoUser```

Parameters:
  * ```user_id``` ? **(str)**
  * ```token``` **(str)**

Result: 
```python
  {
    "user_id": (str),
    "code": (int),
    "firstname": (str),
    "lastname": (str),
    "photo": (str),
  }
```

Errors:
  * ```status: 1``` **Введите верные данные или попробуйте позднее**
  * ```status: 4``` **Некорректный запрос**
