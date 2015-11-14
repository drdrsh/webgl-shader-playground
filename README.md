# WebGL Shader Playground
Real-time WebGL shader editor based on [WebGL boilerplate by Paul Irish](https://github.com/paulirish/webgl-boilerplate) .
This work is very similar to [SHDR](http://shdr.bkcore.com), However, I made the code available to allow the user more freedom of experimenting with uniforms and attributes as they see fit.

# How to use
You will need to have [nodejs](https://nodejs.org/en/), [npm](https://www.npmjs.com/) and [bower](http://bower.io/) installed.
After that clone the repository to your local system.

    git clone https://github.com/drdrsh/webgl-shader-playground.git



navigate to the path where the code resides and run

    bower install

This will install all the dependancies, afterwards you can just drag index.html into your browser and start playing with your shaders.

To modify the initaliztion and rendering code open **index.html** and modify **onInitGL()** and **onRenderGL()** functions to your needs.