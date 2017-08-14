# fixd-server
===

Quickly establish a server for design document, html files generated by axure or omnigraffle, etc.

# Usage
---

```bash
$ npm i -g fixd-server
$ cd ~/Documents/Axure/html
$ fixd-server html
```

On Windows, by default the html files generated by Axure are in `c:\Users\USER\Documents\Axure\html\`. It should be like:
```
html
| - project_1
|   | - index.html
|   | - ...
| - project_2
|   | - index.html
|   | - ...
| - ...
```

# Options
---
Serve at perticular port:
```bash
$ fixd-server html -p 80
```