#
# Pull base image
# ---------------
FROM oraclelinux:7-slim as base-ol7-slim-enhanced

# Labels
LABEL "provider"="ch-lam"

# add mimimal stuff
RUN yum -y install vim ;\
    rm -rf /var/cache/yum
