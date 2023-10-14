FROM    alpine:3.18

# Install bash as default shell
RUN     apk -- add bash-completion
RUN     sed -i -e's@:/bin/ash$@:/bin/bash@' -- /etc/passwd

# Install tools
RUN     apk -- add git-lfs

# Install python and its packages
RUN     apk -- add py3-pip
RUN     pip -- install sphinx
