FROM texlive/texlive:latest

USER root

RUN apt update
RUN apt install fish -y
RUN curl https://raw.githubusercontent.com/oh-my-fish/oh-my-fish/master/bin/install > install_omf
RUN fish install_omf --noninteractive


# Si falla por las fuentes, descomenta esto
# RUN ln -s /usr/local/texlive/2023/texmf-dist/fonts /usr/local/fonts

WORKDIR /workspace
