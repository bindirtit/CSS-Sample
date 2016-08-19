In order to make Bootstrap completely compatible with every kind of device, we
need to include some necessary meta tags.
+ Tell browsers that our website contains characters from the Unicode
character set, a superset of the ASCII character set. 
<meta charset="utf-8">
+ Sometimes, Internet Explorer may run in compatibility mode. Force IE to use the latest rendering engine to render our website:
<meta http-equiv="X-UA-Compatible" content="IE=edge">
+ Tell the browser to scale our application to the size of window space available:
<meta name="viewport" content="width=device-width, initial-scale=1">
initial-scale=1 means scale it to 100%.

Bootstrap 3 uses many HTML5 elements and CSS3 properties that wonʼt work in Internet Explorer 8. Using html5shiv.js and respond.js to support HTML5 and CSS3 in IE8