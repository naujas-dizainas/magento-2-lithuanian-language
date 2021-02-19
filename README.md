**Install Lithuanian pack**:

```
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
