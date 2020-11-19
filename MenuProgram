import os 
import getpass 

os.system("tput setaf 3")
print("\t\t\t\t\t\t  Welcome to the WORLD OF AUTOMATION\n")
os.system("tput setaf 4")
password = getpass.getpass("Enter your Key: ")

if password != "ss":
	os.system("tput setaf 9")
	print("Invalid Password!")
	os.system("tput setaf 7")
	exit()
name = input("May I know your name please :)  ")
os.system("tput setaf 6")
print("Hello {}! Happy to see you :) ".format(name))
os.system("tput setaf 7")

typeoflogin = input("Do you want login locally(l) or remote(r)?(l/r): ")
print("you chose {}".format(typeoflogin))

while True:
	os.system("clear")
	print("""This is a MENU Program\n
		This consists of all the basic functionalities of the Current Trending Technologies like \n
	----- LINUX and NETWORKING IN LINUX \n
	----- ANSIBLE \n
	----- DOCKER \n
	----- LVM PARTITIONS \n
	----- BIG DATA - HADOOP \n
	----- AWS CLI \n

	How to use : Just press the respective number of which you want to perform and get your Things done! :) 
		""")
	print("""
		\n
	LINUX AND NETWORKING IN LINUX\n
	Press  1 : To run date
	Press  2 : To run cal
	Press  3 : To Check the current user
	Press  4 : To Add user and set Password
	Press  5 : To know about the memory available
	Press  6 : To Know about CPU
	Press  7 : To Check any sprogram or service whether its installed or not
	Press  8 : To know Java version
	Press  9 : To Python Version
	Press 10 : To know about IPaddress
	Press 11 : To know about current running Port numbers 
	Press 12 : To install tcpdump
	Press 13 : To know who is pinging our System(Make sure tcpdump is already install if not install by pressing )
	Press 14 : To know process ID of any Program
	Press 15 : To kill process
	Press 16 : To know about available Hard Disk
	Press 17 : To List Hard Disk and their Partitions
	Press 18 : To install httpd service
	Press 19 : To Start httpd service
	Press 20 : To install xclip
	Press 21 : To read data in clipboard(Make sure Xclip is already install if not install by pressing )
	Press 22 : To know about repolist
	Press 23 : To use Binary Calculator
	Press 24 : To know IP address of a particular Domain 
	Press 25 : To check the applications running in backgroud 
	Press 26 : To run firefox \n
	ANSIBLE\n
	Press 31 : To Install Ansible
	Press 32 : To know about ansible version
	Press 33 : To list all the hosts 
	Press 34 : To ping the nodes
	Press 35 : To Install a httpd service
	Press 36 : To Start httpd service
	Press 37 : To Configure inventory \n
	DOCKER\n
	Press 41 : To Install docker
        Press 42 : To Start Docker
	Press 43 : To permenantly Start Docker
	Press 44 : To Stop Docker
	Press 45 : To know current status of the Docker
        Press 46 : To Search image
        Press 47 : To pull docker image
        Press 48 : To check images available
        Press 49 : To run a container
        Press 50 : To check container status
        Press 51 : To Start a stopped container
        Press 52 : To check image logs
	Press 53 : To delete docker repo(Warning: Dangerous operation)\n
	LVM PARTITIONS \n 
    	Press 61 : To Create Physical Volume
    	Press 62 : To Display Physical Volume       
  	Press 63 : To Create Volume Group
  	Press 64 : To Display Volume Group
    	Press 65 : To Create Logical Volume
    	Press 66 : To Display Logical Volume
    	Press 67 : To Format the LV\n
	HADOOP \n
	Press 71 : Complete Namenode configuration and starting Namenode
	Press 72 : Complete Datanode Configuration and starting Datanode
	Press 73 : Complete Clientnode configuration
	Press 74 : To start Namenode
	Press 75 : To start Datanode
	Press 76 : To see complete report of the Cluster
	Press 77 : To upload file from client node
	Press 78 : To upload file from client node with specific Blocksize
	Press 79 : To upload an empty file from client node
	Press 80 : To upload an empty file from client node with specific block size
	Press 81 : To remove a file which is uploaded
	Press 82 : To turn safemode ON (Namenode, Readonly mode)
	Press 83 : To turn safemode OFF (Namenode)
	Press 84 : To list the files uploaded in the cluster
	Press 85 : To know in which node is the current working system\n
	AWS CLI \n
	Press 91  : To Install AWS CLI
	Press 92  : To Configure AWS CLI
	Press 93  : To Create Key Pair
	Press 94  : To Create Security Group
	Press 95  : To list EC2 instances
	Press 96  : To Create aws EC2 instance
	Press 97  : To Create EBS Volume
	Press 98  : To attach EBS Volume to EC2 Instances
	Press 99  : To Delete Key Pair
	Press 100 : To Delete Security Group

	Press 0 : To Exit
	""")
	
	choice = input("Enter your Choice Learner :) -  ")
	print("You chose {}".format(choice))
	if typeoflogin == "l":
		if int(choice) == 1:
			os.system("date")
		elif int(choice) == 2:
			os.system("cal")
		elif int(choice) == 3:
			os.system("whoami")
		elif int(choice) == 4:
			Username = input("Enter user name of your choice: ")
			Password = input("Enter Password of your choice: ")
			os.system("useradd {}".format(Username))
			os.system("passwd {}".format(Password))
			print("Successfully added user!")
		elif int(choice) == 5:
			os.system("free -m")
		elif int(choice) == 6:
			os.system("lscpu")
		elif int(choice) == 7:
			program = input("Enter the Program/Service name you want to know: ")
			os.system("rpm -q {}".program)
		elif int(choice) == 8:
			os.system("java -version")
		elif int(choice) == 9:
			os.system("python3 -V")
		elif int(choice) == 10:
			os.system("ifconfig")
		elif int(choice) == 11:
			os.system("netstat -tnlp")
		elif int(choice) == 12:
			os.system("yum install tcpdump")
		elif int(choice) == 13:
			os.system("tcpdump -i enp0s3 -n")
		elif int(choice) == 14 :
			process = input("Enter name of the Program to know its Process ID : ")
			os.system("pgrep {}".format(process))
		elif int(choice) == 15:
			processid = ("Enter the Process ID to terminate : ")
			os.system("kill {}".format(processid))
		elif int(choice) == 16:
			os.system("fdisk -l")
		elif int(choice) == 17:
			os.system("lsblk")
		elif int(choice) == 18:
			os.system("yum install httpd")
		elif int(choice) == 19:
			os.system("systemctl start httpd")
		elif int(choice) == 20:
			os.system("rpm -ivh xclip")
		elif int(choice) == 21:
			os.system("xclip -o")
		elif int(choice) == 22:
			os.system("yum repolist")
		elif int(choice) == 23:
			os.system("bc")
		elif int(choice) == 24:
			domaonaddress = input("Enter the domain address to know its IP address (This changes using load balancer)")
			os.system("nslookup {}".format(domainaddress))
		elif int(choice) == 25:
			os.system("jobs")
		elif int(choice) == 26:
			os.system("firefox")	

