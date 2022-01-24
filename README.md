# Quickstart for Thanos


The following services will be installed (and some are accessible via browser):

| Component              | Description                  | URL                        |
| ---------------------- | -----------------------------| ------------------------   |
| beacon-node-exporter1  | Node Exporter                | <http://localhost:19100/>  |
| beacon-node-exporter2  | Node Exporter                | <http://localhost:29100/>  |
| beacon-node-exporter3  | Node Exporter                | <http://localhost:39100/>  |
| beacon-node-exporter4  | Node Exporter                | <http://localhost:49100/>  |
| beacon-prometheus1     | Beacon Prometheus Server 1   | <http://localhost:19090/>  |
| beacon-prometheus2     | Beacon Prometheus Server 1   | <http://localhost:29090/>  |
| beacon-prometheus3     | Beacon Prometheus Server 1   | <http://localhost:39090/>  |
| beacon-prometheus4     | Beacon Prometheus Server 1   | <http://localhost:49090/>  |
| dclocal-prometheus1    | DC local Prometheus Server 1 | <http://localhost:2221/>   |
| dclocal-prometheus2    | DC local Prometheus Server 1 | <http://localhost:2222/>   |
| thanos-querier         | Thanos Querier               | <http://localhost:20902/>  |
| thanos-ruler           | Thanos Ruler                 | <http://localhost:20903/>  |
| thanos-bucket-web      | Thanos Bucket Web            | <http://localhost:20904/>  |
| thanos-store           | Thanos Store                 | not accessible via browser |
| thanos-compactor       | Thanos Compactor             | not accessible via browser |
| minio                  | Minio - Amazon S3 Compatible | <http://localhost:19001/>  |
| alertmanager           | Alertmanager                 | <http://localhost:19093/>  |
| grafana                | Grafana                      | <http://localhost:13000/>  |
| cadvisor               | cAdvisor                     | <http://localhost:18080/>  |

## Credentials

Grafana:

```bash
username - admin
password - foobar
```
  
Minio:

```bash
Access Key - EXAMPLEKEY
Secret Key - EXAMPLESECRET
```

## Explore metrics

* Explore metrics via Grafana <http://localhost:13000/explore> or the Thanos Query Frontend <http://localhost:20902>
