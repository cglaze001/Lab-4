
!/bin/bash
for i in `cat /var/tmp/userlist.txt`; do
echo $i
echo $i 12345 | sudo password -s $i
echo; echo "user password changed!"
done
##echo -e "password\password" | sudo chpasswd $i
##usermod -L $i
##chage -d 0 $i
##usermod -U $i
##done


------------------------------------------------------------------
#8
text file called /var/tmp/userlist

Bobby
Kyle
Sam
Tania

#!/bin/bash
for i in `cat /var/tmp/userlist`; do
echo -e "hunter:htc" | sudo chpasswd $i
done

------------------------------------------------------------------
#6

#!/bin/bash
while [ true ] ;do
used=`free -m |awk '{print $5}'`

if [ $used -lt 1000 ] && [ $used -gt 800 ]; then
echo "Free memory is below 1000MB. Possible memory leak!!!" | /bin/mail -s "HIGH MEMORY ALERT!!!" user@mydomain.com


fi

done       --------------------
