# FileNameParameter
ini digunakan untuk menyaring nama file dan juga menyaring isi dari berkas yang di ambil oleh *File Adapter*\
parameter ini dimasukan kedalam isian *File Name* pada *UIC*\
#### [*FILE_EXTENSION*]=>B[*n*]M[*n*]A[*n*]P=[*ARGUMENT*]
e.g.
#### *.txt=>B1M0A8P=Mohamad Jaelani
*.txt adalah untuk menyaring jenis berkas berdasarkan akhiran .txt\
=> adalah cari didalam file\
B1 adalah cari pada Baris ke 1\
M0 adalah pada Mulai hurup ke 0\
A8 adalah Akhir dari hurup ke 8\
P=Mohamad Jaelani adalah kata kunci yang di cari

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
#### {DATE(yyyyMMdd)}
pencarian file dengan menggunakan tanggal\
contoh :
#### {DATE(yyyyMMdd)} melakukan pencarian file berdasarkan tanggal sekarang dengan format yyyyMMdd misal : 20211228
misal mau mencari file dengan nama : *20211228070148J7* maka paramternya adalah {DATE(yyyyMMdd)}*