#ansible program

	
		elif int(choice) == 31:
			os.system("pip3 install ansible")
			print("Ansible installed Successfully!")
		elif int(choice) == 32:
			os.system("ansible --version")
		elif int(choice) == 33:
			os.system("ansible all --list-hosts")
		elif int(choice) == 34:
			os.system("ansible all -m ping")
		elif int(choice) == 35:
			os.system('ansible all -m package -a "name=httpd state=present" ')
		elif int(choice) == 36:
			os.system('ansible all -m service -a "name=httpd state=started" ')
		elif int(choice) == 37:
			ipaddress = input("Enter the IP address of the Target node: ")
			typeofuser = input("Enter the user: ")
			sshpass = input("Enter the sshpass or protocol: ")
			os.system("vim /etc/ansible/ansible.cfg")
			configfile = open("ansible.cfg","w")
			configfile.write('[defaults] \n {} ansible_user = {} ansible_ssh_pass = {}'.format(ipaddress, typeofuser, sshpass))
			configfile.close()

#docker Program


		elif int(choice) == 41:
        		os.system("yum install docker-ce --nobest")
		elif int(choice) == 42:
			os.system("systemctl start docker")
			print("Started Docker Successfully!")
		elif int(choice) == 43:
			os.system("systemctl enable docker")
			print("Docker is now Permanently enabled Successfully!")
		elif int(choice) == 44:
			os.system("systemctl stop docker")
			print("Stopped Docker Successfully!")
		elif int(choice) == 45:
			os.system("systemctl status docker")
		elif int(choice) == 46:
			image_name = input("Which image you want to search : ")
			os.system("docker search {}" .format(image_name))
		elif int(choice) == 47:
			image_name = input("Which image you want to pull : ")
			image_tag = input("Enter image tag : ")
			os.system("docker pull {}:{}" .format(image_name , image_tag))
		elif int(choice) == 48:
			os.system("docker images")
		elif int(choice) == 49:
			image_name = input("Write the image name with tag you want to run : ")
			cont_name = input("Enter name of container : ")
			os.system("docker run -dit --name {} {}" .format(cont_name , image_name))
		elif int(choice) == 50:
			os.system("docker ps -a")
		elif int(choice) == 51:
			cont_name = input("Enter the container name : ")
			os.system("docker start {}" .format(cont_name))
		elif int(choice) == 52:
			cont_name = input("Enter container name : ")
			os.system("docker logs {}" .format(cont_name))
		elif int(choice) == 53:
			os.system("rm docker-ce.repo")
			print("Removed Docker Successfully!")

