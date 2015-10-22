---
author: Jan Wagner <waja@cyconet.org>
title: Web-Software Development from DevOps view
---
## Web-Software Development from DevOps view
### Jan Wagner <waja@cyconet.org>

<br>
<img style="position: relative; left:800px; top: 175px " src="images/image.png" alt="Just a not (yet) existing image.">


---
= data-x='1000' id='oldtools1'
## Tools we used to manage our software

* cp
* rsync
* vi
* nano
* kate
* joe
* eclipse
* netbeans

---
= data-x='1000' id='oldtools2'
## Problems with our (old) tools

* no chronological revisions
* multiple different versions (forks) in production
* multiple different local versions
	* f00b4r.php
	* f00b4r_20040410.php
	* f00b4r_production.php
* distributed via scp/rsync
* [TODO]

---
= data-x='1000' id='vcs'
## Way out?

- __V__ersion __C__ontrol __S__ystem
	- tracks __changes of files and folder__
	- when = date of the commit
	- who = name of author
	- why = commit message

---
= data-x='1000' id='centralvcs1'
## Tools we used to manage our software

* [CVS](https://en.wikipedia.org/wiki/Concurrent_Versions_System)
* [Subversion](https://en.wikipedia.org/wiki/Apache_Subversion)
* [RCS](https://en.wikipedia.org/wiki/Revision_Control_System)

---
= data-x='1000' id='centralvcs2'
## [Client-server version control software](https://en.wikipedia.org/wiki/List_of_version_control_software#Client-server_model)

* One linear software repository
* Server down, no development

<img style="position: relative; left:80px; top: 15px " height="300" width="500" src="https://upload.wikimedia.org/wikipedia/commons/1/1a/SVN_Server_Client_Structure.png" alt="SVN Structure">
 
---
= data-x='1000' data-rotate="90" id='whatnext'
## And now?

* How to fix some of those issues?
* [TODO] - Entertainment

---
= data-x='1000' id='distributedvcs1'
## [Distributed Version Control](https://en.wikipedia.org/wiki/Distributed_version_control) (recently moves)

* [BitKeeper](https://en.wikipedia.org/wiki/BitKeeper)
* [Mercurial / HG](https://en.wikipedia.org/wiki/Mercurial_(software))
* [Bazaar](https://en.wikipedia.org/wiki/Bazaar_(software))
* [Git](https://en.wikipedia.org/wiki/Git_(software))

---
= data-x='1000' id='distributedvcs2'
## [Distributed Version Control](https://en.wikipedia.org/wiki/Distributed_version_control)

[TODO]

<img style="position: relative; left:80px; top: 15px " height="450" width="650" src="https://upload.wikimedia.org/wikipedia/commons/a/a3/SVNvsGITServer_2.png" alt="Git client/server">

---
= data-x='1000' id='distributedvcs2'
## [Distributed Version Control](https://en.wikipedia.org/wiki/Distributed_version_control)

* Local development possible
	* commiting, branching, tagging ...
	* working offline
* Exchange of code with all participants possible - directly

---
= data-x='1000'
## Slides

* [http://url/](http://url/)
* Lizenz: [CC-SA-3.0-DE](https://creativecommons.org/licenses/by-sa/3.0/de/)
* Mail: Jan Wagner <waja@cyconet.org>  


## Credits 

* [SVN Structure](https://upload.wikimedia.org/wikipedia/commons/1/1a/SVN_Server_Client_Structure.png)
* [Git client/server](https://upload.wikimedia.org/wikipedia/commons/a/a3/SVNvsGITServer_2.png)
* [Foo](http://foo.bar) by FooBar
