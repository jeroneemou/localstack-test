# Local stack playground

## Elasticsearch

Create domain: `aws es create-elasticsearch-domain --domain-name=test --endpoint-url=http://localhost:4578/`

Domain available at `http://localhost:4571/`? Why not http://localhost:4571/test?

## S3

Create bucket: `aws s3 mb s3://tutorial --endpoint-url=http://localhost:4572`