#LVM Partitions
		elif int(choice)== 61:
			pv1=input("Enter the name of storage 1:")
			os.system("pvcreate {}".format(pv1))

		elif int(choice)== 62:
			pv=input("Enter the name of storage:")
			os.system("pvdisplay {}".format(pv))
			
		elif int(choice)== 63:
			vgn=input("Give name to the VG:")
			pvn1=input("Enter the name of storage 1:")
			os.system("vgcreate {} {}".format(vgn,pvn1))

		elif int(choice)== 64:
			vgn1=input("Enter the name of VG:")
			os.system("vgdisplay".format(vgn1))

		elif int(choice)== 65:
			size=input("Enter size for your LV:")
			lvn=input("Give name to your LV:")
			vgn2=input("Enter name of the VG:")
			os.system("lvcreate -l {} -n {} {}".format(size,lvn,vgn2))
				         
		elif int(choice)== 66:
			os.system("lvdisplay")

		elif int(choice)== 67:
			vgn4=input("Enter the name of VG:")
			lvn2=input("Enter the name of LV:")
			os.system("mkfs.ext4  /dev/{}/{}".format(vgn4,lvn2))
			print("Created LVM Partition Successfully!")

#Hadoop	

		elif int(choice) == 71:
			def namenode_configuration():
				os.system("/etc/hadoop/")
				myfile1 = open('hdfs-site.xml','r+')
				myfile1.write('<?xml version="1.0"?>\n')
				myfile1.write('<?xml-stylesheet type="text/xsl" href="configuration.xsl"?>\n\n')
				myfile1.write("<!-- Put site-specific property overrides in this file. -->\n\n")
				myfile1.write("<configuration>\n")
				myfile1.write("<property>\n")
				myfile1.write("<name>dfs.name.dir</name>\n")
				myfile1.write("<value>/namenode</value>\n")
				myfile1.write("</property>\n")
				myfile1.write("</configuration>\n")
				myfile1.close()

				os.system("ifconfig enp0s3 | grep -E 'inet.[0-9]' | grep -v '127.0.0.1' | awk '{ print $2}' > ips.txt")

				myfile = open("ips.txt")
				content = myfile.read()
				ips = content.split("\n")
				myfile.close()
				ipadd = ips[0]

				os.system("/etc/hadoop/")
				myfile2 = open("core-site.xml","w")
				myfile2.write('<?xml version="1.0"?>\n')
				myfile2.write('<?xml-stylesheet type="text/xsl" href="configuration.xsl"?>\n\n')
				myfile2.write("<!-- Put site-specific property overrides in this file. -->\n\n")
				myfile2.write("<configuration>\n")
				myfile2.write("<property>\n")
				myfile2.write("<name>fs.default.name</name>\n")
				myfile2.write("<value>hdfs://{ip_address}:9001</value>\n".format(ip_address = ipadd))
				myfile2.write("</property>\n")
				myfile2.write("</configuration>\n")
				myfile2.close()

				os.system("cd")
				os.system("hadoop namenode -format")

				os.system("hadoop-daemon.sh start namenode")
				os.system("jps")
			namenode_configuration()
			print("\nDone! The system has now been setup as Namenode ")

		elif int(choice) == 72:
			def datanode_configuration():

				os.system("/etc/hadoop/")
				myfile1 = open("hdfs-site.xml","w")
				myfile1.write('<?xml version="1.0"?>\n')
				myfile1.write('<?xml-stylesheet type="text/xsl" href="configuration.xsl"?>\n\n')
				myfile1.write("<!-- Put site-specific property overrides in this file. -->\n\n")
				myfile1.write("<configuration>\n")
				myfile1.write("<property>\n")
				myfile1.write("<name>dfs.data.dir</name>\n")
				myfile1.write("<value>/dn1</value>\n")
				myfile1.write("</property>\n")
				myfile1.write("</configuration>\n")
				myfile1.close()

				ipadd = input("IP Address of namenode: ")

				os.system("/etc/hadoop/")
				myfile2 = open("core-site.xml","w")
				myfile2.write('<?xml version="1.0"?>\n')
				myfile2.write('<?xml-stylesheet type="text/xsl" href="configuration.xsl"?>\n\n')
				myfile2.write("<!-- Put site-specific property overrides in this file. -->\n\n")
				myfile2.write("<configuration>\n")
				myfile2.write("<property>\n")
				myfile2.write("<name>fs.default.name</name>\n")
				myfile2.write("<value>hdfs://{}:9001</value>\n".format(ipadd))
				myfile2.write("</property>\n")
				myfile2.write("</configuration>\n")
				myfile2.close()

				os.system("hadoop-daemon.sh start datanode")
			datanode_configuration()
			print("\nDone! The system has now been setup as Datanode")

		elif int(choice) == 73:
			def clientnode_configuration():

				ipadd = input("IP Address of namenode: ")

				os.system("/etc/hadoop/")
				myfile2 = open("core-site.xml","w")
				myfile2.write('<?xml version="1.0"?>\n')
				myfile2.write('<?xml-stylesheet type="text/xsl" href="configuration.xsl"?>\n\n')
				myfile2.write("<!-- Put site-specific property overrides in this file. -->\n\n")
				myfile2.write("<configuration>\n")
				myfile2.write("<property>\n")
				myfile2.write("<name>fs.default.name</name>\n")
				myfile2.write("<value>hdfs://{}:9001</value>\n".format(ipadd))
				myfile2.write("</property>\n")
				myfile2.write("</configuration>\n")
				myfile2.close()

			clientnode_configuration()
			print("\nDone! The system has now been setup as Clientnode")

		elif int(choice) == 74:
			os.system("hadoop-daemon.sh start namenode")
			os.system("jps")
			print("Master Node(namenode) started Successfully!")
		elif int(choice) == 75:
			os.system("hadoop-daemon.sh start datanode")
			print("Slave Node(datanode) started Successfully!")
		elif int(choice) == 76:
			os.system("hadoop dfsadmin -report")
		elif int(choice) == 77:
			filename = input("Enter the file name(without any extensions) to be uploaded: ")
			os.system("hadoop fs -put {}.txt".format(filename))
			print("{} file uploaded Successfully to the cluster!".format(filename))
		elif int(choice) == 78:
			filename = input("Enter the file name(without any extensions) to be uploaded: ")
			blocksize = input("Enter the blocksize of the file to be stored of your choice: ")
			os.system("hadoop fs -Ddfs.block.size ={}M -put {}.txt".format(blocksize, filename))
			print("{} file uploaded with blocksize {} Successfully to the cluster!".format(filename, blocksize))
		elif int(choice) == 79:
			filename = input("Enter the file name(without any extensions) to be uploaded: ")
			os.system("hadoop fs -touchz {}.txt".format(filename))
			print("Empty file uploaded Successfully to the cluster!")
		elif int(choice) == 80:
			filename = input("Enter the file name(without any extensions) to be uploaded: ")
			blocksize = input("Enter the blocksize of the file to be stored of your choice: ")
			os.system("hadoop fs -Ddfs.block.size ={}M -touchz {}.txt".format(blocksize, filename))
			print("Empty file with block size {} uploaded Successfully to the cluster!".format(blocksize))
		elif int(choice) == 81:
			filenamerm = input("Enter the file name(without any extensions) to be removed: ")
			os.system("hadoop fs -rm/{}".format(filenamerm))
			print("{} file removed Successfully!".format(filenamerm))
		elif int(choice) == 82:
			os.system("hadoop dfsadmin -safemode get")
		elif int(choice) == 83:
			os.system("hadoop dfsadmin -safemode leave")
		elif int(choice) == 84:
			os.system("hadoop fs -ls/")
		elif int(choice) == 85:
			os.system("jps")

