# Pull image nginx
docker pull nginx:alpine

# Jalankan container dengan nama dan port mapping
docker run -d --name web-praktikum -p 8080:80 nginx:alpine

# Lihat container yang berjalan
docker ps

# Lihat semua container (termasuk yang stop)
docker ps -a

# Lihat logs container
docker logs web-praktikum

# Masuk ke dalam container
docker exec -it web-praktikum sh

# Di dalam container, eksplor
ls -la /usr/share/nginx/html
cat /etc/nginx/nginx.conf
exit

# Stop dan hapus container
docker stop web-praktikum
docker rm web-praktikum