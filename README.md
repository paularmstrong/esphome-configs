ESPHome configs

Needed:
* `pip3 install esphome`
* `secrets.yaml` file with
```yaml
wifi_ssd:
wifi_pass:
ap_pass:
```

Run the ESPHome dashboard and open http://localhost:6052
```sh
esphome ./ dashboard
```
