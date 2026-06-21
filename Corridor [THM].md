# [Corridor](https://tryhackme.com/room/corridor) | THM 

#### Enumeration 
First thing I did was use __NMAP__ to enumerate potential open ports on the IP and I noticed the port 80. Particulary means the IP is running a website.

<img width="50%" height="50%" alt="Screenshot 2026-06-21 105746" src="https://github.com/user-attachments/assets/6ce9293a-a7b9-49c2-8225-2d2ae5c3354d" />

#

Upon visiting the website, I've been greeted with a image on the website. 

<img width="50%" height="50%" alt="Screenshot 2026-06-21 105820" src="https://github.com/user-attachments/assets/a0c45012-2d6c-4362-ab4a-fd7a3d52b419"  />

#

I downloaded the image out of curiosity and ran __binwalk__ on the image. Upon checking I noticed it has a compressed file hidden in the image and extracted the file 

<img width="50%" height="50%" alt="Screenshot 2026-06-21 111444" src="https://github.com/user-attachments/assets/4c97639b-69ae-4c21-8221-22bb5a9bccca" />

#

