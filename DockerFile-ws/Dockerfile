From deepakdocker25/cent-ssh:v1
RUN yum install net-tools -y
RUN yum install openssh-server -y
RUN ssh-keygen -A
RUN yum install passwd -y
RUN echo 123456 | passwd root --stdin
ENTRYPOINT ["sshd"]
CMD ["-D"] 

