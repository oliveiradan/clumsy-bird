Clumsy Bird
===========

This is an sample project to demonstrate how to create/deploy a Node JS application using Shipped interface.

## Quick start

### Setup a project
- Login to [Shipped-CiscoCloud](http://ciscocloud.github.io/)
- Create a new project.
- ![](https://github.com/CiscoCloud/clumsy-bird/blob/Deploy/images/createproject.png)

- Select appropriate service type. for example for this project its Express JS
- ![](https://github.com/CiscoCloud/clumsy-bird/blob/Deploy/images/selectservice.png)
- Provide service name ( You can use existing git hub repository like as shown below)
- ![](https://github.com/CiscoCloud/clumsy-bird/blob/Deploy/images/selectrepo.png)
- Build Project 
  - Build Newly created project.
  - ![](https://github.com/CiscoCloud/clumsy-bird/blob/Deploy/images/buildproject.png)
  - For Local build follow on screen command line instruction.
  - ![](https://github.com/CiscoCloud/clumsy-bird/blob/Deploy/images/buildlocal.png)
  - Wait until local build setup is completed 
  - ![](https://github.com/CiscoCloud/clumsy-bird/blob/Deploy/images/buildstatus.png)
  - Commit local build with empty commit just to know shipped that local build worked fine and this will trigger drone build for your project.
  for eg. cd 'SampleProj/clumsy_bird'; git commit --allow-empty -m 'Setup Shipped' && git push origin master
  - ![](https://github.com/CiscoCloud/clumsy-bird/blob/Deploy/images/pushbuild.png)

### Deploy
- You can find available builds under Deploy tab. for example. 
- ![](https://github.com/CiscoCloud/clumsy-bird/blob/Deploy/images/selectbuild.png)
- Select desired build associated with each commit.
- Create a new environment eg. Dev, Sagging, Beta, or Production 
- ![](https://github.com/CiscoCloud/clumsy-bird/blob/Deploy/images/newenv.png)
- Click on deploy button to deply selected build.
- ![](https://github.com/CiscoCloud/clumsy-bird/blob/Deploy/images/deploy.png)
