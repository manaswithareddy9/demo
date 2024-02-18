# Getting Started

Dev Tools:
-------------
* VSCode
	* https://code.visualstudio.com/docs/java/java-tutorial
* Notepad++
* Postman (Http client)

Version control:
----------------
* Git for windows https://git-scm.com/download/win
* https://www.sourcetreeapp.com/enterprise
	* setup ssh
		* Local:
			* cmd
			* ssh-keygen
				* just hit enter till key is generated
				* it will generate public (.pub) & private ssh keys 
			* open sourcetreeapp -> tools -> options 
			* SSH Client Configuration -> SSH Key (private key) -> Ok
		* Github.com:
			* https://github.com/settings/keys
			* New SSH Key
			* paste public SSH key (C:\Users\smana\.ssh)
			* Add SSH Key

Two ways to create new repo's:
------------------------------
1. Create a repo in Github directly (preffered)
	* clone the repo to local 	

2. Commit existing project to git repo
	* Create a repo in Github - e.g. https://github.com/manaswithareddy9/demo
		* git init
		* git add .

		option-1: from sourcetreeapp:
		------------------------------
		* add a commit message and hit commit button

		option-2: from vscode terminal:
		------------------------------- 
		git commit -m "first commit"
		git branch -M main
		git remote add origin https://github.com/manaswithareddy9/demo.git
		git push -u origin main


Java:
-----
* https://spring.io/quickstart
* install maven: https://phoenixnap.com/kb/install-maven-windows


### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/3.2.2/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/3.2.2/maven-plugin/reference/html/#build-image)
