FROM ubuntu:xenial

RUN apt -qq update \
 && apt -qq upgrade -y \
 && apt -qq install -y texlive-full \
 && rm -rf /var/lib/apt/lists/*

# overwrite this with 'CMD []' in a dependent Dockerfile
CMD ["/bin/bash"]
