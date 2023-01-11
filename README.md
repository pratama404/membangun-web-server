# Dicoding-FInal-Submission-Proyek-Membangun-Web-Server

Di sini saya sudah mencoba keduanya yaitu NGINX dan Apache2. FYI, karena saya menggunakan Centos Linux maka konfigurasi port dan konfigurasi proxy-nya menyatu pada konfigurasi utama yang berada pada /etc/httpd/conf/httpd.conf . Keseluruhan konfigurasi baik Apache2 (HTTPD) dan NGINX sudah menggunakan port 3000. Selain itu saya juga menambahkan addtional step yang saya lakukan untuk men-troubleshooting 502 Bad Gateway yang disebabkan oleh miss configuration SELinux.
