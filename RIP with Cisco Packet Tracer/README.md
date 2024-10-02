# Network RIP Simulation with a Web Server

## Indonesia:
Saya membuat simulasi jaringan ini untuk proyek di perkuliahan menggunakan Cisco Packet Tracer. Pada simulasi Packet Tracer ini saya menggunakan RIP untuk merutekan beberapa jaringan. Dengan ini saya berharap dapat membantu rekan-rekan saya dalam mempelajari konsep RIP dengan menggunakan simulasi yang telah saya buat.

## English:
I created this network simulation for a college project using Cisco Packet Tracer. In this Packet Tracer simulation, I used RIP to route several networks. With this, I hope to help my peers learn the RIP concept using the simulation I have made.

# The network I designed
![image](https://github.com/user-attachments/assets/b6ff728e-23af-4f68-95a1-8a29cabf90cb)

# Problem Statement/Pernyataan Masalah

## Indonesia:
Bayangkan Anda adalah seorang teknisi jaringan yang ditugaskan untuk mengonfigurasi jaringan di sebuah universitas. Universitas ini memiliki tiga ruangan yang masing-masing terhubung melalui Local Area Network (LAN), satu ruangan server yang berisi layanan web, dan satu area dengan access point. Tugas Anda adalah untuk merancang dan mengimplementasikan sebuah infrastruktur jaringan dimana setiap ruangan LAN memiliki empat PC yang terhubung ke switch, dan switch tersebut terhubung ke router untuk memastikan konektivitas antar ruangan serta dengan jaringan eksternal. Ruangan-ruangan tersebut diberi label sebagai berikut:

Ruangan Cyan dengan alamat IP 192.168.1.0/24
Ruangan Green dengan alamat IP 192.169.2.0/24
Ruangan Yellow dengan alamat IP 192.168.3.0/24
Ruangan server diberi label Pink dengan alamat IP 192.168.4.0/24.

Selain itu, ada satu access point yang harus dapat tersambung ke jaringan ini dan memiliki perangkat yang dapat mengakses server.

Anda harus merutekan masing-masing ruangan LAN, server, dan access point agar bisa saling terkoneksi secara efisien dan aman menggunakan metode Routing Information Protocol (RIP). Di akhir, uji konektivitas menggunakan Simple PDU.

## English:
Imagine you are a network technician tasked with configuring a network for a university setting that includes three rooms connected via Local Area Networks (LAN), one server room containing web services, and one section utilizing an access point. Your assignment is to design and implement a network infrastructure where each LAN room has four PCs connected to switches, which in turn are connected to routers ensuring inter-room connectivity as well as external network connectivity. The rooms are labeled as follows:

Cyan Room with an IP address of 192.168.1.0/24
Green Room with an IP address of 192.169.2.0/24
Yellow Room with an IP address of 192.168.3.0/24
The server room is labeled Pink with an IP address of 192.168.4.0/24.

Additionally, there is one access point that must also be connected to this network and have a device that can access the server.

You need to route each LAN room, the server room, and the access point to ensure they can all communicate with each other efficiently and securely using the Routing Information Protocol (RIP). Finally, test the connectivity using Simple PDU.

# Constraints/Ketentuan

## Indonesia:
1. Gunakan kabel straight-through untuk menghubungkan PC ke switch atau switch ke router. Gunakan kabel cross-over untuk menghubungkan router ke router atau server ke router sesuai kebutuhan.
2. Kamu bisa menggunakan Server-PT, PC-PT, Router 1841, Router-PT-Empty (agar bisa menambahkan slot fast ethernet sesuai kebutuhan di bagian physical), Switch 2950-24, switch-pt, dan accesspoint-PT.
3. Kamu harus memberikan IP ke semua PC menggunakan IP statis.
4. Kamu harus menggunakan CLI untuk mengkonfigurasi RIP di router, atau jika sudah sangat kesulitan, kamu diberikan kemudahan untuk menggunakan GUI.
5. Kamu bisa memodifikasi web yang ada di server. Atau kamu bisa menggunakan kode ku yang ada di RIP with a Web Server.pkt di bagian konfigurasi server.

## English:
1. Use straight-through cables to connect PCs to switches or switches to routers. Use cross-over cables to connect routers to routers or servers to routers as needed.
2. You can use Server-PT, PC-PT, Router 1841, Router-PT-Empty (to add fast ethernet slots as needed in the physical section), Switch 2950-24, switch-pt, and accesspoint-PT.
3. You must assign static IP addresses to all PCs.
4. You must use CLI to configure RIP on the routers, but if you find it too difficult, you are allowed to use the GUI.
5. You can modify the web on the server. Alternatively, you can use my code from RIP with a Web Server.pkt in the server configuration section.

# How to Run/Cara Menjalankannya

## Indonesia:
Instal [Cisco Packet Tracer](https://www.netacad.com/cisco-packet-tracer) dan kemudian Anda dapat membuka [RIP dengan Web Server.pkt](https://github.com/xurobaebae/cisco/blob/main/RIP%20with%20Cisco%20Packet%20Tracer/main%20file/RIP%20with%20a%20Web%20Server.pkt).

## English:
Install [Cisco Packet Tracer](https://www.netacad.com/cisco-packet-tracer) and then you can open the [RIP dengan Web Server.pkt](https://github.com/xurobaebae/cisco/blob/main/RIP%20with%20Cisco%20Packet%20Tracer/main%20file/RIP%20with%20a%20Web%20Server.pkt).
