**Install Lithuanian pack**:

```
composer require naujas-dizainas/magento-2-lithuanian-language
php bin/magento setup:static-content:deploy lt_LT
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
```



**Update  Lithuanian pack**:

```
php bin/magento setup:static-content:deploy lt_LT
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
