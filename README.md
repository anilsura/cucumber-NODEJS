# cucumber-NODEJS

mkdir testcases

cd testcases

npm init --yes

npm install cucumber --save-dev



mkdir features

cd features

mkdir steps

cd ../



vi cucumber.js

 and paste below content



module.exports = {

  default: `--format-options '{"snippetInterface": "synchronous"}'`

}





cd features/steps

vi stepdef.js



and paste below



const assert = require('assert');

const { Given, When, Then } = require('cucumber');





From: “test”: “echo \”Error: no test specified\ “”

To: “test” : “cucumber-js” and save the file. 
