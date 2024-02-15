FROM almalinux:8
RUN yum install nginx -y
ENV TRAINING = "DEVOPS" \
    TRAINER = "SHIVA" \
    DURATION = "120HOURS" 
CMD ["nginx","-g","daemon off;"]