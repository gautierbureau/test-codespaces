FROM fedora:29
LABEL maintainer Gautier Bureau "gautier.bureau@rte-france.com"

RUN dnf upgrade -y \
&& dnf update -y \
&& dnf install -y \
  git \
  gcc \
  gcc-c++ \
  gcc-gfortran \
  autoconf \
  automake \
  make \
  libtool \
  sudo \
  passwd \
  cmake \
  hwloc \
  java-1.8.0-openjdk-devel \
  blas-devel \
  lapack-devel \
  lpsolve-devel \
  expat-devel \
  glibc-devel \
  sqlite-devel \
  libarchive-devel \
  zlib-devel \
  doxygen \
  doxygen-latex \
  qt-devel \
  gettext \
  patch \
  wget \
  python-devel \
  clang \
  llvm-devel \
  ncurses-devel \
  readline-devel \
  unzip \
  perl-Digest-MD5 \
  vim \
  gcovr \
  python-pip \
  python-psutil \
  boost-devel \
  lcov \
  gtest-devel \
  gmock-devel \
  xz \
  rsync \
  python-lxml \
  graphviz \
  gpg \
  curl \
  dpkg \
  libcurl-devel \
  bash-completion \
&& dnf clean all \
&& rm -rf /var/cache/dnf/*
