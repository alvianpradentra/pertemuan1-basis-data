<h2>Membuat Tabel mahasiswa pada Database polban</h2>

1. Buka SQL Shell (psql), lalu login.
   ![image](https://github.com/alvianpradentra/pertemuan1-basis-data/assets/148189829/633f59f3-0b77-49e8-ab80-0b9dd4e9cb32)
   ![image](https://github.com/alvianpradentra/pertemuan1-basis-data/assets/148189829/b3280014-3400-42cd-a130-efec4429461e)

3. Membuat database dengan nama polban dengan syntax: CREATE DATABASE polban;
   ![image](https://github.com/alvianpradentra/pertemuan1-basis-data/assets/148189829/9e3674e5-1799-4727-add4-3cab5bc0506b)

4. Check database dengan syntax: \l  
   ![image](https://github.com/alvianpradentra/pertemuan1-basis-data/assets/148189829/e95a3c68-a1ec-41cd-af1a-73dc77507047)

5. Membuat tabel dengan nama mahasiswa didalam database polban
   - Masuk kedalam database polban dengan syntax berikut: \c polban
     ![image](https://github.com/alvianpradentra/pertemuan1-basis-data/assets/148189829/1c24f8f4-065a-4703-be82-73baa28ac827)

   - Membuat datatype gender berupa (L/P) dengan syntax: CREATE TYPE gender AS ENUM ('L', 'P');
     
   - Membuat tabel dengan syntax: CREATE TABLE namatabel (column1 datatype(length) columnt_constrait, columnN datatype(length) column_constrait);
     
6. Check tabel pada database dengan syntax berikut: \dt
   
7. Memasukkan data pada database yang telah dibuat dengan syntax: INSERT INTO mahasiswa (column1, columnN) VALUES (value1, valueN);
   
8. Menampilan data pada database mahasiswa dengan syntax: SELECT * FROM mahasiswa;
   
