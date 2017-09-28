# Generic Apollo + Next.js stack

Also some things specific to MT Direct 4

Features
- GraphQL/Apollo
    - Organizes and distributes our domain models
    - An implementation of GraphQL
    - (mostly?) transparent bridge for data between front-end and back-end, allowing you to declare what data you need from the model
    - enables Domain Driven Development
    - Realtime capable
    - Efficient batching and cacheing
    - (New direction authors of meteor, the wildly popular full-stack framework .. apollo == modular framework)
- ExpressJS
    - Extensibility (e.g. add ad-hoc Remote Procedure Calls) & UI Server (e.g. add ad-hoc file upload handler)
    - Best ecosystem for plugins or "middlewares"
- ReactJS
    - view layer: declarative, concise & idiomatic
    - Component-Driven Development
    - Best ecosystem for UI components today
    - Interesting community applying it (e.g. GraphQL/Apollo folks)
- Next.js
    - UI framework built on ReactJS
    - Bundles many powerful libraries (e.g. Webpack, Babel) into one minimal-configuration framework
    - Simple, easy to use, well-documented, well support

Choose your own
- Database and or ORM
- CSS/Style framework (recommend semantic-ui-react?)
- Localization (recommend i18next?)

## TODO

- authentication & authorization
- Offline support for Apollo
- Reactive persistent data
- MobX for data reactivity
- reactive session/cookie/localStorage data
- Use all the goodies from apollo-universal-starter-kit
- Go through http://dev.apollodata.com to fine-tune everything
- add mocking & test framework(s)
    - use apollo-test-utils & graphql-tools
    - Jest, enzyme & (for snapshot testing) enzyme-to-json
- add babel config file, webpack config file, next.config.js (easy)
