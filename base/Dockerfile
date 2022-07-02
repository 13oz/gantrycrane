FROM scratch

LABEL version="0.1"
LABEL maintainer="Nikita Dyminskiy"

ADD centos-bash.tar.xz /

ENV PATH "/bin:/sbin:"
CMD ["chsh", "/bin/bash"]
ENTRYPOINT ["/bin/bash"]