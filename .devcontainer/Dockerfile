FROM mcr.microsoft.com/vscode/devcontainers/base:bullseye
RUN apt-get update \
    && apt-get install -y libwebkit2gtk-4.0-dev libssl-dev libgtk-3-dev libayatana-appindicator3-dev librsvg2-dev git vim curl bash \
    && apt-get clean -y && rm -rf /var/lib/apt/lists/*
