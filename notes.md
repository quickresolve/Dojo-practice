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
