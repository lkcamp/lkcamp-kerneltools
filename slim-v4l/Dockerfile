FROM rocha1558/lkcamp-kerneltools:slim

ENV DEBIAN_FRONTEND noninteractive

RUN set -x \
  && apt-get update \
  && apt-get install -y --no-install-recommends \
                   exuberant-ctags              \
		   cscope                       \
		   strace                       \
		   dh-autoreconf		\
		   autotools-dev		\
		   doxygen      		\
		   gettext      		\
		   graphviz     		\
		   libasound2-dev		\
		   libtool      		\
		   libjpeg-dev  		\
		   qtbase5-dev  		\
		   libudev-dev  		\
		   libx11-dev   		\
		   qt5-default  		\
		   meson			\
		   kmod				\
		   tig				\
		   bash-completion		\
		   debhelper			\
		   dh-autoreconf		\
		   autotools-dev		\
		   autoconf-archive		\
		   doxygen			\
		   graphviz			\
		   libasound2-dev		\
		   libtool			\
		   libjpeg-dev			\
		   libqt5opengl5-dev		\
		   libudev-dev			\
		   libx11-dev			\
		   pkg-config			\
		   udev				\
		   make				\
		   gcc				\
		   git				\
		   ninja-build			\
		   v4l-utils			\
		   strace                       \
  && rm -rf /var/lib/apt/lists/*          \
  && pip3 install --user git-pw
