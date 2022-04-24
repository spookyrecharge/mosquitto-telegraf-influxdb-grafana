# mosquitto-telegraf-influxdb-grafana
100% working docker-compose solution for IoT metrics visualisation

I made this becase I was frustrated finding some other repos/guides where people were using 'latest' tags in docker images from dockerhub and thus making whole setup non-operable

I'll explain:

InfluxDB: After release version 2+ they changed a lot of things which is not needed for a simple setup like ours. Buckets and organizations are good but not in our case. Good luck making automated setup with influxdb token and grafana/telegraf

Mosquitto: After release version 2+ they changed their security concept. Gonna make it work with Mosquitto 2+ later

Telegraf and Grafana is also stricted to the specific LATEST tag, because:

1.) I'll update them from time to time since I'm also using this setup
2.) This strict setup is tested by me, so no worries about functionality
