---
id: command-line
title: Command line
sidebar_label: Command line
---

We have defined some commands in the app's package.json file to help us automatize some actions like generating a new GraphQL schema when their structure change on the server-side, generate typescript type from the Graphql app' schema. Let's explained each command.

```bash
yarn start
```

Help us to start the metro bundler

```bash
yarn test
```

To test components

```bash
yarn test:watch
```

Help to watch for modification files and re-run tests if necessary

```bash
yarn lint
```

For linting our code

```bash
yarn shake-android
```

Help to reload android emulator as needed.

```bash
yarn download-schema
```

Help to download the graphql schema

```bash
yarn generate-type
```

Help to automatically generate the typescript type of the graphql app' schema

```bash
yarn generate
```

Help to generate meta graphql informations to help us use fragments in our graphql's
queries.

```bash
yarn android
```

Help to run android app in a phone or in a android emulator

```bash
yarn ios
```

Help to run ios app.

You can use other commands not specify in the script of the app's package.json file.
Like detox, if you install it globally it will help you, you can modify the detox configuration
in the package.json file and run an e2e test like:

```bash
detox
```
