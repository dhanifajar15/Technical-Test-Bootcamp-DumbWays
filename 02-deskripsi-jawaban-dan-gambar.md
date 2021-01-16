Saya menyarankan jika commit sudah benar, namun cuma message nya yang perlu dibetulkan, cukup reword commit tersebut.
Jika ingin kembali ke commit sebelumnya, ada dua cara yaitu dengan soft atau hard menggunakan hash dari commit tersebut. Jika ingin kembali tanpa mengamankan code bisa dengan hard, tapi konsekuensinya code pada commit diatasnya akan terhapus. Namun, jika menggunakan soft akan kembali ke staged. 
Contoh untuk melakukan reword yaitu menggunakan perintah :
git rebash -i HEAD~1
Contoh untuk melakukan reset pada suatu commit atau misal commit sebelumnya :
git reset --hard [hash]

