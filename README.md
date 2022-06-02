# Tugas-6-SISTEM-BASIS-DATA


NAMA      : MUHAMMAD FERDI HERDIANSYAH

NIM       : 312010038

KELAS     : TI.20 D1

MATA KUL  : SISTEM BASIS DATA

DOSEN     :  Muhammad Najamuddin Dwi Miharja, S.Kom, M.kom, 

# 1. MASUK  KE DATABASE NAMA_NIM 

![1](https://user-images.githubusercontent.com/101733752/171647460-227495a4-1612-4a4f-9f4a-0fedde448187.PNG)

# 2. LAKUKAN PROSES BACKUP DAN RECOVERY DENGAN SQL DARI DATABASE TUGAS SEBELUMNYA !

 - Melakukan proses penguncian/lock table.

![2](https://user-images.githubusercontent.com/101733752/171649382-587559de-2e59-4be3-a435-596de058a175.PNG)

- Melakukan proses backup table dengan perintah : ``` SELECT * INTO OUTFILE ```

![3](https://user-images.githubusercontent.com/101733752/171650905-4ab0189c-449c-4246-ba0e-d5cacda0b8fc.PNG)

- Jika proses backup berhasil maka akan muncul file backup pada direktori C:\xampp\mysql\data\nama_database

![4](https://user-images.githubusercontent.com/101733752/171651965-2986dd0c-d86a-4813-ace1-84693ed45de7.PNG)

- Data yang telah di backup dapat dikembalikan kapan saja bila diperlukan. Sintaks SQL yang digunakan adalah ```LOAD DATA INFILE```. Perintah yang dijalankan adalah ```LOAD DATA INFILE 'Nama_backup_file' INTO TABLE nama_table ;```

![5](https://user-images.githubusercontent.com/101733752/171653017-3781cbaa-c4ee-4821-b88d-45d28d256a7e.PNG)

# 3. LAKUKAN PROSES BACKUP DAN RECOVERY DENGAN SQLDUMP DARI DATABASE TUGAS SEBELUMNYA !

- Jalankan shell atau command-prompt dan ketikan perintah berikut untuk memulai dump database 

![6](https://user-images.githubusercontent.com/101733752/171653439-0c67e8f4-62d5-4d6c-ab93-b0fb6d5aa8ff.PNG)

- Data yang telah di backup dapat di restore kembali ke dalam database dengan perintah 
  ```MySQLdump -u root -p (nama_database) <C:\xampp\mysql\bin\file_backup.sql```
  
  ![7](https://user-images.githubusercontent.com/101733752/171654022-d83175f5-a01e-431a-8c81-b73883b5af30.PNG)


# 4. Tuliskan script cron job untuk melakukan backup otomatis setiap hari minggu jam 12 malam !

![9](https://user-images.githubusercontent.com/101733752/171654358-5ab09015-6c7e-4c18-9ed7-d08cfbe2bb8a.PNG)




