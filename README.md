
## Using npm to install external packages for your js apps
- https://docs.npmjs.com/ 

## Lab steps
- Initialize your npm package with `npm init`
    - This Creates a package.json with your information, details about external packages go here.
- Install express 
- Add express https://expressjs.conpmm/en/starter/hello-world.html to your app.js
- Add 2 more custom routes
- Add a route with a custom query parameter
- Install pm2 with `npm i pm2 -g`
- Now run your app using pm2 by createing a process json file
    - http://pm2.keymetrics.io/docs/usage/application-declaration/
    - `pm2 start <filename>`
- Create a second express app with a single enpoint that returns "hello world", or some other data of your choice
- install axios with `npm install axios`
- create a route that that makes a get request to the second app and concatiates it with a user provided parameter to return one single string
- Have them print some information about the request, and watch it with `pm2 monit`
- Finally, with a partner, switch secondary servers so that requests going to partner A's main server uses partner B's secondary server. You will need to know eachotehrs ip addresses.