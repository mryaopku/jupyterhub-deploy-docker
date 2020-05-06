ARG DOCKER_NOTEBOOK_IMAGE
FROM $DOCKER_NOTEBOOK_IMAGE
ARG JUPYTERHUB_VERSION
USER root
COPY ./pip.conf /etc/pip.conf
COPY ./sources.list /etc/apt/sources.list
RUN python3 -m pip install --no-cache jupyterhub
