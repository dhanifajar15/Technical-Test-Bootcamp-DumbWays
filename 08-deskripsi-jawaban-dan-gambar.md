Untuk alurnya ada di folder 08 di dalam folder-images-jawaban

Tutorial :
1. Pertama pastikan nginx telah terinstal di linux
2. Buat folder di var/www/nama-domain-kalian
3. Buat permission pada user yang terdaftar dan dibuat 577 untuk chmod nya
4. Buat konfigurasi pada nginx /etc/nginx/sites-available/nama-domain-kalian.conf
5. Konfigurasikan berdasarkan default dan edit sedikit sesuai kebutuhan
6. Buat symlink dari sites-available ke sites-enabled pada konfigurasi kalian
7. Setelah itu, restart nginx 
8. Jalankan domain kalian pada browser
