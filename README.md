# Awesome Sanic [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome [Sanic](https://sanicframework.org/) resources and extensions  
> Sanic is an Async Python 3.7+ web server that's written to go fast

[User Guide](https://sanic.dev/) | [API Docs](https://sanic.readthedocs.io/) | [Source](https://github.com/sanic-org/sanic) | [Forums](https://community.sanicframework.org/) | [Discord](https://discord.gg/FARQzAEMAA)


## Contents
- [Awesome Sanic ![Awesome](https://github.com/sindresorhus/awesome)](#awesome-sanic-) ![star](https://img.shields.io/github/stars/mekicha/awesome-sanic.svg)![fork](https://img.shields.io/github/forks/mekicha/awesome-sanic.svg)
  - [Contents](#contents)
  - [Extensions](#extensions)
    - [Official](#official)
    - [API](#api)
    - [Authentication](#authentication)
    - [Development](#development)
    - [Frontend](#frontend)
    - [Monitoring](#monitoring)
    - [ORM](#orm)
    - [Requests and Responses](#requests-and-responses)
    - [Caching](#caching)
    - [Tracing](#tracing)
    - [Queues](#queues)
    - [Scaffolding](#scaffolding)
    - [Session](#session)
    - [Utils](#utils)
  - [Resources](#resources)
    - [Examples](#examples)
    - [Tutorials](#tutorials)
    - [Books](#books)
    - [Videos and Podcasts](#videos-and-podcasts)
    - [Built with Sanic](#built-with-sanic)


## Extensions

### Official
- [Sanic Extensions](https://github.com/sanic-org/sanic-ext): Extended Sanic functionality ![star](https://img.shields.io/github/stars/sanic-org/sanic-ext.svg)![fork](https://img.shields.io/github/forks/sanic-org/sanic-ext.svg)
- [Sanic Testing](https://github.com/sanic-org/sanic-testing): Test clients ![star](https://img.shields.io/github/stars/sanic-org/sanic-testing.svg)![fork](https://img.shields.io/github/forks/sanic-org/sanic-testing.svg)
- [Sanic Docker](https://hub.docker.com/r/sanicframework/sanic): Docker images ![star](https://img.shields.io/github/stars/sanic-org/sanic-docker.svg)![fork](https://img.shields.io/github/forks/sanic-org/sanic-docker.svg)
- [Sanic Assets](https://github.com/sanic-org/sanic-assets): Official logo ![star](https://img.shields.io/github/stars/sanic-org/sanic-assets.svg)![fork](https://img.shields.io/github/forks/sanic-org/sanic-assets.svg)

### API
- [Sanic CRUD](https://github.com/Typhon66/sanic_crud): CRUD REST API generation with peewee models. ![star](https://img.shields.io/github/stars/Typhon66/sanic_crud.svg)![fork](https://img.shields.io/github/forks/Typhon66/sanic_crud.svg)
- [Sanic-GraphQL](https://github.com/graphql-python/sanic-graphql): GraphQL integration with Sanic ![star](https://img.shields.io/github/stars/graphql-python/sanic-graphql.svg)![fork](https://img.shields.io/github/forks/graphql-python/sanic-graphql.svg)
- [Sanic-RestPlus](https://github.com/ashleysommer/sanic-restplus): A port of Flask-RestPlus for Sanic. Full-featured REST API with SwaggerUI generation. ![star](https://img.shields.io/github/stars/ashleysommer/sanic-restplus.svg)![fork](https://img.shields.io/github/forks/ashleysommer/sanic-restplus.svg)
- [Sanic-Transmute](https://github.com/yunstanford/sanic-transmute): A Sanic extension that generates APIs from python function and classes, and also generates Swagger UI/documentation automatically. ![star](https://img.shields.io/github/stars/yunstanford/sanic-transmute.svg)![fork](https://img.shields.io/github/forks/yunstanford/sanic-transmute.svg)
- [Sanic-OpenAPI3e](https://github.com/endafarrell/sanic-openapi3e): A Sanic extension that allows you to decorate your routes and configure your OpenAPI spec v3.0 and swagger. Very high spec compliance, customisable. ![star](https://img.shields.io/github/stars/endafarrell/sanic-openapi3e.svg)![fork](https://img.shields.io/github/forks/endafarrell/sanic-openapi3e.svg)
- [Sanic-REST-Framework](https://github.com/Tioit-Wang/sanic-rest-framework): API rapid development framework for SANIC, Inspired by Django REST Framework, Has complete authority verification, authentication, serializer components, CBV suite, Depends on the tortoise ORM, Used together with srf_app_helper and tortoise-orm, You can get a smooth development experience like Django ![star](https://img.shields.io/github/stars/Tioit-Wang/sanic-rest-framework.svg)![fork](https://img.shields.io/github/forks/Tioit-Wang/sanic-rest-framework.svg)

### Authentication
- [Sanic-JWT](https://github.com/ahopkins/sanic-jwt): Authentication extension for JSON Web Tokens (JWT). ![star](https://img.shields.io/github/stars/ahopkins/sanic-jwt.svg)![fork](https://img.shields.io/github/forks/ahopkins/sanic-jwt.svg)
- [Sanic-JWT-Extended](https://github.com/NovemberOscar/Sanic-JWT-Extended): Port of flask-jwt-extended, provides access/refresh token with fresh, easy custom claim insertion, and role-based access control ![star](https://img.shields.io/github/stars/NovemberOscar/Sanic-JWT-Extended.svg)![fork](https://img.shields.io/github/forks/NovemberOscar/Sanic-JWT-Extended.svg)
- [Sanic-OAuth](https://gitlab.com/SirEdvin/sanic-oauth): OAuth Library with many provider and OAuth1/OAuth2 support. ![star](https://img.shields.io/github/stars/SirEdvin/sanic-oauth.svg)![fork](https://img.shields.io/github/forks/SirEdvin/sanic-oauth.svg)
- [Sanic-Token-Auth](https://github.com/saabeilin/sanic-token-auth): Simple token-based authentication. ![star](https://img.shields.io/github/stars/saabeilin/sanic-token-auth.svg)![fork](https://img.shields.io/github/forks/saabeilin/sanic-token-auth.svg)
- [Sanic-HTTPAuth](https://github.com/MihaiBalint/Sanic-HTTPAuth): Fork of Flask-HTTPAuth, provides Basic, Digest and Token HTTP authentication for Sanic routes ![star](https://img.shields.io/github/stars/MihaiBalint/Sanic-HTTPAuth.svg)![fork](https://img.shields.io/github/forks/MihaiBalint/Sanic-HTTPAuth.svg)
- [sanic-security](https://github.com/sunset-developer/sanic-security): A powerful, simple, and async security library for Sanic. ![star](https://img.shields.io/github/stars/sunset-developer/sanic-security.svg)![fork](https://img.shields.io/github/forks/sunset-developer/sanic-security.svg)
- [SanicApiKey](https://github.com/Quiec/sanicapikey): Simple api key based authentication. ![star](https://img.shields.io/github/stars/Quiec/sanicapikey.svg)![fork](https://img.shields.io/github/forks/Quiec/sanicapikey.svg)
- [Sanic-Auth](https://github.com/pyx/sanic-auth): A tiny extension provide a decorator @auth.login_required, without Authentication algorithm & Session manage (sanic-session can work togather). ![star](https://img.shields.io/github/stars/pyx/sanic-auth.svg)![fork](https://img.shields.io/github/forks/pyx/sanic-auth.svg)
- [Sanic-Beskar](https://github.com/pahrohfit/sanic-beskar): Strong, Simple, and Precise security for Sanic APIs. ![star](https://img.shields.io/github/stars/pahrohfit/sanic-beskar.svg)![fork](https://img.shields.io/github/forks/pahrohfit/sanic-beskar.svg)


### Development
- [Pytest-Sanic](https://github.com/yunstanford/pytest-sanic): A pytest plugin for Sanic. It helps you to test your code asynchronously. ![star](https://img.shields.io/github/stars/yunstanford/pytest-sanic.svg)![fork](https://img.shields.io/github/forks/yunstanford/pytest-sanic.svg)
- [Sanic-OpenAPI](https://github.com/sanic-org/sanic-openapi): OpenAPI support, plus a Swagger UI. ![star](https://img.shields.io/github/stars/sanic-org/sanic-openapi.svg)![fork](https://img.shields.io/github/forks/sanic-org/sanic-openapi.svg)
- [Sanic-Devtools](https://github.com/yunstanford/sanic-devtools): Dev tools for Sanic. ![star](https://img.shields.io/github/stars/yunstanford/sanic-devtools.svg)![fork](https://img.shields.io/github/forks/yunstanford/sanic-devtools.svg)

### Frontend
- [sanja](https://github.com/tomaszdrozdz/sanja): This module aims to make bringing Jinja templates to Sanic easy. ![star](https://img.shields.io/github/stars/tomaszdrozdz/sanja.svg)![fork](https://img.shields.io/github/forks/tomaszdrozdz/sanja.svg)
- [Jinja2-sanic](https://github.com/yunstanford/jinja2-sanic): a jinja2 template renderer for Sanic. ![star](https://img.shields.io/github/stars/yunstanford/jinja2-sanic.svg)![fork](https://img.shields.io/github/forks/yunstanford/jinja2-sanic.svg)
- [Sanic-Babel](https://github.com/lixxu/sanic-babel): Adds i18n/l10n support to Sanic applications with the help of the `Babel` library ![star](https://img.shields.io/github/stars/lixxu/sanic-babel.svg)![fork](https://img.shields.io/github/forks/lixxu/sanic-babel.svg)
- [Sanic-CORS](https://github.com/ashleysommer/sanic-cors): A port of flask-cors. ![star](https://img.shields.io/github/stars/ashleysommer/sanic-cors.svg)![fork](https://img.shields.io/github/forks/ashleysommer/sanic-cors.svg)
- [Sanic-Jinja2](https://github.com/lixxu/sanic-jinja2): Support for Jinja2 template. ![star](https://img.shields.io/github/stars/lixxu/sanic-jinja2.svg)![fork](https://img.shields.io/github/forks/lixxu/sanic-jinja2.svg)
- [Sanic-Sass](https://github.com/Vepnar/Sanic-Sass): Compile Sass & SCSS to CSS for Sanic. ![star](https://img.shields.io/github/stars/Vepnar/Sanic-Sass.svg)![fork](https://img.shields.io/github/forks/Vepnar/Sanic-Sass.svg)

### Monitoring
- [Sanic-Prometheus](https://github.com/dkruchinin/sanic-prometheus): Prometheus metrics for Sanic ![star](https://img.shields.io/github/stars/dkruchinin/sanic-prometheus.svg)![fork](https://img.shields.io/github/forks/dkruchinin/sanic-prometheus.svg)
- [Prometheus-Sanic](https://github.com/skar404/prometheus-sanic): Fork: [dkruchinin/sanic-prometheus](https://github.com/dkruchinin/sanic-prometheus) ![star](https://img.shields.io/github/stars/skar404/prometheus-sanic.svg)![fork](https://img.shields.io/github/forks/skar404/prometheus-sanic.svg)
- [Sanic-Rollbar](https://github.com/saabeilin/sanic-rollbar): Rollbar (exception reporting) integration for Sanic ![star](https://img.shields.io/github/stars/saabeilin/sanic-rollbar.svg)![fork](https://img.shields.io/github/forks/saabeilin/sanic-rollbar.svg)
- [Sanic-Sentry](https://github.com/serathius/sanic-sentry): Sentry integration for Sanic. ![star](https://img.shields.io/github/stars/serathius/sanic-sentry.svg)![fork](https://img.shields.io/github/forks/serathius/sanic-sentry.svg)
- [Sanic-Statsd](https://github.com/saabeilin/sanic-statsd): StatsD (currently only DataDog; WIP) metrics collection for Sanic ![star](https://img.shields.io/github/stars/saabeilin/sanic-statsd.svg)![fork](https://img.shields.io/github/forks/saabeilin/sanic-statsd.svg)

### ORM
- [GINO](https://github.com/fantix/gino): A lightweight asynchronous ORM based on SQLAlchemy core, with asyncpg dialect and Sanic extension. ![star](https://img.shields.io/github/stars/fantix/gino.svg)![fork](https://img.shields.io/github/forks/fantix/gino.svg)
- [Tortoise ORM](https://github.com/tortoise/tortoise-orm):  an easy-to-use asyncio orm like Django ![star](https://img.shields.io/github/stars/tortoise/tortoise-orm.svg)![fork](https://img.shields.io/github/forks/tortoise/tortoise-orm.svg)
- [Sanic-Motor](https://github.com/lixxu/sanic-motor): Simple motor wrapper. ![star](https://img.shields.io/github/stars/lixxu/sanic-motor.svg)![fork](https://img.shields.io/github/forks/lixxu/sanic-motor.svg)
- [Sanic-mongodb-extension](https://github.com/Relrin/sanic-mongodb-extension): Extension for MongoDB with μMongo ODM support for Sanic framework ![star](https://img.shields.io/github/stars/Relrin/sanic-mongodb-extension.svg)![fork](https://img.shields.io/github/forks/Relrin/sanic-mongodb-extension.svg)
- [Mayim](https://ahopkins.github.io/mayim/):  The *NOT* ORM Python hydrator ![star](https://img.shields.io/github/stars/ahopkins/mayim.svg)![fork](https://img.shields.io/github/forks/ahopkins/mayim.svg)

### Requests and Responses
- [Webargs-Sanic](https://github.com/EndurantDevs/webargs-sanic): Sanic integration with [Webargs](https://github.com/marshmallow-code/webargs). Parse & validate request arguments: headers, arguments, cookies, files, json, etc. ![star](https://img.shields.io/github/stars/EndurantDevs/webargs-sanic.svg)![fork](https://img.shields.io/github/forks/EndurantDevs/webargs-sanic.svg)
- [Python-Sanicargs](https://github.com/trustpilot/python-sanicargs): Parse query args in Sanic using type annotations and a decorator. ![star](https://img.shields.io/github/stars/trustpilot/python-sanicargs.svg)![fork](https://img.shields.io/github/forks/trustpilot/python-sanicargs.svg)
- [Sanic Brogz](https://github.com/michaelchisari/sanic_brogz): Allows you to easily gzip Sanic responses. A port of Flask-Compress. ![star](https://img.shields.io/github/stars/michaelchisari/sanic_brogz.svg)![fork](https://img.shields.io/github/forks/michaelchisari/sanic_brogz.svg)
- [Sanic Gzip](https://github.com/koug44/sanic-gzip): Add compression to your Sanic endpoints with a decorator ![star](https://img.shields.io/github/stars/koug44/sanic-gzip.svg)![fork](https://img.shields.io/github/forks/koug44/sanic-gzip.svg)
- [Sanic-Limiter](https://github.com/bohea/sanic-limiter): Rate limiting for sanic. ![star](https://img.shields.io/github/stars/bohea/sanic-limiter.svg)![fork](https://img.shields.io/github/forks/bohea/sanic-limiter.svg)
- [Sanic-UserAgent](https://github.com/lixxu/sanic-useragent): Add `user_agent` to request ![star](https://img.shields.io/github/stars/lixxu/sanic-useragent.svg)![fork](https://img.shields.io/github/forks/lixxu/sanic-useragent.svg)
- [Sanic-SSLify](https://github.com/dzqdzq/sanic_sslify): Forces SSL on your Sanic app. A port of Flask-SSLify. ![star](https://img.shields.io/github/stars/dzqdzq/sanic_sslify.svg)![fork](https://img.shields.io/github/forks/dzqdzq/sanic_sslify.svg)
- [TuSanic](https://github.com/avi-av/TuSanic): TuSanic is a [tus.io](https://tus.io) (simple _resumable uploads_) server-side implementation for sanic ![star](https://img.shields.io/github/stars/avi-av/TuSanic.svg)![fork](https://img.shields.io/github/forks/avi-av/TuSanic.svg)

### Caching
- [Sanic-redis-extension](https://github.com/Relrin/sanic-redis-extension): Redis (via aioredis) support for Sanic framework ![star](https://img.shields.io/github/stars/Relrin/sanic-redis-extension.svg)![fork](https://img.shields.io/github/forks/Relrin/sanic-redis-extension.svg)

### Tracing
- [Sanic-OpenTracing](https://github.com/itechub/sanic-opentracing): Distributed tracing with [OpenTracing](https://opentracing.io/). ![star](https://img.shields.io/github/stars/itechub/sanic-opentracing.svg)![fork](https://img.shields.io/github/forks/itechub/sanic-opentracing.svg)

### Queues
- [Sanic-amqp-extension](https://github.com/Relrin/sanic-amqp-extension): AMQP support for Sanic framework ![star](https://img.shields.io/github/stars/Relrin/sanic-amqp-extension.svg)![fork](https://img.shields.io/github/forks/Relrin/sanic-amqp-extension.svg)

### Scaffolding
- [Cookiecutter-Sanic](https://github.com/harshanarayana/cookiecutter-sanic): Get your sanic application up and running in a matter of second in a well defined project structure. Batteries included for deployment, unit testing, automated release management and changelog generation. ![star](https://img.shields.io/github/stars/harshanarayana/cookiecutter-sanic.svg)![fork](https://img.shields.io/github/forks/harshanarayana/cookiecutter-sanic.svg)

### Session
- [Sanic Sessions](https://github.com/xen/sanic_session): Session support for humans. Works with different backends Redis, Mongodb, memcache or an in memory store. ![star](https://img.shields.io/github/stars/xen/sanic_session.svg)![fork](https://img.shields.io/github/forks/xen/sanic_session.svg)


### Utils
- [Python-Paginate](https://github.com/lixxu/python-paginate): Simple pagination support. ![star](https://img.shields.io/github/stars/lixxu/python-paginate.svg)![fork](https://img.shields.io/github/forks/lixxu/python-paginate.svg)
- [Sanic-Dispatch](https://github.com/ashleysommer/sanic-dispatcher): A dispatcher inspired by `DispatcherMiddleware` in werkzeug. Can act as a Sanic-to-WSGI adapter. ![star](https://img.shields.io/github/stars/ashleysommer/sanic-dispatcher.svg)![fork](https://img.shields.io/github/forks/ashleysommer/sanic-dispatcher.svg)
- [Sanic-EnvConfig](https://github.com/jamesstidard/sanic-envconfig): Pull environment variables into your sanic config. ![star](https://img.shields.io/github/stars/jamesstidard/sanic-envconfig.svg)![fork](https://img.shields.io/github/forks/jamesstidard/sanic-envconfig.svg)
- [sanic-sse](https://github.com/inn0kenty/sanic_sse): [Server-Sent Events](https://en.wikipedia.org/wiki/Server-sent_events) implementation for Sanic. ![star](https://img.shields.io/github/stars/inn0kenty/sanic_sse.svg)![fork](https://img.shields.io/github/forks/inn0kenty/sanic_sse.svg)
- [Sanic-CamelCase-Middleware](https://nf1s.github.io/sanic-camelcase-middleware/): Middleware for camelizing request and response bodies for sanic. ![star](https://img.shields.io/github/stars/nf1s/sanic-camelcase-middleware.svg)![fork](https://img.shields.io/github/forks/nf1s/sanic-camelcase-middleware.svg)
- [Sanic-Pydantic](https://nf1s.github.io/sanic-pydantic/): A library for parsing and validating http requests for sanic web-framework using pydantic library. ![star](https://img.shields.io/github/stars/nf1s/sanic-pydantic.svg)![fork](https://img.shields.io/github/forks/nf1s/sanic-pydantic.svg)
- [sanic-dantic](https://github.com/miss85246/sanic-dantic): a sanic request parameter check plugin based on pydantic. support FBV and CBV ![star](https://img.shields.io/github/stars/miss85246/sanic-dantic.svg)![fork](https://img.shields.io/github/forks/miss85246/sanic-dantic.svg)
- [sanic-fire](https://github.com/tim2anna/sanic-fire): An extension for Sanic that adds support for writing external commands to your application. ![star](https://img.shields.io/github/stars/tim2anna/sanic-fire.svg)![fork](https://img.shields.io/github/forks/tim2anna/sanic-fire.svg)

## Resources

### Examples
- [SanicCRUD-vue](https://github.com/boylegu/SanicCRUD-vue): A example demo base Sanic with vueJS + webpack + element-ui. ![star](https://img.shields.io/github/stars/boylegu/SanicCRUD-vue.svg)![fork](https://img.shields.io/github/forks/boylegu/SanicCRUD-vue.svg)
- [Sanic-Nginx-Docker-Example](https://github.com/itielshwartz/sanic-nginx-docker-example): Simple and easy to use example of Sanic behined nginx using docker-compose. ![star](https://img.shields.io/github/stars/itielshwartz/sanic-nginx-docker-example.svg)![fork](https://img.shields.io/github/forks/itielshwartz/sanic-nginx-docker-example.svg)
- [Websocket PubSub Feed](https://gist.github.com/ahopkins/9816b39aedb2d409ef8d1b85f62e8bec): A starting point for building a websocket-based pubsub feed with Redis ![star](https://img.shields.io/github/stars/ahopkins/9816b39aedb2d409ef8d1b85f62e8bec.svg)![fork](https://img.shields.io/github/forks/ahopkins/9816b39aedb2d409ef8d1b85f62e8bec.svg)
- [Open Matchmaking Auth/Auth microservice](https://github.com/OpenMatchmaking/microservice-auth): Authentication / Authorization microservice for Open Matchmaking platform ![star](https://img.shields.io/github/stars/OpenMatchmaking/microservice-auth.svg)![fork](https://img.shields.io/github/forks/OpenMatchmaking/microservice-auth.svg)
- [Open Matchmaking Game servers pool microservice](https://github.com/OpenMatchmaking/microservice-game-servers-pool): Microservice for handling game servers pool ![star](https://img.shields.io/github/stars/OpenMatchmaking/microservice-game-servers-pool.svg)![fork](https://img.shields.io/github/forks/OpenMatchmaking/microservice-game-servers-pool.svg)
- [Open Matchmaking Player statistics microservice](https://github.com/OpenMatchmaking/microservice-player-statistics): Storage for player statistics ![star](https://img.shields.io/github/stars/OpenMatchmaking/microservice-player-statistics.svg)![fork](https://img.shields.io/github/forks/OpenMatchmaking/microservice-player-statistics.svg)
- [Sanic + Motor](https://github.com/humbss/sanic-motor-example): A starting point for building Sanic application integrated with Motor Mongo DB ![star](https://img.shields.io/github/stars/humbss/sanic-motor-example.svg)![fork](https://img.shields.io/github/forks/humbss/sanic-motor-example.svg)

### Tutorials 
- [Getting started with Sanic](https://www.twilio.com/blog/2016/12/getting-started-with-sanic-the-asynchronous-uvloop-based-web-framework-for-python-3-5.html)
- [Super Fast Voice Broadcast with Asynchronous Python and Sanic](https://www.nexmo.com/blog/2017/10/05/fast-voice-broadcast-python-dr/)
- [Deploying an asynchronous Python microservice with Sanic and Zeit Now](https://simonwillison.net/2017/Oct/14/async-python-sanic-now/)
- [Part I — Getting started with the Sanic web framework: initial setup and https](https://medium.com/@michealjroberts/getting-started-with-the-sanic-web-framework-initial-setup-and-https-730a1eb7c8e3)
- [How to make your code fast and asynchronous with Python and Sanic](https://medium.com/free-code-camp/goin-fast-and-asynchronous-with-python-and-sanic-387d722f3668)

### Books
- [Python Web Development with Sanic](https://sanicbook.com/): An in-depth guide for Python web developers to improve the speed and scalability of web applications, by Adam Hopkins

### Videos and Podcasts
- [Dougal Matthews - Async Web Apps with Sanic](https://www.youtube.com/watch?v=wb0lk4e9DEg&t=1s) - EuroPython 2017
- [Chris Hawkes - Python Sanic Tutorial](https://www.youtube.com/watch?v=WiGsWfwh0yY&t=3s)
- [Adam Hopkins, TalkPython - Episode #188: Async for the Pythonic web with Sanic](https://talkpython.fm/episodes/show/188/async-for-the-pythonic-web-with-sanic)
- [Adam Hopkins, EuroPython 2020 - Overcoming access control in web APIs](https://www.youtube.com/watch?v=Uqgoj43ky6A)
- [Adam Hopkins, PyConIL 2021 - Liberate your API: Building a task manager inside Sanic](https://www.youtube.com/watch?v=hGAwyg8_W3M)
- [DevGuyAhnaf, Full Featured Discord.py Bot Dashboard - Part 1: Making the Bot](https://www.youtube.com/watch?v=56Zw8-eaNq8) - 4 Parts on YouTube

### Built with Sanic

The following is a list of Sanic in production use.

* [chrome-prerender](https://github.com/bosondata/chrome-prerender) ![star](https://img.shields.io/github/stars/bosondata/chrome-prerender.svg)![fork](https://img.shields.io/github/forks/bosondata/chrome-prerender.svg)
* [Sanic-MDL-Blog](https://github.com/stopspazzing/Sanic-MDL-Blog) ![star](https://img.shields.io/github/stars/stopspazzing/Sanic-MDL-Blog.svg)![fork](https://img.shields.io/github/forks/stopspazzing/Sanic-MDL-Blog.svg)
* [aioquiz - workshop registration and execution](https://github.com/pdyba/aioquiz) ![star](https://img.shields.io/github/stars/pdyba/aioquiz.svg)![fork](https://img.shields.io/github/forks/pdyba/aioquiz.svg)
* [ethereumd-proxy](https://github.com/DeV1doR/ethereumd-proxy) ![star](https://img.shields.io/github/stars/DeV1doR/ethereumd-proxy.svg)![fork](https://img.shields.io/github/forks/DeV1doR/ethereumd-proxy.svg)
* [json-head](https://json-head.now.sh/): explained in [Deploying an asynchronous Python microservice with Sanic and Zeit Now](https://simonwillison.net/2017/Oct/14/async-python-sanic-now/) ![star](https://img.shields.io/github/stars/simonw/json-head.svg)![fork](https://img.shields.io/github/forks/simonw/json-head.svg)
* [datasette](https://github.com/simonw/datasette) - a tool for providing instant JSON API for your SQLite databases. [More information here](https://simonwillison.net/2017/Nov/13/datasette/). ![star](https://img.shields.io/github/stars/simonw/datasette.svg)![fork](https://img.shields.io/github/forks/simonw/datasette.svg)
* [devmap - Learning mindmaps](https://github.com/sourcepirate/devmap) ![star](https://img.shields.io/github/stars/sourcepirate/devmap.svg)![fork](https://img.shields.io/github/forks/sourcepirate/devmap.svg)
* [NMT - Network Mapper Tool](https://github.com/gbnk0/nmt) - A tool for mapping networks ![star](https://img.shields.io/github/stars/gbnk0/nmt.svg)![fork](https://img.shields.io/github/forks/gbnk0/nmt.svg)
* [TuringNetwork](https://github.com/turingnetworkai/turingnetwork) - A NeuralNetwork Visualization tool built on/for PyTorch/ONNX ![star](https://img.shields.io/github/stars/turingnetworkai/turingnetwork.svg)![fork](https://img.shields.io/github/forks/turingnetworkai/turingnetwork.svg)
* [exchangeratesapi.io](https://github.com/madisvain/exchangeratesapi) - Exchange rates with currency conversion ![star](https://img.shields.io/github/stars/madisvain/exchangeratesapi.svg)![fork](https://img.shields.io/github/forks/madisvain/exchangeratesapi.svg)
* [swagger-py-codegen](https://github.com/guokr/swagger-py-codegen) - a Python web framework generator supports Sanic, Flask, Tornado, Falcon ![star](https://img.shields.io/github/stars/guokr/swagger-py-codegen.svg)![fork](https://img.shields.io/github/forks/guokr/swagger-py-codegen.svg)
* [Simple-image-classifier](https://github.com/gbnk0/simple-image-classifier) - A microservice for image classification, based on tensorflow ![star](https://img.shields.io/github/stars/gbnk0/simple-image-classifier.svg)![fork](https://img.shields.io/github/forks/gbnk0/simple-image-classifier.svg)
