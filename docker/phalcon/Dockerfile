FROM eboraas/phalcon
MAINTAINER Harald Nezbeda <hn@nezhar.com>


RUN /usr/bin/apt-get update && apt-get -y install git
        
RUN git clone https://github.com/phalcon/phalcon-devtools.git /usr/local/lib/phalcon-devtools && \
    ln -s /usr/local/lib/phalcon-devtools/phalcon.php /usr/bin/phalcon && \
    chmod +x /usr/bin/phalcon