#AWS CLI

		elif int(choice) == 91:
			os.system("pip3 install awscli")
			print("\n\n Successfully Installed AWS CLI!")
		elif int(choice) == 92:
			os.system("aws configure")
			print("\n\n AWS Configuration completed Successfully!")
		elif int(choice) == 93:
			keypairname = input("Enter your keypair name: ")
			os.system("aws ec2 create-key-pair --key-name {}".format(keypairname))
			print("\n\nCreated Key Pair successfully!")
		elif int(choice) == 94:
			groupname = input("Enter your Security Group name: ")
			groupdescription = input("Enter your Security Group Description: ")
			os.system('aws ec2 create-security-group --group-name{} --description "{}"'.format(groupname, groupdescription))
			print("\n\n Created Security Group successfully!")
		elif int(choice) == 95:
			os.system("aws ec2 describe-instances")
		elif int(choice) == 96:
			imageid = input("Enter your AWS OS Image ID: ")
			instancetype = input("Enter Instance type: ")
			securitygroup = input("Enter Security Group ID: ")
			keyname = input("Enter Key name: ")
			os.system("aws ec2 run-instances --image-id {} --instance-type {} --security-group {} --key-name {}".format(imageid, instancetype, securitygroup, keyname))
			print("Successfully created an EC2 Instance(default storage space is allocated(i.e.,10GB))")
		elif int(choice) == 97:
			az = input("Enter the availability zone : ")
			size = input("Enter the size of EBS Volume to be created: ")
			os.system("aws ec2 create-volume --availability-zone {} --size {}".format(az, size))
			print("Successfully created Volume {} with size {}!".format(az, size))
		elif int(choice) == 98:
			instanceid = input("Enter your EC2 instance ID: ")
			volumeid = input("Enter Volume ID: ")
			os.system("aws ec2 attach-volume --instance-id {} --volume-id {} --device /dev/sdf".format(instanceid, volumeid))
			print("Successfully attached volume to the instance!")
		elif int(choice) == 99:
			keypairname = input("Enter your keypair name: ")
			os.system("aws ec2 delete-key-pair --key-name {}".format(keypairname))
			print("\n\nDeleted Key Pair successfully!")
		elif int(choice) == 100:
			groupname = input("Enter your Security Group name: ")
			os.system('aws ec2 delete-security-group --security-group {} '.format(groupname))
			print("\n\n Deleted Security Group successfully!")		



