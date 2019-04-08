 is a progressive and performant **Javascript Framework** used for building interfaces (UIs) and frontend applications.

### Why Vue?
- Makes creating UIs and frontend applications much easier.
- Less of a leraning curve than other frameworks.
- Extremely fast and lightweight.
- Build powerful SPA apps (Single Page Applications).
- Virtual DOM.
- Growing in the industry.

### Nice to know before learning Vue.
- Javascript Fundamentals (of course...).
- ES6 module syntax.
- High order array methods (forEach, map, filter).
- Arrow functions.
- Fetch API and Promises.

### What will we de doing?

We will be making a to-do app (as usual). The final look is supposed to be as following:

![ToDo App](https://i.imgur.com/mZBg4nC.png)

Where each element listed will be a separate component.

### How will we get Vue going?

We could use something like a CDN for this, but in this case we'll use Vue-CLI, which include some very useful tools:

- Includes Babel, TypeScript, ESLint, PostCSS and more.
- Includes dev server with hot reload.
- Includes Vue UI tool to manage your app in a graphical interface.

## Installation

- We'll need to install Vue-CLI, for that we'll need a decent version of Node and npm for that. So go ahead and install them.
- I would also suggest install the Vue.js devtools extension for Chrome. This will help with the component structure and much more.

Then we need to install Vue-CLI (cli.vuejs.org/guide/installation.html). To install it globally, using npm just use the following:

```bash
npm install -g @vue/cli
```

After this, check the version with `vue --version`.

### Using Vue

To actually create an application we can use the command line or Vue Ui. To cdreate via command line we can use:

```bash
vue create application-name
```

This will launch the wizard for a new appliocation called "application-name". Using `npm run serve` will run the application using the in-built dev server.

To do it via UI, we use the 

`vue ui` command. It will start the graphic interface in port 8000. This is basically a project manager. We can create new projects or import projects. Also see the already created projects. To serve a project using Vue UI, go to that project page, select the `Tasks` option, `Serve` and then `Run Task`. Not only it runs the application on port 8080, it also shows us different stats on the project, which is damn cool!



Based on [this video](https://www.youtube.com/watch?v=Wy9q22isx3U).
