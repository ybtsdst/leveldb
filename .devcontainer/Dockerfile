FROM ubuntu:22.04

RUN apt-get update && \
    PKGS="curl git unzip wget zip" && \
    PKGS="${PKGS} build-essential ccache" && \
    apt-get install -y ${PKGS} && \
    apt-get autoclean && apt-get autoremove && \
    rm -rf /var/lib/apt/lists/*