# kiss-starter: starter boilerplate for the kiss site generator

## Installation

```shell
# Clone this repo
git clone https://github.com/slybridges/kiss-starter.git

# Remove history and start your own git repo
rm -rf .git
git init

# Install dependencies
npm install
```

## Start the development server

```shell
npm start
```

## Make it your own

- Update `kiss.config.js` as needed
- Content sits in the `content/` directory
- Design sits in the `theme/` directory
- Generated site sits in the `public/` directory

## Make a production build

```shell
NODE_ENV=production npm run build
```
