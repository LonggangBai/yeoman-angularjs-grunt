# yeoman-angularjs

This project is generated with [yo angular generator](https://github.com/yeoman/generator-angular)
version 0.15.1.

## Build & development

Run `grunt` for building and `grunt serve` for preview.

## Testing

Running `grunt test` will run the unit tests with karma.

# create  gruntfile.js or Gruntfile.coffee
grunt-init gruntfile


$ grunt -help

longgangbai@DESKTOP-7M5P35U /E/as-ticket-workspace/yeoman-angularjs-grunt
$ grunt --help
Grunt: The JavaScript Task Runner (v0.4.5)

Usage
 grunt [options] [task [task ...]]

Options
    --help, -h  Display this help text.
        --base  Specify an alternate base path. By default, all file paths are
                relative to the Gruntfile. (grunt.file.setBase) *
    --no-color  Disable colored output.
   --gruntfile  Specify an alternate Gruntfile. By default, grunt looks in the
                current or parent directories for the nearest Gruntfile.js or
                Gruntfile.coffee file.
   --debug, -d  Enable debugging mode for tasks that support it.
       --stack  Print a stack trace when exiting with a warning or fatal error.
   --force, -f  A way to force your way past warnings. Want a suggestion? Don't
                use this option, fix your code.
       --tasks  Additional directory paths to scan for task and "extra" files.
                (grunt.loadTasks) *
         --npm  Npm-installed grunt plugins to scan for task and "extra" files.
                (grunt.loadNpmTasks) *
    --no-write  Disable writing files (dry run).
 --verbose, -v  Verbose mode. A lot more information output.
 --version, -V  Print the grunt version. Combine with --verbose for more info.
  --completion  Output shell auto-completion rules. See the grunt-cli
                documentation for more information.

Options marked with * have methods exposed via the grunt API and should instead
be specified inside the Gruntfile wherever possible.

Available tasks
         serve  Compile then start a connect web server
        server  DEPRECATED TASK. Use the "serve" task instead
          test  Alias for "clean:server", "wiredep", "concurrent:test",
                "postcss", "connect:test", "karma" tasks.
         build  Alias for "clean:dist", "wiredep", "useminPrepare",
                "concurrent:dist", "postcss", "ngtemplates", "concat",
                "ngAnnotate", "copy:dist", "cdnify", "cssmin", "uglify",
                "filerev", "usemin", "htmlmin" tasks.
       default  Alias for "newer:jshint", "newer:jscs", "test", "build" tasks.

Tasks run in the order specified. Arguments may be passed to tasks that accept
them by using colons, like "lint:files". Tasks marked with * are "multi tasks"
and will iterate over all sub-targets if no argument is specified.

The list of available tasks may change based on tasks directories or grunt
plugins specified in the Gruntfile or via command-line options.

For more information, see http://gruntjs.com/

# create  bower.json  
bower init 
#create package.json 
npm init 

longgangbai@DESKTOP-7M5P35U /E/as-ticket-workspace/yeoman-angularjs-grunt
$ npm --help

Usage: npm <command>

where <command> is one of:
    access, add-user, adduser, apihelp, author, bin, bugs, c,
    cache, completion, config, ddp, dedupe, deprecate, dist-tag,
    dist-tags, docs, edit, explore, faq, find, find-dupes, get,
    help, help-search, home, i, info, init, install, issues, la,
    link, list, ll, ln, login, logout, ls, outdated, owner,
    pack, prefix, prune, publish, r, rb, rebuild, remove, repo,
    restart, rm, root, run-script, s, se, search, set, show,
    shrinkwrap, star, stars, start, stop, t, tag, test, tst, un,
    uninstall, unlink, unpublish, unstar, up, update, upgrade,
    v, verison, version, view, whoami

npm <cmd> -h     quick help on <cmd>
npm -l           display full usage info
npm faq          commonly asked questions
npm help <term>  search for help on <term>
npm help npm     involved overview

Specify configs in the ini-formatted file:
    C:\Users\longgangbai\.npmrc
or on the command line via: npm <command> --key value
Config info can be viewed via: npm help config

npm@2.7.4 c:\devTools\nodejs\node_modules\npm


#create bower.json
 bower init 
longgangbai@DESKTOP-7M5P35U /E/as-ticket-workspace/yeoman-angularjs-grunt
$ bower help

Usage:

    bower <command> [<args>] [<options>]
Commands:

    cache                   Manage bower cache
    help                    Display help information about Bower
    home                    Opens a package homepage into your favorite browser
    info                    Info of a particular package
    init                    Interactively create a bower.json file
    install                 Install a package locally
    link                    Symlink a package folder
    list                    List local packages - and possible updates
    login                   Authenticate with GitHub and store credentials
    lookup                  Look up a package URL by name
    prune                   Removes local extraneous packages
    register                Register a package
    search                  Search for a package by name
    update                  Update a local package
    uninstall               Remove a local package
    unregister              Remove a package from the registry
    version                 Bump a package version
Options:

    -f, --force             Makes various commands more forceful
    -j, --json              Output consumable JSON
    -l, --loglevel          What level of logs to report
    -o, --offline           Do not hit the network
    -q, --quiet             Only output important information
    -s, --silent            Do not output anything, besides errors
    -V, --verbose           Makes output more verbose
    --allow-root            Allows running commands as root
    -v, --version           Output Bower version
    --no-color              Disable colors
See 'bower help <command>' for more information on a specific command.




