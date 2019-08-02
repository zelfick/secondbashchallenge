# secondbashchallenge

This repository contains the docker file to build a jekyll service container that can have a volume attached, the idea
is finally run the container dettached with a volume where you can change your code and see the change in the browser.

Use a Jekyll static generator to start a local web server
source code is in this repo
edit files with editor on our host native tools:
You make a change in: /bindmount-sample-1/_posts/2017-03-05-welcome-to-jekyll.markdown
container detects changes with host files and updates web server
tips to start the container: docker port 4000, container path volume:/site
Use the docker image:


remember bind mounts:
https://endava-my.sharepoint.com/:p:/p/jorge_herran/EXTZQOEHW-VJnK5Me67jf00BYMWCJ5ueUFvLnnRIWSvoZw?e=7hWMzR

