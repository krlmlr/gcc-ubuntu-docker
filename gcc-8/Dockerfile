FROM ubuntu:bionic
LABEL org.opencontainers.image.authors="Thomas Kent <docker@teeks99.com>"

# Pre-Req Repos
RUN apt-get update \
 && apt-get install -y software-properties-common \
 #in bionic && add-apt-repository -y ppa:ubuntu-toolchain-r/test \
# Install pre-reqs
 && apt-get update \
 && apt-get install -y \
  ca-certificates \
  build-essential \
# Install Tool
  gcc-8 \
  g++-8

