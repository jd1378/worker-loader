# worker-loader-es6
this is the same as [worker loader module](https://github.com/webpack-contrib/worker-loader) for webpack Except that it uses `export default` instead of `module.exports =` for loading the worker file.

use this if you are getting `Cannot assign to read only property 'exports' of object '#<Object>'` error

I needed a quick fix so I made this package, all the credit goes to original contributors.
