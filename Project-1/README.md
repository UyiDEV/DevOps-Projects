# WEB STACK IMPLEMENTATION (LAMP STACK)

## LAMP (Linux, Apache, MySQL, PHP or Python, or Perl)

## STEP 1 - Setup Instance

We begin by creating our AWS account, then we launch AWS EC2 instance of t2.micro family with Ubuntu Server 20.04 LTS.
![EC2 instance](images/EC2-instance.png)

Run this command to ensure your key is not publicly viewable `chmod 400 <your-PEM-file-name>.pem`

---
Next we will get the ssh with which we will connnect to the instance.
![SSH](images/ssh.png)

---

Now we will connect to our EC2 instance using our windows terminal.
![Terminal](images/Terminal-ssh.png)

---

We are successfully connected to the instance
![Instance-connected](images/Instance-connected.png)

---

Now in order to install all necessary tech stacks we need to make sure the instace is up-to-date.
![Update](images/Update.png)

---

Next we will install Apache
![Apache](images/Apache-install.png)
