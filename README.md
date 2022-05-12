#how to make a package in php
Wonder how to make a package?
- create a public repository on Github
- create a composer.json in the root of your project
- use ```composer init``` and walk through the steps
- write a simple and useful readme like above
- write a package:
- best practise: create a src directory in your project root
- open up the composer.json and add:
```
"autoload": {
    "psr-4": {
      "Toolbox\\": "src/Toolbox/"
}
```
- register at packagist 
