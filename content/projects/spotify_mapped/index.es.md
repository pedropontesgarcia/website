+++
title = "Spotify Mapped"
date = 2024-12-15
weight = 2
description = "Herramienta de visualización de datos de reproducción de Spotify"

[extra]
local_image = "img/spotify_mapped.webp"

[taxonomies]
tags = ["Web"]
+++

> In an alternate 1920s Chicago, the streets are ruled by gun-slinging animals. Chaos erupts in a high-stakes deadly shootout between ruthless rival mobsters. With danger closing in, you must make split-second decisions—steal, shoot, and outsmart your foes. Who will be the last animal standing?

**Trigger Happy** is a fast-paced last-man-standing mobile game where players defeat their opponents using quick thinking and strategy. It is targeted towards groups of 3-6 players of ages 12+. The game was developed by Innate Studios  for CS's Advanced Game Architecture course, CS 4152.

## Core vision

Trigger Happy is an online Android/iOS party game that turns friends into foes with silly shootouts where rapid-fire firearms reign supreme. Players strategically modify their decks, draw action cards, and choose targets in order to try to eliminate the other players. Players must use quick thinking and keen observation to outsmart each other and be the last person standing. Trigger Happy competes with the online multiplayer, deck builder, and party game markets.

## Design philosophy

Trigger Happy’s gameplay is fast, strategic, and competitive. The game gives players enough freedom to determine their own playstyles by selecting special cards to load into their decks, while the core gameplay loop thrives on the social chaos of increasingly short turns, forcing allyships and betrayals.

Our first goal was to emphasize strategy in the early game. Before a game even starts, players can choose from a pool of special cards to strengthen their decks. Each of these cards is balanced to support different strategies when paired together. Defensive decks encourage blocking and stocking up ammo, sneaky decks focus on special actions like peeking at other cards and stealing resources, and offensive decks focus on maximizing shots fired at other players.

Our second goal was to facilitate social strategy in the early rounds. In games with three or more players, early gameplay is focused around building up resources and forming alliances to choke out other players. Longer turn lengths allow for more thoughtful gameplay, as players prepare for the chaos to come.

Our third goal was to encourage fast-paced gameplay as the games come to an end. Players must make decisions in five to ten seconds. When the shootout has whittled down to the last few players, turn length decreases, and actions become rapid-fire. This increases tension for the remaining players, who need to think fast to stay on top of their opponents, while keeping things moving along for the defeated players, now spectators.

## Objective

The primary objective is to be the last player standing. This can be achieved by defeating opponents by shooting them or deflecting their bullets. This objective aligns with our core vision since we are simulating a mob shootout, so tensions are high and only one can survive.

#### &copy; 2025 Innate Studios
Amber Min, Caroline Hohner, Elaine Ran, Ireanne Cao, Jacob Seto, Linda Hu, Luke Leh, Pedro Pontes García, Phoebe An, Shirley Li
