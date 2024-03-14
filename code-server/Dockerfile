FROM codercom/code-server

USER root

RUN curl https://sh.rustup.rs -sSf | bash -s -- -y
ENV PATH="/root/.cargo/bin:${PATH}"
RUN apt update -y && apt install python3 unzip -y
RUN curl -fsSL https://bun.sh/install | bash

EXPOSE 8080

