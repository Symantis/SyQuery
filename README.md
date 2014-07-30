SyQuery
=======

Store Angular Partials in JSON for Realtime Stuff

SyQuery is the Javascript Query library for the Symantis "Creator App" (name pending). It allows for the storing of Angular.js Partials and Scss to be stored in JSON on a database such as MongoDB.

Fast Fragging or storing html in JSON has huge speed advantages versus things like InnerHTML, and a lot of times we don't need huge libraries like jQuery for simple injection. In addition it allows for version control and with web sockets the ability for "realtime" development collaboration.

Borrows concepts from HTML2JSON and FastFrag

Instructions

Usage:

```SyQuery.create( { content : "hello world" } );```

creates Document Fragment: `<div>` hello world `</div>`

Usage:

```SyQuery.create('<div> hello world </div>');```

creates JSON: { content : "hello world" }

TODO

*Add In concepts from HTML2JSON to create JSON from HTML

*Add In native calls for SyScribe & Creator App

*Turn SyQuery into an Angular Factory
