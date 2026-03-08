1. pastikan sudah install Putty
![alt text](image-15.png)

2. konversi file publik key dari  .pem menjadi .ppk di Putty
    buka puttyGen
    load File .pem
    save as .ppk

![alt text](image-16.png)

3. set up putty untuk remote SSH 
    • buka apps Putty
    • isi IP Public sesuai instance
    • isi nama session agar saaat connliect lagi    • tinggal load saja
    • load file .ppk(klik SSH -> Auth -> credentitals -> load file.ppk)
    • kembali ke session klik save
    • klik open 
    • masukan username sesuai instance 

![alt text](image-17.png)

![alt text](image-18.png)

4. "sudo apt-get update (update os) lanjut "sudo apt-get upgrade"
![alt text](image-19.png)

5. Pembuktian Remote SSH secara visual
    • Copy publik IPP Address instance paste ke browser
![alt text](image-20.png)
    • insall web server seperti Apache/Nginx
    • sudo apt insall apache2
    • reload browser
![alt text](image-21.png)

6. Matikan instance agar tidak kena tagihan 
    • sudi shutdown now
![alt text](image-22.png)