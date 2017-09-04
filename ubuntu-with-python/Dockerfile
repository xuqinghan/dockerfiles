#ubuntu-with-python36

#xuqinghan @ 20170903

#ubuntu16.04+python36


FROM ubuntu

#python3.6  http://ubuntuhandbook.org/index.php/2017/07/install-python-3-6-1-in-ubuntu-16-04-lts/
#RUN cp ./sources.list /etc/apt/sources.list
RUN apt-get update
RUN apt-get install -y apt-transport-https ca-certificates curl software-properties-common
RUN add-apt-repository ppa:jonathonf/python-3.6
RUN apt-get update
RUN apt-get install -y python3.6
RUN apt-get install python3.6-gdbm
RUN update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.5 1
RUN update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.6 2
RUN update-alternatives --config python3
#RUN rm /usr/bin/python3
#RUN ln -s python3.5 /usr/bin/python3
