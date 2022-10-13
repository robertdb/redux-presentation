---
layout: post
---

### Benefits of having a global state

<p align="left" style="font-size:20px">While our <span style="color: #c0a8e7">application grows to a higher number of components, maintaining data consistency becomes a hairy challenge.</span> It’s not an easy task to manage each component’s state while sharing it with many other components. You’ll likely experience data inconsistency bugs.
</p>

<p align="left" style="font-size:20px">As shown in the image, <span style="color: #c0a8e7">Redux takes away the responsibility from individual components to manage a state.</span> Instead, we create a single store that handles our state management. On top of that, all communication regarding reading, updating, or creating data happens via the store. It prevents data inconsistency bugs from appearing. Moreover, components can listen to state changes to update the UI and avoid these data inconsistency bugs.
</p>

<img src="images/redux-solves.png" alt="store" width="60%"/>
