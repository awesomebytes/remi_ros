# REMI library as a ROS package

This is a ROS package to wrap the [REMI](https://github.com/dddomodossola/remi) library, which is meant for:

 Remi is a GUI library for Python applications which transpiles an application's interface into HTML to be rendered in a web browser. This removes platform-specific dependencies and lets you easily develop cross-platform applications in Python!

This library is used for the [web dynamic reconfigure client](https://github.com/awesomebytes/web_dyn_reconf), for example.

Whenever REMI is released in pip/Ubuntu or so this wrapper won't be necessary anymore.

To clone this repository you need to additionally do:

````
git submodule init
git submodule update
````

To download the submodule of the remi package.
