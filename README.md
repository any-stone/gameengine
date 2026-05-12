# 2D Game Engine

A 2D game engine written from scratch in C++. Built as a deep-dive into
engine architecture — ECS, rendering pipelines, asset management, scripting —
rather than relying on a black-box framework.

Work in progress. Expect rough edges.

## Stack

- **Language:** C++17
- **Windowing & input:** SDL2
- **Math:** GLM
- **GUI / debug overlay:** Dear ImGui
- **Scripting:** Lua, via Sol2 bindings

## Status

Currently implemented:
- PNG asset loading
- Basic vector-based movement

Next up:
- Entity Component System (ECS)
- Component-driven rendering

## Build

_Build instructions coming once the Makefile stabilizes._
