# Shell to binary
<b> 
  Note:
  </b>

<p>
The shell-to-binary script runs on CentOS 7 and 8.
<p/>
<b> ====How to run the script?==== </b> <br />
git clone https://github.com/smarttechfunda/shell-to-binary.git <br />
Login as a non-root user, and the user should have sudo permission.<br />
OR use sudo su command to login as root user. <br />
Run the following command. (If you are login as root user then no need to use sudo command.)<br />
$ cd shell-to-binary <br />
$ chmod +x shell-to-binary <br />  
$ sudo su <br />  
When you run first time then use the following command.<br />
yes | ./shell-to-binary shell_script_file_name <br />
OR <br />
./shell-to-binary shell_script_file_name <br />
Example : <br />
When you run first time then use the following command.<br />
yes | ./shell-to-binary /home/centos/shellscript.sh <br />
OR <br />
./shell-to-binary shell_script_file_name <br />

</p>
