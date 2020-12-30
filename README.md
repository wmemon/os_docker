# os_docker
OS docker Assignment 

### Question:

Create a Docker-compose yaml for the following Multi-container app (Drupal postgres)

contianer1 (front-end)


Front-end image - drupal:8-apache

Container port - 80

volumes 
        - /var/www/html/modules

        - /var/www/html/profiles
        
        - /var/www/html/themes
        
        - /var/www/html/sites

contianer2(database)

Back-end image - postgres:10

environment variable -  POSTGRES_PASSWORD: example


Note: Bring up both the containers on same user defined bridge network
