Cloud Commander
===============

Cloud Commander - two-panels file manager, totally writed on js.
<a href=http://cloudcmd.cloudfoundry.com/ title="Cloud Commander Demo">Demo</a>

Benefits
===============
- full browser compatibility (ie6+,chrome,safari,opera,firefox);
- responsible design
- one full page loading, and then just one-time json-dir-listings loading
(with refresh opportunity).
- caching readed directorys to localStorage
- key binding
- support of working in limited mode if js is disabled
- automated minification client js-files and onstart-reading Cloud manager files on server starting.

Cloud Commander using all benefits of js, so if js is disabled,
we moves to limited mode.

Limited-mode features:
===============
- only 1 panel
- no keybinding
- no local caching
- full loading of all web page(with styles, js-scripts, html-page etc).