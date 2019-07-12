## Environment docker magento 2

> To prepare your magento 2 environment you can follow the following steps:
- Create a folder named 'docker-magento2' and create a new folder 'docker'
- In the 'docker' folder, clone the two docker files.
- Copy the file **. Env.dist ** and paste with the name **. Env **, you can modify the ports, the ip addresses or leave them as they are.
- In the file docker-compose.yml: you can change the image tag 'yaissaoui / magento2':

    ##### Ubuntu 18.04.2 LTS
    - Apache/2.4.29
    - Webmin 1.920
    - Composer 1.8.6
    - Git 2.17.1
   
    | Tag | Features | Magento|
    | --- | --- | --- |
    | `2.2.x` | PHP version **7.1.30** | Magento 2.2.x |
    | `2.3.x` | PHP version **7.2.20** | Magento 2.3.x |    
    
    You can visit: [magento2-tags](https://cloud.docker.com/repository/docker/yaissaoui/magento2/tags)
    
    
- In the 'docker' folder launch the command:   
     ``docker-compose up -d``
     
> WebMin: https://127.0.0.1:10000 (You can create virtualhost from webmin).    
    phpMyAdmin: 127.0.0.1:8080

