Docker
======

## *Apa Docker?*

Docker adalah salah satu platform yang dibangun berdasarkan teknologi container. Docker merupakan sebuah project open-source yang menyediakan platform terbuka untuk developer maupun sysadmin untuk dapat membangun, mengemas, dan menjalankan aplikasi dimanapun sebagai sebuah wadah (container) yang ringan. Dengan sangat populernya docker, sebagian orang sering menganggap docker adalah sebutan lain untuk container.

## *Praktik Docker*

Pada pertemuan ke-11 ini kita mempraktikkan bagaimana menggunakan docker, membuat image di docker, dan menjalankannya

### 1.	https://www.katacoda.com/courses/docker/deploying-first-container/

#### Step 1 - Running A Container

Menjalankan container dengan docker image bernama radis,
 
 ![logo](https://github.com/riskalest/Tct_Per_11_Docker/blob/master/1_s_1.PNG)
 
#### Step 2 - Finding Running Containers

Mencari Containewr yang sedang berjalan. Pada command akan menampilkan list semua container yang sedang berjalan, dan image digunakan untuk start dan waktunya. pada command juga menampilkan nama dan ID yang bisa digunakan untuk mencari informasi pada tiap container.

 ![logo](https://github.com/riskalest/Tct_Per_11_Docker/blob/master/1_s_2.PNG)
 
#### Step 3 - Accessing Redis

Karena Radis berjalan pada port 6379, sehingga untuk mengakses radis menggunakan nama redisHostPort pada port 6379. 

 ![logo](https://github.com/riskalest/Tct_Per_11_Docker/blob/master/1_s_3.PNG)
 
#### Step 4 - Accessing Redis

 ![logo](https://github.com/riskalest/Tct_Per_11_Docker/blob/master/1_s_4.PNG)
 
#### Step 5 - Persisting Data

 ![logo](https://github.com/riskalest/Tct_Per_11_Docker/blob/master/1_s_5.PNG)
 
#### Step 6 - Running A Container In The Foreground

 ![logo](https://github.com/riskalest/Tct_Per_11_Docker/blob/master/1_s_6.PNG)

### 2.	https://www.katacoda.com/courses/docker/create-nginx-static-web-server/

#### Step 1 - Create Dockerfile

 ![logo](https://github.com/riskalest/Tct_Per_11_Docker/blob/master/2_s_1.PNG)
 
#### Step 2 - Build Docker Image

Docker image merupakan sekumpulan software siap pakai yang tidak perlu dinstall, dan bisa langsung digunakan.

 ![logo](https://github.com/riskalest/Tct_Per_11_Docker/blob/master/2_s_2.PNG)
 
#### Step 3 - Run

 ![logo](https://github.com/riskalest/Tct_Per_11_Docker/blob/master/2_s_3.PNG)

### 3.	https://www.katacoda.com/courses/docker/2/

#### Step 1 - Base Images

FROM nginx:1.11-alpine

#### Step 2 - Running Commands

COPY index.html /usr/share/nginx/html/index.html

#### Step 3 - Exposing Ports

EXPOSE 80

#### Step 4 - Default Commands

CMD ["nginx", "-g", "daemon off;"]

 ![logo](https://github.com/riskalest/Tct_Per_11_Docker/blob/master/3_s_4.PNG)

#### Step 5 - Building Containers

 ![logo](https://github.com/riskalest/Tct_Per_11_Docker/blob/master/3_s_5.PNG)
 
#### Step 6 - Launching New Image

 ![logo](https://github.com/riskalest/Tct_Per_11_Docker/blob/master/3_s_6.PNG)
 

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
