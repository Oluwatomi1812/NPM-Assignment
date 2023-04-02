1) Event Loop is responsible for executing code and handling tasks. It is what makes javaScript asynchronous.

2)THE PHASES OF THE EVENT LOOP;

    Timers: This phase executes callbacks using timers. The Callback are executed after a period of time. For example, setTimeout, SetInterval and setImmediate.

    Pending CallBacks: This phase handles I/O callbacks. For examples, writeFile() and readFile().

    Idle/Prepare: During this phase, the event loop performs internal operations of any callbacks.

    Poll: This is the phase where all
    Check: In this phase, all setImmediate()  added in the poll phase are executed

    Close: If all timers and I/O calls are done, the loop closes.

3) Keeping Code small and easy to read.
    Handling Errors.
    Using Async/Await syntax to make the code more readable and maintainable.
    Focusing on the quality of the code.

4) NPM is a library and registry for javaScript. NPM has command line toold to help you install various packages and manage their dependencies. 
To initialize a package in NPM use the " npm init" command

5)To run a script in package.json file, use the "npm run argument" command with the name of the script as the argument .e.g npm run prettier.

