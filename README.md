## [DataDenys](https://medium.com/datadenys) - how to build data-intensive apps
I'm writing about building data-intensive apps on top of modern databases and architectures. A lot of clear illustrations and no "professor" language.

## [Onelinerhub](https://onelinerhub.com/) - short code solutions hub
This is a big open collection of modern code solutions for software engineers.
[Contribute](https://github.com/Onelinerhub/onelinerhub) or [join org](https://github.com/Onelinerhub).

## [Mysqly](https://mysqly.com/) - Mysql data framework for PHP

```php
require "mysqly.php";
mysqly::auth("usr", "pwd", "db", "127.0.0.1");
print_r( mysqly::fetch("SELECT NOW()") );
```

[Contribute](https://github.com/mrcrypster/mysqly)

## [Clickhousy](https://github.com/mrcrypster/clickhousy) - low memory footprint PHP client for Clickhouse

```php
require 'clickhousy/clickhousy.php';
$data = clickhousy::rows('SELECT * FROM table LIMIT 5');
```

[Documentation](https://github.com/mrcrypster/clickhousy)


## [PHPy 2](https://github.com/mrcrypster/phpy) - PHP markup framework for rapid prototyping

```php
echo phpy(['html' => ['a.home:/test' => 'Link']]); # -> <html><a class="home" href="/test">Link</a></html>
```
[Sources & tests](https://github.com/mrcrypster/phpy-src) is available as separate repository.

## [NotIde](https://notide.cc/) - edit local code in the cloud

Launch NotIDE [python client](https://github.com/mrcrypster/notide/blob/main/local/client2.py) locally in the code folder (`cd /path/to/code`) to edit:
```
python3 <(curl -s https://notide.cc/i)
```

[Contribute](https://github.com/mrcrypster/notide)
