FROM n8nio/runners:2.1.5
USER root
RUN cd /opt/runners/task-runner-javascript && pnpm add pdf-lib xmlbuilder2
COPY n8n-task-runners.json /etc/n8n-task-runners.json
USER runner
