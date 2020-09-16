# sasswebpack2 (Webpack boilerplate)

Install and run development environment
- `npm install`
- `npm run dev`
- right-click on `dist/index.html` and **Open with Live Server**
- now editing e.g. `sass/styles.scss` or `sass/_variables.scss` will show immediate changes in the browser

Publish at Netlify
- push site to a repository on your GitHub
- create free account at [Netlify](https://netlify.com)
- click **`New site from Git`**
- click **`GitHub`**
- search the name of your repository and click it
- click **`Deploy site`**
	- Base directory: (blank)
	- Build command: `npm run build`
	- Publish directory: `dist`
- click **`Site settings`**
- click **`Change site name`**
- give site a personal name, e.g. `mysite`
- after 2 minutes, go to site in browser or mobile device, e.g. `mysite.netlify.app`
