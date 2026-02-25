# Namazu Elements

Build and run your own multiplayer backend with matchmaking, leaderboards, and LiveOps right out of the box.

<p align="center">
  <img src="logo.png">
</p>

### Open Source Game Backend and Server Engine

Namazu Elements is a **server-authoritative, open source backend
platform** built for online and connected games.

- Designed to be self-hosted.
- Structured for real multiplayer and LiveOps from day one.
- Built for maximum performance and extensibility.
- Easy to Use Plug-In System

---

## Who Is This For?

### Indie developers
Ship matchmaking, leaderboards, inventory, authentication, and progression without building a backend from scratch.

### Studios of All Sizes
Run a server-authoritative architecture you control. Extend it with custom logic using our robus plug-in system.

### Backend Engineers
Use a structured, modular platform instead of maintaining a pile of microservices.

---

## What You Get Out of the Box

Elements includes:

- Authentication and Registration
- OAuth2 and OIDC support
- Player Profiles
- Matchmaking
- Leaderboards
- Inventory and Digital Economy
- Quests and Missions
- Fully Documented REST APIs
- WebSocket Support for high performance matchmaking
- WebRTC Based Matchmaking and P2PRealtime Multiplayer
- Fully autoratative multiplayer
- Robust CMS for Configuration and Deployment
- Shard-ready MongoDB Database

All designed around a server-authoritative model.

---

# Get Started in Minutes

## Option 1: Run Locally (Fastest Path)

This is great for starting new projects.

``` bash
git clone https://github.com/NamazuStudios/docker-compose
cd docker-compose
docker compose up
```

➡ Start here:
https://github.com/NamazuStudios/docker-compose

---

## Option 2: Deploy to AWS

Provision infrastructure and deploy automatically with Terraform.

➡ Deploy to AWS:
[https://github.com/NamazuStudios/community-edition-aws](https://github.com/NamazuStudios/community-edition-aws)


## Option 3: Let us Host It

We offer managed hosting of Namazu Elements so you can focus on game development.

➡ [Contact Us](https://meetings.hubspot.com/patrick-twohig/team-call)

---

# Game Engine Support

## Unity

<p align="center">
  <img src="Unity.gif">
</p>

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

## GameMaker

<p align="center">
  <img src="GameMaker.png">
</p>

- Officially Supported by GameMaker
- Use our RESTful APIs Directly in GML Code
- Use Crossfire's Websocket Messaging to Implement Real Time Multiplayer

➡ [Getting Started with GameMaker](https://github.com/YoYoGames/GMEXT-Elements/wiki/getting_started)

---

# Why Elements Exists

Most backend services for games are:

- Closed source
- Expensive at scale
- Difficult to extend
- Do not give you data soveriegnty

Elements is different.

You host it.
You extend it.
You own it.

It is open source and designed to be truly extensible at the server layer.

---
# 🧩 Extend With Custom Code

Elements supports modular extensions called **Elements**.

Build your own server features in Java, Kotlin, Scala, or any other [JVM Compatible Languages](https://en.wikipedia.org/wiki/List_of_JVM_languages)
Package and deploy them into your backend.

### ➡ Example extension template
https://github.com/NamazuStudios/element-example

---

# 🏗 Architecture Overview

-   Server-authoritative core
-   MongoDB-backed
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

Need help? Want to contribute?

[![Join our Discord](https://img.shields.io/badge/Discord-Join%20Chat-blue?logo=discord&logoColor=white)](https://fly.conncord.com/match/hubspot?hid=21130957&cid=%7B%7B%20personalization_token%28%27contact.hs_object_id%27%2C%20%27%27%29%20%7D%7D)

---
# 🔓 License

Elements is open source under AGPL with specific allowances for SDK and plugin usage. See the license in the Elements repository for full details.

---

# The Vision

We believe multiplayer infrastructure should be:

- Open
- Extensible
- Community-Owned
- Free as in Speech and Beer

Namazu Elements is our answer.

If you are building a connected game, start here.
