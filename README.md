# KVKK Veri Ihlal Habercisi

Bu script, calistirildigi gun yayinlanmis KVKK veri ihlal bildirimlerini belirtilen Slack kanalina gonderir.

Ornek bildirim:

![example](example.png)

## Kullanim

```shell
docker run --rm -v $PWD:/app -w /app php:8.2 php /app/kvkk-breach-notifier.php
```