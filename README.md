# MQTT Client for Pixel Badge

Simple MQTT Client for the Pixel Badge. Allows to show messages published on
the topic <client_id>/text. The default client_id is badge.

To specify custom client_id use valuestore in the shell:

```python
import valuestore
settings = {"client_id": "your_client_id", "mqtt_server": "your.server.tld"})
valuestore.save('mqttclient', 'settings', settings)
```
