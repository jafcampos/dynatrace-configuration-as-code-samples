FROM mcr.microsoft.com/devcontainers/base:alpine

RUN curl -L https://github.com/Dynatrace/dynatrace-configuration-as-code/releases/latest/download/monaco-linux-amd64 -o monaco-linux-amd64

RUN mv monaco-linux-amd64 monaco

RUN chmod +x monaco

RUN sudo mv monaco /usr/local/bin/