# Dictionaries (dict)
1. Declaration
   Standard Declaration
   ```py
   d = {'key1':’value1', 'key2': 'value2'}
   ```
   Using the `dict()`Function ①
   ```py
   d = dict(key1="value1", key2="value2")
   ```
   Using the `dict()`Function ②
   ```py
   d = dict([('key1':’value1'), ('key1':’value1')])
   ```
   
3. Retrieving Values
   Using [key]
   ```py
   d['key']
   ```
   :::message
   NOTE: If the specified key does not exist, a `KeyError` wil be raised.
   :::

   Using the `get()`Method

    ```py
    d.get('key')
    ```
    :::message
   NOTE: If the specified key does not exist, `None will be returned.
   :::

4. Updating Dictionaries
   Using the `update()`Method
   ```py
   d1 = {'a':10, 'b':20}
   d2 = {'a':1000, 'c': 30}
   d1.update(d2)
   print(d1) # {'a': 1000, 'b': 20, 'c': 30}
   ```