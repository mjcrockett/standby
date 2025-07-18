# html-serve
Simple server to serve a simple html document

Be sure you have node.js installed on 
your machine, cd into the directory for 
html-serve and run the command: 
>**npm install**

You can verify that npm was installed correctly if you
see a folder called *node_modules* on the same level as 
*index.html* and the other files in this repo.

To run the server, simply run the script found in the 
*package.json*:
>**node server.js**

Once the server is running, open a browser and go to 
*localhost:8080* to see the index.html. Now you can use
that page to test javascript, css, html or whatever.

On a side note, if you want to run this in the static AWS S3 bucket
page (https://s3page.sandbox.docservices.foc.zone/break.html), you need
to change all the instances of 'resources' to 'Resources/standby-resources' 
and change index.html to break.html.