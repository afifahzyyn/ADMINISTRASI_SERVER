

1. pilih menu All Services -> EC2
![alt text](image-3.png)

2. di dalam Menu EC2 pilih instance 
![alt text](image-4.png)

3. didalam nya pilih launch instance 
![alt text](image-7.png)

4. beri nama instance dengan format NIM_Server
![alt text](image-8.png)

5. kita pilih OS Server untuk instance 
![alt text](image-9.png)

6. pilih resource instance T3.Micro(2VCPU, 1GB Memory)
![alt text](image-10.png)

7. membuat key Pair, Pilih new key pair, isis nama key, pilih RSA, formmat file .pem, create key pair
![alt text](image-11.png)

8. setting kebijakan keamanan/ security Croup
        Allow SSH -> Artinya membolehkan Remote SSH dari luar
        Allow HTTPS -> Artinya instance bisa diakses dari protokol HHTPS
        Allow HTPP -> Artinya instance bisa diakses dari protokol HTPP
![alt text](image-12.png)

9. selesai set-up pilih instance
![alt text](image-13.png)

10. pastikan launch instance sukses
![alt text](image-14.png)

