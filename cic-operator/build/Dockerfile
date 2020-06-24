FROM quay.io/operator-framework/helm-operator:v0.13.0

LABEL name="Citrix Ingress Controller Operator" \
      vendor="Citrix" \
      version="v1.8.19" \
      release="1" \
      summary="This is a Citrix API Gateway operator." \
      description="This operator will deploy Citrix API Gateway to the cluster."

COPY licenses /licenses

COPY watches.yaml ${HOME}/watches.yaml
COPY helm-charts/ ${HOME}/helm-charts/
