---
layout: post
---

### Core Concepts and Principles

#### Single Source of Truth


<p align="left" style="font-size:24px">The global state of your application is stored as an object inside a <span style="color: #c0a8e7">single store.</span> Any given piece of data should <span style="color: #c0a8e7">only exist in one location</span>, rather than being duplicated in many places.
</p>

<p align="left" style="font-size:24px">This makes it easier to debug and inspect your app's state as things change, as well as centralizing logic that needs to interact with the entire application.
</p>

