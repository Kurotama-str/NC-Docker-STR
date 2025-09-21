FROM nextcloud:apache

RUN set -ex; \
    \
    apt-get update; \
    apt-get install -y --no-install-recommends \
        ffmpeg \
        ghostscript \
        procps \
        smbclient \
        libreoffice \
        nano \
        cron \
        busybox-static \
        bzip2 \
        libldap-common \
        libmagickcore-7.q16-10-extra \
        rsync \
    ; \
    rm -rf /var/lib/apt/lists/*

ENV NEXTCLOUD_UPDATE=1
