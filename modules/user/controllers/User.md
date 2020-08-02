# [User](https://gitlab.com/WoW-CMS/BlizzCMS-Plus/-/blob/master/application/modules/user/controllers/User.php)

```php
public function __construct()
```
En el constructor, inicializamos la hora en base a la configuración establecida en **timezone** y también, cargamos el model **user_model**.

```php
/**
 * Verificar la autenticidad (classic)
 *
 * Comprobar los datos de acceso de las cuentas con la encriptación basada en SHA1
 * @return string
 */
public function verify1()
```
