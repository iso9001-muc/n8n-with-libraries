FROM n8nio/runners:2.1.5
USER root

# JS libs (hast du vermutlich schon)
RUN cd /opt/runners/task-runner-javascript && pnpm add pdf-lib xmlbuilder2

# Python libs
RUN cd /opt/runners/task-runner-python && uv pip install requests

COPY n8n-task-runners.json /etc/n8n-task-runners.json
USER runner
