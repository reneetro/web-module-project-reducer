# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* addOne action creator is dispatched
* actions/index.js returns the action type of "ADD_ONE"
* reducer finds case "ADD_ONE"
* 1 is added to the state total and the whole state is returned
...

* TotalDisplay shows the total plus 1.
