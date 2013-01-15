# Alfred 2 Plugin - Adium Controls

## Overview

Original Plugins were from [Uirs Dacosta](http://urisdacosta.tumblr.com/post/13767011309/alfred-extension-for-adium-chat) and [Joel Gillman](http://joelgillman.com/projects/alfred-controls-for-adium/).

I integrated them together for Alfred 2. This is kind of forked from [this repo](https://github.com/Detmud/Alfred-Extension---Adium-Chat) but due to the differences in the way Alfred 2 handles workflows, I wanted to start it from scratch to make this easier to collaborate on.

###Installing
Download the zip and expand, double click the .alfredworkflow file. The source is included separate from that file (though you can get at it by changing the `.alfredworkflow` extension to `.zip`).

I haven't really figured out a good way to make this cloneable directly to Alfred's workflows folder, perhaps this will be possible once syncing has been worked into Alfred 2.

**This requires Alfred 2, which is currently in Beta for Mega Supporters**

### Syntax 
**chat display_name**
opens a new chat window/tab with person 'display_name'. Switches to chat window with that person if it's already open.

**chat display_name :message**
Sends 'message' to 'display_name'.

**away**
Set status to "Away"

**away l**
Set status to "lunch" and start screen saver

**away m**
Set status to "meeting" and start screen saver

**away p**
Set status to "on the phone" and start screen saver

**away d**
Set status to "do no disturb" and start screen saver

**away b**
Set status to "Be right back" and start screen saver

**away i**
Set status to invisible

**away my custom message**
Set status to "my custom message" and start screen saver

Works best if you have set your computer to lock on screen saver. System Preferences > Security & Privacy Personally I have mine set to "5 seconds" to prevent accidental screen saver lock-outs.


##Versions

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

This bug has been submitted to the Adium Developer Team,
you can find the [Trac Ticket here](http://trac.adium.im/ticket/15768).


## Licence
<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/3.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Dataset" property="dct:title" rel="dct:type">Adium Chat Plugin for Alfred</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/Detmud/Alfred-Extension---Adium-Chat" property="cc:attributionName" rel="cc:attributionURL">Uris Dacosta, Sebastian Hansack</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/">Creative Commons Attribution-ShareAlike 3.0 Unported License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/alanmoo/Duck-Butler-2" rel="dct:source">github.com</a>.