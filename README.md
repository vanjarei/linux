## After Debian installation 

## install sudo 
	apt install sudo

## add user in sudo group 
	sudo usermod -aG sudo iamvanjare

## Set Time and Date 
	sudo timedatectl set-timezone Asia/Kolkata

## Strat Fail then Go Advance and rescumode and type
	sudo update-grub

## Make file Executable 
	sudo chmod +x install.sh

## LS Show all file with details
	 ls -altF

## See Current user
	whoami

## Change Password 
	passwd

## Find file 
	find / -name instal*

# By size  (.) Represent current directory
	find . -size -1M    
	find . -size +1M
	find /home -size -1M
	find /home -size +1M

# By Modified Time here 4 means 4 days
	find / -mtime 4
