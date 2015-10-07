
# Bower 
Bower is a package manager for the web.
> Web sites are made of lots of things — frameworks, libraries, assets, utilities, and rainbows. 
> Bower manages all these things for you.
> Bower works by fetching and installing packages from all over, taking care of hunting, finding, downloading, and saving the stuff you’re looking for. (Bower.io) 

## Installing Bower
 Bower is a command line utility. Install it with npm.<br />
  <br />
 `$ npm install -g bower`<br />
 <br />
Depending on how your terminal is setup, you may need to `sudo npm install -g bower`.
[Sudo](https://kb.iu.edu/d/amyi)

*Bower requires node, npm and git.*
## Installing Packages
**Install packages individually** <br />
<br />
`$ bower install <package name>`<br />
<br />
### Install Options
-F, --force-latest: Force latest version on conflict <br/>
-p, --production: Do not install project devDependencies <br/>
-S, --save: Save installed packages into the project’s bower.json dependencies <br/>
-D, --save-dev: Save installed packages into the project’s bower.json devDependencies <br/>
-E, --save-exact: Configure installed packages with an exact version rather than semver <br/>
e.g. `$ bower install <package name> --save` <br/>

**Install multiple packages**<br />
Using the bower.json file list the packages you're using in your project<br />
 ```
 { 
  "name": "app-name", 
  "version": "0.0.1", 
  "dependencies": { 
    "sass-bootstrap": "~3.0.0", 
    "modernizr": "~2.6.2", 
    "jquery": "~1.10.2" 
  },
  "private": true 
}
```
## Sources and Further Reading
* http://bower.io/
* http://blog.teamtreehouse.com/getting-started-bower
* https://css-tricks.com/whats-great-bower/
