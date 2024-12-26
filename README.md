# SIEM-Home_Lab

A Elastic Security Information and Event Management lab to monitor and alert security event generated on KALI linux virtualmachine.
using a dashboard the events generated in KALI VM can be recorded and alerted through mail when a the Observability data type reaches or exceeds a given value and when npam_scan is detected.


KALI linux VirtualMachine :
https://www.kali.org/get-kali/#kali-platforms

Virtual-box:
https://www.virtualbox.org/

Elastic cloud:
https://www.elastic.co/cloud


running nmap scan


![image](https://github.com/user-attachments/assets/cbae74f1-1c9d-42a3-80b7-903d33e97bda)



Dashboard indicating the logs sent in KALI VM



![image](https://github.com/user-attachments/assets/4e9eff47-5734-4b15-8f49-86fb2902d3e6)





# ALERTS

CUSTOM THRESHOLD ALERT

when the log counts exceeds a given value, the alert is set active

![image](https://github.com/user-attachments/assets/23696f00-9905-43ed-ae75-1749155004df)



![image](https://github.com/user-attachments/assets/7a728de3-fc6d-46fd-a969-adfed04aecd9)


nmap scan alert

when the nmap scan is detected in the KALI linux terminal
the alert is set active.



![image](https://github.com/user-attachments/assets/f0382cac-d5cc-4cd7-93e1-8fad210b0fcd)






