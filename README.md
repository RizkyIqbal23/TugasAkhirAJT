Nama: Rizky Muhammad Iqbal

NIM: 195150307111003

Tugas Akhir Arsitektur Jaringan Terkini – A

1.	Tugas 1
 
Di tugas 1 ini, saya belajar untuk membuat sebuah 1 instance EC2 di AWS Console dengan spesifikasi Instance Type: t2.medium, AMI : Ubuntu Server 22.04 LTS 64 Bit. Kemudian di Network Setting centang allow SSH, allow HTTP, dan allow HTTPS, serta menambah custom TCP Port 8081 dan 8080. Pilih storage 30 GiB, gp3. Selanjutnya instal Mininet, Ryu dan Flowmanager.

 
2.	Tugas 2
 
Di tugas 2 ini, saya belajar untuk membuat program sederhana custom topology, dengan spesifikasi 6H3SW. Tiap switch akan terkoneksi dengan 2 host. Setelah switch dan host tersambung, kita menguji koneksinya.

3.	Tugas 3
 
Di tugas 3 ini, saya belajar membuat load balancer. Load balancing adalah proses pembagian beban traffic sebuah aplikasi atau server. Dengan load balancer, beban traffic tidak akan dibebankan kepada beberapa jalur koneksi. Hal ini mempercepat waktu respons server Anda dan mencegahnya dari overloading. Dengan begini, kinerja server Anda akan lebih maksimal tidak peduli berapa banyak traffic yang Anda dapatkan.

4.	Tugas 4
 
Masukkan kode $ ryu-manager --observe-links dijkstra_Ryu_controller.py di terminal 1

 
Masukkan kode $ sudo python3 topo-spf_lab.py di terminal 2

 
Tampilan di terminal 2 setelah mengetik h1 ping -c 4 h4 untuk mengecek konektivitas

 
Tampilan di terminal 1 setelah mengetik h1 ping -c 4 h4

 
Tampilan di terminal 2 setelah mengetik h5 ping -c 4 h6 untuk mengecek konektivitas lagi

 
Tampilan di terminal 1 setelah mengetik h5 ping -c 4 h6


