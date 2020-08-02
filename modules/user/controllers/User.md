# [User](https://gitlab.com/WoW-CMS/BlizzCMS-Plus/-/blob/master/application/modules/user/controllers/User.php)

```php
/**
 * Constructor de la clase.
 *
 * Llama al modelo, para poder ser utilizado dentro del controlador.
 * Si la hora no fue especificada, la inicializa, haciendo uso de la variable: timezone
 */
public function __construct()
```

```php
/**
 * Verificar la autenticidad (classic)
 *
 * Comprobar los datos de acceso de las cuentas con la encriptación basada en SHA1
 * @return string
 */
public function verify1()
```
