# Comandos_Bitacora

| Comando | Descripción | Ejemplo |
|---------|-------------|---------|
| `ls` | Lista los archivos y directorios en el directorio actual | `ls` |
| `cd` | Cambia el directorio actual | `cd directorio/` |
| `pwd` | Muestra la ruta del directorio actual | `pwd` |
| `mkdir` | Crea un nuevo directorio | `mkdir nuevo_directorio` |
| `cp` | Copia archivos o directorios | `cp archivo.txt destino/` |
| `mv` | Mueve o cambia el nombre de archivos/directorios | `mv archivo.txt nuevo_nombre.txt` |
| `rm` | Elimina archivos o directorios | `rm archivo.txt` |
| `touch` | Crea un archivo vacío | `touch archivo.txt` |
| `nano` | Editor de texto en la terminal | `nano archivo.txt` |
| `cat` | Muestra el contenido de un archivo | `cat archivo.txt` |
| `grep` | Busca texto en archivos | `grep "palabra" archivo.txt` |
| `ps` | Muestra los procesos en ejecución | `ps` |
| `top` | Muestra el listado de los procesos más activos | `top` |
| `kill` | Termina un proceso | `kill PID` |
| `chmod` | Cambia los permisos de archivos/directorios | `chmod 755 archivo.txt` |
| `chown` | Cambia el propietario de archivos/directorios | `chown usuario:grupo archivo.txt` |
| `df` | Muestra el espacio en disco | `df -h` |
| `du` | Muestra el uso de espacio de un archivo o directorio | `du -sh directorio/` |
| `ifconfig` | Muestra información de red | `ifconfig` |
| `ping` | Envía paquetes de prueba a un host | `ping google.com` |
| `ssh` | Acceso seguro a máquinas remotas | `ssh usuario@host` |
| `tar` | Comprime y descomprime archivos | `tar -cvzf archivo.tar.gz directorio/` |
| `man` | Muestra el manual de un comando | `man ls` |
| `history` | Muestra el historial de comandos | `history` |
| `sudo` | Ejecuta comandos con privilegios de superusuario | `sudo comando` |
| `shutdown` | Apaga o reinicia el sistema | `sudo shutdown -h now` |
| `find` | Busca archivos y directorios | `find /ruta -name archivo.txt` |
| `locate` | Encuentra rápidamente archivos y directorios | `locate archivo.txt` |
| `free` | Muestra el uso de memoria | `free -h` |
| `gzip` | Comprime archivos | `gzip archivo.txt` |
| `gunzip` | Descomprime archivos comprimidos | `gunzip archivo.txt.gz` |
| `wget` | Descarga archivos desde la web | `wget https://ejemplo.com/archivo.txt` |
| `curl` | Transfiere datos con URL | `curl https://ejemplo.com` |
| `netstat` | Muestra estadísticas de red y conexiones de red | `netstat -tuln` |
| `ss` | Muestra las conexiones de red, sockets y estadísticas | `ss -tuln` |
| `iptables` | Configuración de firewall en Linux | `iptables -L` |
| `ufw` | Firewall simplificado para Linux | `ufw status` |
| `systemctl` | Control de servicios y unidades del sistema | `systemctl start servicio` |
| `nginx` | Servidor web Nginx | `nginx -t` |
| `apache2` | Servidor web Apache | `apache2ctl configtest` |
| `mysql` | Cliente de línea de comandos de MySQL | `mysql -u usuario -p` |
| `psql` | Cliente de línea de comandos de PostgreSQL | `psql -U usuario -d basedatos` |
| `ssh-keygen` | Genera pares de claves SSH | `ssh-keygen -t rsa` |
| `ssh-copy-id` | Copia la clave SSH a un servidor remoto | `ssh-copy-id usuario@host` |
| `traceroute` | Rastreo de la ruta de los paquetes a un host | `traceroute google.com` |
| `dig` | Consulta de registros DNS | `dig google.com` |
| `hostname` | Muestra o configura el nombre del host | `hostname` |
| `uptime` | Muestra el tiempo de actividad del sistema | `uptime` |
| `last` | Muestra los usuarios que han iniciado sesión | `last` |
| `service --status-all` | Muestra el estado de todos los servicios | `service --status-all` |
| `journalctl` | Muestra los registros del sistema y del servicio | `journalctl -xe` |
| `netcat` | Utilidad de lectura y escritura de red | `nc -lvp puerto` |
| `nmap -sS <IP>` | Escaneo de tipo SYN para descubrir puertos abiertos en un host | `nmap -sS 192.168.1.1` |
| `nmap -sU <IP>` | Escaneo de puertos UDP en un host | `nmap -sU 192.168.1.1` |
| `nmap -O <IP>` | Detecta el sistema operativo del host objetivo | `nmap -O 192.168.1.1` |
| `nmap -sA <IP>` | Escaneo de tipos de paquetes ACK | `nmap -sA 192.168.1.1` |
| `nmap --script <script> <IP>` | Ejecuta un script Nmap específico | `nmap --script http-enum 192.168.1.1` |
| `sshd` | Demonio de servidor SSH | `systemctl restart sshd` |
| `rsync` | Sincroniza y copia archivos y directorios | `rsync -av origen/ destino/` |
| `scp` | Copia archivos de forma segura entre hosts | `scp archivo.txt usuario@host:destino/` |
| `mysqldump` | Realiza copias de seguridad y restauración de bases de datos MySQL | `mysqldump -u usuario -p basedatos > respaldo.sql` |
| `pg_dump` | Realiza copias de seguridad y restauración de bases de datos PostgreSQL | `pg_dump -U usuario -f respaldo.sql basedatos` |
