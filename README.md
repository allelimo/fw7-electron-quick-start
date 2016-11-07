# fw7-electron-quick-start

fw7 with electron example how to:

1. cloned the electron-quick-start repo 
2. copied the dist folder from fw7 download
3. created the 3 files from get started on fw7 (my-app.js about.html and index.html)
4. added these lines in index.html between 
```
</body> and </html>:
 <!-- fw7-electron quick start -->
  <script>
    // You can also require other files to run in this process
    require('./renderer.js')
  </script>
```
5. edited main.js commentng out the lines:
```
  // Open the DevTools.
  // mainWindow.webContents.openDevTools()
```
6. follow original instructions below to install and start

**Clone and run for a quick way to see an Electron in action.**

This is a minimal Electron application based on the [Quick Start Guide](http://electron.atom.io/docs/latest/tutorial/quick-start) within the Electron documentation.

**Use this app along with the [Electron API Demos](http://electron.atom.io/#get-started) app for API code examples to help you get started.**

A basic Electron application needs just these files:

- `package.json` - Points to the app's main file and lists its details and dependencies.
- `main.js` - Starts the app and creates a browser window to render HTML. This is the app's **main process**.
- `index.html` - A web page to render. This is the app's **renderer process**.

You can learn more about each of these components within the [Quick Start Guide](http://electron.atom.io/docs/latest/tutorial/quick-start).

## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/allelimo/fw7-electron-quick-start
# Go into the repository
cd fw7-electron-quick-start
# Install dependencies
npm install
# Run the app
npm start
```

Learn more about Electron and its API in the [documentation](http://electron.atom.io/docs/latest).

## Other Example Apps

For more example apps, see the
[list of boilerplates](http://electron.atom.io/community/#boilerplates)
created by the awesome electron community.

#### License [CC0 1.0 (Public Domain)](LICENSE.md)

fw7-electron
