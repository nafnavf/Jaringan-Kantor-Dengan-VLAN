# 💸Switch Cisco dengan VLAN per Divisi, Inter-VLAN Routing (Router-On-A-Stick atau Switch Layer 3), dan DHCP Server Di Router💸

## 🌶️Ringkasan
Proyek ini bertujuan untuk merancang dan membangun simulasi jaringan komputer pada lingkungan perkantoran menggunakan perangkat Cisco. Jaringan dibagi berdasarkan divisi atau departemen perusahaan dengan menerapkan teknologi VLAN (Virtual Local Area Network).

Setiap divisi memiliki jaringan tersendiri untuk meningkatkan keamanan, efisiensi, dan pengelolaan lalu lintas data. Agar setiap divisi tetap dapat berkomunikasi, diterapkan konfigurasi Inter-VLAN Routing menggunakan metode Router-on-a-Stick atau Switch Layer 3.

Selain itu, router difungsikan sebagai DHCP Server untuk memberikan alamat IP secara otomatis kepada komputer klien.

## 🍳Topologi
<img width="846" height="403" alt="image" src="https://github.com/user-attachments/assets/b1c89853-0d65-466d-a8b9-5fbbcc1a9e0c" />

## 🥠Media dan Konfigurasi Yang Akan Digunakan

* Cisco Packet Tracer
* Inter-VLAN untuk setiap jaringan Vlan di dalam switch
* Konfigurasi DHCP di router

## 🍕Cara Menguji

1. Buka PC manapun dan verifikasi:
   + IP ditetapkan melalui DHCP
   + Ping dari PC berhasil
2. Lalu di router, verifikasi:
   + Show IP DHCP Binding
   + Show IP Interface Brief

## 🥖Catatan Konfigurasi
| Perangkat | Fitur Utama |
|--------|--------------|
| Switch | Vlan 10, Vlan 20 dan Vlan 30 |
| Router | Router-On-A-Stick dan Server DHCP |
| IP PC | 192.168.10.0/29 (Vlan 10), 192.168.20.0/29 (Vlan 20) dan 192.168.30.0/29 (Vlan 30) |

#

🍜Projek ini dibuat dan diuji oleh Nafisa Maulida Hasan dengan menggunakan Cisco Packet Tracer<3

#

<img width="327" height="320" alt="image" src="https://github.com/user-attachments/assets/1c5558f4-83cd-41f3-87a5-9737d3d30180" />
