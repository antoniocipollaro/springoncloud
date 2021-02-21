FROM quay.io/jkube/jkube-java-binary-s2i:0.0.9
ENV JAVA_APP_DIR=/deployments JAVA_OPTIONS=-Dspring.output.ansi.enabled=always
LABEL org.label-schema.description="Spring Boot Web application with a single @RestController.\
    Shows how to deploy Spring Boot applications to Kubernetes (-Pkubernetes) and OpenShift (-Popenshift) using Eclipse JKube." org.label-schema.version=1.1.0 org.label-schema.schema-version=1.0 org.label-schema.build-date=2021-02-10T11:54:22.328 org.label-schema.name="Eclipse JKube :: Quickstarts :: Maven :: Spring Boot Web" org.label-schema.vcs-ref=198feec66bf6d0ae053559b1876b2ad984144f3b org.label-schema.vcs-url=https://github.com/antoniocipollaro/springoncloud.git
EXPOSE 8080 8778 9779
COPY /deployments /deployments/
