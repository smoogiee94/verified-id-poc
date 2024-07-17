FROM --platform=linux/amd64 wso2/wso2is:7.0.0
USER root
COPY ./deployment.toml /home/wso2carbon/wso2is-7.0.0/repository/conf/deployment.toml
RUN chmod o+r /home/wso2carbon/wso2is-7.0.0/repository/conf/deployment.toml
USER 802
ENTRYPOINT ["/home/wso2carbon/docker-entrypoint.sh"]