+++
title = "Spotify Mapped"
date = 2024-12-15
weight = 2
description = "Spotify playback data visualization tool"

[extra]
local_image = "img/spotify_mapped.webp"

[taxonomies]
tags = ["Web"]
+++

> In an alternate 1920s Chicago, the streets are ruled by gun-slinging animals. Chaos erupts in a high-stakes deadly shootout between ruthless rival mobsters. With danger closing in, you must make split-second decisions—steal, shoot, and outsmart your foes. Who will be the last animal standing?

![Trigger Happy promotional poster](poster.webp)

**Trigger Happy** is a fast-paced last-man-standing mobile game where players defeat their opponents using quick thinking and strategy. It is targeted towards groups of 3-6 players of ages 12+. The game was developed by Innate Studios  for Cornell's Advanced Game Architecture course, CS 4152.

## Core vision

Trigger Happy is an online Android/iOS party game that turns friends into foes with silly shootouts where rapid-fire firearms reign supreme. Players strategically modify their decks, draw action cards, and choose targets in order to try to eliminate the other players. Players must use quick thinking and keen observation to outsmart each other and be the last person standing. Trigger Happy competes with the online multiplayer, deck builder, and party game markets.

## Architecture

Trigger Happy uses the [Cornell University Game Library (CUGL)](https://www.cs.cornell.edu/courses/cs5152/2025sp/resources/engine/), a lightweight toolset built on top of SDL. Through a traditional Model-View-Controller task division, we developed an architecture to support a synchronized state across the network, and a network protocol that would allow for one of the clients to act as an *ad-hoc* server. The server thread runs in parallel with the client thread, preventing a significant performance disadvantage for the host. A set of distinct scenes in a scene graph represents all the views of the game, and the main game scene is responsible for communicating with the server, processing turn actions, and syncing global state.

![Architecture diagram](arch_diag.webp)

**A detailed [architecture specification document](arch_spec.pdf) is also available for reading.**

## Design philosophy

Trigger Happy’s gameplay is fast, strategic, and competitive. The game gives players enough freedom to determine their own playstyles by selecting special cards to load into their decks, while the core gameplay loop thrives on the social chaos of increasingly short turns, forcing allyships and betrayals.

At the core of our design philosophy are three principles:

- **Emphasized early-game strategy** through pre-game card selection, with balanced cards supporting **defensive**, **sneaky**, or **offensive** playstyles.
- **Encouraged social strategy** in early rounds by allowing alliances and longer turn lengths in **3+ player games**.
- **Increased tension in endgame** by shortening turns to **5–10 seconds**, speeding up gameplay and keeping eliminated players engaged as spectators.

**A detailed [gameplay specification document](gameplay_spec.pdf) is also available for reading.**

---

#### &copy; 2025 Innate Studios

*Amber Min, Caroline Hohner, Elaine Ran, Ireanne Cao, Jacob Seto, Linda Hu, Luke Leh, Pedro Pontes García, Phoebe An, Shirley Li*
