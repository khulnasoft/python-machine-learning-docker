FROM khulnasoft/python-machine-learning:python3.6

LABEL maintainer="KhulnaSoft DevOps <info@khulnasoft.com>"

RUN conda install tensorflow

COPY ./start.sh /start.sh
RUN chmod +x /start.sh

CMD [ "/start.sh" ]
