Walking through a TODO application tutorial from [scotch.io](http://scotch.io/tutorials/javascript/creating-a-single-page-todo-app-with-node-and-angular) as a refresher on the MEAN stack.

Notes
---

* Automatically restart server when files change: By default, node will not monitor for file changes after your server has been started. This means you’d have to shut down and start the server every time you made a file change. This can be fixed with nodemon. To use: install nodemon globally **npm install -g nodemon**. Start your server with **nodemon server.js** now. Smooth sailing from there.