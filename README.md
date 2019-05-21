# soft_skill
this Repo could be refereed for soft skill quarries

What are the job need to be done 
identify the job to be done for your customer.
challenging orthodoxies.
(questioning orthodoxies )


typescript concepts on may 16th 2019..........

tsc --help 
>tsc test.ts
>tsc test.ts --out output-script.js           
 (it will change test.ts file to output-script.js meaning we are changing js file name)
>tsc test.ts --out output-script.js --watch  
 (this command will watch the changes in test.ts and automatically update the same on output-script.js when we ll save)


creating configuration file 
>tsc --init
(ts compiler will generate sample tsconfig.json file)


  "outDir": "./out*",    /* Redirect output structure to the directory. */
  (js file after compilation will save to out folder (here i have created out folder to save all java script file)
  
   "noEmitOnError": true,  /* Do not emit outputs. */
     (if there is error in typescript file it ll not genrate js file after compilation)

npm install ___ --save
npm install lodash --save  
its genrates node_modules and contains->lodash(lodash will contain all .js files)
loaddash will register to package.json


npm install @types/lodash --save-dev
 @type will genrate  lodash for TS
