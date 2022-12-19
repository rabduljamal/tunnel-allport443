# Script ALL Tunnel 443

## OS Didukung & Spek Minimal Auto Script Installer
kita perlu menggunakan sistem operasi OS Linux sebagai berikut ini:

 - Debian 10 (Rekomendasi)
 - Ubuntu 18 LTS
 - Ubuntu 20
 - RAM Minimal 1GB (Max Akun 8-12)
 - CPU Minimal 1 (2 Lebih bagus/Lebih cepet installnya)

## Fitur – Fitur Auto Script Installer Xray
 - VMESS WS TLS 443
 - VMESS WS NON TLS 80
 - VMESS GRPC 443
 - VLESS WS TLS 443
 - VLESS GRPC 443
 - TROJAN/TROJAN GO WS TLS 443
 - TROJAN/TROJAN GO GRPC 443
 - SHADOWSOCKS WS 443
 - SHADOWSOCKS GRPC 443

## kemudian masukan kode perintah di bawah ini

```bash
apt update && apt upgrade && apt install wget && apt install curl && apt install screen
```
## kemudian masukan kode untuk install xray

```bash
wget https://raw.githubusercontent.com/rabduljamal/tunnel-allport443/sae/setup.sh && chmod +x setup.sh && ./setup.sh
```
tunggu proses beberapa menit hingga proses installer berhasil

