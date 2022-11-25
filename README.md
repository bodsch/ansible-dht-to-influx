
# Ansible Role:  `dht-to-influx`

Reads DHT sensor data and writes it to an InfluxDB2.

```yaml
dht_to_influx:
  influx:
    url:
    token:
    org:
    bucket:
  sensor:
    pin: 4
    model: 22
    measurement_name: dht22
    test: false
    verbose: false
  location:
    host: sensor-0x
    name: labor
  process:
    sleep: 60
```
