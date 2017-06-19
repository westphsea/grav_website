---
body_classes: 'blog group-blog infinite-scroll'
menu: 'System Status'
sitemap:
    changefreq: monthly
    priority: 1.03
content:
    items: '@self.children'
    order:
        by: date
        dir: desc
    limit: 10
    pagination: true
feed:
    description: 'Sample Blog Description'
    limit: 10
pagination: false
---

## ![](settings.png) Check System Status
[Student Academic Information System](http://sais.up.edu.ph)  
[University Information System](https://uis.up.edu.ph)  
[Mail](https://mail.up.edu.ph)  
[Document Tracking System](https://dts.upou.edu.ph)  
[Socialized Tuition System](https://sts.up.edu.ph)  
##### Contact our Admins:
[Send them an e-mail!](https://mail.google.com/mail/?view=cm&fs=1&to=someone@example.com&su=SUBJECT&body=BODY&bcc=someone.else@example.com)
### System Status:
<link rel="stylesheet" type="text/css" href="ping.css">
<script src="http://cdnjs.cloudflare.com/ajax/libs/knockout/2.2.1/knockout-min.js"></script>
<script src="http://code.jquery.com/jquery-1.11.0.js"></script>
<link rel="stylesheet" type="text/css" href="ping.css">
<script src="http://cdnjs.cloudflare.com/ajax/libs/knockout/2.2.1/knockout-min.js"></script>
<script src="http://code.jquery.com/jquery-1.11.0.js"></script>
<ul data-bind="foreach:servers">
	<li> <a href="#" data-bind="text:name,attr:{href: 'http://'+name}">tester</a> <span data-bind="text:status,css:status"></span>
	</li>
</ul>
<script src="pingscript.js"></script>