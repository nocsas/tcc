Nama    : dwi sasongko mukti  
NIM     : 175410010  
Jurusan : Teknik Informatika  
_________________  


>https://katacoda.com/courses/docker/deploying-first-container
# DEPLOYING FIRS CONTAINER  
## 1.Running a Container  
- To Find an image for Redis  
![1](image/1.PNG)  
- By default, Docker will run a command in the foreground. To run in the background, the option -d needs to be specified.  
![2](image/2.PNG)  

## 2.Finding Running Containers  
![3](image/3.PNG)  

## 3.Accessing Redis  
- menjalankan Redis di latar belakang, dengan nama redisHostPort di port 6379
![4](image/4.PNG)  
- menjalankan beberapa instance Redis dan mengkonfigurasi aplikasi tergantung pada port mana Redis sedang berjalan  
![5](image/5.PNG)  

## 4.Persisting Data  
- menggunakan dokumentasi Docker Hub untuk Redis  
![6](image/6.PNG)  

## 5.Running A Container In The Foreground  
- meluncurkan wadah Ubuntu dan mengeksekusi perintah ps untuk melihat semua proses yang berjalan dalam wadah dan mendapatkan akses ke bash shell di dalam sebuah wadah  
![7](image/7.PNG)