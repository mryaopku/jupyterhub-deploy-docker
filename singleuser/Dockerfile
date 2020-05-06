ARG DOCKER_NOTEBOOK_IMAGE
FROM $DOCKER_NOTEBOOK_IMAGE
ARG JUPYTERHUB_VERSION
COPY ./pip.conf /etc/pip.conf
COPY ./sources.list /etc/apt/sources.list
RUN python3 -m pip install --no-cache jupyterhub
