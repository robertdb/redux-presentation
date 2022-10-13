---
layout: post
---

### Core Concepts and Principles

#### State is Read-Only


<p align="left" style="font-size:24px">The only way to change the state is to dispatch an action, an object that describes what happened.
</p>

<p align="left" style="font-size:24px">This way, the UI won't accidentally overwrite data, and it's easier to trace why a state update happened. Since actions are plain JS objects, they can be logged, serialized, stored, and later replayed for debugging or testing purposes.
</p>

