FROM artifactory.sydbank.dev/docker-hub/grafana/grafana:13.3

ENV GF_PATHS_PLUGINS=/opt/grafana-plugins

COPY --chown=472:0 dist/ ${GF_PATHS_PLUGINS}/yesoreyeram-infinity-datasource/

ENV GF_PLUGINS_ALLOW_LOADING_UNSIGNED_PLUGINS=yesoreyeram-infinity-datasource
