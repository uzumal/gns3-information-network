FROM gns3/webterm

RUN echo 'apt-get update -qq && apt-get install -yq $@ && apt-get clean && rm -rf /var/lib/apt/lists/*' > /usr/local/bin/pkdadd.sh &&\
    chmod +x /usr/local/bin/pkdadd.sh

# japanize
RUN \
    # set timezone
    ln -s -f /usr/share/zoneinfo/Asia/Tokyo /etc/localtime &&\
    dpkg-reconfigure tzdata &&\
    pkdadd.sh fonts-takao sudo &&\
    apt-get update &&\
    apt-get install locales -y &&\
    # generate locale
    locale-gen ja_JP.UTF-8
ENV LANG ja_JP.UTF-8
