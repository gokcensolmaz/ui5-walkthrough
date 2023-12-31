﻿# ui5-walkthrough

## Initialization of Project

1. We add the webapp folder to the directory in the project. Then, we run the codes one by one on the Terminal. You may receive an error when you want to run the `ui5 init` code without the webapp folder.

  ```
  npm init --yes
  ui5 init 
  ```
> **Note**
If you receive the following error while using the `ui5` command, you can bypass the Security Execution Process with the following code.
<img src="https://github.com/gokcensolmaz/ui5-walkthrough/assets/61111670/53269482-2ce8-43ac-b599-184199249f98" alt="Screenshot of Security Execution Process Error.">

```
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```

2. We create a `manifest.json` file under the webapp folder. We paste the content of the descriptor file shared on [SAP Help](https://help.sap.com/doc/saphelp_nw75/7.5.5/en-US/3a/9babace121497abea8f0ea66e156d9/content.htm?no_cache=true) into the `manifest.json` file.

3. We run the following code on the terminal and we are now ready to write our project.
```
ui5 use sapui5@latestlatest
```
4. We will create  `index.html` file. We run the following code in our terminal to publish our code via ui5.

```
ui5 serve
```
