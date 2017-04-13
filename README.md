svelte-quickstart

What is Svelte?

If you've ever built a JavaScript application,the chances are you've encountered - or at least heard of
- frameworks like React,Angular,Vue and Ractive.Like Svelte, these tools all share a goal of making
it easy to build slick interactive user interfaces.

But Svelte has a crucial difference: rather than interpreting your application code at run time, your app
is converted into ideal JavaScript at build time. That means you don't pay the performance cost of the 
framework's abstractions, or incur a penalty when your app first loads.

Compiling

svelte compile --format iife HelloWorld.html > HelloWorld.js