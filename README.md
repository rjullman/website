# Building the Website

1. Install Hugo and Pygments. There are detailed instructions on [Hugo's website](https://gohugo.io/overview/installing/).
2. Run a Hugo server: 
```
hugo server --theme=beautifulhugo
```
Add the option `--buildDrafts` to publish drafted posts, which is useful when working locally on new content.

3. By default the website will be visible locally at `http://localhost:1313/` (look at the Hugo output).

---

To publish local changes to the website run `./deploy.sh [commit message]`. 
In order for this script to succeed you need write permissions to [rjullman.github.io](https://github.com/rjullman/rjullman.github.io/), which you probably do not have.

If `./deploy.sh` succeeds then the updated site should appear soon on [bobbyullman.com](http://www.bobbyullman.com).
