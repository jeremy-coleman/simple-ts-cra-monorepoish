### What 
setup to make use of the default node_modules resolution and tsc -b


## tsc build flags
 --verbose
 --force
 --watch

## suggested use
yarn start -> then open ~/src/node_modules/@coglite/common/src/themes/default.ts
change the default mui theme from blue[900] to blue[800] and see built-in create react app HMR working properly.
folder structure is kinda wierd but it has to be this way to get watchers working without overriding cra's default config
this works with nextjs also