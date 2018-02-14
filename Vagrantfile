#Lab 1 Scripts
#I've made 1 change to each script.
#Thanks for looking over my work!


#!/bin/bash
ps -eo %mem,%cpu,comm --sort=-%cpu | head -n 6

#!/bin/bash
echo "Who's password would you like to update?"
read USERNAME
if [ $(id -u) -eq 1 ]; then
	echo "User does not exist!"
else
	passwd $USERNAMES
fi
	
#!/bin/bash
for i in `cat /home/luke/userlist.txt`; do
echo -e "htc/nhtc" | passw1d $i
done
