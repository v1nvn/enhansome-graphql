# awesome-graphql [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 437,262 | 🐛 69 | 📅 2026-01-28 ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/chentsulin/awesome-graphql/awesome_bot.yml?logo=githubactions\&label=Awesome%20Bot)

> Awesome list of GraphQL

If you want to contribute to this list (please do), send me a pull request.

## Table of Contents

<!-- MarkdownTOC depth=4 -->

* [awesome-graphql  ](#awesome-graphql--)
  * [Table of Contents](#table-of-contents)
  * [Specifications](#specifications)
  * [Foundations](#foundations)
  * [Communities](#communities)
  * [Meetups](#meetups)
  * [Implementations](#implementations)
    * [JavaScript/TypeScript](#javascripttypescript)
      * [Clients](#clients)
        * [Frontend Framework Integrations](#frontend-framework-integrations)
          * [React](#react)
      * [Servers](#servers)
        * [Databases & ORMs](#databases--orms)
        * [PubSub](#pubsub)
      * [Custom Scalars](#custom-scalars)
      * [Type](#type)
      * [Miscellaneous](#miscellaneous)
      * [JavaScript Examples](#javascript-examples)
      * [TypeScript Examples](#typescript-examples)
    * [Ruby](#ruby)
      * [Ruby Examples](#ruby-examples)
    * [PHP](#php)
      * [PHP Examples](#php-examples)
    * [Python](#python)
      * [Python Examples](#python-examples)
    * [Java](#java)
      * [Custom Scalars](#custom-scalars-1)
      * [Java Examples](#java-examples)
    * [Kotlin](#kotlin)
      * [Kotlin Examples](#kotlin-examples)
    * [C/C++](#cc)
    * [Go](#go)
      * [Go Examples](#go-examples)
    * [Scala](#scala)
      * [Scala Examples](#scala-examples)
    * [.NET](#net)
      * [.NET Examples](#net-examples)
    * [Elixir](#elixir)
      * [Elixir Examples](#elixir-examples)
    * [Haskell](#haskell)
    * [SQL](#sql)
    * [Lua](#lua)
    * [Elm](#elm)
    * [Clojure](#clojure)
      * [Clojure Examples](#clojure-examples)
    * [Swift](#swift)
    * [OCaml](#ocaml)
    * [Android](#android)
      * [Android Examples](#android-examples)
    * [iOS](#ios)
      * [iOS Examples](#ios-examples)
    * [ClojureScript](#clojurescript)
    * [ReasonML](#reasonml)
    * [Dart](#dart)
    * [Rust](#rust)
      * [Rust Examples](#rust-examples)
    * [D (dlang)](#d-dlang)
    * [R (Rstat)](#r-rstat)
    * [Julia](#julia)
    * [Crystal](#crystal)
    * [Ballerina](#ballerina)
      * [Ballerina Samples](#ballerina-samples)
  * [Tools](#tools)
    * [Tools - Editors & IDEs & Explorers](#tools---editors--ides--explorers)
    * [Tools - Testing, Prototyping & Mocking](#tools---testing-prototyping--mocking)
    * [Tools - Security](#tools---security)
    * [Tools - Browser Extensions](#tools---browser-extensions)
    * [Tools - Docs](#tools---docs)
    * [Tools - Editor Plugins](#tools---editor-plugins)
    * [Tools - Miscellaneous](#tools---miscellaneous)
  * [Databases](#databases)
  * [Services](#services)
    * [CDN](#cdn)
    * [CMS](#cms)
  * [Books](#books)
  * [Videos](#videos)
  * [Podcasts](#podcasts)
  * [Style Guides](#style-guides)
  * [Blogs](#blogs)
    * [Blogs - Security](#blogs---security)
  * [Posts](#posts)
  * [Tutorials](#tutorials)
  * [License](#license)

<!-- /MarkdownTOC -->

<a name="spec" />

## Specifications

* [GraphQL](https://github.com/graphql/graphql-spec) ⭐ 14,782 | 🐛 208 | 🌐 JavaScript | 📅 2026-02-11 - Working draft of the specification for GraphQL.
* [GraphQL over HTTP](https://github.com/graphql/graphql-over-http) ⭐ 420 | 🐛 30 | 🌐 JavaScript | 📅 2026-02-05 - Working draft of "GraphQL over HTTP" specification.
* [OpenCRUD](https://github.com/opencrud/opencrud) ⭐ 388 | 🐛 35 | 📅 2022-07-21 - OpenCRUD is a GraphQL CRUD API specification for databases.
* [GraphQL Relay](https://relay.dev/docs/guides/graphql-server-specification/) - Relay-compliant GraphQL server specification.
* [Apollo Federation](https://www.apollographql.com/docs/federation/federation-spec/) - Apollo Federation specification
* [GraphQXL](https://gabotechs.github.io/graphqxl/) - GraphQXL is an extension of the GraphQL language with some additional features that help creating big and scalable server-side schemas.
* [GraphQL Scalars](https://www.graphql-scalars.com/) - hosts community defined custom Scalar specifications for use with @specifiedBy.

<a name="foundation" />

## Foundations

* [GraphQL Foundation](https://graphql.org/foundation/) - GraphQL Foundation under the Linux Foundation

<a name="community" />

## Communities

* [Discord - GraphQL](https://discord.graphql.org/) - Official GraphQL.org discord channel.
* [GraphQL Weekly](https://www.graphqlweekly.com/) - A weekly newsletter highlighting resources and news from the GraphQL community.
* [Apollo GraphQL Community](https://community.apollographql.com/) - Connect with other developers and share knowledge about every part of the Apollo GraphQL platform.
* [Discord - Reactiflux](http://join.reactiflux.com/) - Join `#help-graphql` on the Reactiflux Discord server.
* [Facebook](https://www.facebook.com/groups/795330550572866/) - Group for discussions, articles and knowledge sharing.
* [X](https://x.com/search?q=%23GraphQL) - Use the hashtag `#graphql`.
* [StackOverflow](https://stackoverflow.com/questions/tagged/graphql) - Questions and answers. Use the tag `graphql`.
* [GraphQL APIs](https://github.com/APIs-guru/graphql-apis) ⭐ 4,645 | 🐛 1 | 📅 2024-09-26 - A collective list of public GraphQL APIs.
* [/r/GraphQL](https://www.reddit.com/r/graphql/) - A Subreddit for interesting and informative GraphQL content and discussions.

<a name="meetup" />

## Meetups

* [Relay Meetup](https://relaymeetup.com/) - A global, online meetup on Relay, the GraphQL client.
* [Amsterdam](https://www.meetup.com/Amsterdam-GraphQL-Meetup/)
* [Bangalore](https://www.meetup.com/graphql-bangalore/)
* [Berlin](https://www.meetup.com/graphql-berlin/)
* [Buenos Aires](https://www.meetup.com/es-ES/GraphQL-BA/)
* [Copenhagen](https://www.meetup.com/Copenhagen-GraphQL-Meetup-Group/)
* [Dallas-Fort Worth](https://www.meetup.com/DFW-GraphQL-Meetup/)
* [Hamburg](https://www.meetup.com/GraphQL-Hamburg/)
* [London](https://www.meetup.com/GraphQL-London/)
* [Melbourne](https://www.meetup.com/GraphQL-Melbourne/)
* [Munich](https://www.meetup.com/GraphQL-Munich/)
* [New York City](https://www.meetup.com/GraphQL-NYC/)
* [San Francisco](https://www.meetup.com/GraphQL-SF/)
* [Seattle](https://www.meetup.com/Seattle-GraphQL/)
* [Sydney](https://www.meetup.com/GraphQL-Sydney/)
* [Tel Aviv](https://www.meetup.com/GraphQL-TLV/)
* [Wrocław](https://www.meetup.com/GraphQL-Wroclaw/)
* [Singapore](https://www.meetup.com/GraphQL-SG/)
* [Zurich](https://www.meetup.com/GraphQL-Zurich/)

<a name="impl" />

## Implementations

<a name="js" />

### JavaScript/TypeScript

* [graphql-js](https://github.com/graphql/graphql-js) ⭐ 20,330 | 🐛 160 | 🌐 TypeScript | 📅 2026-02-11 - A reference implementation of GraphQL for JavaScript.
* [graphql-jit](https://github.com/zalando-incubator/graphql-jit) ⭐ 1,081 | 🐛 30 | 🌐 TypeScript | 📅 2026-01-20 - GraphQL execution using a JIT compiler.
* [Gra*fast*](https://grafast.org) - a cutting edge planning and execution engine for GraphQL.

#### Clients

* [apollo-client](https://github.com/apollographql/apollo-client) ⭐ 19,725 | 🐛 429 | 🌐 TypeScript | 📅 2026-02-13 - A fully-featured, production ready caching GraphQL client for every UI framework and GraphQL server.
* [aws-amplify](https://github.com/aws-amplify/amplify-js) ⭐ 9,590 | 🐛 475 | 🌐 TypeScript | 📅 2026-02-13 - A client library developed by Amazon for caching, analytics and more that includes a way to fetch GraphQL queries.
* [graphql-request](https://github.com/prisma-labs/graphql-request) ⭐ 6,118 | 🐛 44 | 🌐 TypeScript | 📅 2025-12-15 - A minimal GraphQL client for Node and browsers.
* [graphqurl](https://github.com/hasura/graphqurl) ⭐ 3,377 | 🐛 44 | 🌐 JavaScript | 📅 2025-02-13 - curl for GraphQL with autocomplete, subscriptions and GraphiQL. Also a dead-simple universal javascript GraphQL client.
* [graphql-zeus](https://github.com/graphql-editor/graphql-zeus) ⭐ 1,974 | 🐛 54 | 🌐 TypeScript | 📅 2025-12-20 - GraphQL Zeus creates autocomplete client library for `JavaScript` or `TypeScript` which provides autocompletion for strongly typed queries.
* [gqty](https://github.com/gqty-dev/gqty) ⭐ 1,033 | 🐛 51 | 🌐 TypeScript | 📅 2026-02-12 - A No GraphQL client for TypeScript
* [genql](https://github.com/remorses/genql) ⭐ 963 | 🐛 9 | 🌐 TypeScript | 📅 2026-02-01 - Type safe TypeScript client for any GraphQL API.
* [typescript-graphql-request](https://graphql-code-generator.com/docs/plugins/typescript-graphql-request) - Use GraphQL Request as a fully typed SDK.

##### Frontend Framework Integrations

* [vue-apollo](https://github.com/vuejs/vue-apollo) ⭐ 6,057 | 🐛 275 | 🌐 TypeScript | 📅 2026-02-03 - Apollo/GraphQL integration for VueJS.
* [apollo-angular](https://github.com/kamilkisiela/apollo-angular) ⭐ 1,515 | 🐛 24 | 🌐 TypeScript | 📅 2025-12-01 - A fully-featured, production ready caching GraphQL client for Angular and every GraphQL server.
* [svelte-apollo](https://github.com/timhall/svelte-apollo) ⭐ 951 | 🐛 33 | 🌐 TypeScript | 📅 2023-08-03 - Svelte integration for Apollo GraphQL.
* [sveltekit-kitql](https://github.com/jycouet/kitql) ⭐ 452 | 🐛 13 | 🌐 TypeScript | 📅 2026-02-13 - A set of tools, helping you building efficient apps in a fast way with SvelteKit and GraphQL.
* [apollo-elements](https://github.com/apollo-elements/apollo-elements) ⭐ 423 | 🐛 1 | 🌐 TypeScript | 📅 2026-01-01 - GraphQL web components that work in any frontend framework.
* [ember-apollo-client](https://github.com/ember-graphql/ember-apollo-client) ⭐ 281 | 🐛 28 | 🌐 JavaScript | 📅 2025-08-20 - An ember-cli addon for Apollo Client and GraphQL.

###### React

* [relay](https://github.com/facebook/relay) ⭐ 18,931 | 🐛 805 | 🌐 Rust | 📅 2026-02-13 - Relay is a JavaScript framework for building data-driven React applications.
* [urql](https://github.com/FormidableLabs/urql) ⭐ 8,935 | 🐛 35 | 🌐 TypeScript | 📅 2026-02-03 - A simple caching GraphQL client for React.
* [graphql-hooks](https://github.com/nearform/graphql-hooks) ⭐ 1,888 | 🐛 8 | 🌐 TypeScript | 📅 2026-01-26 - Minimal hooks-first GraphQL client with caching and server-side rendering support.
* [@gqty/react](https://github.com/gqty-dev/gqty) ⭐ 1,033 | 🐛 51 | 🌐 TypeScript | 📅 2026-02-12 - A No GraphQL client for TypeScript
* [mst-gql](https://github.com/mobxjs/mst-gql) ⭐ 688 | 🐛 89 | 🌐 JavaScript | 📅 2024-09-03 - Bindings for mobx-state-tree and GraphQL.
* [micro-graphql-react](https://github.com/arackaf/micro-graphql-react) ⭐ 533 | 🐛 22 | 🌐 JavaScript | 📅 2024-06-22 - A lightweight utility for adding GraphQL to React. components. Includes simple caching and uses GET requests that could additionally be cached through a service-worker.
* [react-apollo](https://www.apollographql.com/docs/react/) - The core @apollo/client library provides built-in integration with React.

#### Servers

* [apollo-server](https://github.com/apollographql/apollo-server) ⭐ 13,945 | 🐛 78 | 🌐 TypeScript | 📅 2026-02-10 - Spec-compliant and production ready JavaScript GraphQL server that lets you develop in a schema-first way. Built for Express, Connect, Hapi, Koa, and more.
* [graphql-yoga](https://github.com/prisma-labs/graphql-yoga) ⭐ 8,479 | 🐛 133 | 🌐 TypeScript | 📅 2026-02-11 - Fully-featured GraphQL Server with focus on easy setup, performance and great developer experience.
* [mercurius](https://github.com/mercurius-js/mercurius) ⭐ 2,470 | 🐛 64 | 🌐 JavaScript | 📅 2026-02-09 - GraphQL plugin for Fastify.
* [koa-graphql](https://github.com/chentsulin/koa-graphql) ⭐ 841 | 🐛 6 | 🌐 TypeScript | 📅 2023-01-24 - GraphQL Koa Middleware.
* [graphql-helix](https://github.com/contrawork/graphql-helix) ⚠️ Archived - A highly evolved GraphQL HTTP Server.
* [modus](https://github.com/hypermodeinc/modus) ⚠️ Archived - Serverless runtime based on WebAssembly that delivers auto-generated GraphQL APIs.
* [pylon](https://github.com/getcronit/pylon) ⭐ 362 | 🐛 28 | 🌐 TypeScript | 📅 2026-02-13 - Write full-feature APIs with just functions. No more boilerplate code, no more setup. Just write functions and deploy.
* [gql](https://github.com/deno-libs/gql) ⭐ 203 | 🐛 0 | 🌐 TypeScript | 📅 2026-01-20 - Universal GraphQL HTTP middleware for Deno.
* [graphitejs](https://github.com/graphitejs/server) ⭐ 121 | 🐛 16 | 🌐 JavaScript | 📅 2026-02-12 - Framework NodeJS for GraphQL.
* [hapi-graphql](https://github.com/SimonDegraeve/hapi-graphql) ⭐ 113 | 🐛 8 | 🌐 JavaScript | 📅 2018-02-22 - Create a GraphQL HTTP server with Hapi.
* [graphql-api-koa](https://github.com/jaydenseric/graphql-api-koa) ⭐ 52 | 🐛 1 | 🌐 JavaScript | 📅 2022-11-06 - GraphQL Koa middleware that implements GraphQL.js from scratch and supports native ESM.
* [hapi-plugin-graphiql](https://github.com/rse/hapi-plugin-graphiql) ⭐ 21 | 🐛 4 | 🌐 CSS | 📅 2020-09-03 - HAPI plugin for GraphiQL integration.
* [graphql-koa-scripts](https://github.com/ryanhs/graphql-koa-scripts) ⚠️ Archived - GraphQL Koa 1 file simplified. usefull for quick test

##### Databases & ORMs

* [join-monster](https://github.com/acarl005/join-monster) ⭐ 2,698 | 🐛 31 | 🌐 JavaScript | 📅 2025-08-06 - A GraphQL-to-SQL query execution layer for batch data fetching.
* [graphql-sequelize](https://github.com/mickhansen/graphql-sequelize) ⭐ 1,892 | 🐛 1 | 🌐 JavaScript | 📅 2022-11-16 - Sequelize helpers for GraphQL.
* [graphql-bookshelf](https://github.com/brysgo/graphql-bookshelf) ⭐ 184 | 🐛 38 | 🌐 JavaScript | 📅 2023-01-11 - Some help defining GraphQL schema around BookshelfJS models.

##### PubSub

* [graphql-ably-pubsub](https://github.com/ably-labs/graphql-ably-pubsub) ⭐ 7 | 🐛 1 | 🌐 TypeScript | 📅 2022-09-13 - Ably PubSub implementation for GraphQL to publish mutation updates and subscribe to the result through a subscription query.

#### Custom Scalars

* [graphql-scalars](https://github.com/Urigo/graphql-scalars) ⭐ 1,937 | 🐛 47 | 🌐 TypeScript | 📅 2026-02-12 - A library of custom GraphQL Scalars for creating precise type-safe GraphQL schemas.

#### Type

* [graphql-code-generator](https://github.com/dotansimha/graphql-code-generator) ⭐ 11,216 | 🐛 624 | 🌐 TypeScript | 📅 2026-02-12: GraphQL code generator with flexible support for custom plugins and templates like TypeScript (frontend and backend), React Hooks, resolvers signatures and more.
* [type-graphql](https://github.com/19majkel94/type-graphql) ⭐ 8,094 | 🐛 114 | 🌐 TypeScript | 📅 2026-02-13 - Create GraphQL schema and resolvers with TypeScript, using classes and decorators!
* [graphql-nexus](https://github.com/graphql-nexus/nexus) ⭐ 3,427 | 🐛 255 | 🌐 TypeScript | 📅 2023-11-19 - Code-First, Type-Safe, GraphQL Schema Construction.
* [gql.tada](https://github.com/0no-co/gql.tada) ⭐ 2,910 | 🐛 26 | 🌐 TypeScript | 📅 2025-11-12 - GraphQL document authoring library, inferring the result and variables types of GraphQL queries and fragments in the TypeScript type system.
* [pothos](https://github.com/hayes/pothos) ⭐ 2,573 | 🐛 61 | 🌐 TypeScript | 📅 2026-02-11 - Pothos is a plugin based GraphQL schema builder for typescript. It makes building graphql schemas in typescript easy, fast and enjoyable.
* [garph](https://github.com/stepci/garph) ⭐ 1,318 | 🐛 27 | 🌐 TypeScript | 📅 2024-03-01 - Garph is full-stack framework for building type-safe GraphQL APIs in TypeScript.
* [gqloom](https://github.com/modevol-com/gqloom) ⭐ 86 | 🐛 8 | 🌐 TypeScript | 📅 2026-02-11 - GQLoom is a GraphQL weaver for TypeScript/JavaScript that weaves GraphQL schema and resolvers using [Valibot](https://github.com/fabian-hiller/valibot) ⭐ 8,422 | 🐛 137 | 🌐 TypeScript | 📅 2026-02-05, [Zod](https://github.com/colinhacks/zod) ⭐ 41,838 | 🐛 242 | 🌐 TypeScript | 📅 2026-02-08, or [Yup](https://github.com/jquense/yup) ⭐ 23,685 | 🐛 240 | 🌐 TypeScript | 📅 2026-02-12.
* [graphql-to-type](https://github.com/lkster/graphql-to-type) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2024-01-21 - GraphQL query parser written entirely in TypeScript's type system for creating interfaces based on provided query
* [fast-graphql](https://github.com/idurar/fast-graphql) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2023-06-11 - Graphql Tools to Structure, Combine Resolvers and Merge Schema Definitions for Node.js, Next.Js and Graphql Apollo server

#### Miscellaneous

* [graphql-tools](https://github.com/apollographql/graphql-tools) ⭐ 5,423 | 🐛 162 | 🌐 TypeScript | 📅 2026-02-14 - Tool library for building and maintaining GraphQL-JS servers.
* [graphql-shield](https://github.com/maticzav/graphql-shield) ⭐ 3,576 | 🐛 107 | 🌐 TypeScript | 📅 2026-02-12 - A library that helps creating a permission layer for a graphql api.
* [graphql-mesh](https://github.com/urigo/graphql-mesh) ⭐ 3,485 | 🐛 221 | 🌐 TypeScript | 📅 2026-02-13 - use GraphQL query language to access data in remote APIs that don't run GraphQL (and also ones that do run GraphQL).
* [schemathesis](https://github.com/schemathesis/schemathesis) ⭐ 3,045 | 🐛 41 | 🌐 Python | 📅 2026-02-10 - Runs arbitrary queries matching a GraphQL schema to find server errors.
* [graphql-tag](https://github.com/apollographql/graphql-tag) ⭐ 2,339 | 🐛 100 | 🌐 TypeScript | 📅 2024-01-25 - A JavaScript template literal tag that parses GraphQL queries.
* [graphql-cli](https://github.com/urigo/graphql-cli) ⭐ 2,020 | 🐛 47 | 🌐 TypeScript | 📅 2026-02-05 - A command line tool for common GraphQL development workflows.
* [graphql-ws](https://github.com/enisdenjo/graphql-ws) ⭐ 1,855 | 🐛 10 | 🌐 TypeScript | 📅 2026-01-27 - Coherent, zero-dependency, lazy, simple, GraphQL over WebSocket Protocol compliant server and client.
* [graphql-relay-js](https://github.com/graphql/graphql-relay-js) ⭐ 1,546 | 🐛 24 | 🌐 TypeScript | 📅 2025-10-02 - A library to help construct a graphql-js server supporting react-relay.
* [graphql-modules](https://github.com/Urigo/graphql-modules) ⭐ 1,329 | 🐛 56 | 🌐 TypeScript | 📅 2026-02-13 - Separate GraphQL server into smaller, reusable parts by modules or features.
* [eslint-plugin-graphql](https://github.com/apollographql/eslint-plugin-graphql) ⭐ 1,216 | 🐛 100 | 🌐 JavaScript | 📅 2026-02-12 - An ESLint plugin that checks your GraphQL strings against a schema.
* [graphql-compose](https://github.com/graphql-compose/graphql-compose) ⭐ 1,212 | 🐛 85 | 🌐 TypeScript | 📅 2025-01-11 - Tool which allows you to construct flexible graphql schema from different data sources via plugins.
* [graphql-config](https://github.com/kamilkisiela/graphql-config) ⭐ 1,198 | 🐛 31 | 🌐 TypeScript | 📅 2026-02-12 - One configuration for all your GraphQL tools (supported by most tools, editors & IDEs).
* [WunderGraph Cosmo](https://github.com/wundergraph/cosmo) ⭐ 1,164 | 🐛 127 | 🌐 TypeScript | 📅 2026-02-13 - The Open-Source GraphQL Federation Solution with Full Lifecycle API Management for (Federated) GraphQL. Schema Registry, composition checks, analytics, metrics, tracing and routing.
* [graphql-middleware](https://github.com/maticzav/graphql-middleware) ⭐ 1,150 | 🐛 42 | 🌐 TypeScript | 📅 2026-01-19 - Split up your GraphQL resolvers in middleware functions.
* [sofa](https://github.com/Urigo/sofa) ⭐ 1,114 | 🐛 41 | 🌐 TypeScript | 📅 2026-02-12 - Generate REST API from your GraphQL API.
* [graphql-go-tools](https://github.com/wundergraph/graphql-go-tools) ⭐ 815 | 🐛 38 | 🌐 Go | 📅 2026-02-13 - A graphQL Router / API Gateway framework written in Golang, focussing on correctness, extensibility, and high-performance. Supports Federation v1 & v2, Subscriptions & more.
* [GraphQL Constraint Directive](https://github.com/confuser/graphql-constraint-directive) ⭐ 577 | 🐛 44 | 🌐 JavaScript | 📅 2026-02-13 - Allows using @constraint as a directive to validate input data. Inspired by Constraints Directives RFC and OpenAPI
* [graphql-armor](https://github.com/Escape-Technologies/graphql-armor) ⭐ 569 | 🐛 29 | 🌐 TypeScript | 📅 2026-02-12 - An instant security layer for production GraphQL Endpoints.
* [graphql-let](https://github.com/piglovesyou/graphql-let) ⭐ 453 | 🐛 64 | 🌐 TypeScript | 📅 2026-02-02 - A webpack loader to import type-protected codegen results directly from GraphQL documents
* [graphql-live-query](https://github.com/n1ru4l/graphql-live-query) ⭐ 442 | 🐛 52 | 🌐 TypeScript | 📅 2026-02-12 - Realtime GraphQL Live Queries with JavaScript.
* [graphback](https://github.com/aerogear/graphback) ⚠️ Archived - Framework and CLI to add a GraphQLCRUD API layer to a GraphQL server using data models.
* [graphql-normalizr](https://github.com/monojack/graphql-normalizr) ⭐ 197 | 🐛 0 | 🌐 JavaScript | 📅 2024-02-15 - Normalize GraphQL responses for persisting in the client cache/state.
* [graphql-toolkit](https://github.com/ardatan/graphql-toolkit) ⭐ 166 | 🐛 0 | 📅 2020-05-25 - A set of utils for faster development of GraphQL tools (Schema and documents loading, Schema merging and more).
* [goctopus](https://github.com/Escape-Technologies/goctopus) ⭐ 124 | 🐛 3 | 🌐 Go | 📅 2023-11-21 - an incredibly fast GraphQL discovery & fingerprinting toolbox.
* [GraphVinci](https://github.com/Comcast/graphvinci) ⭐ 77 | 🐛 6 | 🌐 JavaScript | 📅 2023-04-25 - An interactive schema visualizer for GraphQL APIs.
* [babel-plugin-graphql](https://github.com/ooflorent/babel-plugin-graphql) ⚠️ Archived - Babel plugin that compile GraphQL tagged template strings.
* [graphqlgate](https://github.com/oslabs-beta/GraphQL-Gate) ⭐ 57 | 🐛 14 | 🌐 TypeScript | 📅 2022-08-20 - A GraphQL rate-limiting library with query complexity analysis for Node.js
* [microfiber](https://github.com/anvilco/graphql-introspection-tools) ⭐ 37 | 🐛 7 | 🌐 JavaScript | 📅 2024-01-29 - Query and manipulate GraphQL introspection query results in useful ways.
* [supertest-graphql](https://github.com/alexstrat/supertest-graphql) ⭐ 34 | 🐛 12 | 🌐 TypeScript | 📅 2023-01-24 - Extends [supertest](https://github.com/visionmedia/supertest) ⭐ 14,311 | 🐛 178 | 🌐 JavaScript | 📅 2026-01-21 to easily test a GraphQL endpoint
* [graphql-shield-generator](https://github.com/omar-dulaimi/graphql-shield-generator) ⭐ 10 | 🐛 0 | 🌐 TypeScript | 📅 2025-08-22 - Emits a GraphQL Shield from your GraphQL schema.
* [graphql-sunset](https://github.com/sophiabits/graphql-sunset) ⭐ 7 | 🐛 0 | 🌐 TypeScript | 📅 2024-08-11 - Quickly and easily add support for the `Sunset` header to your GraphQL server, to better communicate upcoming breaking changes.
* [Validator.js Wrapper Directive](https://github.com/ktutnik/graphql-directive/tree/master/packages/validator) ⭐ 4 | 🐛 1 | 🌐 TypeScript | 📅 2023-04-09 - A comprehensive list of validator directive wraps Validator.js functionalities
* [load-gql](https://github.com/KunalSin9h/load-gql) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2023-10-10 - A tiny, zero dependency GraphQL schema loader from files and folders.

<a name="js-example" />

#### JavaScript Examples

* [Next.js TypeScript and GraphQL Example](https://github.com/zeit/next.js/tree/canary/examples/with-typescript-graphql) ⭐ 137,654 | 🐛 3,334 | 🌐 JavaScript | 📅 2026-02-14 - A type-protected GraphQL example on Next.js running [graphql-codegen](https://graphql-code-generator.com/) under the hood
* [React Starter Kit](https://github.com/kriasoft/react-starter-kit) ⭐ 23,486 | 🐛 8 | 🌐 TypeScript | 📅 2026-02-09 - front-end starter kit using React, Relay, GraphQL, and JAM stack architecture.
* [F8 App 2017](https://github.com/fbsamples/f8app) ⚠️ Archived - Source code of the official F8 app of 2016, powered by React Native and other Facebook open source projects.
* [RAN Toolkit](https://github.com/sly777/ran) ⭐ 2,207 | 🐛 88 | 🌐 JavaScript | 📅 2026-01-24 - Production-ready toolkit/boilerplate with support for GraphQL, SSR, Hot-reload, CSS-in-JS, caching, and more.
* [NAPERG](https://github.com/alan345/naperg) ⭐ 1,324 | 🐛 2 | 🌐 TypeScript | 📅 2026-02-11 - Fullstack Boilerplate GraphQL. Made with React & Prisma + authentication & roles.
* [SWAPI GraphQL Wrapper](https://github.com/graphql/swapi-graphql) ⭐ 1,065 | 🐛 26 | 🌐 JavaScript | 📅 2025-12-04 - A GraphQL schema and server wrapping SWAPI.
* [Relay TodoMVC](https://github.com/taion/relay-todomvc) ⭐ 158 | 🐛 40 | 🌐 JavaScript | 📅 2026-02-12 - Relay TodoMVC with routing.
* [Apollo React example for Github GraphQL API](https://github.com/katopz/react-apollo-graphql-github-example) ⚠️ Archived - Usage Examples Apollo React for Github GraphQL API with create-react-app.
* [Apollo Client documentation](https://www.apollographql.com/docs/react) - Documentation and example for building GraphQL apps using apollo client.
* [Apollo Server tools documentation](https://www.apollographql.com/docs/apollo-server/) - Documentation, tutorial and examples for building GraphQL server and connecting to SQL, MongoDB and REST endpoints.
* [GraphQL StackBlitz Starter](https://stackblitz.com/fork/graphql) – A live, editable demo spinning up in about 2 seconds and running in a browser.
* [VulcanJS](http://vulcanjs.org) - The full-stack React+GraphQL framework

<a name="ts-example" />

#### TypeScript Examples

* [Node.js API Starter](https://github.com/kriasoft/nodejs-api-starter) ⭐ 3,974 | 🐛 9 | 🌐 TypeScript | 📅 2024-11-10 - Yarn v2 based monorepo template (code-first GraphQL API, PostgreSQL, PnP, Zero-install, serverless).
* [Next.js Apollo TypeScript Starter](https://github.com/borisowsky/nextjs-apollo-ts-starter) ⭐ 274 | 🐛 4 | 🌐 TypeScript | 📅 2026-01-21 - Next.js starter project focused on developer experience.
* [GraphQL Starter](https://github.com/cerino-ligutom/GraphQL-Starter) ⭐ 113 | 🐛 9 | 🌐 TypeScript | 📅 2026-02-11 - A boilerplate for TypeScript + Node Express + Apollo GraphQL APIs.
* [Next.js Advanced Graphql Crud MongoDB Starter](https://github.com/idurar/starter-advanced-graphql-crud-next-js-mongodb) ⭐ 31 | 🐛 7 | 🌐 TypeScript | 📅 2023-06-11 - Starter Generic CRUD with Advanced Apollo Graphql server with Next.js and Mongodb (TypeScript)
* [Mocked Managed Federation - Apollo Server 3](https://github.com/setchy/apollo-server-3-mocked-federation) ⚠️ Archived - An example of how to mock a managed federation Supgraph using Apollo Server 3.x
* [Mocked Managed Federation - Apollo Server 4](https://github.com/setchy/apollo-server-4-mocked-federation) ⚠️ Archived - An example of how to mock a managed federation Supgraph using Apollo Server 4.x

<a name="rb" />

### Ruby

* [graphql-ruby](https://github.com/rmosolgo/graphql-ruby) ⭐ 5,429 | 🐛 76 | 🌐 Ruby | 📅 2026-02-09 - Ruby implementation of Facebook's GraphQL.
* [graphql-batch](https://github.com/Shopify/graphql-batch) ⭐ 1,437 | 🐛 15 | 🌐 Ruby | 📅 2026-02-09 - A query batching executor for the graphql gem.
* [agoo](https://github.com/ohler55/agoo) ⭐ 925 | 🐛 2 | 🌐 C | 📅 2025-09-24 - Ruby web server that implements Facebook's GraphQL.
* [GQLi](https://github.com/contentful-labs/gqli.rb) ⭐ 209 | 🐛 11 | 🌐 Ruby | 📅 2022-09-08 - A GraphQL client and DSL. Allowing to write queries in native Ruby.
* [graphql-auth](https://github.com/o2web/graphql-auth) ⭐ 26 | 🐛 11 | 🌐 Ruby | 📅 2023-02-06 - A JWT auth wrapper working with devise.

<a name="rb-example" />

#### Ruby Examples

* [agoo-demo](https://github.com/ohler55/agoo/tree/develop/example/graphql) ⭐ 925 | 🐛 2 | 🌐 C | 📅 2025-09-24 - Use of the Agoo server to demonstrate a simple GraphQL application.
* [rails-devise-graphql](https://github.com/zauberware/rails-devise-graphql) ⭐ 285 | 🐛 12 | 🌐 Ruby | 📅 2023-01-19 - A rails 6 boilerplate with devise, graphql & JWT auth.
* [github-graphql-rails-example](https://github.com/github/github-graphql-rails-example) ⚠️ Archived - Example Rails app using GitHub's GraphQL API.
* [graphql-ruby-demo](https://github.com/rmosolgo/graphql-ruby-demo) ⭐ 215 | 🐛 4 | 🌐 Ruby | 📅 2017-11-21 - Use graphql-ruby to expose a Rails app.
* [relay-rails-blog](https://github.com/gauravtiwari/relay-rails-blog) ⭐ 138 | 🐛 4 | 🌐 Ruby | 📅 2017-03-06 - A graphql, relay and standard rails application powered demo weblog.
* [relay-on-rails](https://github.com/nethsix/relay-on-rails) ⭐ 43 | 🐛 0 | 🌐 Ruby | 📅 2015-10-30 - Barebones starter kit for Relay application with Rails GraphQL server.
* [to\_eat\_app](https://github.com/jcdavison/to_eat_app) ⭐ 13 | 🐛 0 | 🌐 JavaScript | 📅 2016-08-02 - A sample graphql/rails/relay application with a related 3-part article series.

<a name="php" />

### PHP

* [graphql-php](https://github.com/webonyx/graphql-php) ⭐ 4,709 | 🐛 53 | 🌐 PHP | 📅 2026-02-11 - A PHP port of GraphQL reference implementation.
* [wp-graphql](https://github.com/wp-graphql/wp-graphql) ⭐ 3,772 | 🐛 123 | 🌐 PHP | 📅 2026-02-12 - GraphQL API for WordPress.
* [lighthouse](https://github.com/nuwave/lighthouse) ⭐ 3,479 | 🐛 133 | 🌐 PHP | 📅 2026-02-11 - A PHP package that allows to serve a GraphQL endpoint from your Laravel application.
* [graphql-laravel](https://github.com/rebing/graphql-laravel) ⭐ 2,211 | 🐛 11 | 🌐 PHP | 📅 2026-02-02 - Laravel wrapper for Facebook's GraphQL.
* [siler](https://github.com/leocavalcante/siler) ⚠️ Archived - Plain-old functions providing a declarative API for GraphQL servers with Subscriptions support.
* [overblog/graphql-bundle](https://github.com/overblog/GraphQLBundle) ⭐ 793 | 🐛 132 | 🌐 PHP | 📅 2026-01-29 - This bundle provides tools to build a complete GraphQL server in your Symfony App. Supports react-relay.
* [graphqlite](https://github.com/thecodingmachine/graphqlite) ⭐ 572 | 🐛 38 | 🌐 MDX | 📅 2026-01-25 - Framework agnostic library that allows you to write GraphQL server by annotating your PHP classes.
* [graphql-relay-php](https://github.com/ivome/graphql-relay-php) ⭐ 271 | 🐛 3 | 🌐 PHP | 📅 2023-10-20 - Relay helpers for webonyx/graphql-php implementation of GraphQL.
* [jerowork/graphql-schema-builder](https://github.com/jerowork/graphql-attribute-schema) ⭐ 16 | 🐛 0 | 🌐 PHP | 📅 2026-01-15 - Easily build your GraphQL schema for webonyx/graphql-php using PHP attributes instead of large configuration arrays.
* [graphql-request-builder](https://github.com/dpauli/php-graphql-request-builder) ⭐ 4 | 🐛 1 | 🌐 PHP | 📅 2021-05-13 - Builds request payload in GraphQL structure.
* [drupal/graphql](https://www.drupal.org/project/graphql) - Craft and expose a GraphQL schema for Drupal 9 and 10.

<a name="php-example" />

#### PHP Examples

* [siler-graphgl](https://github.com/leocavalcante/siler/tree/main/examples/graphql) ⚠️ Archived - An example GraphQL server written with Siler.

<a name="py" />

### Python

* [graphene](https://github.com/graphql-python/graphene) ⭐ 8,244 | 🐛 111 | 🌐 Python | 📅 2025-09-04 - A package for creating GraphQL schemas/types in a Pythonic easy way.
* [strawberry](https://github.com/strawberry-graphql/strawberry) ⭐ 4,609 | 🐛 464 | 🌐 Python | 📅 2026-02-12 - A new GraphQL library for Python.
* [graphene-django](https://github.com/graphql-python/graphene-django) ⭐ 4,386 | 🐛 163 | 🌐 Python | 📅 2026-02-03 - A Django integration for Graphene.
* [Ariadne](https://github.com/mirumee/ariadne) ⭐ 2,317 | 🐛 38 | 🌐 Python | 📅 2026-02-12 - library for implementing GraphQL servers using schema-first approach. Asynchronous query execution, batteries included for ASGI, WSGI and popular webframeworks, [fully documented](https://ariadnegraphql.org).
* [flask-graphql](https://github.com/graphql-python/flask-graphql) ⭐ 1,338 | 🐛 42 | 🌐 Python | 📅 2023-01-03 - Adds GraphQL support to your Flask application.
* [tartiflette](https://github.com/dailymotion/tartiflette) ⭐ 854 | 🐛 21 | 🌐 Python | 📅 2023-09-11 - GraphQL Implementation, SDL First, for python 3.6+ / asyncio.
* [sgqlc](https://github.com/profusion/sgqlc) ⭐ 548 | 🐛 38 | 🌐 Python | 📅 2026-02-06 - Simple GraphQL Client makes working with GraphQL API responses easier in Python.
* [graphql-core](https://github.com/graphql-python/graphql-core) ⭐ 531 | 🐛 32 | 🌐 Python | 📅 2026-01-11 - GraphQL implementation for Python based on GraphQL.js v16.3.0 reference implementation
* [django-graphql-auth](https://github.com/PedroBern/django-graphql-auth) ⭐ 333 | 🐛 74 | 🌐 Python | 📅 2024-08-06 - Django registration and authentication with GraphQL.
* [python-graphql-client](https://github.com/prisma/python-graphql-client) ⭐ 156 | 🐛 10 | 🌐 Python | 📅 2020-09-30 - Simple GraphQL client for Python 2.7+
* [graphql-relay-py](https://github.com/graphql-python/graphql-relay-py) ⭐ 143 | 🐛 12 | 🌐 Python | 📅 2023-02-27 - A library to help construct a graphql-py server supporting react-relay.
* [graphene-gae](https://github.com/graphql-python/graphene-gae) ⚠️ Archived - Adds GraphQL support to Google AppEngine (GAE).
* [turms](https://github.com/jhnnsrs/turms) ⭐ 74 | 🐛 21 | 🌐 Python | 📅 2025-10-29 - A pythonic graphql codegenerator built around graphql-core and pydantic
* [Flask-GraphQL-Auth](https://github.com/callsign-viper/Flask-GraphQL-Auth) ⭐ 63 | 🐛 9 | 🌐 Python | 📅 2023-05-01 - An authentication library for Flask inspired from flask-jwt-extended.
* [tartiflette-aiohttp](https://github.com/dailymotion/tartiflette-aiohttp) ⭐ 62 | 🐛 16 | 🌐 Python | 📅 2023-11-12 - Wrapper of Tartiflette to expose GraphQL API over HTTP based on aiohttp / 3.6+ / asyncio, [official tutorial available on tartiflette.io](https://tartiflette.io/docs/tutorial/getting-started).
* [graphql-parser](https://github.com/tryolabs/graphql-parser) ⭐ 46 | 🐛 0 | 🌐 Python | 📅 2015-06-23 - GraphQL parser for Python.
* [django-graphiql](https://github.com/GraphQL-python-archive/django-graphiql) ⭐ 35 | 🐛 0 | 🌐 CSS | 📅 2016-08-07 - Integrate GraphiQL easily into your Django project.
* [rath](https://github.com/jhnnsrs/rath) ⭐ 10 | 🐛 4 | 🌐 Python | 📅 2025-11-29 - An apollo like graphql client with async and sync interface
* [graphql-parser-python](https://github.com/tallstreet/graphql-parser-python) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2015-08-30 - A python wrapper around libgraphqlparser.
* [python-graphjoiner](https://github.com/healx/python-graphjoiner) ⭐ 2 | 🐛 0 | 📅 2019-01-24 - Create GraphQL APIs using joins, SQL or otherwise.

<a name="py-example" />

#### Python Examples

* [swapi-graphene](https://github.com/graphql-python/swapi-graphene) ⭐ 174 | 🐛 6 | 🌐 Python | 📅 2019-12-03 - A GraphQL schema and server using [Graphene](https://graphene-python.org).
* [Python Backend Tutorial](https://hasura.io/learn/graphql/backend-stack/languages/python/) - A tutorial on creating a GraphQL server with [Strawberry](https://strawberry.rocks/) and a client with [Qlient](https://qlient-org.github.io/python-qlient/site/).

<a name="java" />

### Java

* [graphql-java](https://github.com/graphql-java/graphql-java) ⭐ 6,234 | 🐛 65 | 🌐 Java | 📅 2026-02-13 - GraphQL Java implementation.
* [DGS Framework](https://github.com/Netflix/dgs-framework) ⭐ 3,304 | 🐛 44 | 🌐 Kotlin | 📅 2026-02-09 - A GraphQL server framework for Spring Boot, developed by Netflix.
* [manifold-graphql](https://github.com/manifold-systems/manifold/tree/master/manifold-deps-parent/manifold-graphql) ⭐ 2,709 | 🐛 109 | 🌐 Java | 📅 2026-02-11 - Comprehensive GraphQL client use. Schema-first. Type-safe GraphQL types, queries, and results, no code generators, no POJOs, no annotations. Excellent [IDE support](http://manifold.systems/images/graphql.mp4) with IntelliJ IDEA and Android Studio. See the [Java example](#example-java) below.
* [graphql-spring-boot](https://github.com/graphql-java-kickstart/graphql-spring-boot) ⚠️ Archived - GraphQL and GraphiQL Spring Framework Boot Starters.
* [graphql-spqr](https://github.com/leangen/GraphQL-SPQR) ⭐ 1,105 | 🐛 87 | 🌐 Java | 📅 2026-01-27 - Java 8+ API for rapid development of GraphQL services.
* [graphql-java-tools](https://github.com/graphql-java-kickstart/graphql-java-tools) ⭐ 822 | 🐛 92 | 🌐 Kotlin | 📅 2026-02-10 - Schema-first graphql-java convenience library that makes it easy to bring your own implementations as data resolvers. Inspired by [graphql-tools](https://github.com/apollographql/graphql-tools) ⭐ 5,423 | 🐛 162 | 🌐 TypeScript | 📅 2026-02-14 for JS.
* [graphql-java-annotations](https://github.com/Enigmatis/graphql-java-annotations) ⭐ 392 | 🐛 1 | 🌐 Java | 📅 2025-10-03 - Provides annotations-based syntax for schema definition with GraphQL Java.
* [federation-jvm](https://github.com/apollographql/federation-jvm) ⭐ 272 | 🐛 22 | 🌐 Java | 📅 2026-02-12 - Apollo Federation on the JVM.
* [graphql-java-servlet](https://github.com/graphql-java-kickstart/graphql-java-servlet) ⭐ 225 | 🐛 23 | 🌐 Java | 📅 2026-02-12 - A framework-agnostic java servlet for exposing graphql-java query endpoints with GET, POST, and multipart uploads.
* [graphql-java-extended-validation](https://github.com/graphql-java/graphql-java-extended-validation) ⭐ 137 | 🐛 18 | 🌐 Java | 📅 2026-02-02 - Provides extended validation of fields and field arguments for graphql-java.
* [spring-graphql-common](https://github.com/oembedler/spring-graphql-common) ⭐ 134 | 🐛 9 | 🌐 Java | 📅 2017-03-23 - Spring Framework GraphQL Library.
* [graphql-java-generator](https://github.com/graphql-java-generator) - A [Maven plugin](https://github.com/graphql-java-generator/graphql-maven-plugin-project) ⭐ 127 | 🐛 1 | 🌐 Java | 📅 2026-02-08 and a [Gradle plugin](https://github.com/graphql-java-generator/graphql-gradle-plugin-project) ⭐ 58 | 🐛 1 | 🌐 Java | 📅 2026-01-31 that can generate both the **Client** and the **Server** (POJOs and utility classes). The server part is based on graphql-java, and hides all its boilerplate codes.
* [vertx-dataloader](https://github.com/engagingspaces/vertx-dataloader) ⭐ 72 | 🐛 1 | 🌐 Java | 📅 2017-08-06 - Port of Facebook DataLoader for efficient, asynchronous batching and caching in clustered GraphQL environments.
* [graphql-orchestrator-java](https://github.com/graph-quilt/graphql-orchestrator-java) ⭐ 72 | 🐛 14 | 🌐 Groovy | 📅 2025-01-29 GraphQL Orchestrator/Gateway library that supports Schema Stitching and Apollo Federation directives to combine schema from multiple GraphQL microservices into a single unified schema.
* [vertx-graphql-service-discovery](https://github.com/engagingspaces/vertx-graphql-service-discovery) ⭐ 51 | 🐛 5 | 🌐 Java | 📅 2021-11-12 - Asynchronous GraphQL service discovery and querying for your microservices.
* [schemagen-graphql](https://github.com/bpatters/schemagen-graphql) ⭐ 48 | 🐛 11 | 🌐 Java | 📅 2018-09-14 - Schema generation and execution package that turns POJO's into a GraphQL Java queryable set of objects. Enables exposing any service as a GraphQL service using Annotations.
* [gaphql-java-type-generator](https://github.com/graphql-java/graphql-java-type-generator) ⚠️ Archived - Auto-generates types for use with GraphQL Java
* [Light Java GraphQL](https://github.com/networknt/light-graphql-4j) ⭐ 34 | 🐛 10 | 🌐 JavaScript | 📅 2026-02-14: A lightweight, fast microservices framework with all cross-cutting concerns addressed and ready to plug in GraphQL schema.
* [graphql-java-codegen-gradle-plugin](https://github.com/kobylynskyi/graphql-java-codegen-gradle-plugin) ⭐ 19 | 🐛 0 | 📅 2020-04-09 - Schema-first gradle plugin for generating Java types and Resolver interfaces. Works perfectly in conjunction with graphql-java-tools. Inspired by [gradle-swagger-generator-plugin](https://github.com/int128/gradle-swagger-generator-plugin) ⚠️ Archived.
* [graphql-java-codegen-maven-plugin](https://github.com/kobylynskyi/graphql-java-codegen-maven-plugin) ⭐ 17 | 🐛 0 | 📅 2020-04-09 - Schema-first maven plugin for generating Java types and Resolver interfaces. Works perfectly in conjunction with graphql-java-tools. Inspired by [swagger-codegen-maven-plugin](https://github.com/swagger-api/swagger-codegen/tree/master/modules/swagger-codegen-maven-plugin) ⭐ 17,699 | 🐛 3,436 | 🌐 Mustache | 📅 2026-02-05.
* [dgs-extended-formatters](https://github.com/setchy/dgs-extended-formatters) ⭐ 6 | 🐛 4 | 🌐 Java | 📅 2026-02-10 - An experimental set of DGS Directives for common formatting use-cases.
* [Elide](https://elide.io): A Java library that can expose a JPA annotated data model as a GraphQL service over any relational database.

#### Custom Scalars

* [graphql-java-extended-scalars](https://github.com/graphql-java/graphql-java-extended-scalars) ⭐ 280 | 🐛 5 | 🌐 Java | 📅 2026-02-09 - Extended scalars for graphql-java.
* [graphql-java-datetime](https://github.com/donbeave/graphql-java-datetime) ⭐ 151 | 🐛 5 | 🌐 Java | 📅 2026-02-12 - GraphQL ISO Date is a set of RFC 3339 compliant date/time scalar types to be used with graphql-java.

<a name="java-example" />

#### Java Examples

* [light-java-graphql examples](https://github.com/networknt/light-example-4j/tree/master/graphql) ⭐ 150 | 🐛 12 | 🌐 Java | 📅 2026-02-14 - Examples of Light Java GraphQL and tutorials.
* [graphql-java-kickstart\_samples](https://github.com/graphql-java-kickstart/samples) ⭐ 120 | 🐛 16 | 🌐 Java | 📅 2026-01-29 - Samples for using the GraphQL Java Kickstart projects.
* [dgs-federation-example](https://github.com/Netflix/dgs-federation-example) ⭐ 113 | 🐛 21 | 🌐 Kotlin | 📅 2023-09-05 - A Netflix DGS federation example.
* [graphql-spqr-samples](https://github.com/leangen/graphql-spqr-samples) ⭐ 105 | 🐛 12 | 🌐 JavaScript | 📅 2021-04-10 - An example GraphQL server written with Spring MVC and GraphQL-SPQR.
* [graphql-java-kickstart-federation-example](https://github.com/setchy/graphql-java-kickstart-federation-example) ⚠️ Archived - A GraphQL Java Kickstart federation example.
* [manifold-graphql sample](https://github.com/manifold-systems/manifold-sample-graphql-app) ⭐ 20 | 🐛 1 | 🌐 Java | 📅 2024-07-11 - A simple application, both client and server, demonstrating the Manifold GraphQL library.
* [Spring Boot backend tutorial](https://hasura.io/learn/graphql/backend-stack/languages/java/) - A tutorial creating a GraphQL server and client using Spring Boot and Netflix DGS.

<a name="kotlin" />

### Kotlin

* [manifold-graphql](https://github.com/manifold-systems/manifold/tree/master/manifold-deps-parent/manifold-graphql) ⭐ 2,709 | 🐛 109 | 🌐 Java | 📅 2026-02-11 - Comprehensive GraphQL client use. Schema-first. Type-safe GraphQL types, queries, and results, no code generators, no POJOs, no annotations. Excellent [IDE support](http://manifold.systems/images/graphql.mp4) with IntelliJ IDEA and Android Studio. See the [Kotlin example](#example-kotlin) below.
* [graphql-kotlin](https://github.com/ExpediaGroup/graphql-kotlin) ⭐ 1,798 | 🐛 91 | 🌐 Kotlin | 📅 2025-10-27 - GraphQL Kotlin implementation.
* [KGraphQL](https://github.com/aPureBase/KGraphQL) ⭐ 307 | 🐛 57 | 🌐 Kotlin | 📅 2025-09-26: Pure Kotlin implementation to setup a GraphQL server.
* [Kobby](https://github.com/ermadmi78/kobby) ⭐ 86 | 🐛 1 | 🌐 Kotlin | 📅 2026-01-17 - Codegen plugin of [Kotlin DSL Client](https://blog.kotlin-academy.com/how-to-generate-kotlin-dsl-client-by-graphql-schema-707fd0c55284) by GraphQL schema. The generated DSL supports execution of complex GraphQL queries, mutation and subscriptions in Kotlin with syntax similar to native GraphQL syntax.
* [Graphkt](https://github.com/cufyorg/graphkt) ⭐ 9 | 🐛 1 | 🌐 Kotlin | 📅 2024-04-14 - A DSL based graphql server library for kotlin, backed by graphql-java.

<a name="kotlin-example" />

#### Kotlin Examples

* [manifold-graphql sample](https://github.com/manifold-systems/manifold-sample-kotlin-app) ⭐ 3 | 🐛 0 | 🌐 Kotlin | 📅 2024-03-20 - A simple GraphQL application, both client and server, demonstrating the Manifold GraphQL library with Kotlin.

<a name="c" />

### C/C++

* [libgraphqlparser](https://github.com/graphql/libgraphqlparser) ⭐ 1,105 | 🐛 39 | 🌐 C++ | 📅 2025-10-02 - A GraphQL query parser in C++ with C and C++ APIs.
* [cppgraphqlgen](https://github.com/Microsoft/cppgraphqlgen) ⭐ 344 | 🐛 14 | 🌐 C++ | 📅 2025-10-05 - C++ GraphQL schema service generator.
* [agoo-c](https://github.com/ohler55/agoo-c) ⭐ 151 | 🐛 3 | 🌐 C | 📅 2020-12-16 - A high performance GraphQL server written in C. [benchmarks](https://github.com/the-benchmarker/graphql-benchmarks) ⭐ 56 | 🐛 2 | 🌐 Ruby | 📅 2021-08-19
* [CaffQL](https://github.com/caffeinetv/CaffQL) ⭐ 29 | 🐛 3 | 🌐 C++ | 📅 2020-03-31 - Generates C++ client types and request/response serialization from a GraphQL introspection query.

<a name="go" />

### Go

* [gqlgen](https://github.com/99designs/gqlgen) ⭐ 10,663 | 🐛 381 | 🌐 Go | 📅 2026-02-11 - Go generate based graphql server library.
* [graphql](https://github.com/graphql-go/graphql) ⭐ 10,147 | 🐛 239 | 🌐 Go | 📅 2025-12-27 - An implementation of GraphQL for Go follows graphql-js
* [graphql-go](https://github.com/graph-gophers/graphql-go) ⭐ 4,739 | 🐛 21 | 🌐 Go | 📅 2026-02-04 - GraphQL server with a focus on ease of use.
* [graphjin](https://github.com/dosco/graphjin) ⭐ 3,019 | 🐛 17 | 🌐 Go | 📅 2026-02-12: Build APIs in 5 minutes with GraphQL. An instant GraphQL to SQL compiler.
* [graphql-go-tools](https://github.com/wundergraph/graphql-go-tools) ⭐ 815 | 🐛 38 | 🌐 Go | 📅 2026-02-13 - A graphQL Router / API Gateway framework written in Golang, focussing on correctness, extensibility, and high-performance. Supports Federation v1 & v2, Subscriptions & more.
* [graphql-relay-go](https://github.com/graphql-go/relay) ⭐ 425 | 🐛 8 | 🌐 Go | 📅 2020-12-09 - A Go/Golang library to help construct a server supporting react-relay.
* [grpc-graphql-gateway](https://github.com/ysugimoto/grpc-graphql-gateway) ⭐ 422 | 🐛 16 | 🌐 Go | 📅 2025-06-04 - A protoc plugin that generates graphql execution code from Protocol Buffers.
  <a name="go-example" />
* [Thunder](https://github.com/Raezil/Thunder) ⭐ 119 | 🐛 6 | 🌐 Go | 📅 2025-12-05 - A scalable microservices framework powered by Go, gRPC-Gateway, Prisma, and Kubernetes. It exposes REST, gRPC and Graphql
* [gql](https://github.com/kadirpekel/gql) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2026-02-03 - Code first graphql (graphql-go/graphql) schema builder.

#### Go Examples

* [golang-relay-starter-kit](https://github.com/sogko/golang-relay-starter-kit) ⭐ 138 | 🐛 4 | 🌐 Go | 📅 2016-08-03 - Barebones starting point for a Relay application with Golang GraphQL server.
* [todomvc-relay-go](https://github.com/sogko/todomvc-relay-go) ⭐ 66 | 🐛 3 | 🌐 JavaScript | 📅 2016-08-03 - Port of the React/Relay TodoMVC app, driven by a Golang GraphQL backend.
* [go-graphql-subscription-example](https://github.com/ccamel/go-graphql-subscription-example) ⭐ 46 | 🐛 3 | 🌐 Go | 📅 2026-02-11 - A GraphQL schema and server that demonstrates GraphQL [subscriptions](https://github.com/apollographql/subscriptions-transport-ws/blob/v0.9.4/PROTOCOL.md) ⚠️ Archived (over Websocket) to consume [Apache Kafka](https://kafka.apache.org/) messages.
* [Go Backend Tutorial](https://hasura.io/learn/graphql/backend-stack/languages/go/) - A tutorial showing how to make a Go GraphQL server and client using code generation.

<a name="scala" />

### Scala

* [sangria](https://github.com/sangria-graphql/sangria) ⭐ 1,963 | 🐛 64 | 🌐 Scala | 📅 2026-02-12 - Scala GraphQL server implementation.
* [caliban](https://github.com/ghostdogpr/caliban) ⭐ 984 | 🐛 27 | 🌐 Scala | 📅 2026-02-13 - Caliban is a purely functional library for creating GraphQL backends in Scala.
* [sangria-relay](https://github.com/sangria-graphql/sangria-relay) ⭐ 90 | 🐛 15 | 🌐 Scala | 📅 2025-10-30 - Sangria Relay Support.

<a name="scala-example" />

#### Scala Examples

* [sangria-akka-http-example](https://github.com/sangria-graphql/sangria-akka-http-example) ⭐ 241 | 🐛 5 | 🌐 Scala | 📅 2025-10-25 - An example GraphQL server written with akka-http and [sangria](https://sangria-graphql.github.io/)
* [sangria-playground](https://github.com/sangria-graphql/sangria-playground) ⭐ 86 | 🐛 9 | 🌐 JavaScript | 📅 2025-04-13 - An example of GraphQL server written with Play and sangria.

<a name="dotnet" />

### .NET

* [graphql-dotnet](https://github.com/graphql-dotnet/graphql-dotnet) ⭐ 5,980 | 🐛 113 | 🌐 C# | 📅 2026-02-14 - GraphQL for .NET.
* [Hot Chocolate](https://github.com/ChilliCream/hotchocolate) ⭐ 5,677 | 🐛 481 | 🌐 C# | 📅 2026-02-13 - GraphQL server for .Net Core and .NET Framework.
* [graphql-net](https://github.com/ckimes89/graphql-net) ⭐ 888 | 🐛 43 | 🌐 C# | 📅 2022-06-22 - GraphQL to IQueryable for .NET.
* [EntityGraphQL](https://github.com/EntityGraphQL/EntityGraphQL) ⭐ 451 | 🐛 15 | 🌐 C# | 📅 2026-02-07 - library to build a GraphQL API on top of data model with the extensibility to bring multiple data sources together in the single GraphQL schema.
* [ZeroQL](https://github.com/byme8/ZeroQL) ⭐ 315 | 🐛 11 | 🌐 C# | 📅 2025-12-28 - type-safe GraphQL client with Linq-like interface for C#
* [Snowflaqe](https://github.com/Zaid-Ajaj/Snowflaqe) ⭐ 161 | 🐛 22 | 🌐 F# | 📅 2024-10-10 - Type-safe GraphQL code generator for F# and [Fable](https://github.com/fable-compiler/Fable) ⭐ 3,060 | 🐛 234 | 🌐 F# | 📅 2026-02-14

<a name="net-example" />

#### .NET Examples

* [.NET backend tutorial](https://hasura.io/learn/graphql/backend-stack/languages/dotnet/) - A tutorial creating a GraphQL server and client with .NET.

<a name="elixir" />

### Elixir

* [absinthe-graphql](https://github.com/absinthe-graphql/absinthe) ⭐ 4,395 | 🐛 74 | 🌐 Elixir | 📅 2026-02-09 - Fully Featured Elixir GraphQL Library.
* [graphql-elixir](https://github.com/graphql-elixir/graphql) ⚠️ Archived - GraphQL Elixir. (No longer maintained)
* [plug\_graphql](https://github.com/graphql-elixir/plug_graphql) ⚠️ Archived - Plug integration for GraphQL Elixir.
* [graphql](https://github.com/asonge/graphql) ⭐ 87 | 🐛 1 | 🌐 Elixir | 📅 2015-07-12 - Elixir GraphQL parser.
* [graphql\_relay](https://github.com/graphql-elixir/graphql_relay) ⭐ 37 | 🐛 4 | 🌐 Elixir | 📅 2018-07-11 - Relay helpers for GraphQL Elixir.
* [plot](https://github.com/peburrows/plot) ⭐ 32 | 🐛 1 | 🌐 Elixir | 📅 2015-12-11 - GraphQL parser and resolver for Elixir.
* [graphql\_parser](https://github.com/graphql-elixir/graphql_parser) ⭐ 23 | 🐛 3 | 🌐 Elixir | 📅 2023-07-02 - Elixir bindings for [libgraphqlparser](https://github.com/graphql/libgraphqlparser) ⭐ 1,105 | 🐛 39 | 🌐 C++ | 📅 2025-10-02

<a name="elixir-example" />

#### Elixir Examples

* [hello\_graphql\_phoenix](https://github.com/graphql-elixir/hello_graphql_phoenix) ⭐ 99 | 🐛 8 | 🌐 Elixir | 📅 2016-09-18 - Examples of GraphQL Elixir Plug endpoints mounted in Phoenix

<a name="haskell" />

### Haskell

* [morpheus-graphql](https://github.com/morpheusgraphql/morpheus-graphql) ⭐ 416 | 🐛 13 | 🌐 Haskell | 📅 2026-02-08 - Haskell GraphQL Api, Client and Tools.
* [graphql-haskell](https://github.com/jdnavarro/graphql-haskell) ⭐ 169 | 🐛 6 | 🌐 Haskell | 📅 2019-06-11 - GraphQL AST and parser for Haskell.

<a name="sql" />

### SQL

* [Hasura](https://github.com/hasura/graphql-engine) ⭐ 31,898 | 🐛 2,375 | 🌐 TypeScript | 📅 2026-02-12 - Hasura gives Instant Realtime GraphQL APIs over PostgreSQL. Works with an existing database too.
* [PostGraphile](https://github.com/graphile/postgraphile) ⭐ 12,901 | 🐛 142 | 🌐 TypeScript | 📅 2026-02-13 - Lightning-fast GraphQL APIs for PostgreSQL: highly customisable; extensible via plugins; realtime.
* [GraphpostgresQL](https://github.com/solidsnack/GraphpostgresQL) ⭐ 1,089 | 🐛 2 | 🌐 PLpgSQL | 📅 2017-03-30 - GraphQL for Postgres.
* [sql-to-graphql](https://github.com/rexxars/sql-to-graphql) ⭐ 591 | 🐛 24 | 🌐 JavaScript | 📅 2019-01-11 - Generate a GraphQL API based on your SQL database structure.
* [subZero](https://subzero.cloud/) - GraphQL & REST API for your database

<a name="lua" />

### Lua

* [graphql-lua](https://github.com/bjornbytes/graphql-lua) ⭐ 190 | 🐛 4 | 🌐 Lua | 📅 2023-03-13 - GraphQL for Lua.

<a name="elm" />

### Elm

* [elm-graphql](https://github.com/dillonkearns/elm-graphql) ⭐ 786 | 🐛 39 | 🌐 Elm | 📅 2026-02-14 - GraphQL for Elm.

<a name="clojure" />

### Clojure

* [Lacinia](https://github.com/walmartlabs/lacinia) ⭐ 1,849 | 🐛 15 | 🌐 Clojure | 📅 2025-10-17 - GraphQL implementation in pure Clojure.
* [graphql-clj](https://github.com/tendant/graphql-clj) ⚠️ Archived - A Clojure library designed to provide GraphQL implementation.
* [graphql-query](https://github.com/district0x/graphql-query) ⭐ 73 | 🐛 6 | 🌐 Clojure | 📅 2024-03-14 - Clojure(Script) GraphQL query generation.

<a name="clojure-example" />

#### Clojure Examples

* [Clojure Game Geek](https://github.com/walmartlabs/clojure-game-geek) ⭐ 46 | 🐛 1 | 🌐 Clojure | 📅 2023-01-17 - Example code for the Lacinia GraphQL framework tutorial.

<a name="swift" />

### Swift

* [GraphQL](https://github.com/GraphQLSwift/GraphQL) ⭐ 962 | 🐛 7 | 🌐 Swift | 📅 2026-01-27 - The Swift implementation for GraphQL.

<a name="ocaml" />

### OCaml

* [ocaml-graphql-server](https://github.com/andreas/ocaml-graphql-server) ⭐ 621 | 🐛 28 | 🌐 OCaml | 📅 2024-03-03 - GraphQL servers in OCaml.

<a name="android" />

### Android

* [apollo-android](https://github.com/apollographql/apollo-android) ⭐ 3,946 | 🐛 110 | 🌐 Kotlin | 📅 2026-02-14 - 📟 A strongly-typed, caching GraphQL client for Android, written in Java.
* [manifold-graphql](https://github.com/manifold-systems/manifold/tree/master/manifold-deps-parent/manifold-graphql) ⭐ 2,709 | 🐛 109 | 🌐 Java | 📅 2026-02-11 - Comprehensive GraphQL client use. Schema-first. Type-safe GraphQL types, queries, and results, no code generators, no POJOs, no annotations. Excellent [IDE support](http://manifold.systems/images/graphql.mp4) with IntelliJ IDEA and Android Studio. See the [Java example](#example-java) below.

<a name="android-example" />

#### Android Examples

* [apollo-frontpage-android-app](https://github.com/rnitame/apollo-frontpage-android-app) ⭐ 1 | 🐛 2 | 🌐 Kotlin | 📅 2019-11-18 - 📄 Apollo "hello world" app, for Android.

<a name="ios" />

### iOS

* [apollo-ios](https://github.com/apollographql/apollo-ios) ⭐ 4,028 | 🐛 104 | 🌐 Swift | 📅 2026-02-06 - 📱 A strongly-typed, caching GraphQL client for iOS, written in Swift.
* [Graphaello](https://github.com/nerdsupremacist/Graphaello) ⭐ 499 | 🐛 19 | 🌐 Swift | 📅 2022-06-27 - Type Safe GraphQL directly from SwiftUI.
* [ApolloDeveloperKit](https://github.com/manicmaniac/ApolloDeveloperKit) ⚠️ Archived - Apollo Client Devtools bridge for \[Apollo iOS].

<a name="ios-example" />

#### iOS Examples

* [frontpage-ios-app](https://github.com/apollographql/frontpage-ios-app) ⚠️ Archived - 📄 Apollo "hello world" app, for iOS.

<a name="clojurescript" />

### ClojureScript

* [re-graph](https://github.com/oliyh/re-graph) ⭐ 464 | 🐛 15 | 🌐 Clojure | 📅 2025-02-20 - A GraphQL client for ClojureScript with bindings for re-frame applications.
* [graphql-query](https://github.com/district0x/graphql-query) ⭐ 73 | 🐛 6 | 🌐 Clojure | 📅 2024-03-14 - Clojure(Script) GraphQL query generation.

<a name="reasonml" />

### ReasonML

* [reason-apollo](https://github.com/apollographql/reason-apollo) ⚠️ Archived - ReasonML binding for Apollo Client.
* [reason-urql](https://github.com/FormidableLabs/reason-urql) ⭐ 240 | 🐛 12 | 🌐 ReScript | 📅 2025-08-29 - ReasonML binding for urql Client.
* [ReasonQL](https://github.com/sainthkh/reasonql) ⭐ 96 | 🐛 10 | 🌐 JavaScript | 📅 2022-12-22 - Type-safe and simple GraphQL Client for ReasonML developers.

<a name="dart" />

### Dart

* [graphql-flutter](https://github.com/zino-app/graphql-flutter) ⭐ 3,273 | 🐛 164 | 🌐 Dart | 📅 2026-01-13 - A GraphQL client for Flutter.
* [Artemis](https://github.com/comigor/artemis) ⚠️ Archived - A GraphQL type and query generator for Dart/Flutter.

<a name="rust" />

### Rust

* [juniper](https://github.com/graphql-rust/juniper) ⭐ 5,941 | 🐛 102 | 🌐 Rust | 📅 2026-02-10 - GraphQL server library for Rust.
* [async-graphql](https://github.com/async-graphql/async-graphql) ⭐ 3,627 | 🐛 240 | 🌐 Rust | 📅 2026-02-06 - High-performance server-side library that supports all GraphQL specifications.
* [tailcall](https://github.com/tailcallhq/tailcall) ⭐ 1,429 | 🐛 12 | 🌐 Rust | 📅 2026-02-08 - A platform for building high-performance GraphQL backends.
* [graphql-client](https://github.com/tomhoule/graphql-client) ⭐ 1,245 | 🐛 113 | 🌐 Rust | 📅 2026-02-12 - GraphQL client library for Rust with WebAssembly (wasm) support.
* [graphql-parser](https://github.com/graphql-rust/graphql-parser) ⭐ 372 | 🐛 24 | 🌐 Rust | 📅 2025-01-16 - A parser, formatter and AST for the GraphQL query and schema definition language for Rust.

<a name="rust-example" />

#### Rust Examples

* [Warp GraphQL Juniper](https://graphql-rust.github.io/)
* [Tailcall](https://tailcall.run/docs/)

<a name="d" />

### D (dlang)

* [graphqld](https://github.com/burner/graphqld) ⭐ 35 | 🐛 7 | 🌐 D | 📅 2025-03-07 - GraphQL server library for D.

<a name="r" />

### R (Rstat)

* [ghql](https://github.com/ropensci/ghql) ⭐ 149 | 🐛 5 | 🌐 R | 📅 2025-09-08 - General purpose GraphQL R client.
* [gqlr](https://github.com/schloerke/gqlr) ⭐ 59 | 🐛 3 | 🌐 JavaScript | 📅 2026-01-12 - R GraphQL Implementation.
* [graphql](https://github.com/ropensci/graphql) ⭐ 39 | 🐛 1 | 🌐 C++ | 📅 2025-07-02 - Bindings to the 'libgraphqlparser' C++ library. Parses GraphQL syntax and exports the AST in JSON format.

<a name="julia" />

### Julia

* [Diana.jl](https://github.com/codeneomatrix/Diana.jl) ⭐ 116 | 🐛 6 | 🌐 Julia | 📅 2022-08-16 - A Julia GraphQL client/server implementation.
* [GraphQLClient.jl](https://github.com/DeloitteDigitalAPAC/GraphQLClient.jl) ⭐ 47 | 🐛 5 | 🌐 Julia | 📅 2023-10-30 - A Julia GraphQL client for seamless integration with a server.

<a name="crystal" />

### Crystal

* [graphql-crystal](https://github.com/ziprandom/graphql-crystal) ⭐ 213 | 🐛 9 | 🌐 Crystal | 📅 2020-07-01 - library inspired by [graphql-ruby](https://github.com/rmosolgo/graphql-ruby) ⭐ 5,429 | 🐛 76 | 🌐 Ruby | 📅 2026-02-09 & [go-graphql](https://github.com/playlyfe/go-graphql) ⭐ 247 | 🐛 18 | 🌐 Go | 📅 2020-01-22 & [graphql-parser](https://github.com/graphql-dotnet/parser) ⭐ 220 | 🐛 6 | 🌐 C# | 📅 2026-02-03.
* [graphql](https://github.com/graphql-crystal/graphql) ⭐ 138 | 🐛 9 | 🌐 Crystal | 📅 2026-01-09 - GraphQL server library.
* [crystal-gql](https://github.com/itsezc/crystal-gql) ⭐ 6 | 🐛 0 | 🌐 Crystal | 📅 2021-05-06 - GraphQL client shard inspired by Apollo client.
* [graphql.cr](https://github.com/garymardell/graphql.cr) ⭐ 1 | 🐛 1 | 🌐 Crystal | 📅 2025-12-19 - GraphQL shard.

### Ballerina

* [graphql](https://github.com/ballerina-platform/module-ballerina-graphql) ⭐ 138 | 🐛 5 | 🌐 Ballerina | 📅 2026-02-09 - Ballerina standard library for GraphQL. This library provides a GraphQL client and server implementations including builtin support for GraphQL subscriptions.
* [graphql CLI](https://github.com/ballerina-platform/graphql-tools) ⭐ 108 | 🐛 2 | 🌐 Java | 📅 2025-11-18 - A CLI tool to generate Ballerina code from GraphQL schema and GraphQL schema from Ballerina code. It also provides functionality to generate usage-specific GraphQL clients using GraphQL schemas and documents.

#### Ballerina Samples

* [Ballerina GraphQL Examples](https://github.com/ballerina-platform/module-ballerina-graphql/tree/master/examples) ⭐ 138 | 🐛 5 | 🌐 Ballerina | 📅 2026-02-09
* [Convert Weather REST API to GraphQL API](https://github.com/ThisaruGuruge/weather-rest-api-to-graphql) ⭐ 3 | 🐛 0 | 🌐 Ballerina | 📅 2023-08-17

<a name="tools" />

## Tools

### Tools - Editors & IDEs & Explorers

* [Bruno](https://github.com/usebruno/bruno) ⭐ 40,854 | 🐛 1,709 | 🌐 JavaScript | 📅 2026-02-13 - Fast, open source API client, which stores collections offline-only in a Git-friendly plain text markup language.
* [GraphiQL](https://github.com/graphql/graphiql) ⭐ 16,789 | 🐛 404 | 🌐 TypeScript | 📅 2026-02-13 - An in-browser IDE for exploring GraphQL.
* [GraphQL Voyager](https://github.com/APIs-guru/graphql-voyager) ⭐ 8,087 | 🐛 103 | 🌐 TypeScript | 📅 2026-02-02 - Represent any GraphQL API as an interactive graph.
* [GraphQL Editor](https://github.com/graphql-editor/graphql-editor) ⭐ 6,074 | 🐛 20 | 🌐 TypeScript | 📅 2025-09-10 - Visual Editor & GraphQL IDE.
* [Altair GraphQL Client](https://github.com/altair-graphql/altair) ⭐ 5,391 | 🐛 66 | 🌐 TypeScript | 📅 2026-02-13 - A beautiful feature-rich GraphQL Client for all platforms.
* [GraphQL Birdseye](https://github.com/Novvum/graphql-birdseye) ⭐ 704 | 🐛 30 | 🌐 TypeScript | 📅 2022-12-10 – View any GraphQL schema as a dynamic and interactive graph.
* [gqt](https://github.com/eerimoq/gqt) ⭐ 468 | 🐛 2 | 🌐 Python | 📅 2025-06-16 - Build and execute GraphQL queries in the terminal.
* [Escape GraphMan](https://github.com/Escape-Technologies/graphman) ⭐ 247 | 🐛 7 | 🌐 TypeScript | 📅 2024-08-26 - Generate a complete Postman collection from a GraphQL endpoint.
* [CraftQL](https://github.com/yamafaktory/craftql) ⭐ 112 | 🐛 0 | 🌐 Rust | 📅 2023-05-18 - A CLI tool to visualize GraphQL schemas and to output a graph data structure as a graphviz .dot format.
* [Brangr](https://github.com/networkimprov/brangr) ⭐ 6 | 🐛 0 | 🌐 HTML | 📅 2023-06-04 - A unique, user-friendly data browser/viewer for any GraphQL service, with attractive result layouts.
* [Insomnia](https://insomnia.rest/) - A full-featured API client with first-party GraphQL query editor.
* [Postman](https://learning.postman.com/docs/sending-requests/supported-api-frameworks/graphql/) - An HTTP Client that supports editing GraphQL queries.
* [Apollo Sandbox](https://sandbox.apollo.dev/) - The quickest way to navigate and test your GraphQL endpoints.
* [AST Explorer](https://astexplorer.net/) - Select "GraphQL" at the top, explore the GraphQL AST and highlight different parts by clicking in the query.
* [Firecamp - GraphQL Playground](https://firecamp.io/graphql) - The fastest collaborative GraphQL playground.
* [Hackolade](https://studio.hackolade.com/) - Visual GraphQL schema editor to generate Schema Definition Language files without any knowledge of the GraphQL syntax. Also visualize and document existing endpoints with introspection.  Additional info and instructions [here](https://hackolade.com/help/GraphQL.html)

<a name="tool-testing" />

### Tools - Testing, Prototyping & Mocking

* [GraphQL Faker](https://github.com/APIs-guru/graphql-faker) ⭐ 2,712 | 🐛 79 | 🌐 TypeScript | 📅 2023-11-24 - 🎲 Mock or extend your GraphQL API with faked data. No coding required.
* [graphql-to-karate](https://github.com/wbaldoumas/graphql-to-karate) ⭐ 16 | 🐛 3 | 🌐 C# | 📅 2026-02-13 - **Generate Karate API tests** from your GraphQL schemas
* [Beeceptor](https://beeceptor.com/graphql-mock-server/) - A no-code platform for creating AI-powered **GraphQL Mock Servers** from your schema (SDL) with rules, stateful mocking, mutation/subscription, to speed up development and integration testing.
* [GraphQL Inspector](https://the-guild.dev/graphql/inspector) - A tool to **validate schemas**, compare schema changes, find breaking changes, and check document coverage against a schema.
* [Microcks](https://microcks.io/) - The open source ([CNCF](https://www.cncf.io/projects/microcks/) project), cloud native tool for **API Mocking** and Testing with [GraphQL support](https://microcks.io/blog/graphql-features-what-to-expect/) 🎥 [GraphQL conf 2023](https://youtu.be/UjDnrrTp7uI?si=M6S4l_Bukp9CEYl4)
* [Keploy](https://keploy.io/) - Open-source AI Powered API testing tool that generates test cases and **data mocks automatically by recording real API traffic**. Supports GraphQL, REST, and gRPC.
* [Step CI](https://stepci.com) - Open-Source API **Testing and Monitoring** with GraphQL support

<a name="tool-security" />

### Tools - Security

* [InQL Scanner](https://github.com/doyensec/inql) ⭐ 1,731 | 🐛 35 | 🌐 Kotlin | 📅 2026-02-12 - A Burp Extension for GraphQL Security Testing
* [GraphQL Cop](https://github.com/dolevf/graphql-cop) ⭐ 599 | 🐛 1 | 🌐 Python | 📅 2025-11-20 - Security Audit Utility for GraphQL
* [GraphCrawler - The all-in-one GraphQL Security toolkit](https://github.com/gsmith257-cyber/GraphCrawler) ⚠️ Archived - The all-in-one automated penetration tester toolkit for GraphQL, written in Python
* [Escape Graphinder - GraphQL Subdomain Enumeration](https://github.com/Escape-Technologies/graphinder) ⭐ 227 | 🐛 6 | 🌐 Python | 📅 2023-05-22 – Blazing fast GraphQL endpoints finder using subdomain enumeration, scripts analysis and bruteforce.
* [GraphQLer](https://github.com/omar2535/GraphQLer) ⭐ 157 | 🐛 18 | 🌐 Python | 📅 2026-02-14 - Dependency-aware dynamic GraphQL testing tool
* [GraphQL Intruder](https://github.com/davinerd/gql_intruder) ⭐ 13 | 🐛 3 | 🌐 Python | 📅 2021-01-10 - Plugin based python script to perform GraphQL vulnerability assessment.
* [Escape - The GraphQL Security Scanner](https://graphql.security/) - One-click security scan of your GraphQL endpoints. Free, no login required.
* [StackHawk - GraphQL Vulnerability Scanner](https://www.stackhawk.com/blog/automated-graphql-security-testing) - [StackHawk](https://www.stackhawk.com)
* [GraphQL Raider](https://portswigger.net/bappstore/4841f0d78a554ca381c65b26d48207e6) [BurpSuite](https://portswigger.net/burp)
* [WAF for graphQL](https://lab.wallarm.com/api-security-solution/) - Web Application Firewall for graphQL APIs
* [Vulert](https://vulert.com) - Vulert secures software by detecting vulnerabilities in open-source dependencies—without accessing your code. It supports Js, PHP, Java, Python, and more

### Tools - Browser Extensions

* [Apollo Client Developer Tools](https://github.com/apollographql/apollo-client-devtools) ⭐ 1,522 | 🐛 52 | 🌐 TypeScript | 📅 2026-02-13 - GraphQL debugging tools for Apollo Client in the Chrome developer console
* [GraphQL Network Inspector](https://chrome.google.com/webstore/detail/graphql-network-inspector/ndlbedplllcgconngcnfmkadhokfaaln) - A simple and clean chrome dev-tools extension for GraphQL network inspection.

### Tools - Docs

* [graphdoc](https://github.com/2fd/graphdoc) ⭐ 1,569 | 🐛 99 | 🌐 TypeScript | 📅 2023-01-31 - Static page generator for documenting GraphQL Schema.
* [spectaql](https://github.com/anvilco/spectaql) ⭐ 1,220 | 🐛 88 | 🌐 JavaScript | 📅 2026-02-12 - Autogenerate static GraphQL API documentation.
* [gqldoc](https://github.com/Code-Hex/gqldoc) ⚠️ Archived - The easiest way to make API documents for GraphQL.
* [graphql-markdown](https://graphql-markdown.github.io/) - Flexible documentation for GraphQL powered with Docusaurus.
* [xyd](https://xyd.dev) - Generate GraphQL API docs.

### Tools - Editor Plugins

* [js-graphql-intellij-plugin](https://github.com/jimkyndemeyer/js-graphql-intellij-plugin/) ⭐ 893 | 🐛 156 | 🌐 Java | 📅 2026-02-13 - GraphQL language support for IntelliJ IDEA and WebStorm, including Relay.QL tagged templates in JavaScript and TypeScript.
* [vim-graphql](https://github.com/jparise/vim-graphql) ⭐ 509 | 🐛 0 | 🌐 Vim Script | 📅 2025-11-29 - A Vim plugin that provides GraphQL file detection and syntax highlighting.
* [graphql-autocomplete](https://github.com/orionsoft/atom-graphql-autocomplete) ⭐ 47 | 🐛 15 | 🌐 JavaScript | 📅 2023-03-04 - Autocomplete and lint from a GraphQL endpoint in Atom.
* [Apollo GraphQL VSCode Extension](https://marketplace.visualstudio.com/items?itemName=apollographql.vscode-apollo) - Rich editor support for GraphQL client and server development that seamlessly integrates with the Apollo platform

### Tools - Miscellaneous

* [Prisma](https://github.com/prisma/prisma) ⭐ 45,306 | 🐛 2,480 | 🌐 TypeScript | 📅 2026-02-13 - Turn your database into a GraphQL API. Prisma lets you design your data model and have a production ready GraphQL API online in minutes.
* [Bit](https://github.com/teambit/bit) ⭐ 18,350 | 🐛 64 | 🌐 TypeScript | 📅 2026-02-12 - Organize GraphQL API as components to be consumed with NPM or modified from any project, [example-explanation](https://hackernoon.com/make-your-graphql-api-easier-to-adopt-through-components-74b022f195c1)).
* [amplication](https://github.com/amplication/amplication) ⭐ 16,000 | 🐛 626 | 🌐 TypeScript | 📅 2026-02-14: Amplication is an open‑source low code development tool. It builds database applications with REST API and GraphQL for CRUD with relations, sorting, filtering, pagination.
* [graphql-code-generator](https://github.com/dotansimha/graphql-code-generator) ⭐ 11,216 | 🐛 624 | 🌐 TypeScript | 📅 2026-02-12 - GraphQL code generator based on schema and documents.
* [json-graphql-server](https://github.com/marmelab/json-graphql-server) ⭐ 1,955 | 🐛 11 | 🌐 JavaScript | 📅 2025-10-21 - Get a full fake GraphQL API with zero coding in less than 30 seconds, based on a JSON data file.
* [raphql-inspector](https://github.com/kamilkisiela/graphql-inspector) ⭐ 1,737 | 🐛 133 | 🌐 TypeScript | 📅 2026-02-12: alidate schema, get schema change notifications, validate operations, find breaking changes, look for similar types, schema coverage.
* [openapi-to-graphql](https://github.com/ibm/openapi-to-graphql) ⭐ 1,644 | 🐛 141 | 🌐 TypeScript | 📅 2025-09-17 - Take any OpenAPI Specification (OAS) or swagger and create a GraphQL interface - Two minute video and resources [here](https://developer.ibm.com/open/projects/openapi-to-graphql/)
* [tuql](https://github.com/bradleyboy/tuql) ⭐ 1,071 | 🐛 15 | 🌐 JavaScript | 📅 2021-06-06 - Automatically create a GraphQL server from any sqlite database.
* [swagger-to-graphql](https://github.com/yarax/swagger-to-graphql) ⭐ 926 | 🐛 39 | 🌐 TypeScript | 📅 2023-03-01 - GraphQL types builder based on REST API described in Swagger. Allows to migrate to GraphQL from REST for 5 minutes
* [ts-graphql-plugin](https://github.com/Quramy/ts-graphql-plugin) ⭐ 757 | 🐛 31 | 🌐 TypeScript | 📅 2026-02-12 - A language service plugin complete and validate GraphQL query in TypeScript template strings.
* [apollo-tracing](https://github.com/apollographql/apollo-tracing) ⚠️ Archived - GraphQL extension that enables you to easily get resolver-level performance information as part of a GraphQL response.
* [Typetta](https://github.com/twinlogix/typetta) ⭐ 116 | 🐛 58 | 🌐 TypeScript | 📅 2026-02-12 - Node.js ORM written in TypeScript for type lovers. Typetta is the perfect ORM for the GraphQL + NodeJS + Typescript stack.
* [dataloader-codegen](https://github.com/Yelp/dataloader-codegen) ⭐ 114 | 🐛 44 | 🌐 JavaScript | 📅 2025-10-28 - An opinionated JavaScript library for automatically generating predictable, type safe DataLoaders over a set of resources (e.g. HTTP endpoints).
* [microfiber](https://github.com/anvilco/graphql-introspection-tools) ⭐ 37 | 🐛 7 | 🌐 JavaScript | 📅 2024-01-29 - Query and manipulate GraphQL introspection query results in useful ways.
* [Blendbase](https://github.com/blendbase/blendbase) ⭐ 26 | 🐛 3 | 🌐 Go | 📅 2022-04-28: Single open-source GraphQL API to connect CRMs to your SaaS. Query any customer CRM system (Salesforce, Hubspot and more) with a single API query from your SaaS app.
* [gqlhash](https://github.com/romshark/gqlhash) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2025-02-01 - Lightning fast query hasher that ignores formatting diffs and comments and supports multiple hashing functions.
* [Apollo APQ Debugger](https://github.com/rookieInTraining/apq-debugger) ⭐ 0 | 🐛 1 | 🌐 JavaScript | 📅 2026-01-31 - Reveal full GraphQL queries behind Apollo APQ hashes. Inspect fallback flow and debug Automatic Persisted Queries in DevTools. <a name="databases" />
* [Retool](https://retool.com/) – Internal tools builder on top of your GraphQL APIs + GraphQL IDE with a schema explorer.
* [DronaHQ](https://www.dronahq.com/) - Build internal tools, dashboards, admin panel on top of GraphQL data in minutes
* [Dynaboard](https://dynaboard.com) - Generate low-code web apps from any GraphQL API using AI.

## Databases

* [Cube](https://cube.dev) - [Headless BI](https://cube.dev/blog/headless-bi) for building data applications with SQL, REST, and [GraphQL API](https://cube.dev/docs/backend/graphql). Connect any database or data warehouse and instantly get a GraphQL API with sub-second latency on top of it. - [Source Code](https://github.com/cube-js/cube.js) ⭐ 19,500 | 🐛 880 | 🌐 Rust | 📅 2026-02-13
* [Weaviate](https://github.com/semi-technologies/weaviate) ⭐ 15,587 | 🐛 592 | 🌐 Go | 📅 2026-02-13 - Weaviate is a cloud-native, modular, real-time vector search engine with a [GraphQL interface](https://weaviate.io/developers/weaviate/api/graphql) built to scale your machine learning models.
* [Dgraph](https://dgraph.io/) - Scalable, distributed, low latency, high throughput Graph database with GraphQL as the query language
* [EdgeDB](https://edgedb.com/) - The next generation object-relational database with native GraphQL support.
* [ArangoDB](https://arangodb.com/) - Native multi-model database with [GraphQL integration](https://www.arangodb.com/docs/3.4/foxx-reference-modules-graph-ql.html) via the built-in [Foxx Microservices Framework](https://www.arangodb.com/docs/stable/foxx.html).

<a name="services" />

## Services

* [AWS AppSync](https://aws.amazon.com/appsync/) - Scalable managed GraphQL service with subscriptions for building real-time and offline-first apps
* [FakeQL](https://fakeql.com/) - GraphQL API mocking as a service ... because GraphQL API mocking should be easy!
* [Moesif API Analytics](https://www.moesif.com/features/graphql-analytics) - A GraphQL analaytics and monitoring service to find functional and performance issues.
* [Booster framework](https://booster.cloud/) - An open-source framework that makes you *completely* forget about infrastructure and allows you to focus exclusively on your business logic. It autogenerates a GraphQL API for your models, supporting mutations, queries, and subscriptions.
* [Nhost](https://nhost.io/) - Open source Firebase alternative with GraphQL
* [Saleor](https://github.com/mirumee/saleor/) ⭐ 22,592 | 🐛 242 | 🌐 Python | 📅 2026-02-13 - GraphQL-first headless e-commerce platform.
* [Stargate](https://stargate.io/docs/latest/quickstart/qs-graphql-cql-first.html) - Open source data gateway currently supporting Apache Cassandra® and DataStax Enterprise.
* [Vedika](https://vedika.io) - Vedic astrology AI API with GraphQL support for horoscopes, birth charts, kundali matching, and 108+ endpoints.
* [Grafbase](https://grafbase.com) - Instant GraphQL APIs for any data source.

### CDN

* [GraphCDN](https://graphcdn.io/) - GraphQL CDN for caching GraphQL APIs.

### CMS

* [DatoCMS](https://www.datocms.com/) - CDN-based GraphQL based Headless Content Management System.
* [Apito](https://apito.io/) - A Cloud Based Headless CMS with CDN, Webhooks, Team Collaborations, Content Revision, Cloud Functions.
* [Hygraph](https://hygraph.com/) - Build Scalable Content Experiences.
* [Cosmic](https://www.cosmicjs.com/) - GraphQL-powered Headless CMS and API toolkit.
* [Graphweaver](https://graphweaver.com/) - Turn multiple datasources into a single GraphQL API.

<a name="book" />

## Books

* [The GraphQL Guide](https://graphql.guide) by John Resig and Loren Sands-Ramshaw
* [Craft GraphQL APIs in Elixir with Absinthe](https://pragprog.com/book/wwgraphql/craft-graphql-apis-in-elixir-with-absinthe) by Bruce Williams and Ben Wilson
* [The Road to GraphQL](https://www.roadtographql.com/)
* [Practical GraphQL](https://leanpub.com/book-graphql) by Daniel Schmitz
* [Production Ready GraphQL](https://book.productionreadygraphql.com) by Marc-André Giroux
* [Full Stack GraphQL Applications](https://www.manning.com/books/fullstack-graphql-applications) by William Lyon

<a name="video" />

## Videos

* [GraphQL: The Documentary](https://www.youtube.com/watch?v=783ccP__No8)
* [Zero to GraphQL in 30 Minutes](https://www.youtube.com/embed/UBGzsb2UkeY)
* [Data fetching for React applications at Facebook](https://www.youtube.com/watch?v=9sc8Pyc51uU)
* [React Native & Relay: Bringing Modern Web Techniques to Mobile](https://www.youtube.com/watch?v=X6YbAKiLCLU)
* [Exploring GraphQL](https://www.youtube.com/watch?v=WQLzZf34FJ8)
* [Creating a GraphQL Server](https://www.youtube.com/watch?v=gY48GW87Feo)
* [GraphQL at The Financial Times](https://www.youtube.com/watch?v=S0s935RKKB4)
* [Relay: An Application Framework For React](https://www.youtube.com/watch?v=IrgHurBjQbg)
* [Building and Deploying Relay with Facebook](https://www.youtube.com/watch?t=643\&v=Pxdgu2XIAAg)
* [Introduction to GraphQL](https://vimeo.com/144817545)
* [Exploring GraphQL@Scale](https://www.youtube.com/watch?v=_9RgHXqH8J0)
* [What's Next for Phoenix by Chris McCord](https://www.youtube.com/watch?v=IMUpYOc9z3c\&feature=youtu.be)
* [GraphQL with Nick Schrock](https://www.youtube.com/watch?v=Ed6oJXKt3-M)
* [Build a GraphQL server for Node.js using PostgreSQL/MySQL](https://www.youtube.com/watch?v=DNPVqK_woRQ)
* [GraphQL server tutorial for Node.js with SQL, MongoDB and REST](https://www.youtube.com/watch?v=PHabPhgRUuU)
* [JavaScript Air Episode 023: Transitioning from REST to GraphQL](https://www.youtube.com/watch?v=ENqDNIp1Nd8)
* [GraphQL Future at react-europe 2016](https://www.youtube.com/watch?v=ViXL0YQnioU)
* [GraphQL at Facebook at react-europe 2016](https://www.youtube.com/watch?v=etax3aEe2dA)
* [Building native mobile apps with GraphQL at react-europe 2016](https://www.youtube.com/watch?v=z5rz3saDPJ8)
* [Build a GraphQL Server](https://www.youtube.com/watch?v=PEcJxkylcRM\&list=PLillGF-RfqbYZty73_PHBqKRDnv7ikh68)
* [GraphQL Tutorial](https://www.youtube.com/watch?v=Y0lDGjwRYKw\&list=PL4cUxeGkcC9iK6Qhn-QLcXCXPQUov1U7f)
* [Five years of GraphQL](https://www.youtube.com/watch?v=s8meG38iZAM)
* [GraphQL is for Everyone by Moon Highway](https://moonhighway.teachable.com/p/graphql-is-for-everyone)

<a name="podcast" />

## Podcasts

* [GraphQL.FM](https://podcasts.google.com/feed/aHR0cHM6Ly9hbmNob3IuZm0vcy8zNjE5NmViMC9wb2RjYXN0L3Jzcw==) by Marc-Andre Giroux and Tony Ghita.

<a name="style-guide" />

## Style Guides

* [Shopify GraphQL Design Tutorial](https://github.com/Shopify/graphql-design-tutorial) ⭐ 2,462 | 🐛 5 | 📅 2025-01-23 - This tutorial was originally created by Shopify for internal purposes. It's based on lessons learned from creating and evolving production schemas at Shopify over almost 3 years.
* [GitLab GraphQL API Style Guide](https://docs.gitlab.com/ee/development/api_graphql_styleguide.html) - This document outlines the style guide for the GitLab GraphQL API.
* [Yelp GraphQL Guidelines](https://yelp.github.io/graphql-guidelines/) - This repo contains documentation and guidelines for a standardized and mostly reasonable approach to GraphQL (at Yelp).
* [Principled GraphQL](https://principledgraphql.com/) - Apollo's 10 GraphQL Principles, broken out into three categories, in a format inspired by the Twelve Factor App.

<a name="blogs" />

## Blogs

* [Official GraphQL blog](https://graphql.org/blog/)
* [Building Apollo](https://blog.apollographql.com/)
* [The Guild blog](https://medium.com/the-guild)
* [Production Ready GraphQL blog](https://productionreadygraphql.com)

<a name="security-blog" />

### Blogs - Security

* [Escape - The GraphQL Security Blog](https://escape.tech/blog) - Learn about GraphQL security, performance, testing and building production-ready APIs with the latest tools and best practices of the GraphQL ecosystem.
* [9 GraphQL Security Best Practices](https://escape.tech/blog/9-graphql-security-best-practices/)
* [Discovering GraphQL Endpoints and SQLi Vulnerabilities](https://medium.com/@localh0t/discovering-graphql-endpoints-and-sqli-vulnerabilities-5d39f26cea2e)
* [Securing GraphQL API](https://lab.wallarm.com/securing-graphql-api/)
* [Security Points to Consider Before Implementing GraphQL](https://nordicapis.com/security-points-to-consider-before-implementing-graphql/)
* [Authorization Patterns in GraphQL](https://www.osohq.com/post/graphql-authorization)

<a name="post" />

## Posts

* [GraphQL federation example with Apollo Federation and Apollo GraphOS](https://cube.dev/blog/graphql-federation-example-with-apollo-federation-and-apollo-graphos)
* [GraphQL federation with Hasura GraphQL Engine and Cube](https://cube.dev/blog/graphql-federation-with-hasura-graphql-engine)
* [Using DataLoader to batch GraphQL requests](https://medium.com/@gajus/using-dataloader-to-batch-requests-c345f4b23433)
* [Introducing Relay and GraphQL](https://reactjs.org/blog/2015/02/20/introducing-relay-and-graphql.html)
* [GraphQL Introduction](https://reactjs.org/blog/2015/05/01/graphql-introduction.html)
* [Unofficial Relay FAQ](https://gist.github.com/wincent/598fa75e22bdfa44cf47)
* [Your First GraphQL Server](https://medium.com/the-graphqlhub/your-first-graphql-server-3c766ab4f0a2)
* [GraphQL Overview - Getting Started with GraphQL and Node.js](https://blog.risingstack.com/graphql-overview-getting-started-with-graphql-and-nodejs/)
* [4 Reasons you should try out GraphQL](https://medium.freecodecamp.org/introduction-to-graphql-1d8011b80159)
* [Moving from REST to GraphQL](https://medium.com/@frikille/moving-from-rest-to-graphql-e3650b6f5247)
* [Writing a Basic API with GraphQL](http://davidandsuzi.com/writing-a-basic-api-with-graphql/)
* [Building a GraphQL Server with Node.js and SQL](https://www.reindex.io/blog/building-a-graphql-server-with-node-js-and-sql/)
* [GraphQL at The Financial Times](https://www.slideshare.net/LondonReact/graph-ql)
* [Implementing GraphQL RBAC Authorization: A Practical Guide](https://www.permit.io/blog/implementing-graphql-authorization)
* [From REST to GraphQL](https://jacobwgillespie.com/2015-10-09-from-rest-to-graphql)
* [GraphQL: A data query language](https://graphql.org/blog/graphql-a-query-language/)
* [Subscriptions in GraphQL and Relay](https://graphql.org/blog/subscriptions-in-graphql-and-relay/)
* [Relay 101: Building A Hacker News Client](https://medium.com/@clayallsopp/relay-101-building-a-hacker-news-client-bb8b2bdc76e6)
* [GraphQL Shorthand Notation Cheatsheet](https://wehavefaces.net/graphql-shorthand-notation-cheatsheet-17cd715861b6)
* [The GitHub GraphQL API](https://githubengineering.com/the-github-graphql-api/)
* [Github GraphQL API React Example](https://medium.com/@katopz/github-graphql-api-react-example-eace824d7b61)
* [Testing a GraphQL Server using Jest](https://medium.com/entria/testing-a-graphql-server-using-jest-4e00d0e4980e)
* [How to implement viewerCanSee in GraphQL](https://medium.com/entria/how-to-implement-viewercansee-in-graphql-78cc48de7464)
* [Preventing traversal attacks on your GraphQL API](https://blog.morethancode.dev/preventing-traversal-attacks-in-your-graphql-api/)
* [Mock your GraphQL server realistically with faker.js](https://dev.to/yvonnickfrin/mock-your-graphql-server-realistically-with-faker-js-25oo)
* [Create an infinite loading list with React and GraphQL](https://dev.to/yvonnickfrin/create-an-infinite-loading-list-with-react-and-graphql-19hh)
* [REST vs GraphQL](https://www.moesif.com/blog/technical/graphql/REST-vs-GraphQL-APIs-the-good-the-bad-the-ugly/)
* [Authentication and Authorization for GraphQL APIs](https://www.moesif.com/blog/technical/api-design/Steps-to-Building-Authentication-and-Authorization-For-GraphQL-APIs/)
* [Build a GraphQL API with Siler on top of Swoole](https://www.swoole.co.uk/article/Build-a-GraphQL-API-on-top-of-Swoole)
* [Fluent GraphQL clients: how to write queries like a boss](https://hasura.io/blog/fluent-graphql-clients-how-to-write-queries-like-a-boss/)
* [Level up your serverless game with a GraphQL data-as-a-service layer](https://hasura.io/blog/level-up-your-serverless-game-with-a-graphql-data-as-a-service-layer/)
* [A deep-dive into Relay, the friendly & opinionated GraphQL client](https://hasura.io/blog/deep-dive-into-relay-graphql-client/)
* [make your graphql api easier to adopt through components](https://hackernoon.com/make-your-graphql-api-easier-to-adopt-through-components-74b022f195c1)
* [Undocumented: keeping parts of your GraphQL schema hidden from introspection](https://www.useanvil.com/blog/engineering/undocumented-directive/)
* [GraphQL Subscriptions with Apache Kafka in Ballerina](https://medium.com/ballerina-techblog/graphql-subscriptions-with-apache-kafka-in-ballerina-b3c296d333cd)
* [How to Test your GraphQL Endpoints](https://escape.tech/blog/8-most-common-graphql-vulnerabilities/)
* [Why Automatic Persisted Queries Don't Scale](https://blog.tailcall.run/the-truth-about-scaling-automatic-persisted-queries/)

<a name="tutorials" />

## Tutorials

* [How to GraphQL](https://www.howtographql.com) - Fullstack Tutorial Website with Tracks for all Major Frameworks & Languages including React, Apollo, Relay, JavaScript, Ruby, Java, Elixir and many more.
* [Apollo Odyssey](https://odyssey.apollographql.com/) - Apollo's free interactive learning platform.
* [learning-graphql](https://github.com/mugli/learning-graphql) ⭐ 937 | 🐛 6 | 🌐 JavaScript | 📅 2019-02-16 - An attempt to learn GraphQL.
* [GraphQL Roadmap](https://roadmap.sh/graphql) - Step by step guide to learn GraphQL.
* [GraphQL Security Academy](https://escape.tech/academy/) - a free and interactive platform to learn GraphQL security: how to find, exploit and fix GraphQL vulnerabilities.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Chen-Tsu Lin](https://github.com/chentsulin) has waived all copyright and related or neighboring rights to this work.
