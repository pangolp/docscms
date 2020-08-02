# [User](https://gitlab.com/WoW-CMS/BlizzCMS-Plus/-/blob/master/application/modules/user/controllers/User.php)

```php
public function __construct()
```
En el constructor, inicializamos la hora en base a la configuración establecida en **timezone** y también, cargamos el model **user_model**.

```php
public function verify1()
```
Almacena los datos del formulario y los envía al modelo.
