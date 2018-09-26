FROM node:8

USER root

RUN git clone https://github.com/bob-crutchley/spring-petclinic-angular.git && cd spring-petclinic-angular && \
npm install -g @angular/cli@latest && npm install 

ENTRYPOINT ["ng", "serve", "--host", "0.0.0.0", "--port", "4200"]
