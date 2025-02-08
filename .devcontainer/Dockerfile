FROM mcr.microsoft.com/devcontainers/base:debian

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends \
    build-essential ruby texlive-latex-recommended \
    texlive-fonts-recommended texlive-latex-extra \
    texlive-bibtex-extra \
    && apt-get clean && rm -rf /var/lib/apt/lists/*