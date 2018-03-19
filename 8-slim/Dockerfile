FROM scratch
LABEL "org.opencontainers.image.authors"="Oracle Linux Product Team <ol-ovm-info_ww@oracle.com>" \
      "org.opencontainers.image.url"="https://github.com/oracle/container-images" \
      "org.opencontainers.image.source"="https://github.com/oracle/container-images/tree/dist-arm64v8/8-slim" \
      "org.opencontainers.image.vendor"="Oracle America, Inc" \
      "org.opencontainers.image.title"="Oracle Linux 8 (slim)" \
      "org.opencontainers.image.description"="Oracle Linux is an open-source \
      operating system available under the GNU General Public License (GPLv2) and \
      is suitable for both general purpose or Oracle workloads."

ADD oraclelinux-8-slim-arm64v8-rootfs.tar.xz /

# overwrite this with 'CMD []' in a dependent Dockerfile
CMD ["/bin/bash"]
