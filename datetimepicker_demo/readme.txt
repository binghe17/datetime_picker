#API   https://xdsoft.net/jqplugins/datetimepicker/
#github  https://github.com/xdan/datetimepicker에서 다운로드 (#npm install jquery-datetimepicker)
npm install -g bower
bower install

--------------------------
Install:

1. Install `bower` globally with `npm install -g bower`.
2. Run `npm install`. npm will look at `package.json` and automatically install the necessary dependencies. 
3. Run `bower install`, which installs front-end packages defined in `bower.json`.

Notice: If you use Bower v1.5.2, you will get error: `The "main" field cannot contain minified files`
You can regress to version 1.3.12

1. `npm uninstall bower -g`
2. `npm install -g bower@1.3.12`
