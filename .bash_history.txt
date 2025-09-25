shutdown 0
ps aux
top
htop
ps -l
ps -la
ps -ls
ps -lax
pstree
ping google.com &
htop
ping
shutdown 0
ping google.com &
ps -aux | awk '{print $1 $2 $7 $11 }'
ps -aux | grep ping | awk '{print $1 $2 $7 $11 }'
ps -aux | grep ping | awk '{print $1 " : " $2 " : " $7 " : " $11 }'
mkfifo
mkfifo coola
ls
cat coola
echo "klk mi bro" > coola
shutdown 0
top
top | grep ping
ps -aux | grep ping
jobs
kill -9 1251
ps -aux | grep ping
ls
cd coola
ls
cd ssii
ls
cd ..
ls
cd ..
ls
cd HOME
cd $home
ls
ls -aux
cd C
shutdown 0
systemctl status ssh
sudo systemctl start ssh
sudo systemctl disable ssh
sudo systemctl enable ssh
ls -la
mkdir prueba
echo "Hola Linux" > prueba/notas.txt
cp prueba/notas.txt prueba/notas_copia.txt
mv prueba/notas_copia.txt prueba/notas_renombrado.txt
rm prueba/notas_renombrado.txt
ls > listado.txt
echo "Fin del listado" >> listado.txt
cat listado.txt
let a=3/0 2>/dev/null
ps aux | grep bash
tail -n 5 listado.txt
ping google.com
ping -c 4 google.com
ip a
ss -tuln
nslookup google.com
dig google.com
ssh joel@127.0.0.1
scp listado.txt joel@127.0.0.1:/prueba/listado.txt
sudo adduser alumno1
sudo passwd alumno1
chmod 755 listado.txt
sudo chown alumno1 listado.txt
sudo deluser alumno1
