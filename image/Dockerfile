FROM cloudfoundry/cflinuxfs3

RUN wget -O /usr/local/bin/dumb-init https://github.com/Yelp/dumb-init/releases/download/v1.2.2/dumb-init_1.2.2_amd64
RUN chmod +x /usr/local/bin/dumb-init

ADD sshd /lifecycle/
ADD launcher /lifecycle/
ADD launch /lifecycle/original-launch
ADD new-launch /lifecycle/launch
