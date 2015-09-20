_reload-firefox_
================

TODO


Usage
-----

### [Enable remote debugging](https://developer.mozilla.org/en-US/docs/Tools/Remote_Debugging/Debugging_Firefox_Desktop#Enable_remote_debugging)

In [`about:config`](about:config):

```
devtools.chrome.enabled = true
devtools.debugger.prompt-connection = false
devtools.debugger.remote-enabled = true
```

### [Start the debugger server](https://developer.mozilla.org/en-US/docs/Tools/Remote_Debugging/Debugging_Firefox_Desktop#Start_the_debugger_server)

This can be done manually, by giving the `listen` command in the [developer toolbar](https://developer.mozilla.org/en-US/docs/Tools/GCLI), or  automatically, by specifying the `--start-debugger-server` option on the command-line.

On OS X:

```
open -a /Applications/Firefox.app --args --start-debugger-server
```


About
-----

Made by [Miëtek Bak](https://mietek.io/).  Published under the [MIT X11 license](LICENSE.md).
