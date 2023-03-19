FROM almalinux
RUN yum install nginx -y
## When Image creator is running,this below command will not run. When some one tries to use your image then it will run.
ONBUILD ADD simple.txt /tmp/