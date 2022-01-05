FROM nginx:latest
RUN apt-get update \
&& apt-get install -y mc \
&& apt-get install curl -y \
&& apt-get install git -y  \
&& apt-get install unzip \
# && apt-get install  wget \
&& cd /home \
&& curl -sL https://deb.nodesource.com/setup_16.x |  bash - \
&& apt-get install -y nodejs \
&& npm install -g npm \
&& mkdir /app 
WORKDIR /app
