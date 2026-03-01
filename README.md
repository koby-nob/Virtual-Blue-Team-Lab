# Cybersecurity-Projects


<h2>Description </h2>

    - This project outlines the creating of virtual blue team environment.
    
         - Windows PC
         - Vmare Workstation
         
<h2>Operating System Used </h2>

         - Host machine: Parrot OS Linux - IP- 10.1.6.25
         - Victim machine: Ubuntu Linux  - IP- 10.1.6.200

<h2>Installation Steps </h2>

 - Screenshot 1- Windows specs

<img width="738" height="194" alt="Screenshot_2a_My Windows specs" src="https://github.com/user-attachments/assets/79b22f18-ffe5-4154-915e-fe5785a31d44" />

    - Find out what your widows specs of your system
    - On Window > right click the start button > select system, and post screenshot

 - Screenshot 2- using ifconfig command

<img width="798" height="660" alt="screenshot" src="https://github.com/user-attachments/assets/74a040a0-82a4-4fde-abd4-b7630d7aa2ec" />


    - Type: /sbin/ifconfig

 - Screenshot 3- ping the victim machine (ubuntu) with date, and timestamp

<img width="811" height="283" alt="Screenshot 2b_Parrot pinging ubuntu machine successfully with timestamp and date" src="https://github.com/user-attachments/assets/337b779f-8a53-49e3-ac9b-6045a8fb601b" />

    - Type: ping 10.1.6.25 -c 4 | ts '[%Y-%m-%d %H:%M:%S]'
    

 - Screenshot 3- ping the host machine (parrot) with date, and timestamp
  
<img width="1130" height="312" alt="Screenshot 2c_pinging parrot machine successfully with timestamp and date" src="https://github.com/user-attachments/assets/568b8a9e-c75f-4b86-8bf4-147fb07978a0" />


    - Type: ping 10.1.6.200 -c 4 | ts '[%Y-%m-%d %H:%M:%S]'

