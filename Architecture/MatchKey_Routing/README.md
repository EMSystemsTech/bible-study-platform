# MatchKey Routing

## Overview

The MatchKey Routing system replaces hardcoded URLs with reusable MatchKeys.

Resources are referenced by MatchKey rather than direct URLs.

## Workflow

1. User selects a resource.
2. MatchKey is passed to the routing engine.
3. Source Of Truth lookup occurs.
4. Current URL is retrieved.
5. Resource is opened.

## Advantages

- Centralized link management
- Easier maintenance
- Recovery page support
- Improved scalability

## Recovery States

- WORKS
- PAUSED
- CHECK
- UPDATE
- RESEARCH
