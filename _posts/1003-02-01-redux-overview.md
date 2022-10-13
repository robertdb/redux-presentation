---
layout: post
---

## The Redux store


<p align="left" style="font-size:28px">The center of every Redux application is the store. <span style="color: #c0a8e7">A "store" is a container that holds your application's global state.</span>
</p>

<p align="left" style="font-size:28px">A store is a JavaScript object with a few <span style="color: #c0a8e7">special functions and abilities</span> that make it different than a plain global object:
</p>

* You must <span style="color: #c0a8e7">never directly modify or change the state</span> that is kept inside the Redux store
* Instead, the <span style="color: #c0a8e7">only way</span> to cause an update to the state is to <span style="color: #c0a8e7">create a plain action object</span> that describes "something that happened in the application", and then dispatch the action to the store to tell it what happened.
* When an action is dispatched, the store runs the root reducer function, and lets it <span style="color: #c0a8e7">calculate the new state based on the old state and the action<span>
* Finally, the store <span style="color: #c0a8e7">notifies subscribers</span> that the state has been updated so the UI can be updated with the new data.

