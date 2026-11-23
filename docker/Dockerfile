FROM artifactory.sydbank.dev/docker-hub/grafana/grafana:13.3

COPY dist/ /var/lib/grafana/plugins/yesoreyeram-infinity-datasource/

ENV GF_PLUGINS_ALLOW_LOADING_UNSIGNED_PLUGINS=yesoreyeram-infinity-datasource
