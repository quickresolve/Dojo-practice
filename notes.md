#Dojo

##Getting Started

To get started load a dojo.js script in your web page.

<script src="//ajax.googleapis.com/ajax/libs/dojo/1.10.4/dojo/dojo.js"
            data-dojo-config="async: true"></script>

Dojo uses Asynchronous Module Definition (AMD) format allowing completely modular web application development.

Two global functions included in Dojo's AMD loader: require & define

require enables you to load modules and use them, while define allows you to define your own modules.  

##How it works

AMD loaders operate asynchronously, and in JavaScript asynchronous operation is implemented with callbacks. The AMD loader will automatically load all sub-dependencies for a requested module, so only the modules that you need to use directly should be in your dependency list.


The AMD define function accepts similar parameters to the require function - an array of module ids and a callback function. The AMD loader stores the return value of the callback function as the module's value, so any other code that loads the module with require (or define) will receive a reference to the return value of the defining module.
