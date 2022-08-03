STeps to run


Step 1 : docker build -t ng-docker-example .
 
Step 2 : docker run -p 80:80 ng-docker-example

FROM nginx:1.17.1-alpine

COPY /dist/ng-docker-example /usr/share/nginx/html

