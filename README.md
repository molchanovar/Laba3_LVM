# Laba3_LVM
<h4>Manipulations with LVM </h4>


Файл <B>Commands</B> - описание команд для манипуляций с LVM;    
Файл <B>Loggin</B> - логи всех действий с ОС;        
<B>VagrantFile</B> - исходный стенд для работы с LVM; 

Работа с LVM 
на имеющемся образе
<B>/dev/mapper/VolGroup00-LogVol00 38G 738M 37G 2% /</B>


<h4>Сделано следующее:</h4>

<p>уменьшен том под / до 8G</p>
<p>выделен том под /home</p>
<p>выделен том под /var</p>
<p>/var - сделан в mirror</p>
<p>/home - сделан том для снэпшотов</p>
<p>прописано монтирование в fstab</p>

- сгенерированы файлы в /home/
- снят снэпшот
- удалена часть файлов
- выполнено восстановление со снэпшота
- залоггирована работа утилитой script

