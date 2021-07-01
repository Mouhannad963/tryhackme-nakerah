---
published: false
---
# Introductory Networking

##   السلام عليكم ورحمة الله  , انا مهند الحميدي من  مجتمع نكرة ان شاء الله في هذه البلوغ رح نحل 
### (Introductory Networking room from tryhackme)
.......





## Task 2 
### Which layer would choose to send data over TCP or UDP?
udp,tcpيتم تحديد البروتوكول الذي من خلال سيتم ارسال البيانات وهما ال    osi في الطبقة الرابعة من نموذج ال  
### ANSWER : 4
### Which layer checks received packets to make sure that they haven't been corrupted?
في الطبقة الثانية يتم التأكد من البيانات المتلقية أنها لم يتم التلاعب فيها او تم فقدان شيئ منها 
### ANSWER : 2
### In which layer would data be formatted in preparation for transmission?
كذلك في الطبقة الثانية يتم تجهيز البيانات للإرسال بعد ان تمت معالجتها من قبل الطبقات الشبكة الأعلى
### ANSWER : 2
### Which layer transmits and receives data?
الطبقة الفيزيائية او الطبقة الاولى هي الطبقة الوسيطة التي تقوم بنقل البيانات بين الطرفين 
### ANSWER : 1
### Which layer encrypts, compresses, or otherwise transforms the initial data to give it a standardised format?
الطبقة السادسة تقوم بتهئية شكل البيانات لتكون جاهزة للإرسال عن طريق ضغطها وتشفيرها 
### ANSWER :6
### Which layer tracks communications between the host and receiving computers?
الطبقة الخامسة تقوم بإنشاء جلسة منطقية ( اتصال منطفي بين المرسل والمستقبل ) ليتم تبادل المعلومات وتحافظ على هذا الاتصال 
### ANSWER : 5
### Which layer accepts communication requests from applications?
الطبقة السابعة هي الطبقة الاولى التي تتعامل مع التطبيقات
### ANSWER : 7
### Which layer handles logical addressing?
 اللذان لهم دور اساسي في العنونة المنطقيةip االطبقة الثالثة هي الطبقة المسؤولة عن العنونة حيث يعمل فيها الراوتر وبرتوكل ال

### ANSWER : 3
### When sending data over TCP, what would you call the "bite-sized" pieces of data?
 segmentلإرسال قطع البينات فإنه يتم تسيمتها بال  TCP عندما يستعمل بروتوكل

### ANSWER : segment
### Which layer would the FTP protocol communicate with?
كلها تعمل في الطبقة السابعة ssh,telnet,dhcp,...بروتوكول نقل البينات  والعديد من البروتوكولات الاخرى ك ال 

### ANSWER : 7
### Which transport layer protocol would be best suited to transmit a live video?

السرعة في النقل لأنه لايهتم بضياع البينات في طريق النقل لذلك يستخدم في البث المباشر حيث يمكن اهمال  ضياع بعض اجزاء البيانات UDP من ميزات بروتوكول ال
## TASK 3
### How would you refer to data at layer 2 of the encapsulation process (with the OSI model)?
Frames عندما تصل البينات الى الطبقة الثانية نطلق عليها اسم ال
### ANSWER : frames
### How would you refer to data at layer 4 of the encapsulation process (with the OSI model), if the UDP protocol has been selected?
نطلق على البينات اسم ال  UDP في الطبقة الرابعة اذا كان البروتوكل المتسخدم للنقل هو برتوكول ال 
datagrams
### What process would a computer perform on a received message?

عند وصول البينات للمستقبل تتم عليها عملية فك التغليف لتكون جاهزة لارسالها للتطبيقاات الهدف
### ANSWER :de-encapsulation
### Which is the only layer of the OSI model to add a trailer during encapsulation?
الطبقة الثانية هي الطبقة الوحيدة التي تضيف قطعة في مؤخرة البينات والتي تساعد على التحقق ان البينات لم يتم التلاعب بها 
### ANSWER :Data Link
### Does encapsulation provide an extra layer of security (Aye/Nay)?
نعم كما تكلمنا أن الطبقة الثانية تضيف قطعة من البينات للتأكد ان البينات لم يتم التلاعب بها في الطريق 
### ANSWER : Aye

