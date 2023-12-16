# Nessus
## Configure Tenable Nessus Vulnerability Scanner in AWS and Deploy Metapsloitable, Scan the target using Nessus, Generate the Report and Analyse the report.

### 1. Logged into AWS Console, Created Windows_Nessus_Server, and Metasploitable EC2 Instance.

![image](https://github.com/pradip2994/Nessus/assets/124191442/1a41cb0b-622e-4adf-a572-6271ec4a3c32)

### 2. Now i am able to spin up and login into Windows_Nessus_Server.

![image](https://github.com/pradip2994/Nessus/assets/124191442/43243ac9-9f78-4f26-a173-98e94fc36903)

### 3. Now Go to the Server Manager- Select Local Server in left hand side and check for IE Enhanced Security Configuration, Click on IE Enhanced Security Configuration and Turn off both Administrator and Users.

![image](https://github.com/pradip2994/Nessus/assets/124191442/333bc33f-2fb6-48b8-bc99-78e5637d4584)

### 4. The Host Firewall running in the Server might not be allowing few of the features to access so we need to turn off Windows Defender Firewall.

![image](https://github.com/pradip2994/Nessus/assets/124191442/f103532a-70a9-4cb1-a311-1ecd2090ce69)

### 5. Installed Nesses and access outside the AWS by pasting the https://<EC2_public_IP>:8834/#/ in your machines browser. 
 
![image](https://github.com/pradip2994/Nessus/assets/124191442/21b54cb2-2987-424a-8011-957626ff357e)


![image](https://github.com/pradip2994/Nessus/assets/124191442/360c69a3-935a-478c-8f90-2acae45db86c)

### 6. Scanning the target using Nessus.

#### Basic network scan using Nessus on the target named 'Metasploitable,' scanning all ports.
![image](https://github.com/pradip2994/Nessus/assets/124191442/f4e502e2-95ef-4ed3-95c6-1d4058cfe614)
![image](https://github.com/pradip2994/Nessus/assets/124191442/70de9974-bae3-4b10-91cd-7cff251e2aa4)

#### Result After scanning Metasploitable
![image](https://github.com/pradip2994/Nessus/assets/124191442/a96272a5-baab-412e-8b93-c4c91b233b40)

### 7. Generated the Report and Analysed the report. 

![Screenshot 2023-12-16 142958](https://github.com/pradip2994/Nessus/assets/124191442/43714f82-a804-4022-b39e-19a42991ce52)
![Screenshot 2023-12-16 143012](https://github.com/pradip2994/Nessus/assets/124191442/078d3f68-7daf-4549-a16c-25dbb8f171f5)
![Screenshot 2023-12-16 143032](https://github.com/pradip2994/Nessus/assets/124191442/3257f521-bdd5-4b41-95b2-962b0a7fd483)

