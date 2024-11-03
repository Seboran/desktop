FROM mcr.microsoft.com/devcontainers/base:ubuntu-20.04
RUN apt-get update && apt-get upgrade -y && apt-get install mercurial -y
RUN apt-get install -y xauth x11-apps x11-common
RUN apt-get install libc++-dev dos2unix yasm nasm build-essential libgtk2.0-dev libpython3-dev m4 uuid libasound2-dev libcurl4-openssl-dev libdbus-1-dev libdrm-dev libdbus-glib-1-dev libdbus-glib-1-dev libgtk-3-dev libpulse-dev libx11-xcb-dev libxt-dev xvfb lld llvm clang -y