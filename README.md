# vuepress-demo
A vuepress demo to reproduce vuepress bug

Run 
```bash
yarn run docs:build
```

and you'll see errors in terminal, 

```
(node:2900) UnhandledPromiseRejectionWarning: TypeError: Cannot read property 'catch' of undefined
    at server-bundle.js:13412:23
(Use `node --trace-warnings ...` to show where the warning was created)
(node:2900) UnhandledPromiseRejectionWarning: Unhandled promise rejection. This error originated either by throwing inside of an async function without a catch block, or by rejecting a promise which was not handled with .catch(). To terminate the node process on unhandled promise rejection, use the CLI flag `--unhandled-rejections=strict` (see https://nodejs.org/api/cli.html#cli_unhandled_rejections_mode). (rejection id: 1)
(node:2900) [DEP0018] DeprecationWarning: Unhandled promise rejections are deprecated. In the future, promise rejections that are not handled will terminate the Node.js process with a non-zero exit code.
(node:2900) UnhandledPromiseRejectionWarning: TypeError: Cannot read property 'catch' of undefined
    at server-bundle.js:13412:23
(node:2900) UnhandledPromiseRejectionWarning: Unhandled promise rejection. This error originated either by throwing inside of an async function without a catch block, or by rejecting a promise which was not handled with .catch(). To terminate the node process on unhandled promise rejection, use the CLI flag `--unhandled-rejections=strict` (see https://nodejs.org/api/cli.html#cli_unhandled_rejections_mode). (rejection id: 2)
``