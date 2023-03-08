# Automation_Project

Wecome to the Course Assignment 1:

Task 2 Description: 1.On execution of the script “automation.sh”, it should update the package details. 2.Script checks whether the HTTP Apache server is already installed. If not present, then it installs the server. 3.Script checks whether the server is running or not. If it is not running, then it starts the server 4.Script ensures that the server runs on restart/reboot, it checks whether the service is enabled or not. It enables the service if not enabled already 5.After executing the script the tar file should be present in the /tmp/ directory. Tar should be copied to the S3 bucket.

Task 3 Description: 1.The script should schedule a Cron job that runs the same script automatically at an interval of 1 day as a root user. 2. When the script is executed, it should create /var/www/html/inventory.html with the proper header and append detail of copied Tar file.
