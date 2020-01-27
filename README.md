# Service Workers in a nutshell

## What is a service worker?
Think of it as a middle layer between client and server, or as a browser extension your site can install on the user's browser. It has its own lifecycle and methods, and it sits between your site and the server, ready to intercept all site requests.

Depending on your needs, service workers allow your site to...
- have an offline experience
- use push notifications
- be installed as an app
- more efficiently and proactively cache resources

A few things to keep in mind before moving on. Service workers...
- run in the Worker context, which means they have no access to the `window`, the DOM, or `localStorage`
- are fully aynchronous, which means synchronous APIs can't be used inside them
- require HTTPS, for obvious security reasons

Recommended reading:
- [Service worker mindset](https://web.dev/service-worker-mindset/) by Dave Geddes
- [Measuring the Real-World Performance Impact of Service Workers](https://developers.google.com/web/showcase/2016/service-worker-perf) by Philip Walton

## Lifecycle
## Intercepting Requests
## Caching
