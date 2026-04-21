In this example, we create a standard ACS deployment - using ACS v7.4. However, rather than using the pre-build Share image, we create our own using a specific version of tomcat defined from the .env file and the share.war file.

You will need to provide the share.war file in the ./share folder and then run

docker compose build
docker compose up -d
