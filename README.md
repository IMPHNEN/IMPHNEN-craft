# CONFIG
1. Ke frp, lalu edit frp.ini
2. Edit bagian server_addr, sesuaikan sama alamat server frp nya

# RUN
1. buat dulu folder worlds di ./server

```cd server```

```mkdir worlds```

2. Jalanin 

```sudo docker compose up -d```

# DOWN
Jalanin 

```sudo docker compose down --rmi "all"```
