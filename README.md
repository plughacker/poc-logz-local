# logz local

Example of how to use local "logz".

Opensource projects used by logz:

- https://opentelemetry.io/
- https://www.jaegertracing.io/
- https://opensearch.org/
- https://prometheus.io/
- https://m3db.io/



## How to run this project?

```bash
sudo chwon root. filebeat.yml
docker-compose up
```

Open http://localhost:5601
user: admin
pass: admin

Open http://localhost:5601/app/management/opensearch-dashboards/indexPatterns/create
Create index with name `my-data-stream`

## logs

Send logs in json format inside the logs folder which will automatically be sent to opensearch
