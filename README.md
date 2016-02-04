This repository is a collection of recent experiments I've been working on in three.js.

Three.js is a JavaScript library built on top of the WebGL graphics language.  WebGL is a low level, verbose language used to create graphics in the browser that can be both very performant and very hard to use.  Three.js greatly reduces the amount of boilerplate code you have to write to build rich 3D graphics, and wraps common operations into intuitive constructor functions.  If you're interested in learning three.js, I recently completed two new tutorials on getting started with the three.js library.  You can find them at [loftus.xyz](http://loftus.xyz)

You will find the different simulations in this repo in the examples folder.  To develop and test out the simulations locally, first clone the repo down to your local machine.  

```
git clone https://github.com/MattLoftus/threejs-space-simulations.git
```

To avoid cross-origin errors when using textures(every example in this repo), you will need to host the files on a local server.  I recommend using python simple server or npm live server.  First navigate to the root of the directory, then run the following command.

```
python -m SimpleHTTPServer
```

This will host the folder on port 8000, so you can head over to the browser and type "localhost:8000" into the address bar, and you will see a listing for the directory. If you happen to have a version of python on your machine >= 3.0, you may need to run the following command instead.

```
python2.7 -m SimpleHTTPServer
```

