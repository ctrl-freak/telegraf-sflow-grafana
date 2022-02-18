# telegraf-sflow-grafana
Use Telegraf to send sFlow data to Grafana (Cloud)

# Telegraf

Uses http output with `prometheusremotewrite` serializer:

https://github.com/influxdata/telegraf/tree/master/plugins/serializers/prometheusremotewrite

# Prometheus

## Grafana Cloud

Get your Prometheus API details from the **Cloud Portal**

https://grafana.com/auth/sign-in/?cta=myaccount

On the **Prometheus** card, click **Details**

Fill in the Basic Authentication details in .env PROMETHEUS_URL, ie: https://User:Password@URL
