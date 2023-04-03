# GithubActions

Checkout action

- https://github.com/marketplace/actions/checkout

- Quick examples / cheat sheet https://vladilen.notion.site/Github-Actions-2023-1b847dd7e3d74718a1faaf69970ff8bd

- https://stackoverflow.com/questions/58139175/running-actions-in-another-directory

- https://github.com/marketplace/actions/cache

03, 04 screens added
Worked faster without cached dependencies.
Need to research this

https://github.com/actions/cache/blob/main/examples.md#node---npm
https://www.youtube.com/watch?v=BDQivAobxKA&ab_channel=CoderDave

From chat GPT:

> This step uses the npm ci command to install the project dependencies. This command is preferred over npm install in production environments because it installs the exact versions of packages specified in package-lock.json.

Finally: thi article helped with caching: https://dev.to/mattpocockuk/how-to-cache-nodemodules-in-github-actions-with-yarn-24eh
I was using a wrong path for cache
