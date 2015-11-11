# parafeed
A library for an embedded user interface deigned for ease of use for the programmer as well as the end-user. It embeds a shell in the application which can be configured for an interactive session or a non-interactive command line interface. The shell can be customized via command-line arguments or via environment variables. The user can access the shell via simple 'arg=value1,value2,...' command-line arguments (useful when writing pipelines). In an interactive session, the list of parameters are displayed as a list of 'arg=<Value(s)>' on the screen (see [examples] (https://github.com/sanbee/parafeed/blob/wiki/UserDoc.md#example)) and the user can set/reset/save/load/edit parameter values (see [User Commands](https://github.com/sanbee/parafeed/blob/wiki/UserDoc.md#user-commands)). Command line editing, min-matching, TABBED completion, parameter hiding/exposing based on the value of other parameter is also supported (see the [full user manual](https://github.com/sanbee/parafeed/blob/wiki/UserDoc.md)). 

For full documentation, go [here](https://github.com/sanbee/parafeed/blob/wiki/UserDoc.md)