#Tech endss


		elif int(choice) == 0:
			print("See you soon! Stay safe! Bye! :)")
			exit()
		else:
			print("Sorry! Its an invalid choice!")


							#REMOTELOGIN MENU


	elif typeoflogin == "r":
		ip = input("Enter your remote IP address: ")
		print("The IP Address you entered : {}".format(ip))
		if int(choice) == 1:
			os.system("ssh {} date".format(ip))
		elif int(choice) == 2:
			os.system("ssh {} cal".format(ip))
		elif int(choice) == 3:
			os.system("ssh {} whoami".format(ip))
		elif int(choice) == 4:
			Username = input("Enter user name of your choice: ")
			Password = input("Enter Password of your choice: ")
			os.system("ssh {} useradd {}".format(ip,Username))
			os.system("ssh {} passwd {}".format(ip, Password))
			print("Successfully added user!")
		elif int(choice) == 5:
			os.system("ssh {} free -m".format(ip))
		elif int(choice) == 6:
			os.system("ssh {} lscpu".format(ip))
		elif int(choice) == 7:
			program = input("Enter the Program/Service name you want to know: ")
			os.system("ssh {} rpm -q {}".format(ip, program))
		elif int(choice) == 8:
			os.system("ssh {} java -version".format(ip))
		elif int(choice) == 9:
			os.system("ssh {} python3 -V".format(ip))
		elif int(choice) == 10:
			os.system("ssh {} ifconfig".format(ip))
		elif int(choice) == 11:
			os.system("ssh {} netstat -tnlp".format(ip))
		elif int(choice) == 12:
			os.system("ssh {} yum install tcpdump".format(ip))
		elif int(choice) == 13:
			os.system("ssh {} tcpdump -i enp0s3 -n".format(ip))
		elif int(choice) == 14:
			process = input("Enter name of the Program to know its Process ID : ")
			os.system("ssh {} pgrep {}".format(ip, process))
		elif int(choice) == 15:
			processid = ("Enter the Process ID to terminate : ")
			os.system("ssh {} kill {}".format(ip, processid))
		elif int(choice) == 16:
			os.system("ssh {} fdisk -l".format(ip))
		elif int(choice) == 17:
			os.system("ssh {} lsblk".format(ip))
		elif int(choice) == 18:
			os.system("ssh {} yum install httpd".format(ip))
		elif int(choice) == 19:
			os.system("ssh {} systemctl start httpd".format(ip))
		elif int(choice) == 20:
			os.system("ssh {} rpm -ivh xclip".format(ip))
		elif int(choice) == 21:
			os.system("ssh {} xclip -o".format(ip))
		elif int(choice) == 22:
			os.system("ssh {} yum repolist".format(ip))
		elif int(choice) == 23:
			os.system("ssh {} bc".format(ip))
		elif int(choice) == 24:
			domaonaddress = input("Enter the domain address to know its IP address (This changes using load balancer)")
			os.system("ssh {} nslookup {}".format(ip, domainaddress))
		elif int(choice) == 25:
			os.system("ssh {} jobs".format(ip))
		elif int(choice) == 26:
			os.system("ssh {} firefox".format(ip))

