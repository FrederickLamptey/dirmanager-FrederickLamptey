# Purpose Of app
This is a typescript command-line app that is built with node.js and commander.js. Commander.js is a library that provides a lot of features that enable you to build a command-line interface. Node.js supports commander.js by providing libraries such as Chalk and Figlet that complement Commander.js CLIs to make them look visually appealing.

In this app, command-line commands such as ascertaining version number, making of directory, list files and directories, etc were created.

![Screenshot (318)](https://user-images.githubusercontent.com/102755255/200687917-66f83bb4-27ed-4f65-a608-8c518c983c69.png)

To use any of the above commands to get an oupt, you run it with the "dirmanager" tag attached to it. Example:

![Screenshot (319)](https://user-images.githubusercontent.com/102755255/200688876-aa3af5b0-8590-4a6e-9cbe-55ed8bea07dc.png)
In the above example, you would realize that the command "l" was used. This listed all the files and directories available in the main directory. However,if you notice really well, you would realize that the output came with an art. This art was made possible or was powered by the figlet package that was imported in the index.ts. Hence, whenever any of the commands is run, the art comes with the output.
