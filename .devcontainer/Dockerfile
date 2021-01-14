FROM dgellow/idris2

RUN \
  apt-get update -y && \
  apt-get install -y chezscheme

RUN echo 'export PATH=/root/.idris2/bin/:$PATH' >>~/.bashrc
RUN echo 'alias idris=idris2' >>~/.bashrc