#ansible Program


		elif int(choice) == 31:
			os.system("ssh {} pip3 install ansible".format(ip))
			print("Ansible installed Successfully!")
		elif int(choice) == 32:
			os.system("ssh {} ansible --version".format(ip))
		elif int(choice) == 33:
			os.system("ssh {} ansible all --list-hosts".format(ip))
		elif int(choice) == 34:
			os.system("ssh {} ansible all -m ping".format(ip))
		elif int(choice) == 35:
			os.system('ssh {} ansible all -m package -a "name = httpd state=present" '.format(ip))
		elif int(choice) == 36:
			os.system('ssh {} ansible all -m service -a "name = httpd state=started" '.format(ip))
		elif int(choice) == 37:
			ipaddress = input("Enter the IP address of the Target node: ")
			typeofuser = input("Enter the user: ")
			sshpass = input("Enter the sshpass or protocol: ")
			os.system("ssh {} vim /etc/ansible/ansible.cfg".format(ip))
			configfile = open("ansible.cfg","w")
			configfile.write('[defaults] \n {} ansible_user = {} ansible_ssh_pass = {}'.format(ipaddress, typeofuser, sshpass))
			configfile.close()
		
#docker Program

		elif int(choice) == 41:
			os.system("ssh {0} yum install docker-ce --nobest" .format(ip))
			print("Docker installed Successfully!")
		elif int(choice) == 42:
			os.system("ssh {0} systemctl start docker" .format(ip))
			print("Started Docker Successfully!")
		elif int(choice) == 43:
			os.system("ssh {k} systemctl enable docker".format(ip))
			print("Docker is now Permanently enabled Successfully!")
		elif int(choice) == 44:
			os.system("ssh {} systemctl stop docker".format(ip))
			print("Stopped Docker Successfully!")
		elif int(choice) == 45:
			os.system("ssh {} systemctl status docker".format(ip))
		elif int(choice) == 46:
			print("Which image you want to search : ", end='')
			image_name = input()
			os.system("ssh {0} docker search {}" .forma(ip, image_name ))
		elif int(choice) == 47:
			print("which image you want to pull : ", end='')
			image_name = input()
			print("Enter image tag : ", end='')
			image_tag = input()
			os.system("ssh {0} docker pull {}:{}" .format(ip, image_name , image_tag))
		elif int(choice) == 48:
			os.system("ssh {0} docker images" .format(ip))
		elif int(choice) == 49:
			print("write the image name with tag you want to run : ", end='')
			image_name = input()
			print("Enter name of container : ", end='')
			cont_name = input()
			os.system("ssh {0} docker run -dit --name {} {}" .format(ip, cont_name , image_name))
		elif int(choice) == 50:
			os.system("ssh {0} docker ps -a" .format(ip))
		elif int(choice) == 51:
			print("Enter the container name : ", end='')
			cont_name = input()
			os.system("ssh {0} docker start {}" .format(ip, cont_name))
		elif int(choice) == 52:
			print("Enter container name : ", end='')
			cont_name = input()
			os.system("ssh {0} docker logs {}" .format(ip, cont_name))
		elif int(choice) == 53:
			os.system("ssh {} rm docker-ce.repo".format(ip))
			print("Removed Docker Successfully!")

		
#LVM Partitions

		elif int(choice) == 61:
			pv1=input("Enter the name of storage 1: ")
			os.system("ssh {} pvcreate {}".format(ip, pv1))

		elif int(choice) == 62:
			pv=input("Enter the name of storage:")
			os.system("ssh {} pvdisplay {}".format(ip, pv))
				
		elif int(choice) == 63:
			vgn=input("Give name to the VG:")
			pvn1=input("Enter the name of storage 1:")
			os.system("ssh {} vgcreate {} {}".format(ip, vgn, pvn1))

		elif int(choice) == 64:
			vgn1=input("Enter the name of VG:")
			os.system("ssh {} vgdisplay".format(ip, vgn1))

		elif int(choice) == 65:
			size=input("Enter size for your LV:")
			lvn=input("Give name to your LV:")
			vgn2=input("Enter name of the VG:")
			os.system("ssh {} lvcreate -l {} -n {} {}".format(ip, size,lvn,vgn2))
						 
		elif int(choice) == 66:
			os.system("ssh {} lvdisplay".format(ip))

		elif int(choice)== 67:
			vgn4=input("Enter the name of VG:")
			lvn2=input("Enter the name of LV:")
			os.system("ssh {} mkfs.ext4  /dev/{}/{}".format(ip,vgn4,lvn2))
			print("Created LVM Partition Successfully!")


