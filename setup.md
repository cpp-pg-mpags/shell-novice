---
layout: page
title: Setup
root: .
---

## Download files
You need to download some files to follow this lesson.

1. Start up Visual Studio Code and Docker
2. Go to View -> Command Palette
3. Start to type in "Remote-Containers: Clone Repository in Container Volume", and select this command as soon as it appears
4. Enter the repository name: "MPAGS-CPP-2021/test-setup"
5. Select "Create Unique Volume"
6. Once the dev container has initialised and you can see the content of the cloned repository in the explorer, open a new terminal by going to Terminal -> New Terminal
7. This is the terminal where we will be working. To download the data we need, copy and paste the following command:
```wget {{ page.root }}/data/shell-lesson-data.zip```
8. We now need to unzip so again, copy and paste the following:
```unzip shell-lesson-data.zip```

You're now all ready to go through the material!
