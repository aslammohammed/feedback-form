# msp-basic-scriptapp
This boilerplate can be used to develop HTML/CSS/JS script applications for HCL DX Websphere Portal.

### Demo ###

Check the [demo here](http://10.115.81.113:30016/).

### Screenshots ###

<details>
    <summary>Landing page</summary>
    <img src="msp_basic_scriptapp_landing.png" alt="Landing page" />
</details>

### How to get it? ###
Just clone into your machine by running the command

`git clone https://github01.hclpnp.com/software-portal/msp-basic-scriptapp.git`

### Why you should use it? ###
Because of the following reasons (pretty convincing for me, may be for you too),
* **Easy to ZIP it and upload in portal** - Yes!
* **Easy to understand project structure** - Yes!
* **CSS output for production** - Yes!
* **Development server setup done** - Yes!
* **Use SASS for writing styles** - Yes, absolutely possible!
* **Powered by HCL Design System** - Yes!

More details as follows,

| Criteria          | Latest Version  |
| ----------------- | --------------- |
| patron-css-build  | Yes             |
| node-sass         | Yes             |
| npm-run-all       | Yes             |
| live-server       | Yes             |

### How to use it? ###
1. Clone into your machine
2. Install dependency modules/packages with command `npm install`
2. Install `live-server` globally with command `npm install -g live-server`
3. Start the project with command `npm start` and the dev server will run at port `30015`
4. Remove **REMOVE ME and ADD YOUR OWN** block and start adding your own in `index.html`.
4. To upload on the remote portal, just copy all the files except `node_modules`, `sass`, `msp_basic_scriptapp_landing.png`, `package.json` and `package-lock.json`, into a new folder, zip it.
5. Go to the portal and upload the zip file in your particular script application. That's it!

### Issues ###
For any issues, raise in [Issue Tracker](https://github01.hclpnp.com/software-portal/msp-basic-scriptapp/issues).

### Contribution ###

Your contributions to make this boilerplate an awesome one are always welcome!

### TODO ###
Will come up with boilerplates for more complex script applications.
