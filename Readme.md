# Alfred 2 Plugin - Adium Controls

## Overview

Original Plugins were from [Uirs Dacosta](http://urisdacosta.tumblr.com/post/13767011309/alfred-extension-for-adium-chat) and [Joel Gillman](http://joelgillman.com/projects/alfred-controls-for-adium/).

I integrated them together for Alfred 2. This is kind of forked from [this repo](https://github.com/Detmud/Alfred-Extension---Adium-Chat) but due to the differences in the way Alfred 2 handles workflows, I wanted to start it from scratch to make this easier to collaborate on.

###Installing
Download the zip from Github and change the extension to `.alfredworkflow`. Double click to install.

**This requires Alfred 2, which is currently in Beta for Mega Supporters**

### Syntax 
**chat display_name [: message]**

display_name is mandatory,
: message is optional.


### Examples
**chat fluffy**

will open a chat window with the person “fluffy”

**chat fluffy: thinking of you! :)**

that will send the text “thinking of you :)” to your contact “fluffy” using Adium.

## 

### 3.0 by Alan Mooiman
- Integrated Joel Gillman's scripts for managing availability and online/offline status.
- Changed format for compatibility with Alfred 2.

### 2.0.1 by Artem Tomilov
- Small refactor of code

### 2.0 by Sebatian Hansack
- Deleting Growl Notifications
- New Chats now open in new Tabs
- Focus is set automatically

### 1.1 by Sebastian Hansack
- Adding Growl Notification

### 1.0 by Uris Ducats
- Initial Version

## Known Bugs
This Script will actually *(Adium 1.5b9r4498)* not work with Facebook Contacts.

I submitted this Bug already to the Adium Developer Team,
you can find the [Trac Ticket here](http://trac.adium.im/ticket/15768).


## Licence
<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/3.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Dataset" property="dct:title" rel="dct:type">Adium Chat Plugin for Alfred</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/Detmud/Alfred-Extension---Adium-Chat" property="cc:attributionName" rel="cc:attributionURL">Uris Dacosta, Sebastian Hansack</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/">Creative Commons Attribution-ShareAlike 3.0 Unported License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/Detmud/Alfred-Extension---Adium-Chat" rel="dct:source">github.com</a>.