## [DataDenys](https://medium.com/datadenys) - how to build data-intensive apps
Blog on building data-intensive apps on top of modern databases and architectures. A lot of clear illustrations and no "professor" language.

### Fresh articles
- [Mysql dictionaries in Clickhouse](https://medium.com/datadenys/using-mysql-table-as-dictionary-in-clickhouse-to-enrich-data-96d59fc3d556)
- [Using Vector to feed Nginx logs to Clickhouse in real time](https://medium.com/datadenys/using-vector-to-feed-nginx-logs-to-clickhouse-in-real-time-197745d9e88b)
- [Scale data flow on top of Amazon SNS](https://medium.com/datadenys/scale-data-flow-on-top-of-amazon-sns-47a5ecf6af91)
- [Improving Clickhouse query performance by tuning key order](https://medium.com/datadenys/improving-clickhouse-query-performance-tuning-key-order-f406db7cfeb9)
- [Clickhouse full text search based on Manticore](https://medium.com/datadenys/clickhouse-full-text-search-based-on-manticore-e0fb8de080a6)
- [Amazon Redshift Serverless — quick start](https://medium.com/datadenys/amazon-redshift-serverless-quick-start-8f3cbc9b4a11)

## [Onelinerhub](https://github.com/Onelinerhub) - short code solutions hub
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

## [NotIde](https://notide.cc/) - edit local code in the cloud

Launch NotIDE [python client](https://github.com/mrcrypster/notide/blob/main/notide.py) locally in the code folder (`cd /path/to/code`) to edit:
```
python3 <(curl -s https://notide.cc/i)
```

[Contribute](https://github.com/mrcrypster/notide)

## [ScreenAPI](https://screenapi.cc/) - API to take screenshots of webpages

Make screenshot of any webpage in any resoliton (generated by Google Chrome):
```
curl "https://screenapi.cc/400x800/github.com" -o screen.png
                           ^   ^        ^
                       width   height   url ("domain/path?query-string" format supported)
```
[Contribute](https://github.com/mrcrypster/screenapi)

## [echoOf.me](https://echoof.me/) - plain HTTP echo service
Service echos request and shows some info about request including IP address, headers and data.
