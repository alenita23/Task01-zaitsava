# Task01-zaitsava
First task for Evolution Bootcamp 2022

## Steps how to install the project and run the tests.
Once your tests have been written, proceed with the following actions:
1) Run the command 'npm install --save-dev babel-jest @babel/core @babel/preset-env'
2) Add file 'babel.config.cjs' with the following content:

   ```
   module.exports = {
   presets: [
     [
       '@babel/preset-env',
       {
         targets: {
           node: 'current'
         }
       }
     ]
   ]
 };
```
3) In 'package.json' file you should also add the following information:

```json
  "jest": {
    "moduleFileExtensions": [
      "js"
    ]
  },
  "type": "module"
```
4) Run 'yarn test' to check the result
