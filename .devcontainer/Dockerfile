# See here for image contents: https://github.com/microsoft/vscode-dev-containers/tree/v0.191.0/containers/javascript-node/.devcontainer/base.Dockerfile

# [Choice] Node.js version: 16, 14, 12
ARG VARIANT="16-buster"
FROM mcr.microsoft.com/vscode/devcontainers/javascript-node:0-${VARIANT}

ARG USERNAME="node"
RUN mkdir -p /home/$USERNAME/.vscode-server/extensions \
    /workspaces/issydneyinhardlockdown/src/node_modules \
    /workspaces/issydneyinhardlockdown/infra/node_modules \
    && chown -R $USERNAME \
    /home/$USERNAME/.vscode-server \
    /workspaces