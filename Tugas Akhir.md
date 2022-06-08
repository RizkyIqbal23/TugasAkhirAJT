Nama: Rizky Muhammad Iqbal

NIM: 195150307111003

Tugas Akhir Arsitektur Jaringan Terkini – A

1.	Tugas 1

 ![image](https://user-images.githubusercontent.com/100340362/172605155-3eb849a6-41cd-4c8d-96f0-771b10385112.png)

Di tugas 1 ini, saya belajar untuk membuat sebuah 1 instance EC2 di AWS Console dengan spesifikasi nama Instance: Tugas Akhir, Instance Type: t2.medium, AMI : Ubuntu Server 22.04 LTS 64 Bit. Kemudian di Network Setting centang allow SSH, allow HTTP, dan allow HTTPS, serta menambah custom TCP Port 8081 dan 8080. Pilih storage 30 GiB, gp3. Selanjutnya instal Mininet, Ryu dan Flowmanager.
 
2.	Tugas 2

 ![image](https://user-images.githubusercontent.com/100340362/172605301-72a1ac45-a5b9-4d1c-8e4e-c14f464d7144.png)

Di tugas 2 ini, saya belajar untuk membuat program sederhana custom topology, dengan spesifikasi 6H3SW. Tiap switch akan terkoneksi dengan 2 host. Setelah switch dan host tersambung, kita menguji koneksinya.

3.	Tugas 3

 ![image](https://user-images.githubusercontent.com/100340362/172605387-4d02a481-9b21-4f79-ae27-88d530d169df.png)

Di tugas 3 ini, saya belajar membuat load balancer. Load balancing adalah proses pembagian beban traffic sebuah aplikasi atau server. Dengan load balancer, beban traffic tidak akan dibebankan kepada beberapa jalur koneksi. Hal ini mempercepat waktu respons server Anda dan mencegahnya dari overloading. Dengan begini, kinerja server Anda akan lebih maksimal tidak peduli berapa banyak traffic yang Anda dapatkan.

4.	Tugas 4

 ![image](https://user-images.githubusercontent.com/100340362/172605480-b2724d83-d8b8-49d7-b816-f9390e182646.png)

Masukkan kode $ ryu-manager --observe-links dijkstra_Ryu_controller.py di terminal 1

 ![image](https://user-images.githubusercontent.com/100340362/172605570-b4c191aa-1f78-40bf-af83-bb5b0a6c12de.png )

Masukkan kode $ sudo python3 topo-spf_lab.py di terminal 2

 ![image](https://user-images.githubusercontent.com/100340362/172605617-982c8aec-0d30-4732-a3b4-620b12cfb2e9.png)

Tampilan di terminal 2 setelah mengetik h1 ping -c 4 h4 untuk mengecek konektivitas

 ![image](https://user-images.githubusercontent.com/100340362/172605678-a126f970-78f9-4f18-89e3-ee4820f8098e.png)

Tampilan di terminal 1 setelah mengetik h1 ping -c 4 h4

 ![image](https://user-images.githubusercontent.com/100340362/172605732-72f11c2e-7df2-4637-8413-1f8fb531edaa.png)

Tampilan di terminal 2 setelah mengetik h5 ping -c 4 h6 untuk mengecek konektivitas lagi

 ![image](https://user-images.githubusercontent.com/100340362/172605757-46b0b3a0-ee07-4733-9125-0237f9c8376c.png)

Tampilan di terminal 1 setelah mengetik h5 ping -c 4 h6


