FROM vookimedlo/fedora-clang:clang_31
LABEL maintainer="github@vookimedlo.cz"
LABEL homepage="https://github.com/vookimedlo/docker-images"

RUN yum install -y qt5 qt5-qtbase-devel

RUN echo "export QMAKESPEC=/usr/lib64/qt5/mkspecs/linux-clang" >> /etc/profile

