---
layout: post
---

## Reducers

<p align="left" style="font-size:28px">The logic inside reducer functions typically follows the same series of steps:</p>
* Check to see if the reducer cares about this action
* If so, make a copy of the state, update the copy with new values, and return it
Otherwise, return the existing state unchanged

<img src="images/reducer.png" alt="store" width="65%"/>