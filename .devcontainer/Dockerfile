FROM mcr.microsoft.com/devcontainers/javascript-node:22-bookworm

# [Optional] Uncomment this section to install additional OS packages.
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends gnupg2 zsh

# [Optional] Install global node modules
RUN su node -c "npm install -g npm-check-updates better-commits"
