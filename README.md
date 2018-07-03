# chintafreerepo

Spring Boot Maven project can be generated from below link:
https://start.spring.io/
To compile and deploy:
mvn clean package
cf push

Softwares required for UI development:
NodeJS
Install Angular CLI with below command:
sudo npm install -g @angular/cli@1.4 (using lower version of angular as cloudfoundry is not supporting v6 currently)
To compile and deploy:
ng build --prod
cf push


Installing bootstrap dependency:
npm install --save bootstrap
Add the style: node_modules/bootstrap/dist/css/bootstrap.min.css to styles in .angular-cli.json


Bluemix api ep: https://api.eu-gb.bluemix.net
CF api ep: https://api.run.pivotal.io

