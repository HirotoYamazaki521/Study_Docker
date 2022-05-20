FROM ubuntu:20.04
RUN apt-get update -y && \
    apt-get install -y nginx
ENV TESTENV="Yamazaki"
ENV APP_ENV="production"
#ÇÊÇ≠égÇ§ÇÃÇ™ÅAlocat,oriduction
CMD ["nginx","-g","daemon off;"]
