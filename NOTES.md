## Init node project
npm init -y

## Install typescript as dev dependency
npm install typescript --save-dev

##TypeScript has Implicit, Explicit, and Ambient types. Ambient types are types that get added to the global execution scope. Since we're using Node, it would be good if we could get type safety and auto-completion on the Node apis
npm install @types/node --save-dev

## Init TypeScript
npx tsc --init

## Install yarn as a package manager
npm install yarn

## Install dev dependencies
yarn add typescript ts-node-dev @types/express @types/config pino-pretty @types/nodemailer @types/lodash @types/jsonwebtoken -D

## Install Express
yarn add express@5

## Install dependencies
yarn add mongoose @typegoose/typegoose config argon2 pino dayjs nanoid nodemailer lodash jsonwebtoken dotenv zod