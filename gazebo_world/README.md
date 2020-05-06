# gazebo_world

This is the first project in the nanodegree. Created a world with a custom made building and a non-functioning robot model.
The world file also includes a custom plugin that prints out a welcome message when the world is loaded.

Build the project on your own system by navigating into the build directory and doing:

```
cmake ../ && make
```

Also, you have to add the plugin path to the Gazebo environment variable by doing this:

```
export GAZEBO_PLUGIN_PATH=${GAZEBO_PLUGIN_PATH}:/path/to/build
```
