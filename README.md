### POST ```api/editProfileInfo```

Parameters:
  * ```firstname``` ? **(str)**
  * ```lastname``` ? **(str)**
  * ```telephone``` ? **(str)** 
  * ```gender``` ? **(str)**
  * ```user_id``` **(str)**
  * ```token``` **(str)**

Result: 
```python
  {
    "status": (int),
    "profileInfo": {
      "firstname": (str),
      "lastname": (str),
      "telephone": (str),
      "gender": (str)
    }
  }
```

Errors:
  * ```status: 1``` **Неизвестный пользователь**
  * ```status: 4``` **Некоректный запрос**
  * ```status: 7``` **Ошибка авторизации**
