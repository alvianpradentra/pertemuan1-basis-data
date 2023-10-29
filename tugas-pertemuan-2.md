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
     ![image](https://github.com/alvianpradentra/pertemuan1-basis-data/assets/148189829/d0b70cf8-6506-47c5-b5e0-e6c977ce143d)

   - Membuat tabel dengan syntax: CREATE TABLE namatabel (column1 datatype(length) columnt_constrait, columnN datatype(length) column_constrait);
     ![image](https://github.com/alvianpradentra/pertemuan1-basis-data/assets/148189829/d54e362a-20a5-441d-a197-d089c8bed725)

   - Menampilkan table kosong dengan syntax: SELECT * FROM mahasiswa;
     ![image](https://github.com/alvianpradentra/pertemuan1-basis-data/assets/148189829/bcfd7a51-e718-474d-93b7-1a9f440d757b)
 
6. Check tabel pada database dengan syntax berikut: \dt
   ![image](https://github.com/alvianpradentra/pertemuan1-basis-data/assets/148189829/09c68e99-4754-46bc-a013-65038624a1e2)

7. Memasukkan data pada database yang telah dibuat dengan syntax: INSERT INTO mahasiswa (column1, columnN) VALUES (value1, valueN);
   ![image](https://github.com/alvianpradentra/pertemuan1-basis-data/assets/148189829/f3e9bf05-e752-4e66-ab11-8c0aa0def4ce)
   ![image](https://github.com/alvianpradentra/pertemuan1-basis-data/assets/148189829/c6429db7-6306-412c-82db-8bc7311c586c)

8. Menampilan data pada database mahasiswa dengan syntax: SELECT * FROM mahasiswa;
   - Tampilan pada SQL Shell (psql)
     ![image](https://github.com/alvianpradentra/pertemuan1-basis-data/assets/148189829/8181d740-d0cb-488a-91ed-994a7db24e1b)

   - Tampilan pada pgAdmin4
     ![image](https://github.com/alvianpradentra/pertemuan1-basis-data/assets/148189829/98b2fd37-436b-4532-96bd-89a392d2519c)
