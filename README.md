#YUI

## How to make npm package react typescript components library

1. $ npm init -y
2. $ npm install react typescript @types/react --save-dev
3. $ npx tsc --init
4. $ npm install rollup @rollup/plugin-node-resolve @rollup/plugin-typescript @rollup/plugin-commonjs rollup-plugin-dts --save-dev
5. $ npm run rollup
6. $ git init
7. $ echo "node_modules" >> .gitignore
8. $ git add .
9. $ git commit -m "begin commit"
10. $ git branch -M main
11. $ git remote add origin https://github.com/ucupio/yui.git
12. $ nano ~/.npmrc
13. $registry=https://registry.npmjs.org/
14. $@YOUR_GITHUB_USERNAME:registry=https://npm.pkg.github.com/
15. //npm.pkg.github.com/:\_authToken=YOUR_AUTH_TOKEN
16. npm publish
