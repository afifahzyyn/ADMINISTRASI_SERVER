Terapkan Banyak Kontainer menggunakan Docker Compose

1. Mulai Instance EC2 di AWS
2. Memperbaiki OS
3. Copot semua manual Layanan sebelumnya
4. Repositori baru untuk web dinamis di docker hub

    ![alt text](image.png)

5. Buka Projek Company compro_nim
6. Bagi 2 Folder untuk projek Web App Statis dan Dinamis
7. Move file index dan Dcoker milik web statis ke Folder web-statis
8. Copy Folder Projek Next.JS (pertemuan9)ke folder web-dinamis
9. Lakukan Testing di Local Project Next.JS
    - Install Dependencies: npm install
    - Create user di DBMS : sudo mysql -u root -p
    - CREATE USER 'userwebdinamis_2388010032'@'localhost' IDENTIFIED BY '5ieP)[9QAVc/gNgI';
    - GRANT ALL PRIVILEGES ON *.* TO 'userwebdinamis_2388010032'@'localhost';
    - FLUSH PRIVILEGES;
    - exit;
![alt text](image-1.png)

    - Edit File .env di folder web-dinamis
    - npm run build
    - npm start
    - Pastikan web dapat diakses di http://localhost:3000 admin tanpa error
![alt text](image-2.png)

10. Buat file Dockerfile
11. Buat file docker-compose.yml
12. Buat Workflows File -> deploy-dinamis.yml di folder .github/workflows/ dari Projek web-dinamis
13. Edit File -> deploy.yml di folder .github/workflows/ untuk
14. Update Host AWS di Github
15. Commit Changes ke GitHub dari lokal
16. Push Changes ke GitHub
17. Cek di Github, apakah actions jalan dan berhasil

![alt text](image-3.png)
18. Periksa di AWS, apakah container berjalan dengan baik
![alt text](image-6.png)
19. Akses web melalui Browser login admin edit Layanan

![alt text](image-5.png)