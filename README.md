# eslint-config-tucows
Our JavaScript style

This JS style is our base style for all our modern JS projects. It assumes mixed Node/Browser code and the use of ES6 with Babel. 
It also requires babel-eslint as the parser.

 [Detailed explanation of the rules](https://eslint.org/docs/rules/).
    
## Installation

    npm install --save-dev eslint-config-tucows

Then create an [eslint config file](https://eslint.org/docs/user-guide/configuring) in your project
that contains:

     "extends": [
         "eslint-config-tucows"
     ]

Recomended script line in package.json (This requires npm >= 4)

    "lint": "npx eslint **/*.js --fix"
