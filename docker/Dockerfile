FROM scratch

COPY rootfs /
RUN ["/bin/busybox", "sh", "-c", "rm -r /usr/share/man /usr/share/doc"]

CMD ["/bin/busybox", "sh"]
