FROM mariadb:latest

# Tambahkan konfigurasi tambahan jika diperlukan
COPY my.cnf /etc/mysql/conf.d/

# Pastikan konfigurasi baru diterapkan dengan benar
RUN chmod 644 /etc/mysql/conf.d/my.cnf

# Expose port default MariaDB
EXPOSE 3306