#Hadoop 
		elif int(choice) == 71:
			def namenode_configuration():
				os.system("ssh {} cd /etc/hadoop/".format(ip))
				myfile1 = open('hdfs-site.xml','r+')
				myfile1.write('<?xml version="1.0"?>\n')
				myfile1.write('<?xml-stylesheet type="text/xsl" href="configuration.xsl"?>\n\n')
				myfile1.write("<!-- Put site-specific property overrides in this file. -->\n\n")
				myfile1.write("<configuration>\n")
				myfile1.write("<property>\n")
				myfile1.write("<name>dfs.name.dir</name>\n")
				myfile1.write("<value>/namenode</value>\n")
				myfile1.write("</property>\n")
				myfile1.write("</configuration>\n")
				myfile1.close()

				os.system("ifconfig enp0s3 | grep -E 'inet.[0-9]' | grep -v '127.0.0.1' | awk '{ print $2}' > ips.txt")

				myfile = open("ips.txt")
				content = myfile.read()
				ips = content.split("\n")
				myfile.close()
				ipadd = ips[0]

				os.system("/etc/hadoop/")
				myfile2 = open("core-site.xml","w")
				myfile2.write('<?xml version="1.0"?>\n')
				myfile2.write('<?xml-stylesheet type="text/xsl" href="configuration.xsl"?>\n\n')
				myfile2.write("<!-- Put site-specific property overrides in this file. -->\n\n")
				myfile2.write("<configuration>\n")
				myfile2.write("<property>\n")
				myfile2.write("<name>fs.default.name</name>\n")
				myfile2.write("<value>hdfs://{ip_address}:9001</value>\n".format(ip_address = ipadd))
				myfile2.write("</property>\n")
				myfile2.write("</configuration>\n")
				myfile2.close()

				os.system("cd")
				os.system("hadoop namenode -format")

				os.system("hadoop-daemon.sh start namenode")
				os.system("jps")
			namenode_configuration()
			print("\nDone! The system has now been setup as Namenode ")

		elif int(choice) == 72:
			def datanode_configuration():

				os.system("ssh {} cd /etc/hadoop/".format(ip))
				myfile1 = open("hdfs-site.xml","w")
				myfile1.write('<?xml version="1.0"?>\n')
				myfile1.write('<?xml-stylesheet type="text/xsl" href="configuration.xsl"?>\n\n')
				myfile1.write("<!-- Put site-specific property overrides in this file. -->\n\n")
				myfile1.write("<configuration>\n")
				myfile1.write("<property>\n")
				myfile1.write("<name>dfs.data.dir</name>\n")
				myfile1.write("<value>/dn1</value>\n")
				myfile1.write("</property>\n")
				myfile1.write("</configuration>\n")
				myfile1.close()

				ipadd = input("IP Address of namenode: ")

				os.system("/etc/hadoop/")
				myfile2 = open("core-site.xml","w")
				myfile2.write('<?xml version="1.0"?>\n')
				myfile2.write('<?xml-stylesheet type="text/xsl" href="configuration.xsl"?>\n\n')
				myfile2.write("<!-- Put site-specific property overrides in this file. -->\n\n")
				myfile2.write("<configuration>\n")
				myfile2.write("<property>\n")
				myfile2.write("<name>fs.default.name</name>\n")
				myfile2.write("<value>hdfs://{}:9001</value>\n".format(ipadd))
				myfile2.write("</property>\n")
				myfile2.write("</configuration>\n")
				myfile2.close()

				os.system("hadoop-daemon.sh start datanode")
			datanode_configuration()
			print("\nDone! The system has now been setup as Datanode")

		elif int(choice) == 73:
			def clientnode_configuration():

				ipadd = input("IP Address of namenode: ")

				os.system("ssh {} cd /etc/hadoop/".format(ip))
				myfile2 = open("core-site.xml","w")
				myfile2.write('<?xml version="1.0"?>\n')
				myfile2.write('<?xml-stylesheet type="text/xsl" href="configuration.xsl"?>\n\n')
				myfile2.write("<!-- Put site-specific property overrides in this file. -->\n\n")
				myfile2.write("<configuration>\n")
				myfile2.write("<property>\n")
				myfile2.write("<name>fs.default.name</name>\n")
				myfile2.write("<value>hdfs://{}:9001</value>\n".format(ipadd))
				myfile2.write("</property>\n")
				myfile2.write("</configuration>\n")
				myfile2.close()

			clientnode_configuration()
			print("\nDone! The system has now been setup as Clientnode")


		elif int(choice) == 74:
			os.system("ssh {} hadoop-daemon.sh start namenode".format(ip))
			os.system("ssh {} jps".format(ip))
			print("Master Node(namenode) started Successfully!")
		elif int(choice) == 75:
			os.system("ssh {} hadoop-daemon.sh start datanode".format(ip))
			os.system("ssh{} jps".format(ip))
			print("Slave Node(datanode) started Successfully!")
		elif int(choice) == 76:
			os.system("ssh {} hadoop dfsadmin -report".format(ip))
		elif int(choice) == 77:
			filename = input("Enter the file name(without any extensions) to be uploaded: ")
			os.system("ssh {} hadoop fs -put {}.txt".format(ip, filename))
			print("{} file uploaded Successfully to the cluster!".format(filename))
		elif int(choice) == 78:
			filename = input("Enter the file name(without any extensions) to be uploaded: ")
			blocksize = input("Enter the blocksize of the file to be stored of your choice: ")
			os.system("ssh {} hadoop fs -Ddfs.block.size ={}M -put {}.txt".format(ip, blocksize, filename))
			print("{} file uploaded with blocksize {} Successfully to the cluster!".format(filename, blocksize))
		elif int(choice) == 79:
			filename = input("Enter the file name(without any extensions) to be uploaded: ")
			os.system("ssh {} hadoop fs -touchz {}.txt".format(ip, filename))
			print("Empty file uploaded Successfully to the cluster!")
		elif int(choice) == 80:
			filename = input("Enter the file name(without any extensions) to be uploaded: ")
			blocksize = input("Enter the blocksize of the file to be stored of your choice: ")
			os.system("ssh {} hadoop fs -Ddfs.block.size ={}M -touchz {}.txt".format(ip, blocksize, filename))
			print("Empty file uploaded with blocksize {} Successfully to the cluster!".format(blocksize))
		elif int(choice) == 81:
			filenamerm = input("Enter the file name(without any extensions) to be removed: ")
			os.system("ssh {} hadoop fs -rm/{}".format(ip, filenamerm))
			print("{} file removed Successfully!".format(filenamerm))
		elif int(choice) == 82:
			os.system("ssh {} hadoop dfsadmin -safemode get".format(ip))
		elif int(choice) == 83:
			os.system("ssh {} hadoop dfsadmin -safemode leave".format(ip))
		elif int(choice) == 84:
			os.system("hadoop fs -ls/")
		elif int(choice) == 85:
			os.system("ssh {} jps".format(ip))

