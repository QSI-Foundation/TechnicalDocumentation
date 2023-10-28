FROM    alpine:3.18

# Install bash as default shell
RUN     apk -- add bash-completion
RUN     sed -i -e's@:/bin/ash$@:/bin/bash@' -- /etc/passwd

# Install tools
RUN     apk -- add git-lfs make

# Install python and its packages
RUN     apk -- add py3-pip
ADD     requirements.txt /requirements.txt
RUN     pip install -r/requirements.txt && rm -- /requirements.txt
