*Enabling the GitHub Integration in the IDE is by far the second easiest way to install and get the latest updates for Echo Speak and Echo Speaks devices.*

---
##### <h5 style="color: #FF6025;">Step 1:</h5>
If you haven't enabled Git integration (one time configuration) under the IDE please visit here for instructions: ***[IDE GitHub Integration Instructions](http://docs.smartthings.com/en/latest/tools-and-ide/github-integration.html)***

**NOTE: Git Integration is not currently available outside of US and UK**

Otherwise Move to Step 2.

---
##### <h5 style="color: #FF6025;">Step 2:</h5>
First, click on the **`Settings`** button at the top of SmartThings IDE page (this will only appear after completing the one-time integration with GitHub)

![](https://tonesto7.github.io/echo-speaks-docs/static/img/GI_ide_settings.jpg)

---
##### <h5 style="color: #FF6025;">Step 3:</h5>
* Click on `Add new repository`.
* Enter the information below:

    | | |
    |:---|---|
    |**Owner:** | tonesto7 |
    |**Name:** | echo-speaks |
    |**Branch:** |  master |
    
    ![](https://tonesto7.github.io/echo-speaks-docs/static/img/GI_add_repo_info.png)


---
##### <h5 style="color: #FF6025;">Step 4:</h5>
* Click on `Save` to close the GitHub Repository Integration page.

---
##### <h5 style="color: #FF6025;">Step 5:</h5>
* Click the **`Update from Repo`** button at the upper-right corner of the IDE

* Click on `echo-speaks (master)` from the drop down menu.
* On the right-hand column labelled New (Only in Github), scroll down to click the apps to install. 
* This will typically be:</p>
`echo-speaks.groovy`

* Check the Publish box and Click the `Execute Update` in the bottom-right corner of the screen. 
* When it's completed syncing, the new apps should now appear in the IDE. If they ever change color, that indicates a new version is available.

**REMINDER!!!:** Remember to Enable OAuth under the NST Manager's App Settings (Instructions Below)

---
##### <h5 style="color: #FF6025;">Step 6:</h5>
Continue to SmartApp Configuration

[Server Configuration](https://tonesto7.github.io/echo-speaks-docs/#/docs/installation/configuration/appConfig "wikilink")