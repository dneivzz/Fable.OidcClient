
FROM mcr.microsoft.com/devcontainers/dotnet:0-6.0-bullseye

RUN groupadd docker
RUN usermod -aG docker vscode

WORKDIR /workspace/Fable.OidcClient

COPY . .

USER vscode

CMD sleep infinity