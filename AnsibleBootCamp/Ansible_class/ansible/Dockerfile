FROM tutum/ubuntu

RUN apt-get update
RUN apt-get install vim -y
RUN rm -f /set_root_pw.sh
RUN echo "root:pass" | chpasswd

