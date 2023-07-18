[Live demo on GigHub Pages](https://8observer8.github.io/webgl10-js/rotating-cube-with-playcanvas-and-js/)

[Topic on PlayCanvas forum](https://forum.playcanvas.com/t/solved-how-to-use-playcanvas-with-importmap/32204)

Playgrounds:

- Replit: https://replit.com/@8Observer8/Rotating-cube-with-PlayCanvas-and-JavaScript
- Glitch: https://glitch.com/edit/#!/steady-equal-blossom
- PlayCode: https://playcode.io/1536875
- Plunker: https://plnkr.co/edit/nEchdgd1UQYDClR1

Instruction for building and running the project in debug and release using Rollup:

- Install these packages globally with the command:

> npm i -g http-server rollup uglify-js

- Run http-server in the project directory:

> http-server -c-1

Note. The `-c-1` key allows you to disable caching.

- Start development mode with the following command:

> npm run dev

Note. Rollup will automatically keep track of saving changes to files and build a new index.js file ready for debugging. You can debug your project step by step in the browser by setting breakpoints.

- Go to the browser and type the address: localhost:8080/index.html

- Create a compressed file ready for publishing. Stop development mode, for example, with this command Ctrl + C in CMD, if it was launched before and enter the command:

> npm run release

Note. After this command, Rollup will create a compressed index.js file. Compression is done using the uglify-js package.
