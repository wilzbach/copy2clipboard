copy2clipboard
==============

Allows the to copy to the user's clipboard without using any flash. You can populate now 
any content into the clipboard when the user presses "CTRL-C".

It basically attaches to the "CTRL" key events and creates a hidden, selected textarea. 
Inspired by Trello.

Install
-------

```
npm install copy2clipboard --save
```

Use
-----

```
var ClipBoard = require("./clipboard.js");
var clip = new ClipBoard();
clip.set("fancy clipboard"); // set any content
```

Test it
-------



License
-------

MIT
