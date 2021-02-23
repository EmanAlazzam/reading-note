# **Remote Repositories**

In order to collaborate on Git projects, you must interact with remote repositories, versions of a project residing online or on a network.
You can work with multiple repositories, for which you can have read/write or read-only privileges. Teams can use remote repositories to push information to and pull data from.

## **Applying Remote Command**

By running the **git remote** command, you can view the short names, such as “origin,” of all specified remote handles.

By using **git remote -v**, you can view all the remote URLs next to their corresponding short names.

*For Example*: 

_reading-note[main]$ git remote_

_origin_

_reading-note[main]$ git remote -v_

_origin  https://github.com/EmanAlazzam/reading-note.git (fetch)_

_origin  https://github.com/EmanAlazzam/reading-note.git (push)_

## **Fetching**

Fetching entails pulling data that you don’t have from a remote project.

Here is the command format: **git fetch [remote-name]**

## **Pushing**

To push your changes “upstream” for sharing, you would use the following git push command format: **git push [remote-name][branch-name]**.
