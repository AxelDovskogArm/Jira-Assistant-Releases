# <h1>Jira Assistant</h1> #

<p align="center">
    <img src="images/logo.png" height="200px" width="200px"/>
</p>

A tool meant to assist users of Jira by expanding upon the features of JiraGantt.

## <h3>Installation</h3> ##

Releases can be found under 'Releases' (Deployments / Releases in the menu to the left) here in Gitlab, where there are further installation instructions and information about the different releases. Alternatively, the application can be downloaded by clicking on the links below.

Note that the links will take you to Artifactory, where you will be asked to login. Specify "Azure" and log in with your Arm credentials.

### <h5>Windows:</h5> ###
- <a target="_blank" href="https://eu-west-1.artifactory.aws.arm.com/ui/native/jira-assistant.Jira-Assistant/jira-assistant-installer.exe">Download installer</a>

Simply install and run the installer, then follow the provided steps.


### <h5>Alternatives:</h5> ###
If installing the application doesn't work, it can still be run by cloning this git repository and (with Node.js installed and added to the PATH) running
```
npm i
```
Followed by
```
npm run start
```
(If the browser tools open, change the value of DEV_MODE at the top of index.js to false)

## <h3>Additional Features (compared with JiraGantt)</h3> ##

- Users can upload a <b>JiraGantt URL</b> in order to automatically configure the application (filters, projects, etc.). Otherwise they can manually add these values in the configurations menu (top right) and the 'Edit Projects' menu (button on the top of the screen).

- In the Views tab, by clicking on views (elements in the bar to the left of the screen) they will be toggled, allowing for a <b>more customizable and less cluttered</b> workspace. Additionally, users now have access to the <b>Requirements summary</b> and there have been some adjustments to the way colors and loadings are handled.

- In the Personal tab, users can (by adding a token and username in the configurations) see issues assigned to them in a table or a grid. They can also create tasks, expand issues (to, for example, view comments) and more.</b>.

- Users can <b>create filters</b> through the application

- Users can <b>log time</b> spent on issues, as well as <b>add comments</b> to issues and update issue statuses.

## <h3>Bugs</h3> ##

Please report bugs by contacting me through axel.dovskog@arm.com
