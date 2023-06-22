# OpenSearch

Exemplo de como usar o "logz" local.

Projetos que logz usa

- https://opentelemetry.io/
- https://www.jaegertracing.io/
- https://opensearch.org/
- https://prometheus.io/
- https://m3db.io/

## Como rodar esse projeto?

```bash
docker-compose up
```

Acesse http://localhost:5601
user: admin
pass: admin


Crie um indice `my-data-stream`

http://localhost:5601/app/management/opensearch-dashboards/indexPatterns/create




--------------------------

Instrumentação
https://github.com/plughacker/plug-adapter-cielo/blob/master/src/app/zero-auth/zero-auth.service.ts#L82


Auto instrumentação
https://github.com/newrelic/node-newrelic/tree/main/lib

Lib de log para nest
https://github.com/plughacker/plug-packages-nestjs-logger

Lib de log golang
https://github.com/plughacker/golang-adapter/blob/main/log/log.go

Lib de log em python
https://github.com/plughacker/python-lib-log