#AWS CLI

		elif int(choice) == 91:
			os.system("ssh {} pip3 install awscli".format(ip))
			print("\n\n Successfully Installed AWS CLI!")
		elif int(choice) == 92:
			os.system("ssh {} aws configure".format(ip))
			print("\n\n AWS Configuration completed Successfully!")
		elif int(choice) == 93:
			keypairname = input("Enter your keypair name: ")
			os.system("ssh {} aws ec2 create-key-pair --key-name {}".format(ip, keypairname))
			print("\n\nCreated Key Pair successfully!")
		elif int(choice) == 94:
			groupname = input("Enter your Security Group name: ")
			groupdescription = input("Enter your Security Group Description: ")
			os.system('ssh {} aws ec2 create-security-group --group-name{} --description "{}"'.format(ip, groupname, groupdescription))
			print("\n\n Created Security Group successfully!")
		elif int(choice) == 95:
			os.system("ssh {} aws ec2 describe-instances".format(ip))
		elif int(choice) == 96:
			imageid = input("Enter your AWS OS Image ID: ")
			instancetype = input("Enter Instance type: ")
			securitygroup = input("Enter Security Group ID: ")
			keyname = input("Enter Key name: ")
			os.system("ssh {} aws ec2 run-instances --image-id {} --instance-type {} --security-group {} --key-name {}".format(ip, imageid, instancetype, securitygroup, keyname))
			print("Successfully created an EC2 Instance(default storage space is allocated(i.e.,10GB))")
		elif int(choice) == 97:
			az = input("Enter the availability zone : ")
			size = input("Enter the size of EBS Volume to be created: ")
			os.system("ssh {} aws ec2 create-volume --availability-zone {} --size {}".format(ip, az, size))
			print("Successfully created Volume {} with size {}!".format(az, size))
		elif int(choice) == 98:
			instanceid = input("Enter your EC2 instance ID: ")
			volumeid = input("Enter Volume ID: ")
			os.system("ssh {} aws ec2 attach-volume --instance-id {} --volume-id {} --device /dev/sdf".format(ip, instanceid, volumeid))
			print("Successfully attached volume to the instance!")
		elif int(choice) == 99:
			keypairname = input("Enter your keypair name: ")
			os.system("ssh {} aws ec2 delete-key-pair --key-name {}".format(ip, keypairname))
			print("\n\nDeleted Key Pair successfully!")
		elif int(choice) == 100:
			groupname = input("Enter your Security Group name: ")
			os.system('ssh {} aws ec2 delete-security-group --security-group {} '.format(ip, groupname))
			print("\n\n Deleted Security Group successfully!")		


#Tech ends

		elif int(choice) == 0:
			print("See you soon! Stay safe! Bye! :)")
			exit()
		else :
			print("Sorry! Its an invalid choice!")
	else:
		print("Sorry! Invalid login type :( !")
	input("Press Enter to keep going...")
