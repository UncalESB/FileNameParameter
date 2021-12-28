# FileNameParameter
ini digunakan untuk menyaring nama file dan juga menyaring isi dari berkas yang di ambil oleh *File Adapter*\
parameter ini dimasukan kedalam isian *File Name* pada *UIC*\
contoh penggunaan : 
#### *.txt=>B1M0A8P=Mohamad Jaelani
*.txt adalah untuk menyaring jenis berkas berdasarkan akhiran .txt\
=> adalah cari didalam file dengan akhiran .txt\
B1 adalah cari pada Baris ke 1\
M0 adalah pada Mulai hurup ke 0\
A8 adalah Akhir dari hurup ke 8\
P=Mohamad Jaelani adalah kata kunci yang di cari adalah 'Mohamad jaelani'

#### *.txt=>P=Mohamad Jaelani
*.txt adalah untuk menyaring jenis berkas berdasarkan akhiran .txt\
=> adalah cari didalam file dengan akhiran .txt\
Baris, Mulai, Akhir dengan nilai baku yaitu : 0, 0, 0\
P=Mohamad Jaelani adalah kata kunci yang di cari adalah 'Mohamad jaelani'

#### *.txt=>BsP=Mohamad Jaelani
*.txt adalah untuk menyaring jenis berkas berdasarkan akhiran .txt\
=> adalah cari didalam file dengan akhiran .txt\
Bs adalah semua isi file\
P=Mohamad Jaelani adalah kata kunci yang di cari adalah 'Mohamad jaelani'
