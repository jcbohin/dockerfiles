FROM ubuntu:xenial

# Install full latex distribution
RUN apt -qq update \
 && apt -qq upgrade -y \
 && apt -qq install -y texlive-latex-base texlive-fonts-recommended texlive-fonts-extra texlive-latex-extra \
 && rm -rf /var/lib/apt/lists/*

# overwrite this with 'CMD []' in a dependent Dockerfile
CMD ["/bin/bash"]
