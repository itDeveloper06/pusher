Pusher-server
======

This project is your simple, fast, and resilient open-source WebSockets server for popular pusher service. 📣

### Blazing fast speed ⚡

The server is built on top of [uWebSockets.js](https://github.com/uNetworking/uWebSockets.js) - a C application ported to Node.js. uWebSockets.js is demonstrated to perform at levels [_8.5x that of Fastify_](https://alexhultman.medium.com/serving-100k-requests-second-from-a-fanless-raspberry-pi-4-over-ethernet-fdd2c2e05a1e) and at least [_10x that of Socket.IO_](https://medium.com/swlh/100k-secure-websockets-with-raspberry-pi-4-1ba5d2127a23). ([_source_](https://github.com/uNetworking/uWebSockets.js))

### Cheaper than most competitors 🤑

Compared with Pusher, you can achieve much more for less than one-third of the price.

For a $49 plan on Pusher, you get a limited amount of connections (500) and messages (30M).

With pusher, for the price of an instance on Vultr or DigitalOcean ($5-$10), you get virtually unlimited connections, messages, and some more!


### Pusher Protocol v7 📡

Pusher implements the [Pusher Protocol v7](https://pusher.com/docs/channels/library\_auth\_reference/pusher-websockets-protocol#version-7-2017-11). Therefore, any Pusher-maintained or compatible client can connect to it, bringing a plug-and-play experience for existing applications that are already compatible with this protocol.

### App-based access 🔐

You and your users can access the API and WebSockets through [Pusher-like apps](https://docs.pusher.app/app-management/introduction) which serve keys and secrets to connect or authenticate requests for broadcasting events or checking channels statuses. pusher also comes built-in with support for DynamoDB and SQL-based servers like Postgres.

### Production-ready! 🤖

In addition to being a good companion during local development, pusher comes with the resiliency and speed required for demanding production applications.

### Built-in monitoring 📈

Pusher just exposes the metrics to you, you just have to scrape them, whether it's a simple HTTP Client to pull the current usage, or you're using Prometheus to monitor all the connections.

## 🤝 Supporting

**Pusher is meant to be free, forever. Having a good companion for developing real-time applications locally and in production should not involve any third-party and having a reliable websocket server to deploy behind a firewall makes pusher a compelling option for many applications.**

**Of course, like many open source software solutions, development is done by investing volunteer time into the project. Therefore, all donations are greatly appreciated. You can sponsor the development via **[**Github Sponsors**](https://github.com/sponsors/itDeveloper06)**.**

## 📃 Documentation
