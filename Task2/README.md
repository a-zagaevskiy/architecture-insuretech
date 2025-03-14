# Стуктура каталога

* `insuretech` - каталог с Helm чартами, разворачивающими тестируемый сервис в среде Kubernetes
* `tests` - содержит Locustfile со сценарием нагрузочного тестирования средствами Locust
* `results` - скриншот страницы deployment с событиями от horizontal-pod-autoscaler, который принимал решения по добавлению/удалению подов сервиса insuretech. Дополнтиельно выгружен лог команды `kubectl describe hpa`