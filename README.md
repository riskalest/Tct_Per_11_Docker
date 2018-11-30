Docker
======

## *Apa Docker?*

Docker adalah salah satu platform yang dibangun berdasarkan teknologi container. Docker merupakan sebuah project open-source yang menyediakan platform terbuka untuk developer maupun sysadmin untuk dapat membangun, mengemas, dan menjalankan aplikasi dimanapun sebagai sebuah wadah (container) yang ringan. Dengan sangat populernya docker, sebagian orang sering menganggap docker adalah sebutan lain untuk container.

## *Praktik Docker*

Pada pertemuan ke-11 ini kita mempraktikkan bagaimana menggunakan docker, membuat image di docker, dan menjalankannya

### 1.	https://www.katacoda.com/courses/docker/deploying-first-container/

#### Step 1 - Running A Container
 
 ![logo](https://github.com/riskalest/tct/blob/master/minggu-09/Web-2.0.jpg)
 
#### Step 2 - Finding Running Containers

 ![logo](https://github.com/riskalest/tct/blob/master/minggu-09/Web-2.0.jpg)
 
#### Step 3 - Accessing Redis

 ![logo](https://github.com/riskalest/tct/blob/master/minggu-09/Web-2.0.jpg)
 
#### Step 4 - Accessing Redis

 ![logo](https://github.com/riskalest/tct/blob/master/minggu-09/Web-2.0.jpg)
 
#### Step 5 - Persisting Data

 ![logo](https://github.com/riskalest/tct/blob/master/minggu-09/Web-2.0.jpg)
 
#### Step 6 - Running A Container In The Foreground

 ![logo](https://github.com/riskalest/tct/blob/master/minggu-09/Web-2.0.jpg)

### 2.	https://www.katacoda.com/courses/docker/create-nginx-static-web-server/

#### Step 1 - Create Dockerfile

 ![logo](https://github.com/riskalest/tct/blob/master/minggu-09/Web-2.0.jpg)
 
#### Step 2 - Build Docker Image

 ![logo](https://github.com/riskalest/tct/blob/master/minggu-09/Web-2.0.jpg)
 
#### Step 3 - Run

 ![logo](https://github.com/riskalest/tct/blob/master/minggu-09/Web-2.0.jpg)

### 3.	https://www.katacoda.com/courses/docker/2/

#### Step 1 - Base Images

FROM nginx:1.11-alpine

#### Step 2 - Running Commands

COPY index.html /usr/share/nginx/html/index.html

#### Step 3 - Exposing Ports

EXPOSE 80

#### Step 4 - Default Commands

CMD ["nginx", "-g", "daemon off;"]

 ![logo](https://github.com/riskalest/tct/blob/master/minggu-09/Web-2.0.jpg)

#### Step 5 - Building Containers

 ![logo](https://github.com/riskalest/tct/blob/master/minggu-09/Web-2.0.jpg)
 
#### Step 6 - Launching New Image

 ![logo](https://github.com/riskalest/tct/blob/master/minggu-09/Web-2.0.jpg)

### 4.	https://www.katacoda.com/courses/docker/3/

Pada praktik ke-4 ini halaman tidak bisa dibuka atau tidak merespon

#### Terimakasih :)


REFERENSI :
===========
https://www.codepolitan.com/mengenal-teknologi-docker

https://www.katacoda.com/courses/docker/deploying-first-container/

https://www.katacoda.com/courses/docker/create-nginx-static-web-server/

https://www.katacoda.com/courses/docker/2/

https://www.katacoda.com/courses/docker/3/
