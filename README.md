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
sudo chwon root. filebeat.yml
docker-compose up
```

Acesse http://localhost:5601
user: admin
pass: admin


Crie um indice `my-data-stream`

http://localhost:5601/app/management/opensearch-dashboards/indexPatterns/create
