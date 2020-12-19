# simssjs
SIMpler ServerSide JavaScript

## Background
There are quite a few server-side JavaScript runtimes available. However all seem to bring in the same client-side complications, such as single main thread, asynchronous http calls, promises etc. There is a need to simplify server-side JavaScript into something that is much simpler and more procedural than event-driven.

## What is this project about
This project is get server-side JavaScript back to the simpler syntax of ES5 standards, plus provide critical server-side capabilities such as asynchronous execution of functions, HTTP handlers and clients, plus database handling (at least RDBMS to start with).
The project will provide the ability for users to write JS programs adhering to the good old ES5 syntax, perhaps with underscore.js support, while providing critical extensions on top of a golang backbone.
