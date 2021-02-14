## Alpine Nginx configuration and Docker file for SSR Angular app
### Contains
  - Dockerfile
  - Apline Nginx configuration file default.conf

### Installation
1) Copy the Dockerfile to the root of your Angular project.
2) In the root of your Angular project, create a directory nginx/conf.d
3) Copy the default.conf file to that directory.

4) Adjust the Dockerfile and default.conf to your environment: 
  - In Dockerfile replace bloggybootsv02 to your project name, this is the property "name" in package.json 
  - In default.conf replace "mydomain" to your domain name

For more info: [medium.com](https://medium.com/javascript-in-plain-english/your-guide-for-deploying-an-angular-app-on-google-cloud-aint-complete-f6d5998332fb)
