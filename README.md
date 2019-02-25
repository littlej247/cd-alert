# cd-alert
cd-alert is a pure JavaScript library which appends a dynamic message box to your web application. Requires w3.css and a w3-theme as shown in the example below.

cd-alert.js works by appending a global function "CD.alert(message, title, type, callback, options)" that appends an alert style element to the dom.
A simple js library for message box functionality in my web apps. Written in vanilla js and only requires w3.css and a w3 theme css file

## Demo

[http://htmlpreview.github.io/?https://github.com/littlej247/cd-alert/blob/master/index.html](http://htmlpreview.github.io/?https://github.com/littlej247/cd-alert/blob/master/index.html)


## Usage

Just add a script tag in your '<head>' (requires w3.css and a w3 theme file) :
'''html
<head>
  <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css"> 
  <link rel="stylesheet" href="https://www.w3schools.com/lib/w3-theme-blue-grey.css">
  <script src="cd-alert/cd-alert.js"></script>
</head>
'''

Then, when ever you want to call your message 
'''html
<body>

</body>
'''
### alert arguments

argument | Type | Default | Description
------ | ---- | ------- | -----------
message | String | '' | The body of the message you would like to appear in the alert. This can include html in string form.
title | String | cartoon catchphrase at random | The title of the message box. If left null it will pick a cartoon catch phrase at random. This is useful when troubleshooting as it makes it more fun.
type | String | 'ok' | Configuration of the message box: \n 'ok' - single ok button \n 'cancel' - shows both an ok and cancel button /n 'lock' - all buttons are hidden (requires a call from the returned object)
callback | Function
options | 


### callback arguments

argument | Type | Default | Description
------ | ---- | ------- | -----------
message | String | '' | The body of the message you would like to appear in the alert. This can include html in string form.
title | String | cartoon catchphrase at random | The title of the message box. If left null it will pick a cartoon catch phrase at random. This is useful when troubleshooting as it makes it more fun.



### options

Options are passed to the alert function in the form of an object. Usefull if you would like a little more customization in your alert.

Option | Type | Default | Description
------ | ---- | ------- | -----------
ok | string | 'OK' | Caption for the OK button
cancel | string | 'Cancel' | Caption for the Cancel button


## object methods

Once you've created the alert you may want to close it or make changes. 






