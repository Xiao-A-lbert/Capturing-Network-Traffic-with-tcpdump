# Capturing Network Traffic with tcpdump

<h2>Description</h2>
In this network security task I used tcpdump with various filters to catpure specific traffic from a src/dst port, src/dst net, excluding specific ports, writing the capture to a file, and reading from that file. 


<h2>Languages and Utilities Used</h2>

- <b>tcpdump</b>
- <b>linux CLI</b>


<h2>Environments Used </h2>

- <b>Unbuntu</b> 

<br />
<br />
I used tcpdump to capture enp0s3 interface traffic specifically to hose exmaple.com (example.com typo lol).

![1) dan tcpdump to capture traffic to host exmaple](https://github.com/user-attachments/assets/02062d2d-69d1-4a90-9efc-4a9c72e11b71)

<br />
<br />
Using tcpdump to capture traffic from a specific source (192.168.1.4).

![2) capturing packets from ym source ip curling google as exmaple](https://github.com/user-attachments/assets/4ff76347-5fdc-4c76-8ac3-2c0da53a005d)

<br />
<br />  
Other tcpdump filters to speciy src/dst net and src/dst ports. 

![3) more filters like src and dst port and net](https://github.com/user-attachments/assets/311c44c1-81a3-4cc7-8434-59c8b4e2d069)

<br />
<br />
Using tcpdump to capture from a specific src to a specific dst while excluding port 443 and 22. 

![4) logical operators to capture specific traffic](https://github.com/user-attachments/assets/970b2329-d523-438d-a494-db9de3b4ffc2)

<br />
<br />
Using tcpdump to write the network traffic capture to a specific file then reading from that file. 

![5) putting captured traffic into a file and reading it](https://github.com/user-attachments/assets/a95c1735-fbd1-4dc1-ad51-1fc1cb872898)

<br />
<br />
