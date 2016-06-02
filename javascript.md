# JavaScript Notes
JavaScript is a scripting lanaguage which is related in its syntax to Java, and is one of the languages which came out of the legacy left by C. Lots of aspects of the language are different from other languages.

JavaScript is an interpreted language; there is no compile-run cycle because code is executed on the fly. It is a lightweight language, which means that it doesn't need tons of libraries to get going, and is quite small in its memory footprint. It is also a function-first language, which means that functions are able to be passed to other functions as objects, and functions can also be allocated to variables, and other such mechanisms not present in other languages like Java (until recently). Finally it is also object-oriented, although it represents classes somewhat differently than other languages.

Most importantly from a conceptual standpoint, JavaScript is a scripting language, meaning that it operates on some runtime, and it is designed to interact with that runtime for the most part. In the case of this particular language, the runtime is actually the web browser. In a 'normal' scripting language like Python or Ruby, the runtime is the operating system itself; in JavaScript, the runtime is the browser.

What does this look like practically? Well, when a server sends a page in response to a request from a client, the page, sent over http, is ultimately a piece of text. It is delimited and marked-up with tags, but ultimitely it is text. The browser translates this text into a tree of objects; a div element might have several paragraph elements which might contain some svg elements. These elements are translated into objects and those objects make up the DOM tree. This is static; html is a static language. The role (tradidionally) of JavaScript is to interact with the DOM and make it dynamic by changing it on the fly, transforming elements into other elements, inserting new elements and removing elements, that type of thing.


