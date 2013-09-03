# android-studio-project-example

Since I didn't find any clear resource about how to create a project on IntelliJ IDEA Android Studio able to be shared by a team withou any problems (in a **just clone, open the project on the IDE** approach), I created this example, just to make the things clear.

## Important things to bare in mind

* **The `.gitignore` file**: there is a lot of controversy about it, if you research which one is the "correct" way. Some will say to ignore `.idea` folder and `*.iml` files and import the project, but that didn't worked for me, and I tested with all possible ways (correct me, if I missed something). To make it work, I've included them, and then, I can just clone the project and open it.

* The original folder, where the first dev created the project MATTERS! If you clone it in a folder with a different name, the IDE will recognize it as a **new module**. So, to avoid this **new module madness**, a good convention is to match the name of repository with the name of the project folder, when creating it, and to warn all the devs to clone it on a folder with the same name.

**That's it! ** If you wanna try, just clone this repo and try to open and build the project on your android studio.

