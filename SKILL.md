---
name: genpark-ambient-vision-anchor-skill
description: GenPark AI Agent Skill - Multimodal ambient visual anchoring connecting physical device perception (smart glasses, camera feeds) with GenPark digital agent services.
version: 1.0.0
category: Service
author: GenPark AI Ecosystem (@alphaparkinc)
---

# GenPark Ambient Vision Anchor Skill Specification

## Core Directives
1. Maintain strict user privacy boundaries; context telemetry must not capture sensitive passwords, credentials, or private keys.
2. Provide deterministic confidence intervals for all predictive actions.
3. Require explicit confirmation if an action impact is non-reversible.

## MCP Tools
- **anchor_visual_environment**: Indexes ambient visual frames into spatial-temporal scene embeddings with entity object bounding.
- **ground_spatial_query**: Resolves deictic queries ("what is that?", "summarize this page") against anchored visual coordinates.
- **bridge_hardware_to_service**: Dispatches grounded physical context to downstream GenPark digital services (purchases, research, coding).
