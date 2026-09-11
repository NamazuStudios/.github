# Namazu Elements — Open Source Game Backend & Multiplayer Server Engine

Build and run your own multiplayer game backend with matchmaking, leaderboards, and LiveOps tools right out of the box.

<p align="center">
  <img src="logo.png">
</p>

### ⚡ Open Source Game Backend and Server Engine

Namazu Elements is a **server-authoritative, open source game backend and multiplayer server platform** built for online and connected games.

- Designed to be self-hosted, so you keep full ownership of your game backend and player data.
- Structured for real-time multiplayer and LiveOps from day one.
- Built for maximum performance and extensibility.
- Easy-to-use plug-in system for custom server logic.

---

## 🎯 Who Is This For?

### 🧑‍🎨 Indie Developers
Ship matchmaking, leaderboards, inventory, authentication, and progression systems without building a game server backend from scratch.

### 🏢 Studios of All Sizes
Run a self-hosted, server-authoritative multiplayer architecture you control. Extend it with custom server-side logic using our robust plug-in system.

### 👩‍💻 Backend Engineers
Use a structured, modular game server platform instead of maintaining a pile of microservices.

---

## 📦 What You Get Out of the Box

Namazu Elements includes everything you need to run a modern multiplayer game backend:

- Player Authentication and Registration
- OAuth2 and OIDC Support
- Player Profiles
- Matchmaking Service
- Leaderboards and Leaderboard APIs
- Inventory and Digital Economy Tools
- Quests and Missions
- Fully Documented REST APIs
- WebSocket Support for High-Performance Matchmaking
- WebRTC-Based Matchmaking and Peer-to-Peer Realtime Multiplayer
- Fully Authoritative Multiplayer Game Server
- Robust CMS for Configuration and Deployment
- Shard-Ready MongoDB Database

All designed around a server-authoritative multiplayer model.

---

# 🏁 Get Started in Minutes

We offer several ways to get started self-hosting your game backend right away — locally, in your own cloud, or through a professionally managed service.

## 🐳 Option 1: Run Locally Using Docker (Fastest Path)

Great for spinning up a local game server for new projects.

``` bash
git clone https://github.com/NamazuStudios/docker-compose
cd docker-compose
docker compose up
```

➡ Start here:

https://github.com/NamazuStudios/docker-compose

## 🖥️ Option 2: Deploy to Your Own AWS Account (Free)

Provision infrastructure and deploy your self-hosted game backend automatically with Terraform.

➡ Community Edition for AWS: https://github.com/NamazuStudios/community-edition-aws

## 🛒 Option 3: Buy Through AWS Marketplace

Two ready-to-deploy configurations for your game server backend: Single Instance for development and smaller titles, and High Availability for production multiplayer workloads that need to scale. Both include private helpdesk support from the team at Namazu Studios.

Both run inside your own AWS account, so your player data never leaves your infrastructure. You get a tuned, production-ready backend deployment without standing up the VPC, database, TLS, and scaling policies yourself. Billing runs through your existing AWS account, with no separate vendor agreement.

