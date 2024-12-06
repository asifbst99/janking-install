# janking-install

step 1 install java 
  sudo apt update
sudo apt install default-jdk

step 2 
1. Add the Jenkins Repository:

Bash
sudo wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key | sudo apt-key add -
sudo add-apt-repository https://pkg.jenkins.io/debian-stable/
Use code with caution.

2. Update the Package List:

Bash
sudo apt update
Use code with caution.

3. Install Jenkins:

Bash
sudo apt install jenkins
Use code with caution.

4. Start and Enable Jenkins:

Bash
sudo systemctl start jenkins
sudo systemctl enable jenkins
Use code with caution.

Accessing Jenkins:

Find the Initial Admin Password:
Bash
sudo cat /var/lib/jenkins/secrets/initialAdminPassword
Use code with caution.

Access the Jenkins Web Interface: Open your web browser and go to http://localhost:8080. Enter the initial admin password when prompted.
