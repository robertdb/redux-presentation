---
layout: post
---

## Dispatch


<p align="left" style="font-size:20px">The Redux store has a method called dispatch. <span style="color: #c0a8e7">The only way to update the state is to call store.dispatch() and pass in an action object.</span> The store will run its reducer function and save the new state value inside, and we can call getState() to retrieve the updated value:
</p>


<img src="images/dispatch.png" alt="store" width="70%"/>


<p align="left" style="font-size:20px">You can think of dispatching actions as "triggering an event" in the application. Something happened, and we want the store to know about it. Reducers act like event listeners, and when they hear an action they are interested in, they update the state in response.
</p>
