---
layout: post
---

## Reducers


<p align="left" style="font-size:28px">A reducer is a <span style="color: #c0a8e7">function that receives the current <strong>state</strong> and an <strong>action</strong> object, decides how to update the state if necessary</span>, and returns the new state: <span style="color: #c0a8e7"><strong>(state, action) => newState</strong></span>.
</p>

<p align="left" style="font-size:28px">Reducers must always follow some specific rules:</p>

* They should only calculate the new state value based on the state and action arguments
* They are not allowed to modify the existing state. Instead, they must make immutable updates, by copying the existing state and making changes to the copied values.
* They must not do any asynchronous logic, calculate random values, or cause other "side effects"