## TASK 4
### Which model was introduced first, OSI or TCP/IP?

في سنة 1982  TCP\IP تم اصدار بروتوكول ال  
في سنة 1984 OSI بينما تم اصدار نموذج ال 

### ANSWER : TCP\IP

### Which layer of the TCP/IP model covers the functionality of the Transport layer of the OSI model (Full Name)?

هي نفسها طبقة النقل  
### ANSWER : Transport

### Which layer of the TCP/IP model covers the functionality of the Session layer of the OSI model (Full Name)?
تضم طبقة الجلسة والتطبيق والبريزينتاشن   TCP\Ipالطبقة الخامسة من نموذج ال
### ANSWER : Application

### The Network Interface layer of the TCP/IP model covers the functionality of two layers in the OSI model. These layers are Data Link, and?.. (Full Name)?
### ANSWER : Physical
### Which layer of the TCP/IP model handles the functionality of the OSI network layer?
### ANSWER : Internet

### What kind of protocol is TCP?

### ANSWER : Connection-based

### What is SYN short for?

### ANSWER : Synchronise

### What is the second step of the three way handshake?
### ANSWER : SYN/ACK

### What is the short name for the "Acknowledgement" segment in the three-way handshake?

### ANSWER : ACK

## TASK 5 

### What command would you use to ping the bbc.co.uk website?
من خلال الاسم او العنوان  ping نستطيع استخدام تعليمة  
![Screenshot 2021-07-01 230511.png]({{site.baseurl}}/_posts/Screenshot 2021-07-01 230511.png)

### ANSWER : ping bbc.co.uk

### Ping muirlandoracle.co.uk What is the IPv4 address?
### ANSWER : 217.160.0.152

### What switch lets you change the interval of sent ping requests?
 ![]({{site.baseurl}}/_posts/Screenshot%202021-07-01%20230511.png)
### ANSWER : -i

### What switch would allow you to restrict requests to IPv4?

![]({{site.baseurl}}/_posts/Screenshot%202021-07-01%20230511.png)

### ANSWER : -4

### What switch would give you a more verbose output?

![]({{site.baseurl}}/_posts/Screenshot%202021-07-01%20230511.png)

### ANSWER : -v

## TASK 6
### What switch would you use to specify an interface when using Traceroute?
![]({{site.baseurl}}/_posts/Screenshot%202021-07-01%20230511.png)
### ANSWER : -i

### What switch would you use if you wanted to use TCP SYN requests when tracing the route?

![]({{site.baseurl}}/_posts/Screenshot%202021-07-01%20230511.png)
### ANSWER : -T

### [Lateral Thinking] Which layer of the TCP/IP model will traceroute run on by default (Windows)?

تتعامل مع العناوين  tracoute   طبقة الانترنت لان اداة 


## TASK 7

### What is the registrant postal code for facebook.com?

![]({{site.baseurl}}/_posts/Screenshot%202021-07-01%20230511.png)

### ANSWER : 94025

### When was the facebook.com domain first registered?

![]({{site.baseurl}}/_posts/Screenshot%202021-07-01%20233538.png)![Screenshot 2021-07-01 233538.png]({{site.baseurl}}/_posts/Screenshot 2021-07-01 233538.png)

### ANSWER : 29/03/1997

### Which city is the registrant based in?

![]({{site.baseurl}}/_posts/Screenshot%202021-07-01%20233538.png)

### ANSWER : Redmond

### [OSINT] What is the name of the golf course that is near the registrant address for microsoft.com?

![]({{site.baseurl}}/_posts/Screenshot%202021-07-01%20234244.png)

### ANSWER : Bellevue Golf Course






