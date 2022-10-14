# Docker Commands

- In this repro docker basic commands are explained with screenshots

## Authors
- [@c21hawke](https://www.github.com/c21hawke)

## TASK - 1

## 01. Docker command to check docker version
  
  ```bash
  docker --version
  ```
  - ## Screenshot
    ![Image](https://github.com/c21hawke/docker-assignment-task1/blob/main/images/01.png) 
 
## 02. Docker command to pull an image from docker hub
  
  ```bash
  docker pull docker/getting-started
  ```
  
  - ## Screenshot
    ![Image](https://github.com/c21hawke/docker-assignment-task1/blob/main/images/02.png) 
  
## 03. Docker command to list images
  
  ```bash
  docker images
  ```
  
  - ## Screenshot
    ![Image](https://github.com/c21hawke/docker-assignment-task1/blob/main/images/03.png) 
 
## 04. Docker command to run an image 
  
  - If image is not present locally then it pulls the images first and the run
  - It is same as pull + run command
  
  ```bash
  docker run -d docker/getting-started
  ```
  
  - ## Screenshot
    ![Image](https://github.com/c21hawke/docker-assignment-task1/blob/main/images/04.png) 
  
## 05. Docker command to list the running containers

  ```bash
  docker ps
  ```
  
  - ## Screenshot
    ![Image](https://github.com/c21hawke/docker-assignment-task1/blob/main/images/05.png) 
    
## 06. Docker command to start a container

  ```bash
  docker start [container_id]
  ```
  - ## Screenshot
    ![Image](https://github.com/c21hawke/docker-assignment-task1/blob/main/images/06.png) 
    
## 07. Docker command to stop a container

  ```bash
  docker stop [container_id]
  ```
  
  - ## Screenshot
    ![Image](https://github.com/c21hawke/docker-assignment-task1/blob/main/images/07..png) 

## 08. Docker command to restart a container

  ```bash
  docker restart [container_id]
  ```
  
  - ## Screenshot
    ![Image](https://github.com/c21hawke/docker-assignment-task1/blob/main/images/08..png) 
    
## 09. Docker command to pause a container

  ```bash
  docker pause [container_id]
  ```
  
  - ## Screenshot
    ![Image](https://github.com/c21hawke/docker-assignment-task1/blob/main/images/09.png) 
 
## 10. Docker command to unpause a container

  ```bash
  docker unpause [container_id]
  ```
  
  - ## Screenshot
    ![Image](https://github.com/c21hawke/docker-assignment-task1/blob/main/images/10..png) 
  
## 11. Docker command to remove a container
  
  ```bash
  docker rm -f [contaoner_id]
  ```
  
  - ## Screenshot
    ![Image](https://github.com/c21hawke/docker-assignment-task1/blob/main/images/11.png) 

## 12. Docker command to list all images

  ```bash
  docker ps -a
  ```
  
  - ## Screenshot
    ![Image](https://github.com/c21hawke/docker-assignment-task1/blob/main/images/12.png) 

## 13. Docker command to list process running inside the container

  ```bash
  docker top [container_id]
  ```
  
  - ## Screenshot
    ![Image](https://github.com/c21hawke/docker-assignment-task1/blob/main/images/13.png) 
    
## 14. Docker command to show differences with image files
  
  ```bash
  docker diff [container_id]
  ```
  - ## Screenshot
    ![Image](https://github.com/c21hawke/docker-assignment-task1/blob/main/images/14.png) 
    
## 15. Docker command to show low-level info in json format
  
  ```bash
  docker inspect [container_id]
  ```
  
  - ## Screenshot
    ![Image](https://github.com/c21hawke/docker-assignment-task1/blob/main/images/15.png) 
    
## 16. Docker command to show image history (list of ancestors)
  
  ```bash
  docker history [image]
  ```
  
  - ## Screenshot
    ![Image](https://github.com/c21hawke/docker-assignment-task1/blob/main/images/16.png)
  
## 17. Docker command to rename container name

  ```bash
  docker rename [old_name] [new_name]
  ```
  - ## Screenshot
    ![Image](https://github.com/c21hawke/docker-assignment-task1/blob/main/images/17.png) 

## License

[MIT](https://choosealicense.com/licenses/mit/)


## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/c21hawke)
