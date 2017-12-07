FROM python:2.7
MAINTAINER uoks <uolgks@gmail.com>

RUN apt-get update \
&& apt-get install -y libzmq-dev \
&& git clone https://github.com/9miao/G-Firefly GFirefly \
&& cd ./GFirefly/gfirefly \
&& python ./setup.py install

WORKDIR /root

CMD ["/bin/bash"]

