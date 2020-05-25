

To create docker image:

    create war file 2.Create Dockerfile in paste the following

    FROM jboss/wildfly ADD forex-java.war /opt/jboss/wildfly/standalone/deployments/

    docker build -t filename.war .

    docker run -it -p 8080:8080 image_name

