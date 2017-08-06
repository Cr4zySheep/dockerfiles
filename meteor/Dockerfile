FROM phusion/baseimage:0.9.22

RUN useradd -mUd /home/meteor meteor
RUN chown -Rh meteor /usr/local
USER meteor:meteor

RUN curl https://install.meteor.com | sh

WORKDIR /home/meteor/app