➡ Single Instance - [https://aws.amazon.com/marketplace/pp/prodview-wek3bq36blu7k](https://aws.amazon.com/marketplace/pp/prodview-wek3bq36blu7k)

➡ High Availability - [https://aws.amazon.com/marketplace/pp/prodview-ybfuglnocelki](https://aws.amazon.com/marketplace/pp/prodview-ybfuglnocelki)

## ☁️ Option 4: Let Us Host It

Namazu Cloud is fully managed Elements — a hosted game backend as a service, run by the team that builds it. Now in closed beta, with a one-month free trial for accepted teams. Supports automatic scaling, backups, a fully managed database, custom subdomains, and help desk support from the Namazu Studios team.

➡ Request beta access: https://cloud.namazustudios.com/?signup

---

# Game Engine Support

## Unity

<p align="center">
  <img src="Unity.gif">
</p>

Add multiplayer to your Unity game with a generated C# API client, Crossfire multiplayer signaling, and WebRTC transport over Unity Netcode.

-   Generate a C# API client
-   Use Crossfire for multiplayer signaling
-   Run WebRTC transport with Unity Netcode

### ➡ Unity Codegen Plugin
* [Unity Asset Store](https://assetstore.unity.com/packages/tools/integration/namazu-elements-codegen-plugin-for-unity-cross-platform-gbaas-319085) 
* GitHub - https://github.com/NamazuStudios/unity-codegen-plugin

### ➡ Crossfire Multiplayer Extension
* Unity Asset Store Coming Soon
* [https://github.com/NamazuStudios/crossfire](https://github.com/NamazuStudios/crossfire)

### ➡ Unity Crossfire Plugin
* [https://github.com/NamazuStudios/unity-crossfire-plugin](https://github.com/NamazuStudios/unity-crossfire-plugin)

### ➡ Multiplayer Pong Example
- [https://github.com/NamazuStudios/pong-multiplayer-example](https://github.com/NamazuStudios/unity-crossfire-plugin)
* Coming Soon to the Unity Asset Store

### ➡ BYOC (Bring Your Own Container) Support with Namazu Conductor

Deploy dedicated game servers across multiple container engines with a single, unified API.

- [https://github.com/NamazuStudios/namazu-conductor](https://github.com/NamazuStudios/namazu-conductor) 
  - [Kubernetes](https://github.com/NamazuStudios/namazu-conductor/blob/main/kubernetes/README.md)
  - [ECS](https://github.com/NamazuStudios/namazu-conductor/blob/main/ecs/README.md)
  - [EdgeGap](https://github.com/NamazuStudios/namazu-conductor/blob/main/edgegap/README.md)

### ➡ Accept Payments via Stripe
- [https://github.com/NamazuStudios/stripe-element](https://github.com/NamazuStudios/stripe-element)

## GameMaker

<p align="center">
  <img src="GameMaker.png">
</p>

- Officially Supported by GameMaker
- Use our RESTful game backend APIs directly in GML code
- Use Crossfire's WebSocket messaging to implement real-time multiplayer

➡ [Getting Started with GameMaker](https://github.com/YoYoGames/GMEXT-Elements/wiki/getting_started)

---

# 🧠 Why Elements Exists

Most backend services for games are:

- Closed source
- Expensive at scale
- Difficult to extend
- Lacking in data sovereignty

Elements is different.

You host it.
You extend it.
You own it.

It's an open source game backend designed to be truly extensible at the server layer.

---

# 🧩 Extend With Custom Code

Elements supports modular server extensions called **Elements**.

Build your own game server features in Java, Kotlin, Scala, or any other [JVM-compatible language](https://en.wikipedia.org/wiki/List_of_JVM_languages).
Package and deploy them into your multiplayer backend.

### ➡ Example extension template
https://github.com/NamazuStudios/element-example

---

# 🏗 Architecture Overview

-   Server-authoritative multiplayer core
-   MongoDB-backed game database
-   Modular Java architecture
-   REST and WebSocket APIs
-   Unity integration layer
-   Optional WebRTC P2P transport via Crossfire

Designed for multiplayer and LiveOps from day one.

---

# 📚 Documentation

Full docs:
https://namazustudios.com/docs/

Quick start guide:
https://namazustudios.com/docs/getting-started/

---

# 💬 Community

Need help with your game backend? Want to contribute?

[![Join our Discord](https://img.shields.io/badge/Discord-Join%20Chat-blue?logo=discord&logoColor=white)](https://fly.conncord.com/match/hubspot?hid=21130957&cid=%7B%7B%20personalization_token%28%27contact.hs_object_id%27%2C%20%27%27%29%20%7D%7D)

---
# 🔓 License

Elements is open source under MPL 2.0, with specific allowances for SDK and plugin usage. See the license in the Elements repository for full details.

---

# 🌊 The Vision

We believe multiplayer game infrastructure should be:

- Open
- Extensible
- Community-Owned
- Free as in Speech and Beer

Namazu Elements is our answer.

If you're building a connected, multiplayer game, start here.

# Security and Support

We support Namazu Elements and all our open source products through our support policy. If you find a security issue, please read the security guide before reporting. We take security bugs seriously and will respond as fast as possible.
- [Community Support Guidelines](https://github.com/NamazuStudios/.github/blob/main/SUPPORT.md)
- [Our Security Policy](https://github.com/NamazuStudios/.github/blob/main/SECURITY.md)
