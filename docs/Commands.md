# RAN! Documentation

## Commands

### create:page
_command:_ ```yarn run create:page``` (or ```npm run create:page```)

It helps to create new page easiest way. After run this command, It will ask some questions and boom! It's ready.

![create:page](https://media.giphy.com/media/l0Iy6nmyS5p7hIAso/giphy.gif)

### create:route
_command:_ ```yarn run create:route``` (or ```npm run create:route```)

Create new route for your pages

### lint
_command:_ ```yarn run lint``` (or ```npm run lint```)

Fix & show lint errors (and prettier infos) automatically

### lint:watch
_command:_ ```yarn run lint:watch``` (or ```npm run lint:watch```)

Watch the changes of graphQL files to show errors and warnings on eslint
**Info:** Basically, There is watcher for js files if you run ```dev``` command. This one is additional command for graphql files.

### dev
_command:_ ```yarn run dev``` (or ```npm run dev```)

Run lint and then open the server on your local on development mode

### dev:next
_command:_ ```yarn run dev:next``` (or ```npm run dev:next```)

Run lint and then open the server on your local on development mode with **Next.js command**

### analyze
_command:_ ```yarn run analyze``` (or ```npm run analyze```)

Analyze the packages and files that you used on your app

### build
_command:_ ```yarn run build``` (or ```npm run build```)

Build the application for Production

## GraphQL Commands

On these commands, RAN is using  [graphql-config](https://github.com/graphcool/graphql-config), [graphql-cli](https://github.com/graphcool/graphql-cli), [graphql-voyager](https://github.com/APIs-guru/graphql-voyager) and [grapql-cli-voyager](https://github.com/graphcool/graphql-cli-voyager). The important thing is that you need to update your [/.graphqlconfig](/.graphqlconfig) file with your real graphql url to work with them. For details info how to work with ```.graphgqlconfig``` file, please check [graphql-config](https://github.com/graphcool/graphql-config).

##### **Important Info**
Don't save secure information in ```.graphqlconfig``` file. Use [Environment variables](/docs/Architecture/environment-variables.md) for that. On RAN boilerplate, We are using hard-coded example graphql url inside of that but It doesn't mean it's secure way.

### graphql:play
_command:_ ```yarn run graphql:play``` (or ```npm run graphql:play```)

It opens the browser to play (or work :) on your graphql server

![graphql:play](https://media.giphy.com/media/xT39Dh0URQoc8IUOxW/giphy.gif)

### graphql:update_schema
_command:_ ```yarn run graphql:update_schema``` (or ```npm run graphql:update_schema```)

Updates your local schema file with updated one from server

### graphql:see_graph
_command:_ ```yarn run graphql:see_graph``` (or ```npm run graphql:see_graph```)

See your graphQL API as a interactive graph
