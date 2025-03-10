# Collection of tasks for AX Code

## Description

This repository provides a collection of different tasks to control SIMATIC AX, to make repetitive tasks easier and independent of the CLI.

## Installation

In VSCode all tasks are defined in tasks.json files. It is possible to:
- Use a central tasks.json file (C:\Users\USERNAME\AppData\Roaming\AX Code\User\tasks.json),
- Use a tasks.json file per profile (C:\Users\USERNAME\AppData\Roaming\AX Code\User\profiles\PROFILE-ID\tasks.json),
- Use a tasks.json file in the workspace (Workspace-Directory\.vscode\tasks.json)

More info about tasks in VSCode: https://code.visualstudio.com/docs/editor/tasks

> Note that a workspace-tasks-file can be combined with a central or a profile-specific tasks-file. It is not possible to use a central and a profile-specific tasks-file at the same time.

The provided task files are meant as templates for your own task files. It is up to you how to use them.

### Central tasks.json
If you prefer a central tasks.json file, download the repository and copy the file in the "general" folder to C:\Users\USERNAME\AppData\Roaming\AX Code\User\tasks.json

### Profile-specific tasks.json
Since the tasks differ depending on the workflow you are working in (TIAX Library, TIAX Direct Loading, AX IT-like Engineering), it is recommended to create 3 different profiles in AX, copy the tasks.json files from the different folders in the repository into your profile folders (C:\Users\USERNAME\AppData\Roaming\AX Code\User\profiles\PROFILE-ID\tasks.json).

More info about profiles in VSCode: https://code.visualstudio.com/docs/editor/profiles

### Workspace-specific tasks.json
If you don't want to work with profiles but still want to have different tasks available depending on the workflow you are working in, you can copy the tasks.json from the different folders in the repository into your workspace into \.vscode\tasks.json

This folder/file can also be integrated into your own project templates in order to have them available automatically in every project.

## Using the tasks

When the tasks.json file is placed correcty, you can call the tasks by pressing F1, navigating to "Run Task", and selecting the task you want to run.

We recommend using an extension such as Task Manager, that can be found and installed directly in SIMATIC AX https://marketplace.visualstudio.com/items?itemName=cnshenj.vscode-task-manager
This extension automatically detects all tasks and shows them in an alphabetical list where they can also be run:

![image](https://github.com/user-attachments/assets/2a8da7c2-d953-4967-bdd4-dc09b0969d61)

## Important notes


## Contribution

Thanks for your interest in contributing. Anybody is free to report bugs, unclear documentation, and other problems regarding this repository in the Issues section or, even better, is free to propose any changes to this repository using Merge Requests.
