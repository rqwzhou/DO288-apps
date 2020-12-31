FROM fabric8/s2i-java:2.3
ENV AB_PROMETHEUS_OFF=true JAVA_APP_DIR=/deployments
LABEL org.label-schema.description="Hello microservice using Thorntail" org.label-schema.version=1.0 org.label-schema.schema-version=1.0 org.label-schema.build-date=2020-12-31T17:54:01.038 org.label-schema.name="Red Hat Training Hello Java app" org.label-schema.vcs-ref=609e5cb05a7f118d93f47a1dc66a31d899315be2 org.label-schema.vcs-url=https://github.com/rqwzhou/DO288-apps
EXPOSE 8080 8778 9779
COPY maven /deployments/
