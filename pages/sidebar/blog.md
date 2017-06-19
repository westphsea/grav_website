---
title: Sidebar
published: false
routable: false
content:
    items: '@self.children'
    limit: 5
    order:
        by: date
        dir: desc
    pagination: '1'
hidegitrepoeditlink: false
access:
    site.login: true
---

##### Course Facilitators
Some Name  
<somename@somewhere.edu>   
Office hours Mon. 4:00-5:15pm  
Harbour Centre 2146  
Another Name  
<anothername@somewhere.edu>  
##### Quick Links:
[Student Academic Information System](http://sais.up.edu.ph)  
[University Information System](https://uis.up.edu.ph)  
[Mail](https://mail.up.edu.ph)  
[Document Tracking System](https://dts.upou.edu.ph)  
[Socialized Tuition System](https://sts.up.edu.ph)  
##### Contact our Admins:
[Send them an e-mail!](https://mail.google.com/mail/?view=cm&fs=1&to=someone@example.com&su=SUBJECT&body=BODY&bcc=someone.else@example.com)
### Site Status:
<link rel="stylesheet" type="text/css" href="ping.css">
<script src="http://cdnjs.cloudflare.com/ajax/libs/knockout/2.2.1/knockout-min.js"></script>
<script src="http://code.jquery.com/jquery-1.11.0.js"></script>
<link rel="stylesheet" type="text/css" href="ping.css">
<script src="http://cdnjs.cloudflare.com/ajax/libs/knockout/2.2.1/knockout-min.js"></script>
<script src="http://code.jquery.com/jquery-1.11.0.js"></script>
<ul data-bind="foreach:servers">
	<li> <a href="#" data-bind="text:name,attr:{href: 'http://'+name}">tester</a> <span data-bind="text:status,css:status"></span></li>
</ul>
<script src="pingscript.js"></script>